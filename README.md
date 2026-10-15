# Hatch Wars Auto Farm

Auto farm script for Hatch Wars (Petsim99). Claims houses 1–8, waits for door
timers to finish, then idles at a standby spot hatching eggs continuously.

## ⚠️ IMPORTANT — Egg ID changes every server

The `EggId` inside the script **changes every time you join a new server**.
If you don't update it, the script will run but **eggs will not hatch**.

### How to get the correct Egg ID for your server

Use **SimpleSpy** (or any remote spy) to grab it:

1. Load SimpleSpy in your executor:
   ```lua
   loadstring(game:HttpGet("https://raw.githubusercontent.com/ActiniumScripts/SimpleSpy/main/SimpleSpy.lua"))()
