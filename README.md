# A Custom camera from my old unreleased Horror game
- Didnt release it due to Enemy monster bugs
# History
- Created on 10/7/2020
- Created on my first account octtou
- First time trying to change the roblox camera

# Video Demo
https://github.com/user-attachments/assets/eef4ad82-d268-480a-80a2-d8c58437518e

# How to use
- Insert a Local Script inside StarterGui
- Copy the CustomCamera code to the Local Script

- You can change the camera by editing the Vector3 of the camera in this line
```luau
camera.CFrame = CFrame.new(player.Character.HumanoidRootPart.CFrame.p + Vector3.new(0, offset, 0), player.Character.HumanoidRootPart.CFrame.p)
```

- Example: if you wanna make it a side scroller
```luau
camera.CFrame = CFrame.new(player.Character.HumanoidRootPart.CFrame.p + Vector3.new(20, 0, 0), player.Character.HumanoidRootPart.CFrame.p)
```
You can do this or just put the Offset Variable to the X axis

- Example: Cool Isometric camera!
```luau
camera.CFrame = CFrame.new(player.Character.HumanoidRootPart.CFrame.p + Vector3.new(20, 20, 20), player.Character.HumanoidRootPart.CFrame.p)
```

## Pro tip!

Change the FOV of the camera to make it look more Isometric like if you are making a Isometric camera
```luau
camera.FieldOfView = 20
camera.CFrame = CFrame.new(player.Character.HumanoidRootPart.CFrame.p + Vector3.new(50, 50, 50), player.Character.HumanoidRootPart.CFrame.p)
```
