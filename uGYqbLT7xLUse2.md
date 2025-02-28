# Me Right neow
![Mr Ballz Cat](https://raw.githubusercontent.com/imstupid3/cnS2kULHdG/refs/heads/main/Maxwell-Cat-Expressive-Ears-Alert-Curiou-PNG.png)

** Join on our discord server **
https://discord.gg/n3bA2kVQ2x

# Getting Loadstring
```lua 
local BallzLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/imstupid3/cnS2kULHdG/refs/heads/main/Lib/O3KMWLd1snLibv2"))()
```

--------------------------------------------------------------------------

# Creating Window
```lua 
local BallzWindow = UI:CreateLibrary({
    Name = "Name of the library",
    Author = "marky boo",
    Transparency = 0,
    TabColor = Color3.fromRGB(255, 165, 0),
    HasLoading = true,
    Loading = {
     Title = "Loading Screen",
    },
    CanDrag = true
})
```

# Creating Tabs
```lua
local BallzTab = BallzWindow:CreateTab({
  Name = "Tab",
  Color = Color3.fromRGB(255, 165, 0)
})
```

# Creating Section
```lua
local Ballz = BallzTab:CreateSection({
  Name = "Section"
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

# Updating dropdown list
```lua
dropdown:Update(list[table],true)
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
