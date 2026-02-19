# NexusUI
A modern, clean, and minimal Roblox UI Library — free & easy to set up.

## Features
- Tabs with sidebar navigation
- Buttons, Toggles, Sliders, Dropdowns
- Dynamic sections with renaming support
- Minimize pill toggle (draggable)
- Modern close button
- Notification system with progress bar
- Smooth animations and tweens
- Mobile & PC compatible

## Usage
```lua
local NexusUI = loadstring(game:HttpGet("YOUR_RAW_URL"))()

local Win = NexusUI:CreateWindow({
    Title     = "NexusUI",
    SubTitle  = "v2.0",
    ToggleKey = Enum.KeyCode.RightShift,
})

local Tab     = Win:CreateTab({ Name = "Main", Icon = "⚡" })
local Section = Tab:CreateSection("Player")

Section:CreateButton({
    Name     = "Click Me",
    Callback = function()
        print("Hello!")
    end
})
Credits
Made by Defyz Hub. Free to use & Lightweight Of Use.
