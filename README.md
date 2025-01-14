# Wizard's UI Library
Simple UI Library. With Clean And Sexy UI for you
Credit To Wizard
###Setup The Library
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/BTermux/Wizard-s-UI-Library/refs/heads/main/Wizard-Library"), true)()
```


### Adding Window
```lua
local PhantomForcesWindow = Library:NewWindow("Window-Name")
```


### Adding Folder (Section)
```lua
local KillingCheats = PhantomForcesWindow:NewSection("Folder-Name")
```


### Adding Button
```lua
KillingCheats:CreateButton("Button", function()
print("Button Pressed!")
end)
```


### Adding Toggle
```lua
KillingCheats:CreateToggle("Toggle-Name", function(value)
print(value)
end)
```


### Adding DropDown
```lua
-- Number after Arguments is Argument that selected by Default
KillingCheats:CreateDropdown("DropDown", {"First", "Second", "Third"}, 2, function(text)
print(text)
end)
```


### Adding Slider
```lua
---1st number is Minimum value, 2nd is Maximum Value, 3rd is Value that selected by Default
KillingCheats:CreateSlider("Slider", 0, 100, 15, false, function(value)
print(value)
 end)
```


### Adding Color Picker
```lua
KillingCheats:CreateColorPicker("Picker", Color3.new(255, 255, 255), function(value)
print(value)
end)
```


### Credits: Wizard and alimkulov
