# Medical Attention
Enhanced Medications. All meds, kits, injectors, and balms enhanced for your pleasure.

This is meant to be a replacement for SuperIFAK and SuperAFAK mods, however, you may still use those mods if you keep the IFAK and AFAK settings for this mod disabled. If you do not keep them disabled in this mod, the the three mods can conflict with one another and your server may not load and/or their functionality could be broken in game

HP resource values for all items are listed below...
Some items have extra features added but are not listed here. To see those changes, please review the code in src folder.

>Author  : jbs4bmx


### /* ========== CONFIGURABLE MEDICAL SUPPLIES ========== */
Medical Supplies are now customizable.
Edit .\src\config.json to change the HP Resource or functionality of Medical Supplies.

Example of config.json
```jsonc
{

    "AI2": {
        "Enable": false,
        "hpResource": 250,
        "hpResourceRate": 50
    },

    "CAR": {
        "Enable": false,
        "hpResource": 500,
        "hpResourceRate": 70
    },

    "SALEWA": {
        "Enable": false,
        "hpResource": 1000,
        "hpResourceRate": 85
    },

    "IFAK": {
        "Enable": false,
        "hpResource": 900,
        "hpResourceRate": 50,
        "fixFracture": false,
        "fixDestroyedPart": false
    },

    "SANITAR": {
        "Enable": false,
        "hpResource": 5000,
        "hpResourceRate": 1,
        "fixFracture": false,
        "fixDestroyedPart": false
    },

    "AFAK": {
        "Enable": false,
        "hpResource": 1200,
        "hpResourceRate": 60,
        "fixFracture": false,
        "fixDestroyedPart": false
    },

    "GRIZZLY": {
        "Enable": false,
        "hpResource": 5000,
        "hpResourceRate": 175,
        "fixFracture": false,
        "fixDestroyedPart": false
    },

    "PILLS": {
        "Enable": false,
        "hpResource": 24,
        "Duration": 360,
        "HydrationBurn": -4
    },

    "BANDAGES": {
        "Enable": false,
        "hpResource": 4
    },

    "SPLINTS": {
        "Enable": false,
        "hpResource": 8
    },

    "TOPICALS": {
        "Enable": false,
        "hpResource": 10,
        "Energy": 25,
        "Hydration": 25,
        "Duration": 360
    },

    "SURGICALKITS": {
        "Enable": false,
        "hpResource": 10
    },

    "TOURNIQUETS": {
        "Enable": false,
        "hpResource": 5
    },

    "INJECTORS": {
        "Enable": false,
        "hpResource": 4,
        "Duration": 360,
        "HydrationBurn": -4,
        "EnergyBurn": -4
    }
}
```
#

### NOTICE
**WARNING** - There is one caveat to using this mod after enabling "fix fractures" and/or "fix destroyed body parts" on Ifak, Afak, Sanitar Med Kit, or Grizzly...
>When healing fractures or destroyed parts with enhanced med kits, your character cannot move.
>It is a side-effect of adding the "surgical kit"-like features to med kits.
>Take cover to heal if you have these features enabled!
#

### End
#