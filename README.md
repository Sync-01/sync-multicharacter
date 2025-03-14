# sync-Multicharacter
Multi Character Feature for QBCore Multicharacter And inspired by NoPixel 4.0. 

## Features
- Ability To Create Max 4 Characters.
- Ability Delete Any Character.
- Ability To See Character Information During Selection.
- Ability To Customise Your Character Slot At [config.lua](https://github.com/P4ScriptsFivem/sync-multicharacter/blob/main/config.lua).

## Features
If You Use [qb-houses](https://github.com/qbcore-framework/qb-houses)
Go To Line 324 in Server/main.lua [here](https://github.com/qbcore-framework/qb-houses/blob/main/server/main.lua)

Remove This 
```
    TriggerClientEvent('qb-multicharacter:client:chooseChar', src)
```
Add This  
```
    TriggerClientEvent('sync-multicharacter:client:chooseChar', src)
```

## Screenshots
(https://private-user-images.githubusercontent.com/120780563/324484842-9d7d768b-799f-4dfe-9567-62077479db63.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDE5MzQ1NjgsIm5iZiI6MTc0MTkzNDI2OCwicGF0aCI6Ii8xMjA3ODA1NjMvMzI0NDg0ODQyLTlkN2Q3NjhiLTc5OWYtNGRmZS05NTY3LTYyMDc3NDc5ZGI2My5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMzE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDMxNFQwNjM3NDhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xOGMxZTIyZDhlOGNiNmNkYWIyOGZlM2M1NDM3ZTEwMjIzMWY0ZGZlMzVhZDQ5Y2I3OGNhZjg0ZDVlMjk3ZTNjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.9z-h3Mi3uBxtTWM8xaLb2e1nmXzxUjlzmWNsnUK7Gq0)


## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg

```
ensure qb-core
ensure sync-multicharacter
ensure qb-spawn
ensure qb-apartments
ensure qb-clothing
ensure qb-weathersync
```

## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-spawn](https://github.com/qbcore-framework/qb-spawn) - Spawn selector
- [qb-apartments](https://github.com/qbcore-framework/qb-apartments) - For giving the player a apartment after creating a character.
- [qb-clothing](https://github.com/qbcore-framework/qb-clothing) - For the character creation and saving outfits.
- [qb-weathersync](https://github.com/qbcore-framework/qb-weathersync) - For adjusting the weather while player is creating a character.

## Credits & Original Repository
- [qb-multicharacter](https://github.com/qbcore-framework/qb-multicharacter)
  
## License
[GPL-3.0 license](LICENSE)
