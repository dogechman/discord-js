# Discord Bot

## Overview
A Discord bot built with discord.js v14 that supports slash commands.

## Project Structure
- `index.js` - Main bot entry point
- `deploy-commands.js` - Script to register slash commands with Discord
- `commands/utility/` - Command files (ping, server, user)

## Environment Variables Required
- `DISCORD_TOKEN` - Your Discord bot token
- `DISCORD_CLIENT_ID` - Your Discord application's client ID
- `DISCORD_GUILD_ID` - The Discord server (guild) ID for command deployment

## Running the Bot
1. Set the required environment variables
2. Run `node deploy-commands.js` to register commands (first time only)
3. Run `node index.js` to start the bot

## Commands
- `/ping` - Responds with Pong
- `/server` - Shows server info
- `/user` - Shows user info
