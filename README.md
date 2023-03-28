# Inventory in Lua System for VORPCore framework

## Modifications
![image](https://cdn.discordapp.com/attachments/776118735764717578/940338885119066203/playerselector_showcase_gif.gif)
* Select other Players with [MEGA Nplayerselector](https://github.com/MegaITA/mega_nplayerselector)
* If Players Die Items will be Despawn and not Dropped on Ground
* Edits for [Xakra Weapons](https://xakra-scripts.tebex.io/package/5432140) includet
* Give Gold fixed.
* Money Give Animations.


## Requirements
- [VORP_Core](https://github.com/VORPCORE/vorp-core-lua)
- [VORP Inputs](https://github.com/VORPCORE/vorp_inputs-lua)
- [MEGA Nplayerselector](https://github.com/MegaITA/mega_nplayerselector)

## How to install
* Download the lastest version of my VORP Inventory Mod
* Download latest of MEGA Nplayerselector.
* Copy and paste ```vorp_inventory``` folder to ```resources/vorp_inventory```
* Copy and paste ```mega_nplayerselector``` folder to ```resources/mega_nplayerselector```
* Add ```ensure vorp_inventory``` to your ```resource.cfg``` file
* Add ```ensure mega_nplayerselector``` to your ```resource.cfg``` file
* To change the language go to ```resources/vorp_inventory/Config``` and change the default language, also you will have to edit the html file to change the text on the inventory menu


## Features
* Unique weapons in order not to duplicate them.
* Each weapon has its own ammo and can have diferent type of ammo.
* give ammo from your belt
* When dropping or giving a weapon you give it with all the modifications and ammo.
* It also has usable items.
* KLS.
* metadata
* storage Api


![image](https://user-images.githubusercontent.com/87246847/156600012-3901dac7-73f8-4577-a8f5-9a60d7e3150b.png)
<img width="354" alt="image" src="https://user-images.githubusercontent.com/87246847/156600211-cc3fc70f-60bb-4884-971a-1d2ad4fdb8ad.png">
<img width="286" alt="image" src="https://user-images.githubusercontent.com/87246847/176539805-57997f6d-967d-4341-bdf6-cf88f2277a0f.png">

## Extra Features
* All features from vorp_inventory_lua 1.0.7
* Description of all items in DB
* Gold item like Dollars (You can give and drop item)
- You can choose if using Gold like Dollars in config.lua and config.js
- Added descriptions of each item in inventory, for items (desc is in DB), for weapons (desc is in config.lua), for dollars and gold (desc are in html)


## Wiki
[Wiki VORP Inventory](https://outsider31000.github.io/VORP_API-docs/posts/inventory-lua)

## Credits
- To [Val3ro](https://github.com/Val3ro) for the initial work.
- to [Emolitt](https://github.com/RomainJolidon) and [Outsider](https://github.com/outsider31000) for finishing/testing.   
- Credits to Vorp Team for creating the C# version and [Local9](https://github.com/Local9).
- to [blue](https://github.com/kamelzarandah) for making this possible
