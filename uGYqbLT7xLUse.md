# Getting Loadstring
```lua 
local BallzLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/imstupid3/cnS2kULHdG/refs/heads/main/LibO3KMWLd1sn"))()
```

--------------------------------------------------------------------------

# Creating Window
```lua 
local BallzWindow = BallzLib:CreateLibrary({
    Name = "Name of the library",
    HasLoading = false,
    Loading = {
     Title = "Loading Screen",
    },
    CanDrag = false
})
```

# Creating Tabs
```lua
local BallzTab = BallzWindow:CreateTab({
  Name = "AA",
  Color = Color3.fromRGB(255, 165, 0)
})
```

# Creating Section
```lua
local Ballz = BallzTab:CreateSection({
  Name = "brub"
})
```

# Adding Label
```lua
local label = Ballz:AddLabel("Labels name")
```

# Updating Label
```lua
label:Set("Hot Ballz?")
```

# Adding Button
```lua
Ballz:AddButton({
  Name = "Button",
  Callback = function()
    print("Hello, World")
  end    
})
```

# Adding Toggle
```lua
Ballz:AddToggle({
  Name = "Toggle",
  Default = false,
  Callback = function(Value)
    print(Value)
  end    
})
```

# Adding Textbox
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

# Adding Dropdown
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

# Adding Slider
```lua
sec:AddSlider({
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
