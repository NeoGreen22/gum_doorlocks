# gum_doorlocks
# void_doorlocks-vorp Conversion to GUM


## Features
1. Toggle between Using item or Alt button to open doors
2. Lock breaking doors
3. Possibility to use different item for each door

## Installation
1. Download this repo/codebase
2. Extract and place `gum_doorlocks` into your `resources` folder
3. Extract and place `lockpick to your 'resources' folder
4. Add `ensure gum_doorlocks` to your `server.cfg` file
5. Add `ensure lockpick` to your `server.cfg` file
6. Restart your server (unless you have nightly restarts)

## Dependency
- [lockpick](https://github.com/VoidZero69/lockpick)

## How-to-configure
If the Config.useitems is set to True :
authorizedItem is responsible of locking/unlocking doors
authorizedJobs will be neglected in the process

If the Config.useitems is set to False :
Alt button is responsible of locking/unlocking doors (authorizedJob used for this)

Using Lockbreaker :
You can use it whether the Config.useitems is set to True or False
+You can choose if the door can be lockbreakable or not (canlockbreak)

## Disclaimers and Credits
  - This is a modification to [bulgar_doorlocks_vorp] (Made by Bulgar)

## Do not forget to:
- ensure this resource after its dependencies 
- if you're adding a new key item you need to register it in the server side
- add the item in db
- exemples are provided in `/config.lua` and `/server/main.lua




Add items to your SQL

provision_jail_keys,
consumable_lock_breaker,
doctor_keys,


Good to go
inside config change if you want to use items or use Left Alt to lock/unlock doors.
