wait(1)
local Notification = loadstring(game:HttpGet("https://api.irisapp.ca/Scripts/IrisBetterNotifications.lua"))()

wait(1)
Notification.Notify("Credits Scripts", "Credits : 03.s#6260", "Credits", {
Duration = 1,       
Main = {
    Rounding = true,
}
});
wait(2)
Notification.Notify("Anti Afk System", "Anti Afk Always On", "AFK", {
Duration = 1,       
Main = {
    Rounding = true,
}
});

for i,v in pairs(getconnections(game.Players.LocalPlayer.Idled)) do
v:Disable()
end


wait(3)
Notification.Notify("Discord", "Discord Server Already Copy in Your Clipboard", "Discord", {
Duration = 1,       
Main = {
    Rounding = true,
}
});

setclipboard("discord.gg/x4gGhjVxXz")
