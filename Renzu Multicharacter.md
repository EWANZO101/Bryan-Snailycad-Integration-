Before opening a ticket or reporting an issue, please [check here](https://github.com/EWANZO101/Bryan-Snaily-CAD-Integration/issues?q=is%3Aissue+is%3Aclosed) to see if someone has encountered a similar issue in the past.

# Scripts Compatible with Renzu Multicharacter
Framework == ESX or qb core 

## 1. Bryan Snaily's New Citizen System
- **Script Name:** Bryan Snaily's New Citizen System
- **GitHub Repository:** [Bryan Snaily - New Citizen](https://github.com/bryan_snaily/new_citizen)
- **Compatibility Modification:**
  - Framework: ESX OR QB CORE 
  - Modify the `renzu_multicharacter/server/framework/main.lua` file.
  - Find the `Login` function.
  - Change the following...:
    ```lua
    Login = function(source, data, new, qbslot)
        local source = source
        if Config.framework == 'ESX' then
            TriggerEvent('esx:onPlayerJoined', source, Config.Prefix..data, new or nil)
            LoadPlayer(source)
        else
            if new then
                new.cid = data
                new.charinfo = {
                    firstname = new.firstname,
                    lastname = new.lastname,
                    birthdate = new.birthdate or new.dateofbirth,
                    gender = new.sex == 'm' and 0 or 1,
                    nationality = new.nationality
                }
                -- Insert This Here --
                exports['bryan_snaily']:InsertNewCitizen(new.charinfo.firstname, new.charinfo.lastname, new.charinfo.birthdate, new.charinfo.gender, new.charinfo.nationality)
                --
            end
            <...>
        end
    end
    ```
  - Save the changes.
