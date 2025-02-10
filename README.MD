# SkyBlockcatia
<div align="center">
  <a target="_blank">
    <img alt="version" src="https://img.shields.io/github/v/release/Quantizr/DungeonRoomsMod?color=%239f00ff&style=for-the-badge" />
  </a>
  <a target="_blank">
    <img alt="mcversion" src="https://img.shields.io/badge/MC%20Version-1.8.9-blue?color=%239f00ff&style=for-the-badge" />
  </a>
</div>


Skyblockcatia is a small mod that contains features for Hypixel Skyblock. Full feature list is provided below.

## Overview
- In-game API Viewer

<details>
<summary>Show Images</summary>

<img src="https://i.imgur.com/fMBMNXx.png" alt="In-game API Viewer" width="1113" height="626">
<img src="https://i.imgur.com/wf9EFIn.png" alt="In-game API Viewer" width="1113" height="626">
<img src="https://i.imgur.com/9NYFH6X.png" alt="In-game API Viewer" width="1113" height="626">
<img src="https://i.imgur.com/yMlphTc.png" alt="In-game API Viewer" width="1113" height="626">
Please don't complain, I'm not ready to make this finished with limited time ;-;
<img src="https://i.imgur.com/KfvhOQT.png" alt="In-game API Viewer" width="1113" height="626">
<img src="https://i.imgur.com/AogRvLw.png" alt="In-game API Viewer" width="1113" height="626">
</details>

- Item Rarity

<details>
<summary>Show Image</summary>

<img src="https://i.imgur.com/Xd6My5V.png" alt="Item Rarity" width="1113" height="626">
</details>

- Toast Notifications

<details>
<summary>Show Image</summary>

<img src="https://i.imgur.com/enrs1uv.png" alt="Toast Notifications" width="1113" height="626">
</details>

- Auction Bids Overlay

<details>
<summary>Show Image</summary>

<img src="https://i.imgur.com/WHWvVqZ.png" alt="Auction Bids Overlay" width="1113" height="626">
</details>

- Fixed Skin Rendering for most Talismans

<details>
<summary>Show Image</summary>

<img src="https://i.imgur.com/tZKY9H6.png" alt="Fixed Skin Rendering" width="1113" height="626">
</details>

- Fixed Enchanted Glint rendering on skulls

<details>
<summary>Show Image</summary>

<img src="https://i.imgur.com/4zQpues.gif" alt="Fixed Enchanted Glint" width="600" height="338">
</details>

