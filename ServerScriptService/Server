local ServerStorage = game:GetService("ServerStorage")
local BottomRightCorner = Vector3.new(-805.92, -14.439, -37.852)
local TopLeftCorner = Vector3.new(-906.36, -13.592, -927.246)

local random = Random.new(tick())

local function gr(mi, ma)
	return random:NextNumber(mi, ma)
end

while true do
	local Meteor = ServerStorage.Meteor:Clone()
	Meteor.CanCollide = false
	Meteor.Position = Vector3.new(
		gr(TopLeftCorner.X, BottomRightCorner.X),
		1000,
		gr(TopLeftCorner.Z, BottomRightCorner.Z)
	)
	Meteor.Parent = workspace
	task.wait()
end
