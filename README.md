local Fluent = loadstring(game:HttpGet("https://github.com/Dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Script X Roleplay Brasil | QTWQ Estúdio " .. Fluent.Version,
    TabWidth = 160,
    Size = UDim2.fromOffset(580, 460),
    Theme = "Dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "SCRIPTS" }),
    Settings = Window:AddTab({ Title = "OUTROS SCRIPTS", Icon = "play" }),
    BROOKHAVEN = Window:AddTab({ Title = "BROOKHAVEN ", Icon = "play" })
}

-- Parágrafos
Tabs.Main:AddParagraph({ Title = "CRÉDITOS/SCRIPTS", Content = "SCRIPT FEITO POR = YUMI,DAVI,ERIKE IDEIA DE DAVI, PROGAMADOR YUMI" })

-- Botões
Tabs.Main:AddButton({ Title = "infinite yield", Callback = function() 
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgelyAnfiniteyield/master/source'))()
end })

Tabs.Main:AddButton({ Title = "aimbot", Callback = function() 
    loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Update-script-hitbox-9326"))()
end })

Tabs.Main:AddButton({ Title = "fly", Callback = function()
    loadstring(game:HttpGet('https://pastebin.com/raw/YSL3xKYU'))()
end })

Tabs.Main:AddButton({ Title = "Aimbot,esp", Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ttwizz/Open-Aimbot/master/source.lua"))()
end })

-- Adicionando botões na aba BROOKHAVEN
Tabs.BROOKHAVEN:AddButton({ Title = "SCRIPT 1", Callback = function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Hyz0r-Dev404/Hyz0/refs/heads/main/Working%25Hyz0r-Hub.md'))()
end })
