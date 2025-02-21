# Getting Loadstring
```lua 
local Hawk = loadstring(game:HttpGet("https://raw.githubusercontent.com/TheHanki/HawkHUB/main/LibSources/HawkLib.lua", true))()
```

--------------------------------------------------------------------------

# Creating Window
```lua 
local Window = Hawk:Window({
	ScriptName = "Hawk HUB",
	DestroyIfExists = true, --if false, gui wont disappear
	Theme = "Dark" --Themes: Pink, White, Dark
})
```
