# EduRPG- The Ultimate Learning Adventure
Turn your studying into a playable RPG. Track progress as XP, take damage on failed challenges, collect items that modify stats, and unlock story chapters as you master course objectives.

## ✨ Features
- **Character Sheet**: HP hearts, XP/Level bar, gold, equipped items.
- **Story Mode**: Scenes with DC checks (d20 + Study Mod) that reveal success/failure text.
- **Chapters & Unlocks**: Chapters unlock when prior progress hits a threshold you set (e.g., 80%).
- **Quest Log**: XP comes from completed study tasks; tie quests to chapters/scenes.
- **Battle Log**: Buttons for damage (25/50/100) and healing (potions/rest) auto-update HP.
- **Inventory**: Items add HP bonus, damage reduction, or Study Mod; equip/unequip to affect rolls.
- **Dice-friendly**: Criticals, fumbles, and random encounters are easy to add.
- 
- ## 🗺️ Databases
- **Character**: Total XP (rollup), Level (formula), Max HP (formula), HP (Current) (formula), Gold (optional), Equipped bonuses (rollups).
- **Inventory**: Item, Equipped?, Lost?, HP Bonus, Damage Reduction, Study Mod, **Effective** formulas (return 0 if not equipped/lost).
- **Scenes**: Scene Text, Hidden Success/Failure, DC, Roll (Manual), Study Mod (rollup), Chapter relation, **Visible Text** formula, Chapter Unlocked? (rollup).
- **Chapters**: Order, Required %, Completed Scenes (rollup), Total Scenes (rollup), Progress % (formula), **Unlocked?** (formula).
- **Quest Log**: XP Reward, Completed?, XP Counted (formula).
- **Battle Log**: Damage (Manual), Healed (Manual), Counted formulas, Character relation.
