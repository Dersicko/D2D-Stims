# D2D-Stims
You can find the original files here: <href>https://github.com/DareToDoyle/D2D-Stims</href>.
<p>
This has been modified for use with the most recent QBCore. It has been tested to work as intended.<p>
4 Items intended for PvP (fragging servers) but can definitely be brought into RP.

> - Adrenaline: Gives you 100% health.
> - Meldonin: Gives you unlimited stamina and super sprint speed.
> - Anesthetic: Gives you 100% armour.
> - Ketamine: Gives you wobbly legs :horse:

I have not applied visual effects to the first three stims due to visual effects being quite annoying when you're trying to have a gunfight. They each have a subtle screenshake instead.

All stim shot effects last 25 seconds (changeable) and have the following:

> - Injection animation
> - Injection sound effect
> - Heartbeat sound effect

Installation guide:

1) Paste this into your shared/items.lua:<p>
  --Stims<br>
	["ketamine"] = {["name"] = "ketamine", ["label"] = "Ketamine Shot", ["weight"] = 1, ["type"] = "item", ["image"] = "ketamine.png", ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Do the stanky leg.."},<br>
	["anesthetic"] = {["name"] = "anesthetic", ["label"] = "Anesthetic Shot", ["weight"] = 1, ["type"] = "item", ["image"] = "anesthetic.png", ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Be numb on purpose."},<br>
	["meldonin"] = {["name"] = "meldonin", ["label"] = "Meldonin Shot", ["weight"] = 1, ["type"] = "item", ["image"] = "meldonin.png", ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Temporarily feel like superman"},<br>
	["adrenaline"] = {["name"] = "adrenaline", ["label"] = "Adrenaline Shot", ["weight"] = 1, ["type"] = "item", ["image"] = "adrenaline.png", ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Zoom zoom!"},

2) Drag and Drop "D2D-Stims" into your resource directory.
3) Add "D2D-Stims" into your "Server.CFG"
4) Add item PNG's into your inventory system (if you wish)
5) Restart server & Enjoy!
