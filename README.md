# Obsidian Sample Plugin

This is a sample plugin for Obsidian (https://obsidian.md).

This project uses TypeScript to provide type checking and documentation.
The repo depends on the latest plugin API (obsidian.d.ts) in TypeScript Definition format, which contains TSDoc comments describing what it does.

This sample plugin demonstrates some of the basic functionality the plugin API can do.

- Adds a ribbon icon, which shows a Notice when clicked.
- Adds a command "Open Sample Modal" which opens a Modal.
- Adds a plugin setting tab to the settings page.
- Registers a global click event and output 'click' to the console.
- Registers a global interval which logs 'setInterval' to the console.

## How to use

Run `yarn run dev` to start development mode. This will automatically set up your development environment by selecting an Obsidian vault, installing the hot-reload plugin, and building the plugin with watch mode enabled.

## API Documentation

See https://github.com/obsidianmd/obsidian-api

## Reference

- [obsidian-imgur-plugin](https://github.com/gavvvr/obsidian-imgur-plugin)