- Glowing Dragon Armor! (Overlay works only with [Hypixel HQ Skyblock Pack](https://packshq.com/content/packs/), Head always glows without RS)

<details>
<summary>Show Image</summary>

<img src="https://i.imgur.com/rv9RQyH.png" alt="Glowing Dragon Armor" width="1113" height="626">
</details>

- Exact Event Estimated Time (Sync to your timezone)

<details>
<summary>Show Image</summary>

<img src="https://i.imgur.com/KD2jsRP.png" alt="Exact Event Estimated Time" width="1113" height="626">
</details>

## GUI Settings
- F4 - Main Settings for Hypixel SkyBlock

## Full Feature List

### Commands
<details>
<summary>Show Commands</summary>

- /sbapi - View Player API in-game
- /sbbazaar - View simple item price on Bazaar
- /sbapirefresh - Refresh API Data
</details>

### Skyblock
<details>
<summary>Show Skyblock Features</summary>

- Fully compatible with SkyblockAddons 1.5.1+
- Zealot Spawn cooldown in the end
- Grappling Hook cooldown
- Jungle Axe/Treecapitator block break cooldown
- Option to show Ender Dragon Hitbox automatically when dragon spawned
- Option to show Only Ender Dragon/Ender Crystal Hitbox in Dragon Nest
- Visit Island/Rare Drop/Fish Catch/Gift/Dungeon Quality Drop Toast (Shows on top right of screen)
- Add party when click on chat message
- Right click on player to add party
- Chat Mode (Party, Guild, SB Coops)
- Show current server day when switch server or in the HUD
- Show Event/Bank Interest/Pet Care/Auction Ends exact time in item tooltip instead of estimate time
- Shortcut Menu button in player inventory screen (Ender Chest, Crafting Table, Wardrobe, Pets, SB Menu) when in inventory GUI (Trades, Shop Trading Options, etc.)
- Chat GUI shows in inventory screen (Player Trade, Ender Chest, Craft Item, Trades, Shop Trading Options, Runic, Your Bids, Bank, Bank Deposit, Bank Withdraw, Reforge Accessory, Catacombs Gate)
- Item Rarity overlay
- Bazaar Sell/Buy price on item tooltip
- Search by price in Auction Browser
- Glowing Dragon Armor/Diver Armor (SkyBlock Pack only)
- Show bid and unbid overlay on item in Auction Browser
- Middle click in Auction Browser to view seller auction
- Prevent clicking and tooltips on dummy items (Glass Pane and other items)
- Selection List on sign (Auction Price, Auction Query, Bank Withdraw, Bank Deposit, Bazaar Order)
- Disable Bow/Axe Reequip Animation (Item bobbing animation, **Not bow recharge**, See [Forge Patch](https://github.com/MinecraftForge/MinecraftForge/blob/1.8.9/patches/minecraft/net/minecraft/item/Item.java.patch#L645-L657))
- Disable Boss Bar Dark Lighting (caused by dummy wither on server side)
- Fixed switching armor causes hurt camera effect
- Placed Summoning Eye tracker
- More accurate boss bar for Ender Dragon health
- Auction Bid confirm
- Disable block particles option
- Ignore Bush hitbox option
- Only mineable block hitbox option (Same as adventure mode)
- Ignore Interact Invisible Armor Stand option
- Automatic Open Maddox option
- Sneak to trade on other player island option
- Special Zealot with End Portal Frame rendered with gold block option
- Lobby Player Viewer option
- Better Hand animation when right click with skull items
- Display Max Used of Item Ability config
- Prevent scroll hotbar while fighting dragon config
- Coins info in Reforge Item screen
</details>

### API Viewer
<details>
<summary>Show API Viewer Features</summary>

- Base Info Viewer (Health, Fairy Souls, Bank Account, etc.)
- Show all player inventory and armor
- Show collections/crafted minions
- Skills Viewer - Including skill average and skill progress
- Slayers Viewer - Shows mob, your current EXP, progress bar to next level, total amount on each slayer, total amount spent all slayers, total slayer EXP, current active slayer
- Other Stats Viewer - Shows all your SkyBlock Stats (Kills, Deaths, Others)
- Point at player and press F8 to view their profile
</details>

### Client changes/fixes
<details>
<summary>Show Client changes/fixes</summary>

- Option to change glint rendering from 1.15
- Lightning Bolt rendering fix (Workaround)
- Fixed Fishing Hook in 3rd mode
- Fixed Enderman teleport glitch on client side
- Fixed most 2D texture entities rendering in 3rd mode
- Fixed nameplate rendering in 3rd mode
- Fixed XPOrb rendering
- Fixed bad position of GuiControls button
- Fixed Guardian Beam rendering
- Fixed vanilla skin rendering
- Fixed enchantment glint rendering on skull
- Fixed firework blast particle rendering
- Glowing Skin rendering only for me
</details>

## How to install

### For Minecraft 1.8.9
<details>
<summary>Show Installation Instructions</summary>

- Install Minecraft Forge 1.8.9 (11.15.1.2318)
- Download mod and put it into your .minecraft/mods folder.
- Done
</details>

## Compatible mods
<details>
<summary>Show Compatible Mods</summary>

- SkyblockAddons 1.5.1+
- OptiFine
- Patcher 1.5+
- Not Enough Updates
- Smooth Font
- Apec
- Skypixel
</details>

## Incompatible mod
<details>
<summary>Show Incompatible Mods</summary>

- Frames+ 2.0 (Use Patcher 1.5

### Installation

Download the newest Release and use it like every other forge mod.

### How to install a forge mod
- [Download the latest forge version](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.8.9.html "Download Forge")
- Run it to install forge  

- Open minecraft launcher and check if forge's profile is there, if not then you can create it ![image](https://user-images.githubusercontent.com/74936369/111808098-b8d7bf00-88e4-11eb-8a2d-60e93b1406a5.png)
- **Windows**: Press windows+r and type %appdata%/.minecraft/
- **Linux**: .minecraft is located in your home folder. ~/.minecraft
- **Mac**: do ⌘ (Command) + Space type "~/Library/Application Support/minecraft/
- Create a folder called "mods" if it isnt there already. then put the mods you download inside that folder and start minecraft.
                   
### Legal Disclaimer

This was made for educational purposes only, nobody which directly involved in this project is responsible for any damages caused.
**You are responsible for your actions.**
