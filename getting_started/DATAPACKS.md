---
layout: page
title: Data Packs
parent: Getting Started
nav_order: 6
---

# Data Packs in Alive Mod

So you want to know more about how data packs work in Alive? You're in the right place! This page explains the basics of our data pack system in a way that won't make your head spin.

## What Are Data Packs?

Think of data packs as little bundles of customization for your Alive mod. They're just simple text files (JSON format) that tell the mod how villagers should behave, what names they can have, and other cool stuff.

The best part? You don't need to know any coding to use them!

## What Can You Customize?

With data packs, you can change:

- **Villager Traits**: All those personalities, backstories, and quirks
- **Villager Names**: The pool of names that villagers can get
- **World Instructions**: General rules for how the world works
- **Mod Information**: Details about different mods in your game

## How It Works (The Simple Version)

1. The mod looks for special JSON files in your Minecraft data packs
2. It reads these files when the game starts or when you use `/reload`
3. The information from these files is used instead of the built-in defaults
4. If it can't find a file, it falls back to the defaults

## Where to Find the Files

All the data pack files live in the `data/alive/` folder:

- Villager traits: `data/alive/villager_traits/[profession].json`
- Villager names: `data/alive/villager_names.json`
- World instructions: `data/alive/world.json`
- Mod information: `data/alive/mods.json`

## Making Your Own Data Pack

Want to create your own data pack? It's pretty straightforward:

1. Create a new folder in your Minecraft world's `datapacks` directory
2. Add a `pack.mcmeta` file (there's an example in the [Customization]({{ site.baseurl }}/datapacks/CUSTOMIZATION) page)
3. Create a `data/alive/` folder structure inside it
4. Add your custom JSON files

## What Happens If Something Goes Wrong?

Don't worry! The mod has your back:

- If a file is missing, it uses built-in defaults
- If a file has errors, it logs them and uses defaults
- You can always go back to the original files if needed

## Want More Details?

If you're interested in the nitty-gritty of data packs:

- Check out the [Data Packs]({{ site.baseurl }}/datapacks/) section for user-friendly guides
- Look at the example files in the default data pack
- Experiment with small changes to see what happens

Data packs are meant to be fun to play with, so don't be afraid to try things out!
