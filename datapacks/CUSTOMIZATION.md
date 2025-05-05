---
layout: page
title: Customization
parent: Data Packs
nav_order: 2
---

# Customizing Data Packs

This guide explains how to create and customize your own data packs for the Alive mod.

## File Structure

To create a custom data pack, you'll need to follow this structure:

```
your_datapack/
├── pack.mcmeta
└── data/
    └── alive/
        ├── villager_traits/
        │   ├── armorer.json
        │   ├── butcher.json
        │   └── ... (other profession files)
        ├── villager_names.json
        ├── world.json
        └── mods.json
```

## Creating a Basic Data Pack

1. Create a new folder in your Minecraft world's `datapacks` directory
2. Create a `pack.mcmeta` file with this content:

```json
{
  "pack": {
    "pack_format": 10,
    "description": "Your custom data pack for Alive mod"
  }
}
```

3. Create the necessary folders and files following the structure above

## Customizing Villager Traits

Each profession has its own JSON file in the `villager_traits` directory. The file structure looks like this:

```json
{
  "Archetypes": ["Trait 1", "Trait 2", ...],
  "Personalities": ["Trait 1", "Trait 2", ...],
  "Backstories": ["Story 1", "Story 2", ...],
  "Goals": ["Goal 1", "Goal 2", ...],
  "Fears": ["Fear 1", "Fear 2", ...],
  "Quirks": ["Quirk 1", "Quirk 2", ...],
  "SpeechPatterns": ["Pattern 1", "Pattern 2", ...],
  "PhysicalTraits": ["Trait 1", "Trait 2", ...],
  "Relationships": ["Relationship 1", "Relationship 2", ...],
  "Values": ["Value 1", "Value 2", ...],
  "Hobbies": ["Hobby 1", "Hobby 2", ...],
  "CulturalBackground": ["Background 1", "Background 2", ...],
  "AgeGroup": ["Age 1", "Age 2", ...],
  "LifeEvents": ["Event 1", "Event 2", ...],
  "EmotionalState": ["State 1", "State 2", ...]
}
```

You can add, remove, or modify any of these traits to customize the villager's personality and behavior.

### Example: Custom Farmer Traits

```json
{
  "Archetypes": ["Green Thumb", "Crop Whisperer", "Soil Scientist"],
  "Personalities": ["Patient", "Hard-working", "Early Riser"],
  "Backstories": [
    "Grew up on a family farm",
    "Learned farming from village elders"
  ],
  "Goals": ["Grow the perfect pumpkin", "Expand the village farms"],
  "Fears": ["Crop failure", "Drought", "Pests"]
}
```

## Customizing Villager Names

The `villager_names.json` file contains a list of names that can be assigned to villagers:

```json
{
  "Names": [
    "Name1",
    "Name2",
    "Name3",
    ...
  ]
}
```

You can add, remove, or modify names in this list to customize the pool of names available for villagers.

## Customizing World Instructions

The `world.json` file contains default instructions that apply to all entities in the world:

```json
{
  "Instructions": "Your custom world instructions here. This text provides general guidance about the world, its rules, and how entities should behave."
}
```

You can modify this text to set the tone and rules for your world.

## Customizing Mod Information

The `mods.json` file contains information about various mods:

```json
{
  "Mods": [
    {
      "Name": "Mod Name",
      "Instructions": "Information about the mod"
    },
    {
      "Name": "Another Mod",
      "Instructions": "Information about another mod"
    }
  ]
}
```

You can add, remove, or modify entries in this list to provide information about the mods in your game.

## Loading Your Custom Data Pack

To load your custom data pack:

1. Place it in the `datapacks` folder of your Minecraft world
2. Start or reload the game
3. Type `/reload` in the game chat to reload data packs if the game is already running

## Tips for Creating Good Data Packs

- **Be consistent**: Keep a consistent tone and style across all your custom content
- **Be specific**: The more specific and detailed your traits and instructions, the more interesting and unique your villagers will be
- **Be creative**: Don't be afraid to add unusual or unexpected traits to make your villagers stand out
- **Test thoroughly**: After making changes, test your data pack to make sure everything works as expected

## Sharing Your Data Packs

You can share your custom data packs with other players by:

1. Zipping the data pack folder
2. Sharing the zip file
3. Having other players extract it to their `datapacks` folder

This allows you to create and share unique villager experiences with the Alive mod community.
