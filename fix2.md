# Fixing Common Issues with SnailyCAD API: Handling 400 Bad Request Errors

## Common Issue: 400 Bad Request

When importing characters to the SnailyCAD database, you might encounter a `400 Bad Request` error. This error often occurs due to missing `gender` and `ethnicity` IDs.

### Requirements for Successful Import

To avoid this error, ensure the following conditions are met:

1. **Gender IDs**: The CAD must have genders created for "Male" and "Female".
2. **Ethnicity IDs**: The CAD must have at least one ethnicity entry created.

### Understanding `GetValueId` Function

The `GetValueId` function makes a request to the CAD to search for the necessary IDs. Here's how it works:

- **Gender**: Ensure that genders for "Male" and "Female" are created in the CAD. If these entries are missing, the function will fail to retrieve the necessary IDs, causing a `400 Bad Request` error.
- **Ethnicity**: Although the function will return the top entry of the database if a `null` value is passed, it's best practice to have at least one ethnicity entry created. If a specific ethnicity is passed to the export, ensure that exact string entry exists in the ethnicity database.

### Steps to Resolve the Issue

1. **Create Gender Entries**:
   - Navigate to the CAD management interface.
   - Create entries for "Male" and "Female" under the gender settings.

2. **Create Ethnicity Entry**:
   - Navigate to the CAD management interface.
   - Create at least one entry under the ethnicity settings. This can be a general entry if specific ethnicities are not required.

### Important Note

These distinctions are crucial for the successful use of the SnailyCAD API but are only outlined in the readme for New Vehicles.
