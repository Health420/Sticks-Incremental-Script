# Sticks-Incremental-Script
Script For Sticks Incremental. Very OP Change the stated value to increase speed don’t go above 100. If you are interested in this project just send a pull request or something ive been attempting other parts of the game but not successful so far.


local ReplicatedStorage = game:GetService("ReplicatedStorage")
local PickUp = ReplicatedStorage.Events.PickUp

while true do
    for i = 1, 10 do -- spawn 10 sticks per iteration
        PickUp:FireServer("ShadowStick")
    end
    wait(0.0001)
end
