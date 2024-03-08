# Helldivers-2-Internal-Hack-Dll-Proxy-PoC

#### This is a PoC that I created to learn about dll proxy using C++ on 64bit application / game.

### Thanks to cfemen and gir489 for all information and CE Tables.

## Feature List
<details>
  <summary>Click to show</summary>
  
```c
//Console Menu
std::vector<Checkbox> checkboxes = { 
      {_XOR_("Inf Health"), false}  //Makes you invulnerable to most forms of damage
    , {_XOR_("Inf Grenades"), false} //Grenades are always at max capacity
    , {_XOR_("Inf Grenades(Legit)"), false} //Grenades decrease, but never drops to zero. Allows you to collect grenade boxes
    , {_XOR_("Inf Ammo"), false} //Ammunition is always at max capacity
    , {_XOR_("Inf Ammo(Legit)"), false} //Ammunition decreases, but never drops to zero. Allows you to collect supply packs
    , {_XOR_("Inf Syringes"), false} //Syringes are always at max capacity
    , {_XOR_("Inf Syringes(Legit)"), false}  //Syringes decrease, but never drops to zero. Allows you to collect supply packs
    , {_XOR_("Inf Stamina"), false} //Disables stamina meter. Run forever
    , {_XOR_("Inf Stratagems"), false} //Stratagems are always at maximum capacity. No stratagem cooldown
    , {_XOR_("MoveSpeed X6"), false} //Move 6x faster than usual
    , {_XOR_("Inf Mission Time"), false} //Mission timer does not decrease
    , {_XOR_("No Reload"), false} //Magazine capacity does not decrease
    , {_XOR_("No Reload V2"), false} //Some other weapons magazine capacity does not decrease
    , {_XOR_("Max Resources"), false} //Picking up a sample will pick up x500 of each type. There is a max capacity on board your own ship
    , {_XOR_("Add 5 Samples"), false} //Picking up a sample adds 5 samples to your inventory
    , {_XOR_("No Recoil"), false} //Prevents your weapon from having a recoil effect
    , {_XOR_("Inf Backpack"), false} //Backpack 'resource' is never depleted (eg. full ammo, rover no overheat)
    , {_XOR_("Inf Special Weapon"), false} //Special weapon has unlimited ammunition
    , {_XOR_("No Laser Cannon Overheat"), false} //Laser cannon can be fired forever without swapping cartridge
    , {_XOR_("Instant Railgun"), false} //Arc Thrower and Railgun do not need to be charged for max damage
    , {_XOR_("Show All Map Icons"), false} //Simulates radar tower, all POI and objectives shown on the map
    , {_XOR_("No Stationary Turret Overheat"), false} //Heavy Machine Gun emplacement does not require cooling down
    , {_XOR_("No Backpack Shield Cooldown"), false} //When backpack energy shield is broken, it instantly gets replaced
    , {_XOR_("No JetPack Cooldown"), false} //Jetpack does not require recharging, jump constantly
    , {_XOR_("All Stratagems in Loadout"), false} //Enables in-development stratagems, as well as locked stratagems
    , {_XOR_("All Equipment in Armory"), false} //Enables in-development, or locked, primary, secondary weapons, and grenades
    , {_XOR_("All Armor in Armory"), false} //Enables in-development, or locked armor

};
```
</details>

## How to use
### - Download DLL
Get the latest by clicking the most recent action [here](https://github.com/emoisback/Helldivers-2-Internal-Hack-Dll-Proxy-PoC/actions) and downloading "version" from the artifacts section
### - Extract DLL inside helldivers 2 game folder ( same folder as helldivers2.exe ), and rename it to version.dll
### - Run Game
### - Choose Feature ( Navigate using arrow key to up/down, space for select / unselect )
### - Enter To Applied Feature
### - Happy Cheating

### Doesnt need old exe, you can use latest exe.

## Building 
You don't need to build this in Visual Studio, the most recent versions are posted here: \
https://github.com/emoisback/Helldivers-2-Internal-Hack-Dll-Proxy-PoC/actions \
Because github automatically builds the master branch, you can:
- Fork the repository. 
- Go to the Actions tab and make sure workflow is enabled.
- Make any changes to a file, and github will rebuild the .dll in the Actions tab of that fork.

For example: [https://github.com/DeathWrench/Helldivers-2-Internal-Hack-Dll-Proxy-PoC/actions](https://github.com/emoisback/Helldivers-2-Internal-Hack-Dll-Proxy-PoC/actions) \
As you can see, commits from forks get built by github as long as they're in the master branch.
#### Still if you want to build it yourself in Visual Studio:
![image](https://github.com/DeathWrench/Helldivers-2-Internal-Hack-Dll-Proxy-PoC/assets/45341450/cd8bb59e-72fb-492e-be0d-1a952295e27c)\
![image](https://github.com/DeathWrench/Helldivers-2-Internal-Hack-Dll-Proxy-PoC/assets/45341450/d7ef335a-ff96-48d0-bce6-e6bf2445f264)\
File will be here: \
``Helldivers-2-Internal-Hack-Dll-Proxy-PoC\x64\Release\``**version.dll**
