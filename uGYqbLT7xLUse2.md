# Me RN
![Mr Ballz Cat](https://raw.githubusercontent.com/imstupid3/cnS2kULHdG/refs/heads/main/Maxwell-Cat-Expressive-Ears-Alert-Curiou-PNG.png)

> idk if yall see this but this is markk library btw Mind joining on our discord server?

- https://discord.gg/n3bA2kVQ2x

# Calling the Loadstring
```lua 
local BallzLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/imstupid3/cnS2kULHdG/refs/heads/main/Lib/O3KMWLd1snLib2"))()
```

--------------------------------------------------------------------------

> Creating Window
```lua 
local BallzWindow = UI:CreateLibrary({
    Name = "Name of the library",
    Author = "Markk",
    Transparency = 0,
    TabColor = Color3.fromRGB(255, 165, 0),
    HasLoading = true,
    LoadingConfig = {
        Title = "My Script Loader",
        Description = "Loading resources...",
    },
    CanDrag = true
})
```

> Creating Tabs
```lua
local BallzTab = BallzWindow:CreateTab({
  Name = "Tab"
})
```

> Creating Section
```lua
local Ballz = BallzTab:CreateSection({
  Name = "Section"
})
```

> Adding Label
```lua
local label = Ballz:AddLabel("Labels name")
```

- Updating Label Text
```lua
label:Set("Hot Ballz?")
```

> Adding Discord Button
```lua
Ballz:AddDiscord({
  Name = "Join",
  PromptText = {
    Default = "Join Server",
    TriggerText = "Copied"
  },
  Callback = function()
    print("Hello, World")
  end    
})
```

> Adding Button
```lua
Ballz:AddButton({
  Name = "Button",
  Callback = function()
    print("Hello, World")
  end    
})
```

> Adding Toggle
```lua
Ballz:AddToggle({
  Name = "Toggle",
  Default = false,
  Callback = function(Value)
    print(Value)
  end    
})
```

- Updating Toggle value
```lua
Toggle.Set(false)
```

> Adding Textbox
```lua
Ballz:AddInput({
  Name = "Textbox",
  Default = "default box input",
  HideText = true,
  Callback = function(Value)
    print(Value)
  end	  
})
```

> Adding Dropdown
```lua
Ballz:AddDropdown({
  Name = "Dropdown",
  Default = "1",
  Choices = {"1", "2", "3", "4"},
  Callback = function(Value)
    print(Value)
  end    
})
```

- Updating dropdown list
```lua
dropdown:Update(list[table],true)
```

> Adding Slider
```lua
Ballz:AddSlider({
  Name = "Slider",
  Default = 5,
  Range = {1, 100},
  Color = Color3.fromRGB(255,255,255),
  Increment = 1,
  Callback = function(Value)
    print(Value)
  end    
})
```

- Updating Slider Value
```lua
Slider.Set(10)
```

> and for the last is notification haha
```lua
BallzLib:CreateNotify({
    Name = "Test Notification",
    Description = "This is a test message.",
    Icon = "rbxassetid://123456789",
    Duration = 10,
    ShowDuration = false
})

-- The [ShowDuration] will display the countdown in the description like "[1]"
```
