
# BlocKCL – Advanced Building & Structure Generator

**BlocKCL** is an advanced building and structure generation addon for Minecraft Bedrock Edition. It provides powerful building tools, instant structure placement, tree generation, house generation, and support for selected original Minecraft Jigsaw structures.

Build faster, generate structures, and create your own Minecraft world with BlocKCL!

## Features

### 1. Vanilla Jigsaw Structure Generation
- Generate selected original Minecraft Jigsaw structures.
- Supports selected vanilla village structures.
- Load supported structures directly into your world.

### 2. Tree Generator
- Generate trees instantly in your Minecraft world.
- Place tree structures using a function command.

### 3. Instant House Generator
- Generate a complete house instantly.
- Place a house at your current location.
- No need to build the entire house manually.

### 4. Advanced Building Tools
- **Area Selection:** Use a Stick to select Position 1 and a Blaze Rod to select Position 2.
- **Block Fill:** Fill selected areas with your chosen blocks.
- **Block Replace:** Replace specific blocks within selected areas.
- **Wall Generator:** Quickly create walls.
- **Hollow Structures:** Create hollow buildings and outlines.
- **Large Area Support:** Automatically divide large fill operations into smaller sections.

### 5. Custom Structure Loader
- Load custom `.mcstructure` files.
- Use simple function commands to place structures.
- Supports multiple included structure files.

## Supported Versions

- Minecraft Bedrock Edition 26.60.
- Other versions are not officially supported or tested.
- Minecraft Java Edition is not supported.

## Required Packs

**Behavior Pack (BP)**
- BlocKCL Behavior Pack is required.
- Handles building tools, structure loading, and Script API functions.

**Resource Pack (RP)**
- No separate Resource Pack is required.

**Script API**
- Requires `@minecraft/server` version 2.11.0.

## Installation Guide

1. Download the BlocKCL `.mcaddon` file.
2. Open the downloaded file with Minecraft.
3. Wait for the import process to finish.
4. Create a new world or edit an existing world.
5. Open the Experiments settings.
6. Enable ALL available Experimental Features.
7. Open Behavior Packs.
8. Activate the BlocKCL Behavior Pack.
9. Enter the world.
10. Check the chat for the addon startup message.

## How to Use

### 1. Area Selection

- Hold a Stick and interact with a block to set Position 1.
- Hold a Blaze Rod and interact with another block to set Position 2.
- Your selected area will be defined by these two positions.

### 2. Building Commands

Fill an area with stone:
`/scriptevent bcl:edit set minecraft:stone`

Replace dirt with stone:
`/scriptevent bcl:edit replace minecraft:dirt minecraft:stone`

Create stone walls:
`/scriptevent bcl:edit walls minecraft:stone`

Create a hollow glass structure:
`/scriptevent bcl:edit hollow minecraft:glass`

Display the help menu:
`/function bcl_help`

Clear the current selection:
`/function bcl_clear`

### 3. Tree Generation

Generate a tree using:
`/function load_tree`

### 4. Instant House Generation

Generate a house using:
`/function load_house`

Stand at your desired building location before executing the command.

### 5. Structure Generation and Loading

The following commands load the included structures:

- `/function load_village`
- `/function load_village_taiga`
- `/function load_village_snowy`
- `/function load_village_desert`
- `/function load_untitled`
- `/function load_vill1`
- `/function load_vill2`
- `/function load_vill3`
- `/function load_vill4`
- `/function load_feture`
- `/function load_pillraid`

Stand at the desired location before executing a structure loading command.

## Important Notes

- Enable ALL available Experimental Features before using the addon.
- Activate the BlocKCL Behavior Pack.
- A separate Resource Pack is not required.
- Structure placement depends on the included structure files.
- Large structures may take some time to load.
- Always test the addon in a backup world before using it in your main world.

## Credits

**Addon Name:** BlocKCL

**Author:** BlocKCLteme

**Edition:** Minecraft Bedrock Edition

**Supported Version:** 26.60
