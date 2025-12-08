🧟‍♂️ Shoot the Zombie – WebGL Game

A browser-based zombie defense shooter built with Unity + C#, featuring color-matching combat, ricochet damage boosts, evolving enemy waves, and a light tower-defense upgrade system.

🎮 Play Now

👉 https://lcwnvgp.github.io/shoot-the-zombie/gold

📝 Overview

Shoot the Zombie is a fast-paced WebGL zombie defense game where players combine precise shooting, color strategy, and tower upgrades to survive increasingly difficult waves.
The game mixes shooting, resource management, and tower defense elements to create simple yet engaging gameplay.

🧩 Game Features
🔫 Color-Matching Bullet System

Bullets come in red / green / blue.

Zombies have matching colors.

Only bullets with the same color can damage that zombie.

🪞 Ricochet Damage Bonus

Bullets that bounce off the side walls deal double damage on their next hit.

Encourages trick shots and angle-based gameplay.

🧟 Multiple Zombie Types

Slow tanks, fast runners, high-damage attackers, and more.

Each type scales in HP, speed, and attack power over time.

🌊 Automatic Wave Generation

Zombies spawn in procedurally generated attack waves.

Each wave becomes harder with increased stats and spawn patterns.

⬆️ Player Upgrade System

Killing zombies grants XP.

Leveling up allows players to choose from several upgrades.

🏰 Placeable Defense Towers

After leveling up, players can install defensive towers with unique effects:

Auto-shooter towers

Slow / debuff towers

Splash-damage towers

🧱 Wall Defense Mechanic

Zombies attack the wall when they reach it.

The wall takes 30 damage every 2 seconds.

If wall HP reaches 0, the game ends.

🛠️ Tech Stack

Unity 2022+

C# gameplay logic

WebGL browser build

Custom systems:

Zombie AI

Wave spawner

Bullet physics + ricochet

Upgrade + tower-placement system

Color-matching damage logic

📂 Project Structure
Assets/
  Scripts/
    Zombie/
    Bullet/
    Towers/
    UI/
    Systems/   (WaveManager, UpgradeSystem, etc.)
  Prefabs/
  Scenes/

▶️ How to Run Locally

Clone the repo:

git clone https://github.com/lcwnvgp/stz.git


Open in Unity 2022 or newer

Load:

Assets/Scenes/Main.unity


Press Play
