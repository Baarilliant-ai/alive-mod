---
layout: page
title: Configuration
parent: Getting Started
nav_order: 2
---

# Configuring Alive Mod

Alive mod can be customized through its configuration file to suit your preferences. This guide explains how to modify the configuration settings.

## Configuration File Location

The configuration file for Alive mod is located at:

- `config/alive.json` in your Minecraft installation directory

## Configuration Options

The configuration file uses JSON format. Here's an example of the default configuration:

```json
{
  "enabled": true,
  "mode": "adventure",
  "model": "gpt-4o-mini",
  "temperature": 0.6
}
```

### Available Settings

#### enabled

- **Type**: Boolean (`true` or `false`)
- **Default**: `true`
- **Description**: Enables or disables the Alive mod functionality. Set to `false` to temporarily disable the mod without removing it.

#### mode

- **Type**: String (`"adventure"` or `"creative"`)
- **Default**: `"adventure"`
- **Description**: Determines how villagers interact with players.
  - `"adventure"`: Enables full character interactions with villagers automatically.
  - `"creative"`: Requires books and quills for interactions, doesn't enable characters automatically.

#### model

- **Type**: String
- **Default**: `"gpt-4o-mini"`
- **Description**: Specifies which AI model to use for villager conversations. The default model provides a good balance of performance and quality.

#### temperature

- **Type**: Number (between 0.0 and 1.0)
- **Default**: `0.6`
- **Description**: Controls the randomness of villager responses.
  - Lower values (closer to 0) make responses more focused and deterministic.
  - Higher values (closer to 1) make responses more random and creative.
  - The default value of 0.6 provides a good balance between consistency and variety.

## How to Edit the Configuration

1. **Locate the configuration file** in your Minecraft installation directory
2. **Open the file** with any text editor (Notepad, VS Code, etc.)
3. **Modify the values** according to your preferences
4. **Save the file**
5. **Restart Minecraft** for the changes to take effect

## Example Configurations

### Adventure Mode (Default)

```json
{
  "enabled": true,
  "mode": "adventure",
  "model": "gpt-4o-mini",
  "temperature": 0.6
}
```

### Creative Mode

```json
{
  "enabled": true,
  "mode": "creative",
  "model": "gpt-4o-mini",
  "temperature": 0.6
}
```

### More Consistent Responses

```json
{
  "enabled": true,
  "mode": "adventure",
  "model": "gpt-4o-mini",
  "temperature": 0.3
}
```

### More Creative Responses

```json
{
  "enabled": true,
  "mode": "adventure",
  "model": "gpt-4o-mini",
  "temperature": 0.8
}
```

## Troubleshooting

If your configuration changes don't seem to be taking effect:

1. Verify that the JSON syntax is correct (no missing commas, brackets, etc.)
2. Make sure you've saved the file after making changes
3. Restart Minecraft completely
4. Check the Minecraft logs for any error messages related to the configuration

For additional help with configuration, join the [Alive Discord community](https://discord.gg/7KVqSQ3XXK).
