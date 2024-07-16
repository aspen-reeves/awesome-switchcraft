# Awesome SwitchCraft

> Awesome programs and libraries for the [SwitchCraft](https://sc3.io/) Minecraft server

> This list is licensed under the FAFO-1-Clause, [a permissive public license](https://github.com/aspen-reeves/FAFO-PL)

**SwitchCraft** is a Minecraft server with [CC: Tweaked](https://github.com/cc-tweaked/CC-Tweaked), [Plethora](https://github.com/SwitchCraftCC/Plethora-Fabric), [Krist](https://github.com/tmpim/Krist), among [others](https://github.com/SwitchCraftCC)

This list is meant to cater directly to SwitchCraft players; for a more generic ComputerCraft list, see [awesome-computercraft](https://github.com/tomodachi94/awesome-computercraft)

If you would like to contribute, read [CONTRIBUTING.md](./CONTRIBUTING.md) (or just create an issue with the program and a link to its source or wiki)

## Contents

- [Programs](#programs)
  - [Shops](#shops)
  - [Storage Systems](#storage-systems)
    - [Data Storage](#data-storage)
  - [Neural Interface Programs](#neural-interface-programs)
  - [Operating Systems](#operating-systems)
  - [External Software](#external-software)
  - [Other](#other)
- [Libraries](#libraries)
  - [Utility](#utility)
  - [Builtins](#builtins)
- [Other Projects](#other-projects)
- [Resources](#resources)

## Programs

### Shops

- [Radon](https://github.com/Allymonies/Radon) - A highly-configurable Krist shop
  - [Microlayout.lua](https://gist.github.com/umnikos/3c8b2f99ae9df0a4f00744437d579cee) - A Radon layout for 1x1 monitor shops
- [Kristify](https://github.com/Kristify/Kristify) - Krist shop for ComputerCraft
- [yfshop](https://github.com/yourfriendoss/yfshop) - Extremely basic & easy to run Krist shop for ComputerCraft

### Storage Systems

- [Argon](https://github.com/Allymonies/Argon) - Automation-friendly inventory management system for CC: Tweaked
- [Artist](https://github.com/SquidDev-CC/artist) - A Rather Tremendous Item SysTem
- [RoundJay](https://github.com/hugeblank/RoundJay) - Extendable item system, with great addon/module support
- [MISC](https://github.com/MasonGulu/CC-MISC) - Modular Inventory Storage and Crafting
- [Milo](https://github.com/kepler155c/opus-apps/tree/develop-1.8/milo) - Another popular storage system; an application for the [opus operating system](#operating-systems)

#### Data Storage

- [Netmount](https://github.com/tmpim/netmountcc) - Websocket based file transfer system for CC

### Neural Interface Programs

- [ShrekFlight](https://p.sc3.io/t6ZRrJutrN) - Basic flight program
- [Dynoverlay](https://p.sc3.io/EcMBeGtp7K) - View occupied claim information as well as nearby claim overlays in 3d
- [`\track` Client](https://p.sc3.io/wMnaMhYrWe) - Client program for the `\track` chatbox command
- [Plethora Meters](https://github.com/Snowflake-Software/plethora-meters) - Rainmeter-esque information display on a neural interface with overlay glasses
- [Minit](https://github.com/Ale32bit/Minit) - Elytra flight program and auto feeder
- [Katze Xray](https://p.sc3.io/kfFWEXa4KX) - Simple plethora Xray program, usage: `xray minecraft:diamond_ore`
- [Hyperlane.lua](https://p.sc3.io/eWFm4yawhX) - Program to efficiently fly in the hyperlane without rubberbanding

### Operating Systems

- [opus](https://github.com/kepler155c/opus) - Cool operating systems with lots of builtin programs
  - [opus-apps](https://github.com/kepler155c/opus-apps) - Collection of opus apps

### External Software

- [pmkam](https://github.com/migeyel/pmkam) - An OpenCL vanity address miner for Krist
- [img2poster](https://github.com/PatriikPlays/img2poster) - Fast converter between images and 2dj/a
- [Tenebra](https://github.com/Allymonies/Tenebra) - Tenebra is a alternative currency to krist, earned by staking
  - [Tenebra Staking Node (Allymonies)](https://github.com/Allymonies/tenebrastakingnode) - Tenebra staking node written in JavaScript
  - [Tenebra Stake (Erb3)](https://github.com/Erb3/TenebraStake) - Tenebra staking node written in Rust
  - [Tenebra Stake Node (PatriikPlays)](https://github.com/PatriikPlays/tenebrastakenode) - Tenebra staking node written in C++
  - [Tenebra Validator (Anavrins)](https://github.com/xAnavrins/TenebraValidator) - Tenebra staking node written in JavaScript
  - [Tenebra.lua (AlexDevs)](https://gist.github.com/Ale32bit/2978fd3962506a8a943fbcf115084b6b) - Tenebra staking node for CC: Tweaked written in Lua
- [QuartzEncoder](https://cc.alexdevs.me/) - DFPWM and MDFPWM online converter from media services such as YouTube
- [FindShop chatbox](https://github.com/Pixium/findshop) - The chatbox which powers \findshop, which allows to search through ShopSync-capable shops

### Other

- [chester](https://p.sc3.io/qEDtRRMeny) - Enderstorage frequency picker
- [CarrotPay](https://github.com/scmcgowen/carrotpay) - A simple chatbox based kristpay replacement to have more control over your kst
- [`^pchat` Server](https://p.sc3.io/AcyUGmkyM7) - Server for pchat private messaging
- [FindShop reciever](https://github.com/slimit75/fs-reciever) - The ComputerCraft app which recieves ShopSync data, and passes it to \findshop
- [Musicify](https://github.com/knijn/musicify) - A music player for ComputerCraft
- [ShopIndex](https://shops.alexdevs.me) - Shops aggregator to browse the catalogue. Uses ShopSync
- [Quartz](https://github.com/Ale32bit/Quartz) - DFPWM and MDFPWM audio player for ComputerCraft
- [CCTunes](https://github.com/Hellscaped/cctunes) - Music radio station software & websocket audio player, with built-in cover art and metadata providers
- [bsp](https://github.com/aspen-reeves/bsp) - Music player that streams from a subsonic compatible server

## Libraries

### Utility

- [Krypton](https://github.com/Allymonies/Krypton) - Event-based node-agnostic Krist API library for Lua
- [Basalt](https://github.com/Pyroxenium/Basalt) - A UI Framework for CC:Tweaked
- [Dynmap](https://p.sc3.io/hxHMUvEx8y) - Functions to wrap Dynmap API
- [cbb](https://github.com/migeyel/cbb) - Simple Chatbox parser
- [ccryptolib](https://github.com/migeyel/ccryptolib) - Collection of cryptographic primitives written in Lua
- [ECDHA key exchange implementation](https://www.computercraft.info/forums2/index.php?/topic/29803-elliptic-curve-cryptography/) - This allows for entierly secure, quick, public/private key cryptography in CC.
- [speakerlib](https://github.com/throughthefog/speakerlib) - CC speaker library with support for stereo audio
- [hopper.lua](https://github.com/umnikos/hopper.lua) - The ffmpeg of Minecraft item transportation: move items from A to B without any hassle

### Builtins

> These programs and libraries are preinstalled on computers in the [ROM](https://docs.sc3.io/faq/rom.html)

- [Bigfont](https://pastebin.com/3LfWxRWh) - Functions to write in bigger fonts
- [Cloud Catcher](https://cloud-catcher.squiddev.cc/) - Web terminal for ComputerCraft
- [MBS](https://github.com/SquidDev-CC/mbs) - A Mildly Better Shell for ComputerCraft

## Other Projects

- [No Armor SC](https://i.patriik.one/no-armor-sc.zip) - Resource pack that removes Elytras, Armor, NIs, Magnets, and Hover Boots

## Resources

- [SwitchCraft Rules and Documentation](https://docs.sc3.io/) - Has general information about the server and some of its mods
- [Plethora Documentation](https://plethora.madefor.cc/) - Can be outdated, see [here](https://docs.sc3.io/whats-new/plethora.html) for changes
- [SwitchCraft Website](https://sc3.io) - Has general info and link to discord
- [SC3 Ingame Chat Ping Graphs](https://forged.phd/scpings/) - View global and per-player chat ping graphs
- [SC3 introduction for new players](https://gist.github.com/umnikos/590a2cd6f15078c97d50c350977c022e) - A detailed guide for new players
