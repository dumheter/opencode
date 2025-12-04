# OpenCode Configuration Directory

## Overview
This is an OpenCode user configuration directory containing `opencode.json` settings.

## Structure
- `opencode.json` - Main configuration file (JSON with trailing commas allowed)
- `package.json` - Dependencies for OpenCode plugins

## Guidelines
- **Config Format**: JSON with schema validation (`"$schema": "https://opencode.ai/config.json"`)
- **Key Settings**: `share`, `permission`, `autoupdate`
- **Permissions**: Use `"bash": "allow"` for shell access
- **Validation**: Ensure JSON is valid before saving (trailing commas are permitted)
- **No Build/Test**: This is a config-only directory; no build or test commands needed

## Editing
- Always validate against the schema at https://opencode.ai/config.json
- Preserve existing settings unless explicitly asked to change them
- Check OpenCode docs (https://opencode.ai/docs) for configuration options

## Common Tasks
- Update plugin version: Modify `@opencode-ai/plugin` in `package.json`
- Change permissions: Edit `permission` object in `opencode.json`
- Toggle features: Modify top-level keys like `share`, `autoupdate`
