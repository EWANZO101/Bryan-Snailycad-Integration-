# Known Issues/Errors

This README.md file outlines the known issues and errors that users may encounter while using the application. Please refer to this list for troubleshooting and potential solutions.

## List of Known Issues:

### 1. [Script: bryan_snaily] API Error: 400 badRequest
- **Description:** Users may encounter an API error with the bryan_snaily script, specifically at line 124 of the server.lua file.
- **Error Message:** `[ script:bryan_snaily] SCRIPT ERROR: @bryan_snaily/server/server.lua:124: [Error] API Error: 400 badRequest`
- **Resolution:** Investigate the error in the specified file and line (server.lua:124) to identify the root cause. Ensure that the API request being made complies with the expected format and requirements.
----
- #### Fix: [Go to fix](https://github.com/EWANZO101/Bryan-Snailycad-Integration-/blob/main/1fix.md)
----
- -----------------------------------------------------------------------------------------------------------------------------------------------------------------------
NOTE THERE IS MORE COMING SOON
____________________________________________________________________________________________________________________________________________________________________________
### 2. [Script: bryan_snaily] <Error_Type>
- **Description:** This issue involves an unspecified script and error type. Users may encounter various script errors with different error messages.
- **Error Message:** `[ local info = {}
    if item.item == "id_card" then
        info.citizenid = Player.PlayerData.citizenid
        info.firstname = Player.PlayerData.charinfo.firstname
        info.lastname = Player.PlayerData.charinfo.lastname
        info.birthdate = Player.PlayerData.charinfo.birthdate
        info.gender = Player.PlayerData.charinfo.gender
        info.nationality = Player.PlayerData.charinfo.nationality
    elseif item.item == "driver_license" then
        info.firstname = Player.PlayerData.charinfo.firstname
        info.lastname = Player.PlayerData.charinfo.lastname
        info.birthdate = Player.PlayerData.charinfo.birthdate
        info.gender = Player.PlayerData.charinfo.gender
        info.type = "Class C Driver License"
    elseif item.item == "weaponlicense" then
        info.firstname = Player.PlayerData.charinfo.firstname
        info.lastname = Player.PlayerData.charinfo.lastname
        info.birthdate = Player.PlayerData.charinfo.birthdate
        info.gender = Player.PlayerData.charinfo.gender
    end

    Player.Functions.AddItem(item.item, 1, false, info)
    TriggerClientEvent('inventory:client:ItemBox', src, QBCore.Shared.Items[item.item], 'add')
    TriggerClientEvent('QBCore:Notify', src, Lang['bought']:format(item.label), 'success')
    exports['bryan_snaily']:InsertNewCitizen(info.firstname, info.lastname, info.birthdate, info.gender)

end)

but i get this error
[ script:bryan_snaily] SCRIPT ERROR: @bryan_snaily/server/server.lua:39: [Error] API Error: 400 badRequest
[ script:bryan_snaily] > userCallback (@bryan_snaily/server/server.lua:39)] <Error_Type>`
- **Resolution:**
-  [Go to fix](https://github.com/EWANZO101/Bryan-Snailycad-Integration-/blob/main/2fix.md)
----
------------------------------------------------------------------------------------------------------
### 3. [Script: <script_name>] <Error_Type>
- **Description:** This issue involves an unspecified script and error type. Users may encounter various script errors with different error messages.
- **Error Message:** `[ script:<script_name>] <Error_Type>`
- **Resolution:** Examine the specific script and error type to understand the nature of the issue. Review the corresponding script file and address any code-related problems. If needed, consult the documentation for the script or seek assistance from the script developer.

-  [Go to fix](https://github.com/EWANZO101/Bryan-Snailycad-Integration-/blob/main/3fix.md)
----
------------------------------------------------------------------------------------------------------
### 4. [Script: <script_name>] <Error_Type>
- **Description:** This issue involves an unspecified script and error type. Users may encounter various script errors with different error messages.
- **Error Message:** `[ script:<script_name>] <Error_Type>`
- **Resolution:** Examine the specific script and error type to understand the nature of the issue. Review the corresponding script file and address any code-related problems. If needed, consult the documentation for the script or seek assistance from the script developer.

-  [Go to fix](https://github.com/EWANZO101/Bryan-Snailycad-Integration-/blob/main/4fix.md)
----
------------------------------------------------------------------------------------------------------
### 5.[Script: <script_name>] <Error_Type>
- **Description:** This issue involves an unspecified script and error type. Users may encounter various script errors with different error messages.
- **Error Message:** `[ script:<script_name>] <Error_Type>`
- **Resolution:** Examine the specific script and error type to understand the nature of the issue. Review the corresponding script file and address any code-related problems. If needed, consult the documentation for the script or seek assistance from the script developer.
--------------------------------------------------------------------------------------------
-  [Go to fix](https://github.com/EWANZO101/Bryan-Snailycad-Integration-/blob/main/5fix.md)
----
------------------------------------------------------------------------------------------------------
### 6. [Script: <script_name>] <Error_Type>
- **Description:** This issue involves an unspecified script and error type. Users may encounter various script errors with different error messages.
- **Error Message:** `[ script:<script_name>] <Error_Type>`
- **Resolution:** Examine the specific script and error type to understand the nature of the issue. Review the corresponding script file and address any code-related problems. If needed, consult the documentation for the script or seek assistance from the script developer.
-----------------------------------------------------------------------------
-  [Go to fix](https://github.com/EWANZO101/Bryan-Snailycad-Integration-/blob/main/6fix.md)
----
- ------------------------------------------------------------------------------------------------------
### 7. [Script: <script_name>] <Error_Type>
- **Description:** This issue involves an unspecified script and error type. Users may encounter various script errors with different error messages.
- **Error Message:** `[ script:<script_name>] <Error_Type>`
- **Resolution:** Examine the specific script and error type to understand the nature of the issue. Review the corresponding script file and address any code-related problems. If needed, consult the documentation for the script or seek assistance from the script developer.
- ------------
 [Go to fix](https://github.com/EWANZO101/Bryan-Snailycad-Integration-/blob/main/7fix.md)
----
------------------------------------------------------------------------------------------------------
### 8. [Script: <script_name>] <Error_Type>
- **Description:** This issue involves an unspecified script and error type. Users may encounter various script errors with different error messages.
- **Error Message:** `[ script:<script_name>] <Error_Type>`
- **Resolution:** Examine the specific script and error type to understand the nature of the issue. Review the corresponding script file and address any code-related problems. If needed, consult the documentation for the script or seek assistance from the script developer.
------------
-  [Go to fix](https://github.com/EWANZO101/Bryan-Snailycad-Integration-/blob/main/8fix.md)
----
------------------------------------------------------------------------------------------------------
### 9. [Script: <script_name>] <Error_Type>
- **Description:** This issue involves an unspecified script and error type. Users may encounter various script errors with different error messages.
- **Error Message:** `[ script:<script_name>] <Error_Type>`
- **Resolution:** Examine the specific script and error type to understand the nature of the issue. Review the corresponding script file and address any code-related problems. If needed, consult the documentation for the script or seek assistance from the script developer.
--------
 [Go to fix](https://github.com/EWANZO101/Bryan-Snailycad-Integration-/blob/main/9fix.md)
----
------------------------------------------------------------------------------------------------------
### 10. [Script: <script_name>] <Error_Type>
- **Description:** This issue involves an unspecified script and error type. Users may encounter various script errors with different error messages.
- **Error Message:** `[ script:<script_name>] <Error_Type>`
- **Resolution:** Examine the specific script and error type to understand the nature of the issue. Review the corresponding script file and address any code-related problems. If needed, consult the documentation for the script or seek assistance from the script developer.
---------
 [Go to fix](https://github.com/EWANZO101/Bryan-Snailycad-Integration-/blob/main/10fix.md)
----
------------------------------------------------------------------------------------------------------
Feel free to add more known issues as they are identified during testing or usage. Each issue should be numbered and include a brief description, the associated error message, and any suggested resolutions.
