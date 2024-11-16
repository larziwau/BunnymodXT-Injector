# BunnymodXT Injector

A small and simple injector for **Bunnymod XT**. It injects **BunnymodXT.dll** from the directory where the injector is located. If present, it will also inject `bxt_rs.dll` when using the "Game start" method.

---

## How to Use

### Step 1: Download the Bunnymod XT DLL

1. Download the Bunnymod XT DLL from the [releases page](https://github.com/YaLTeR/BunnymodXT/releases).
2. Place the downloaded DLL into the same folder as the injector.

### Standard Method

1. Run the game.
2. Run the injector.

### Game Start Method (One-time setup)

You only need to complete these steps once to create a shortcut that launches the game with Bunnymod XT.

1. If you don't have a shortcut to your `hl.exe`, create one.
2. Right-click on the shortcut and select **Properties**.
3. Copy the entire contents of the **Target** field.
4. You can now delete this shortcut.
5. Create a new shortcut to the injector.
6. Right-click on the new shortcut and select **Properties**.
7. In the **Target** field, place the cursor at the end, press space, and paste the copied target (Ctrl+V). Click **OK**.
8. Use this new shortcut to launch the game with Bunnymod XT.

---

## Additional Flags

- **-dllname \<name.dll\>**  
  Injects the specified DLL instead of **BunnymodXT.dll**.  
  Example: `-dllname bxt_with_cheats.dll`

- **-processname \<name\>**  
  Injects into a process with the specified name.  
  Example: `-processname hlds.exe`
