<h1 style="font-size:36px">🧟‍♂️ Shoot the Zombie – WebGL Game</h1>

<p style="font-size:18px">
A browser-based zombie defense shooter built with <strong>Unity + C#</strong>, featuring color-matching combat, ricochet damage boosts, evolving enemy waves, and a light tower-defense upgrade system.
</p>

<h2 style="font-size:28px">🎮 Play Now</h2>
<p style="font-size:18px">
👉 <a href="https://lcwnvgp.github.io/shoot-the-zombie/gold">https://lcwnvgp.github.io/shoot-the-zombie/gold</a>
</p>

<h2 style="font-size:28px">📝 Overview</h2>
<p style="font-size:18px">
Shoot the Zombie is a fast-paced WebGL zombie defense game where players combine precise shooting, color strategy, and tower upgrades to survive increasingly difficult waves.  
The game mixes shooting, resource management, and tower defense elements to create simple yet engaging gameplay.
</p>

<h2 style="font-size:28px">🧩 Game Features</h2>

<h3 style="font-size:24px">🔫 Color-Matching Bullet System</h3>
<p style="font-size:18px">
- Bullets come in red / green / blue.<br>
- Zombies have matching colors.<br>
- Only bullets with the same color can damage that zombie.
</p>

<h3 style="font-size:24px">🪞 Ricochet Damage Bonus</h3>
<p style="font-size:18px">
- Bullets that bounce off the side walls deal double damage on their next hit.<br>
- Encourages trick shots and angle-based gameplay.
</p>

<h3 style="font-size:24px">🧟 Multiple Zombie Types</h3>
<p style="font-size:18px">
- Slow tanks, fast runners, high-damage attackers, and more.<br>
- Each type scales in HP, speed, and attack power over time.
</p>

<h3 style="font-size:24px">🌊 Automatic Wave Generation</h3>
<p style="font-size:18px">
- Zombies spawn in procedurally generated attack waves.<br>
- Each wave becomes harder with increased stats and spawn patterns.
</p>

<h3 style="font-size:24px">⬆️ Player Upgrade System</h3>
<p style="font-size:18px">
- Killing zombies grants XP.<br>
- Leveling up allows players to choose from several upgrades.
</p>

<h3 style="font-size:24px">🏰 Placeable Defense Towers</h3>
<p style="font-size:18px">
After leveling up, players can install defensive towers with unique effects:<br>
- Auto-shooter towers<br>
- Slow / debuff towers<br>
- Splash-damage towers
</p>

<h3 style="font-size:24px">🧱 Wall Defense Mechanic</h3>
<p style="font-size:18px">
- Zombies attack the wall when they reach it.<br>
- The wall takes 30 damage every 2 seconds.<br>
- If wall HP reaches 0, the game ends.
</p>

<h2 style="font-size:28px">🛠️ Tech Stack</h2>
<p style="font-size:18px">
- Unity 2022+<br>
- C# gameplay logic<br>
- WebGL browser build<br>
- Custom systems:<br>
&nbsp;&nbsp;- Zombie AI<br>
&nbsp;&nbsp;- Wave spawner<br>
&nbsp;&nbsp;- Bullet physics + ricochet<br>
&nbsp;&nbsp;- Upgrade + tower-placement system<br>
&nbsp;&nbsp;- Color-matching damage logic
</p>

<h2 style="font-size:28px">📂 Project Structure</h2>
<p style="font-size:18px">
<pre>
Assets/
  Scripts/
    Zombie/
    Bullet/
    Towers/
    UI/
    Systems/   (WaveManager, UpgradeSystem, etc.)
  Prefabs/
  Scenes/
</pre>
</p>

<h2 style="font-size:28px">▶️ How to Run Locally</h2>
<p style="font-size:18px">
1. Clone the repo:<br>
<code>git clone https://github.com/lcwnvgp/stz.git</code><br><br>
2. Open in Unity 2022 or newer<br>
3. Load the scene:<br>
<code>Assets/Scenes/Main.unity</code><br>
4. Press Play
</p>
