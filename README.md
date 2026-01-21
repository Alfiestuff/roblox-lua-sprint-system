# 🔎 roblox-lua-sprint-system
### description:

This Lua code uses **delta time** to calculate the sprint duration.

---

# 🔧 Installation

### For add in your game:

1. **Firts folder:** In ReplicatedStorage create Folder and name it "Systems"

2. **Second Folder:** Create another Folder and name it sprintSystems⚙️

3. **Add ModuleScript:** Create a new ModuleScript inside that folder and paste this code.

5. **Final Step:** Require the SprintSystem module from a LocalScript inside StarterCharacterScripts.

---

### ⚙️ How the Module Works

This system is built as a **ModuleScript**, which ensures that the sprint logic is **clean, reusable, and easy to manage**. It centralizes the movement mechanics, preventing code clutter in your project.

#### Core Mechanics:
* **Dual-Phase Regeneration:** * **Normal Regen:** Standard recovery when you stop sprinting.
    * **Exhaustion Penalty:** If stamina hits 0%, the `slowRegenTime` delay is triggered before recovery starts.
* **Dynamic Speed States:** Manages different speeds for walking, running, and exhaustion (SlowSpeed).
* **Optimization:** Includes a toggleable debug mode to keep the game running smoothly.
