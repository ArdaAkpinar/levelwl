local whitelist = {
    "ItzSwara31",
    "Arda1420",
    "252531_werza",
    "Tpsciawain", --me
    "madridhayatimolmus", --1 hafta
    "arda",
    "qazztr",
    "31cihasanxd",
    "Alexnimo2022",
    "ablanidelim",
    "azemessi3a",
    "itsh0r",
    "2525israfil",
    "Zzz_tps2",
    "tpsciawain",
    "harunisteaq9" -- giveaway winner
}

if table.find(whitelist, game.Players.LocalPlayer.Name) then
        local id = game.PlaceId
if id == 335760407 or 13762482705 then
game.StarterGui:SetCore("SendNotification",{
			Title = "Loading...";
			Text = "Loading will take some seconds...";
			Duration = 5;
})
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ArdaAkpinar/level/main/README.md"))()
else
    game.Players.LocalPlayer:Kick("It's not TPS SS!")
end
else
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ArdaAkpinar/kicked1/main/README.md"))();
end
