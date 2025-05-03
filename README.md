# 👋 Hello, I'm XCL-Zypher!

<img align="right" alt="Coding" width="400" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif">

![Profile Visitors](https://komarev.com/ghpvc/?username=XCL-Zypher&color=blueviolet&style=flat-square&label=Profile+Views)

## 🧑‍💻 About Me
- 🎮 Passionate Roblox script developer
- 🌱 Currently learning Lua programming
- 👨‍💻 Started my coding journey at age 11
- 🚀 Always looking to improve my skills

## 🛠️ Skills
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![Roblox](https://img.shields.io/badge/Roblox-00A2FF?style=for-the-badge&logo=roblox&logoColor=white)

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=XCL-Zypher&theme=radical" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=XCL-Zypher&show_icons=true&theme=radical&count_private=true" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=XCL-Zypher&layout=compact&theme=radical" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=XCL-Zypher&theme=radical" />
</p>

## 🏆 GitHub Trophies
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=XCL-Zypher&theme=radical&row=1&column=6" />
</p>

## 💻 Code Sample
```lua
-- A simple Roblox script example
local function createParticleEffect(part)
    local particleEmitter = Instance.new("ParticleEmitter")
    
    particleEmitter.Texture = "rbxassetid://6880496307"
    particleEmitter.Size = NumberSequence.new({
        NumberSequenceKeypoint.new(0, 0.5),
        NumberSequenceKeypoint.new(1, 0)
    })
    particleEmitter.Transparency = NumberSequence.new({
        NumberSequenceKeypoint.new(0, 0),
        NumberSequenceKeypoint.new(1, 1)
    })
    particleEmitter.Speed = NumberRange.new(2, 5)
    particleEmitter.Lifetime = NumberRange.new(1, 2)
    particleEmitter.Rate = 50
    particleEmitter.SpreadAngle = Vector2.new(0, 180)
    particleEmitter.Parent = part
    
    return particleEmitter
end

-- Usage
local part = workspace.EffectPart
local effect = createParticleEffect(part)
```

## 🚀 Current Projects
- 🎮 Developing custom Roblox game mechanics
- 📚 Building a library of reusable Lua scripts
- 🔍 Exploring advanced Roblox Studio features

## 🌐 Connect With Me
<p align="left">
  <a href="https://discord.com" target="_blank">
    <img src="https://img.shields.io/badge/Discord-.chillboy123.-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/>
  </a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" />
</p>

⭐ *"Coding is not just about making things work, it's about making things better."* ⭐
