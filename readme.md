# IF YOU WANNA THIS PLUGIN CONTACT ME ON DISCORD : deadswim [MY DISCORD SERVER](https://discord.gg/WNK777rhwg)


##### Lists of my plugins
> [VIP](https://github.com/DeadSwimek/cs2-vip), [VIP Premium](https://github.com/DeadSwimek/cs2-vip-premium), [SpecialRounds](https://github.com/DeadSwimek/cs2-specialrounds), [Countdown](https://github.com/DeadSwimek/cs2-countdown), [CTBans](https://github.com/DeadSwimek/cs2-ctban), [HideAdmin](https://github.com/DeadSwimek/cs2-hideadmin)


                

![](https://camo.githubusercontent.com/6f4dcc3ce2ec908ab308be1f42581be46c9bb46cc9958637cc6044f640ed835f/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313137363533373237323732343735383634382f313137363533373237323938303630373133382f7669702e706e67)
### Features PREMIUM
- 5 VIPs group
- Colored models
- Instant reloading when have 1 ammo
- Trials for players [ShowCase](https://ctrlv.tv/video/2023/12/03/23/0d9z.webm)
- Shoot laser for VIPS [ShowCase](https://ctrlv.tv/video/2023/12/04/00/lkMz.webm)
- Can set to pistols one ammo after player spawn. [ShowCase](https://ctrlv.tv/video/2023/12/04/14/WJOp.webm)
- Can remove NONVIP all pistols when player spawn after first round.
- Can setup every hit with knife giving -40hp.
- Can setup automaticall free vip at time.
### Features
- AutoBHOP
- Can enable noknifedamage.
- Special VIP tag in chat. 
- Pack of guns for free.
- Set 115 HP on RoundStart.
- Set 100 Arrmor on RoundStart.
- Welcome messages.
- Translation file in config.
- Connect to database.
- Doubble jump.
- Reservation slots.
- Colored smokes.
- VIPs can be added from keys.
- You can take /testvip.
- VIP can be respawned by command /respawn.
- Rewards after bomb detonate.
- Configurated packages.
- 5 VIPs groups.
- AntiTeam flash

# Commands
**css_testvip**

`Usage: /testvip` Automatical giving group 0 (GROUP 1)

**css_generatevip**

`Usage: css_generatevip <Time In Seconds> <Group 0,1,2>`

**css_activator**

`Usage: /activator <YOUR_TOKEN>`

**css_addvip**

`Usage: /addvip <Time In Seconds> <STEAMID64> <Group 0,1,2>`

**css_respawn**

`Usage: /respawn` Give a VIP to player on steamid.

**css_settings**

`Usage: /settings` Open menu with settings

**css_vips**

`Usage: /vips` Give you a VIP player list.

**css_weapon**

`Usage: /weapon <Number of weapon>` List of packages:

| ID      | Weapon   |
| ------------ | ------------ |
| `1`    | AK-47     |
| `2`    | M4A1     |
| `3`    | M4A1-S     |
| `4`    | AWP     |

**css_pack**

`Usage: /pack <Number of pack>` Configuration in config

**css_guns_off**

`Usage: /guns_off` Turn of automatically weapons giving

| Command      | Permission   |
| ------------ | ------------ |
| `css_generatevip`    | @css/root     |
| `css_addvip`    | @css/root     |
| `css_weapon`    | Database add     |
| `css_respawn`    | Database add     |
| `css_pack`  | Database add   |
| `css_color`  | Database add   |
| `css_guns_off`  | NONE   |
| `css_activator`  | NONE   |
| `css_testvip`  | NONE   |

#Config

```JSON
// This configuration was automatically generated by CounterStrikeSharp for plugin 'VIP', at 2023/12/03 09:16:31
{
  "Token": "YOUR_TOKEN",
  "Prefix": " \u0001[\u0004MadGames.eu\u0001]",
  "GiveHPAfterKill": true,
  "GiveMoneyAfterKill": true,
  "AllowKillMessages": true,
  "EnableVIPPrefix": true,
  "EnableVIPAcceries": true,
  "EnableVIPColoredSmokes": true,
  "EnableFalldamage": false,
  "RespawnAllowed": true,
  "DetonateRewards": true,
  "EnableDoubbleJump": true,
  "KnifeDMGEnable": false,
  "WelcomeMessageEnable": true,
  "ReservedSlotsForVIP": 1,
  "ReservedMethod": 1,
  "Bombinfo": true,
  "DeletePistolsForNonVIP": false,
  "DisablePackWeaponAfter20Sec": false,
  "MinimumRoundToUseCommands": 3,
  "AutogivingDeagle": false,
  "DBDatabase": "database",
  "DBUser": "user",
  "DBPassword": "password",
  "DBHost": "localhost",
  "DBPort": 3306,
  "money": {
    "FirstSpawnMoney": 1200,
    "SpawnArmor": 100,
    "SpawnHP": 110,
    "KillHP": 10,
    "KillMoney": 300,
    "DetonateMoney": 300
  },
  "pack1": {
    "Gun": "ak47",
    "Pistol": "deagle",
    "Acceroies": "healthshot",
    "Acceroies_2": "molotov",
    "Acceroies_3": "smokegrenade",
    "Acceroies_4": "hegrenade"
  },
  "pack2": {
    "Gun": "m4a1",
    "Pistol": "deagle",
    "Acceroies": "healthshot",
    "Acceroies_2": "molotov",
    "Acceroies_3": "smokegrenade",
    "Acceroies_4": "hegrenade"
  },
  "pack3": {
    "Allowed": false,
    "Gun": "m4a1",
    "Pistol": "deagle",
    "Acceroies": "healthshot",
    "Acceroies_2": "molotov",
    "Acceroies_3": "smokegrenade",
    "Acceroies_4": "hegrenade"
  },
  "GroupsNames": {
    "Group1": "VIP",
    "Group2": "VIP II",
    "Group3": "VIP III",
    "Group4": "VIP IV",
    "Group5": "VIP V"
  },
  "GroupsSettings_G1": {
    "Respawn": true,
    "Pack": true,
    "Weapons": true,
    "Acceries": true,
    "Smoke": true,
    "DoubbleJump": true,
    "BombInfo": true,
    "ReservedSlots": true,
    "FastReload": true,
    "Color": true,
    "Trials": true,
    "ShootLaser": true,
    "OneBulletDeagle": false,
    "BiggestKnifeDMG": true,
    "DMGInfo": true,
    "AntiFlash": true,
    "BHop": true
  },
  "GroupsSettings_G2": {
    "Respawn": true,
    "Pack": true,
    "Weapons": true,
    "Acceries": true,
    "Smoke": true,
    "DoubbleJump": true,
    "BombInfo": true,
    "ReservedSlots": true,
    "FastReload": true,
    "Color": true,
    "Trials": true,
    "ShootLaser": true,
    "OneBulletDeagle": false,
    "BiggestKnifeDMG": true,
    "DMGInfo": true,
    "AntiFlash": true,
    "BHop": true
  },
  "GroupsSettings_G3": {
    "Respawn": true,
    "Pack": true,
    "Weapons": true,
    "Acceries": true,
    "Smoke": true,
    "DoubbleJump": true,
    "BombInfo": true,
    "ReservedSlots": true,
    "FastReload": true,
    "Color": true,
    "Trials": true,
    "ShootLaser": true,
    "OneBulletDeagle": false,
    "BiggestKnifeDMG": true,
    "DMGInfo": true,
    "AntiFlash": true,
    "BHop": true
  },
  "GroupsSettings_G4": {
    "Respawn": true,
    "Pack": true,
    "Weapons": true,
    "Acceries": true,
    "Smoke": true,
    "DoubbleJump": true,
    "BombInfo": true,
    "ReservedSlots": true,
    "FastReload": true,
    "Color": true,
    "Trials": true,
    "ShootLaser": true,
    "OneBulletDeagle": false,
    "BiggestKnifeDMG": true,
    "DMGInfo": true,
    "AntiFlash": true,
    "BHop": true
  },
  "GroupsSettings_G5": {
    "Respawn": true,
    "Pack": true,
    "Weapons": true,
    "Acceries": true,
    "Smoke": true,
    "DoubbleJump": true,
    "BombInfo": true,
    "ReservedSlots": true,
    "FastReload": true,
    "Color": true,
    "Trials": true,
    "ShootLaser": true,
    "OneBulletDeagle": false,
    "BiggestKnifeDMG": true,
    "DMGInfo": true,
    "AntiFlash": true,
    "BHop": true
  },
  "Messages": {
    "AllowCenterMessages": true
  },
  "TestVIP": {
    "EnableTestVIP": true, // If is true, player can take testvip
    "TimeOfVIP": 3600, // Time of Test VIP (Seconds)
    "AutoTurnVIP": true, // IF is true, NONVIPs player get VIP at time from STartAt
    "StartAt": 21, // Time is in horus (Giving 1 hours of VIP)
    "EndAt": 23 // Time is in hours, must be in same day with start AT
  },
  "ConfigVersion": 1
}
```

