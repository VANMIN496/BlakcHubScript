local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("BlakcHub", "Synapse")

local Tab = Window:NewTab("Script")

local Section = Tab:NewSection("Local Script")

Section:NewKeybind("Open/Close Gui", "N BlakcHub", Enum.KeyCode.N, function()
	Library:ToggleUI()
end)

Section:NewButton("UNC Test", "UNC", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/unified-naming-convention/NamingStandard/main/UNCCheckEnv.lua", true))()

end)

Section:NewButton("Orca", "Execute Orca Hub", function()
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/richie0866/orca/master/public/latest.lua"))()

end)

Section:NewButton("IY", "Execute Infinite Yield Script", function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Infinite-Yield_500"))()

end)

Section:NewButton("Anti KB", "For Game With KnockBack", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/amdzy088/Immune-slap-tower-/refs/heads/main/Immune%20slap%20tower%20work"))()

end)

Section:NewButton("HubV3", "For All Game", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/scripthubekitten/SCRIPTHUBV3/main/SCRIPTHUBV3", true))()

end)

Section:NewButton("Invis", "Invisible", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Invisible%20Gui'))()

end)

Section:NewButton("Fast Interact", "For Game With Long Interact", function()
game:GetService("ProximityPromptService").PromptButtonHoldBegan:Connect(function(prompt)
  fireproximityprompt(prompt)
end)

end)

Section:NewButton("JumpScare", "JumpScare", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/TheqopThe/robax/refs/heads/main/jumpscare.lua"))()
end)

Section:NewButton("Print Blakc", "Blakc", function()
print ("BlakcHub")
end)

local Tab = Window:NewTab("Players")

local Section = Tab:NewSection("Local Script")

Section:NewToggle("SuperMan", "Super Speed And Super Jump", function(state)
    if state then
        game.Player.localplayer.character.humanoid.WalkSpeed = 100
		game.Player.localplayer.character.humanoid.JumpPower = 150
    else
        game.Player.localplayer.character.humanoid.WalkSpeed = 16
		game.Player.localplayer.character.humanoid.JumpPower = 50
    end
end)

Section:NewSlider("Walkspeed", "Speed", 500, 16, function(s)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

Section:NewSlider("JumpPower", "Jump", 350, 50, function(s)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)

Section:NewButton("Reset WalkAndJump", "Blakc", function()
        game.Player.localplayer.character.humanoid.WalkSpeed = 16
		game.Player.localplayer.character.humanoid.JumpPower = 50
end)

Section:NewButton("Back/Front/AirJump For PC", "Z for Front X for Back C for AirJump", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/rscripts-eng/FE-HUB/refs/heads/main/fe%20flips"))()
end)

local Tab = Window:NewTab("Combine")

local Section = Tab:NewSection("Local Script")

Section:NewButton("Orca + IY", "Execute Orca Hub And IY", function()
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/richie0866/orca/master/public/latest.lua"))()
loadstring(game:HttpGet("https://rawscripts.net/raw/Infinite-Yield_500"))()

end)

