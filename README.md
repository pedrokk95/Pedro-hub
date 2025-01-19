local UniverseID = jogo:GetService("HttpService"):JSONDecode(jogo:HttpGet("https://apis.roblox.com/universes/v1/places/"..game.PlaceId.."/universe")).universeId
se game.PlaceId == 1537690962 ou game.PlaceId == 4079902982 então
    se getgenv().betabss então
        loadstring(jogo:HttpGet("https://raw.githubusercontent.com/hlamx/huhu/master/bssrewrite-obfuscated.lua"))()
    outro
        loadstring(jogo:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/BSS-BananaCat.lua"))()
    fim
elseif game.PlaceId == 10260193230 então
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/Seahuhu-BananaCat.lua"))()
elseif game.PlaceId == 7449423635 ou game.PlaceId == 2753915549 ou game.PlaceId == 4442272183 então
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/BF-BananaCat.lua"))()
elseif game.PlaceId == 4520749081 ou game.PlaceId == 6381829480 ou game.PlaceId == 15759515082 ou game.PlaceId == 5931540094 então
    início local = tick()
    repita task.wait() até game.Players.LocalPlayer e game.Players.LocalPlayer:FindFirstChild("DataLoaded") e game.Players.LocalPlayer:FindFirstChild("DataLoaded").Value
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/KL-BananaCat.lua"))()
elseif game.PlaceId == 18901165922 ou game.PlaceId == 19006211286 então
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/refs/heads/main/PetsGo.lua"))()
elseif game.PlaceId == 16732694052 então
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/AhmadV99/Banana-Cat-Hub/main/Fisch.lua"))()
elseif UniverseID == 5844593548 então
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/AnimeReborn.lua"))()
outro
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/AV-BananaCat.lua"))()
fim
