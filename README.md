# esx-hud
This is ESX Hud system ... simple &amp; nice velocimeter

# Requirements
  - Brain
  - ESX


## Installation	

- Import `esx_status.sql` from `esx_status` folder in your database
- Import `esx_basicneeds.sql` from `esx_basicneeds` folder in your database
- Add this in your `server.cfg` in the following order:
```bash
start esx_status
start esx_basicneeds
start esx_stress
start ultra-hud
```

# Credits

I do not own `esx_status`, `esx_basicneeds`, `esx_stress` and all the credit goes to the respective developers.
## Resources used:
- `esx_stress` is an edited version of [Stress-System-by-utku](https://github.com/utkuali/Stress-System-by-utku)
- [esx_status](https://github.com/esx-framework/esx_status)
- [esx_basicneeds](https://github.com/esx-framework/esx_basicneeds) 
