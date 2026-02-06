# WoW 1.12 / Lua 5.0 Compatibility Fixes Applied

## Changes Made (2026-01-19)
1. Line 81: Changed #val to 	able.getn(val) - Lua 5.0 doesn't have # operator for tables
2. Lines 145-149: Changed select() to rg table pattern - Different varargs handling in Lua 5.0

## Testing
- Compatible with WoW 1.12 (Turtle WoW)
- Compatible with Lua 5.0/5.1
- All original functionality preserved

## Original Library
- Author: rxi
- License: MIT
- Source: https://github.com/rxi/json.lua
