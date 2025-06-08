    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

    local Window = Library.CreateLib("BlakcHub - VANMINGAMING", "Synapse")

    local Tab = Window:NewTab("Script")

    local Section = Tab:NewSection("Local Script")

    Section:NewKeybind("Open/Close Gui", "N BlakcHub", Enum.KeyCode.N, function()
        Library:ToggleUI()
    end)



    Section:NewButton("Chat Spoofer", "Like Sudo", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/4cYHvVmc"))()

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
    print ("OP")
    end)

    local Tab = Window:NewTab("Players")

    local Section = Tab:NewSection("Local Script")

    Section:NewButton("Sword Reach", "Make Hitbox BIGGER!", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Severitylol/Universal-Sword-Reach/main/swordreach.lua"))()

    end)

    Section:NewToggle("SuperMan", "Super Speed And Super Jump", function(state)
        if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 150
        else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
        end
    end)

    Section:NewSlider("Walkspeed", "Speed", 500, 16, function(s)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
    end)

    Section:NewSlider("JumpPower", "Jump", 350, 50, function(s)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
    end)

    Section:NewButton("Reset WalkAndJump", "Blakc", function()
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
    end)

    Section:NewButton("Back/Front/AirJump For PC", "Z for Front X for Back C for AirJump", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/rscripts-eng/FE-HUB/refs/heads/main/fe%20flips"))()
    end)
    
    Section:NewButton("Fly V3 Gui", "Fly", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()

    end)

    Section:NewButton("Executor", "Execute", function()
    loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-fxe0-V1-open-source-33446"))()

    end)

    Section:NewButton("Fast Interact", "No CD", function()
game:GetService("ProximityPromptService").PromptButtonHoldBegan:Connect(function(prompt)
  fireproximityprompt(prompt)
end)

    end)

    local Tab = Window:NewTab("Combine")

    local Section = Tab:NewSection("Local Script")

    Section:NewButton("Orca + IY", "Execute Orca Hub And IY", function()
    loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/richie0866/orca/master/public/latest.lua"))()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Infinite-Yield_500"))()

    end)

    local Tab = Window:NewTab("Fe")

    local Section = Tab:NewSection("All fe scripts are not from me")
    
    Section:NewButton("Fe Punch", "Works all R15/R6 games", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/obf_rf6iQURzu1fqrytcnLBAvW34C9N55kS9g9G3CKz086rC47M6632sEd4ZZYB0AYgV.lua.txt'),true))()
    end)
    
    Section:NewButton("Fe Neko", "Works only R6 games", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Gazer-Ha/Neko-v1/main/Extremely%20Broken"))()
    end)
    
    Section:NewButton("Fe Ender ", "Works only R6 games", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/9BtJhHrp", true))()
    end)
    
    Section:NewButton("Fe Glios", "Works only R6 games", function()
    loadstring(game:HttpGet(('https://glot.io/snippets/gua2ntmbdm/raw/main.lua'),true))()
    end)
    
    Section:NewButton("Fe Gale fighter", "Works only R6 games", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/XPGSMEw9"))()
    end)
    
    Section:NewButton("Fe Griddy", "Works only R6 games", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/MelonsStuff/hub/main/Griddy.txt"))()
    end)
    
    Section:NewButton("Fe KJ", "Works only R6 games", function()
    loadstring(game:HttpGet("https://pastefy.app/sdAujywd/raw"))()
    end)
    
    Section:NewButton("Fe Caducus", "Works only R6 games", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/LDL9AyQ4"))();
    end)
    
    Section:NewButton("Fe Sonic", "Works only R6 games", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/uacVtsWe"))()
    end)
    
    Section:NewButton("Fe Sad boy", "Works only R6 games", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/hgPJbwF0"))()
    end)
    
    Section:NewButton("Fe G-Man", "Works only R6 games", function()
    _G.clientsidedeffect = true --set it to false if you don't want the effect
    loadstring(game:HttpGet("https://raw.githubusercontent.com/randomstring0/Qwerty/refs/heads/main/qwerty18.lua"))()
    end)
    
    Section:NewButton("Fe Car", "You can use car hat or without hat", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AlexCr4sh/FeScripts/main/FeCarScript.lua", true))()
    end)
    
    Section:NewButton("Fe Fighter", "Works only R6 games", function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-FE-Fighter-inspired-by-Gale-21557"))()
    end)
    
    Section:NewButton("Fe Hug", "Works all game", function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Hug-Gui-R6-17818"))()
    end)
    
    Section:NewButton("Fe Honored", "Works only R6 games", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/Cortzalno666/NectoVerse-Industries-Data/master/Scripts%20Folder/Honored.lua'),true))()
    end)
    
    Section:NewButton("Fe Invisible", "Works all games", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/3Rnd9rHf'))()
    end)
    
    Section:NewButton("Fe NPC control ", "Works only R6 games", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/randomstring0/Qwerty/refs/heads/main/qwerty13.lua"))()
    end)
    
    Section:NewButton("Fe Telekinesis V5", "Works only if parts are unanchored + you can also grab NPC", function()
    loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/randomstring0/Qwerty/refs/heads/main/qwerty11.lua"))()
    end)
    
    Section:NewButton("Fe Tool Draw", "You need more Tools to draw something", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Affexter/Programs/refs/heads/main/scripts/tooldrawFE.lua"))()
    end)
    
    Section:NewButton("Fe Zombie", "Works only R6 and R15 games ig", function()
    loadstring(game:HttpGet(('https://pastefy.app/w7KnPY70/raw'),true))()
    end)
    
    Section:NewButton("Fe Blackhole", "Works only if parts are unanchored", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Bac0nHck/Scripts/main/BringFlingPlayers"))("More Scripts: t.me/arceusxscripts")
    end)
    
    Section:NewButton("Fe Radius Blackhole", "Same as like fe Blackhole script", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/RkWYLL5t"))();
    end)
    
    Section:NewButton("Fe Super Ring V4", "Kinda like Blackhole", function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Natural-Disaster-Survival-Super-ring-V4-24296"))()
    end)
    
    Section:NewButton("Fe Audio spam", "It works only if games support", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/kmXCTkBt"))();
    end)
    
    Section:NewButton("Fe Goner Divine Edge", "Works only R6 games", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/sFf9MeBE"))();
    end)
    
    Section:NewButton("Fe Crystal Dance", "Works only R6 games", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/vT1URaRJ"))() 
    end)
    
    Section:NewButton("Fe Jerk", "Works all R15 and R6 games", function()
    --Made by muscle_legends2021 (Gio)
    --YouTube: GioBolqvi
    
    loadstring(game:HttpGet("https://pastefy.app/YZoglOyJ/raw"))()
    end)
    
    
    local Tab = Window:NewTab("Animations")
    local Section = Tab:NewSection("R6 Animation")
    
    Section:NewButton("Fe Animation Man", "Works only R6 games", function()
    loadstring(game:HttpGet("https://pastefy.app/ZWgckZdU/raw"))()
    end)
    
    Section:NewButton("Fe R6 Animations", "Works only R6 games", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ocfi/Animations-obfus/refs/heads/main/obfus"))()
    end)
    
    
    local Section = Tab:NewSection("R15 Animation")
    
    Section:NewButton("Fe Adidas Walk Animation", "Works all R15 games", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/VFBVQ6zb"))()
    end)
    
    Section:NewButton("Fe Animation Walk (Chill)", "Works all R15 games", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/T7kdfUmG"))();
    end)
    
    Section:NewButton("Fe Get Sturdy", "It works only Baseplate game", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/xAHFn1hh"))();
    end)
    
    Section:NewButton("Fe Superman", "Works all R15 games", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/H20CalibreYT/SystemBroken/main/script"))()
    end)
    
    Section:NewButton("Fe Emotes", "Works only R15 games", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/eCpipCTH"))()
    end)
    
    
    local Tab = Window:NewTab("Chat bypass")
    local Section = Tab:NewSection("You wont get banned")
    
    Section:NewButton("Fe Gaze Bypass V4", "Works all games", function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Gaze-bypass-Altered-21081"))()
    end)
