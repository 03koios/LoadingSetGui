wait(1)
game.StarterGui:SetCore("SendNotification", {
Title = "Pog Hub Loaded"; 
Text = "Loaded";
Duration = 1; 
})

bc = BrickColor.new("White")
game.StarterGui:SetCore("ChatMakeSystemMessage", {
	Text = "Pog Hub is Ready | discord.gg/urs2cRBHXU | Credits 03.s#6260";
	Font = Enum.Font.Cartoon;
	Color = bc.Color;
	FontSize = Enum.FontSize.Size96;	
})
