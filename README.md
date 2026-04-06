🧟 Roguelike Shooter

A wave-based roguelike shooter built in Unreal Engine 5, featuring multiple enemy types, ability selection, and progressive difficulty.

🎮 Gameplay Overview

The player fights through increasingly difficult waves of enemies in an arena.

Start a wave by interacting with the idol in the center
Defeat all enemies to complete the wave
After each wave, interact with the shopkeeper to upgrade and prepare
Survive as long as possible as difficulty scales

🔁 Core Loop

Interact with Idol → Start wave
Fight enemies → Clear wave
Interact with Shopkeeper → Upgrade weapons & abilities
Repeat with increased difficulty

🔫 Weapons

You can equip 1 weapon at a time:

Assault Rifle (AR)
Shotgun

⚡ Abilities
Total abilities available: 4
You can equip 2 abilities simultaneously

- Mouse Button 4 → Ability 1
- Mouse Button 5 → Ability 2
❤️ Healing System
- Healing charges are shown as a green circle next to the health bar
When available:
- Hold F to heal
- Player must remain stationary while healing
  
🎯 Controls

- Left Click → Shoot
- Mouse Button 4 / 5 → Use abilities
- F (Hold) → Heal
- Interact Key → Idol / Shopkeeper
  
📈 Difficulty Scaling

Enemy count increases with each wave
Player progression through:
Weapon upgrades
Ability selection

🤖 AI Systems (High-Level)

Wave-based enemy spawning using EQS
Multiple enemy types:
Melee (close-range attackers)
Ranged (maintain distance)
Summoner (spawns minions, conditional vulnerability)
Distance-based behavior and state transitions

🛠️ Built With

Unreal Engine 5
Blueprint + Unreal AI systems (Behavior Trees, EQS)


⚠️ Notes

This project was developed as part of learning and experimentation with gameplay and AI systems in Unreal Engine.
