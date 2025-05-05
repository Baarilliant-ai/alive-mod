---
layout: page
title: Data Packs
nav_order: 4
has_children: true
permalink: /datapacks/
---

# Data Packs in Alive Mod

Data packs allow you to customize various aspects of the Alive mod without changing any code. They make the mod more flexible and easier to personalize to your liking.

{: .important }

> Data packs are loaded automatically when the game starts or when you use the `/reload` command in Minecraft.

## What Can Be Customized

The Alive mod uses data packs for several key features:

1. **Villager Traits**: Personalities, backstories, and other traits for each villager profession
2. **Villager Names**: The pool of names that can be assigned to villagers
3. **World Instructions**: Default instructions that apply to all entities in the world
4. **Mod Information**: Details about various mods that can be accessed in-game

## Available Data Packs

Currently, the Alive mod comes with one built-in data pack:

- [Default Pack]({{ site.baseurl }}/datapacks/DEFAULT_PACK): The standard data pack included with the mod

## How Data Packs Work

Data packs use simple JSON files to define various aspects of the mod. When the game loads, these files are read and their contents are used to customize the mod's behavior.

The data pack system prioritizes files in this order:

1. Custom data packs in the `datapacks` folder
2. Built-in data in the mod's resources

This means you can override any default settings by creating your own data pack with files that match the same path and name.

## Creating Your Own Data Pack

To create a custom data pack:

1. Create a new folder in your Minecraft world's `datapacks` directory
2. Add a `pack.mcmeta` file with the appropriate metadata
3. Create the necessary JSON files following the structure outlined in [Customization]({{ site.baseurl }}/datapacks/CUSTOMIZATION)

For more detailed instructions on creating and customizing data packs, see the [Customization]({{ site.baseurl }}/datapacks/CUSTOMIZATION) page.

## Next Steps

- Learn about the [Default Pack]({{ site.baseurl }}/datapacks/DEFAULT_PACK) included with the mod
- Explore [Customization]({{ site.baseurl }}/datapacks/CUSTOMIZATION) options for creating your own data packs
- Check out [Villager Traits]({{ site.baseurl }}/villager-traits/) to see how traits are used in the game
