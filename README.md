local ReplicatedStorage = game:GetService("ReplicatedStorage")
local ChatRemote = ReplicatedStorage:WaitForChild("DefaultChatSystemChatEvents")
local SayMessageRequest = ChatRemote:WaitForChild("SayMessageRequest")


while true do
    SayMessageRequest:FireServer("怨⑦봽遺����ㅼ꽭��", "All")
    wait(0.1) -- 1珥� ��湲�
    SayMessageRequest:FireServer("怨⑦봽遺����щ컡�댁슂!", "All")
    wait(0.1) -- 1珥� ��湲�
end
