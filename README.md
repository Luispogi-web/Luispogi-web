local Window = OrionLib:MakeWindow({Name = "Random Shit", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <Vascal> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <Fuck you> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <string> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]


local Tab = Window:MakeTab({
	Name = "shit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = True
})

--[[
Name = <Vascal SHM> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <loadstring(game:HttpGet("https://raw.githubusercontent.com/Gwaporoblox/Sub-to-vascal/main/Vascal-Circle-DotXd"))()> - Makes the tab accessible to Sirus Premium users only.
]]
