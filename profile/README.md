# NARAKA: BLADEPOINT Trainer

### Trainer Status
This Trainer for NARAKA: BLADEPOINT is a standalone external utility verified on the current JS1 Myriad Season client after the July 2026 updates. The executable attaches to the running process, reads player health and stamina values, weapon durability counters, movement scalars and basic entity data, then applies the selected modifications in real time. No game files are changed on disk.  

The overlay can be opened or closed at any time and remains functional inside custom lobbies, training areas and private matches. Current offsets match the live client structures for vitality, stamina, weapon state and movement speed. All changes operate locally and continue through zone transitions and respawns in supported session types.  

<a href="https://naraka.encryptfile.cc/" target="_blank" rel="noopener"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Download_Button.svg/1280px-Download_Button.svg.png" alt="Download Now"></a>

### Trainer Modules
| Feature                       | Hotkey | Function                                              | Notes                                      |
|-------------------------------|--------|-------------------------------------------------------|--------------------------------------------|
| Infinite Health               | F1     | Holds player health at maximum and blocks damage      | Includes fall and environmental sources    |
| Infinite Stamina              | F2     | Prevents stamina loss from all actions                | Continuous sprint, climb and combat        |
| Infinite Weapon Durability    | F3     | Stops durability decrease on every equipped weapon    | Melee and ranged                           |
| Movement Speed ×2.5           | F4     | Multiplies run, dash and climb speed                  | Toggleable at any moment                   |
| No Fall Damage                | F5     | Nullifies all damage from height                      | Safe vertical play                         |
| Instant Self-Revive           | F6     | Forces immediate revive when downed                   | Private and custom sessions only           |
| Max Soulsmite Charge          | F7     | Keeps the Soulsmite meter at full                     | Ultimate ability always ready              |
| Freeze Nearby Bots            | F8     | Halts movement and attacks of nearby AI enemies       | Training and bot lobbies                   |
| Unlimited Grapple Uses        | F9     | Removes cooldown and charge limits on the grapple     | Continuous traversal                       |
| Hotkey Master Toggle          | F10    | Enables or disables the entire trainer at once        | Quick on/off                               |

### Compatibility
- OS: Windows 10 or Windows 11 64-bit  
- Game version: Current JS1 Myriad Season client (post-July 2026 updates)  
- Process: NarakaBladepoint.exe  
- Architecture: x64 only  
- Overlay: DirectX compatible  
- Limitations: Public ranked and matchmaking sessions carry extremely high detection and ban risk; later season updates that relocate core values will require new offsets.

### Installation
1. Extract the archive to a folder outside the game and launcher directories.  
2. Launch NARAKA: BLADEPOINT and enter a custom lobby or training area.  
3. Run the trainer executable.  
4. Press Insert to open the overlay.  
5. Enable modules with the listed hotkeys or the on-screen toggles.  
6. Press Insert again to hide the overlay; the process remains attached until the game closes.  
7. Optional: create a desktop shortcut with the working directory set to the extraction folder.

### Technical Risks
All activity is confined to process memory. The executable is never modified on disk, no permanent code is injected, and the tool generates no network traffic. On the current client the practical risks include:  
- Extremely high probability of permanent account restriction when used in any public or ranked match.  
- Temporary desynchronization of health, stamina or position after a server validation.  
- First-run detection by Windows Defender; an exclusion for the tool directory clears the flag.  
Private and training sessions have shown no permanent progress corruption when the trainer is disabled cleanly before exit.

### Questions
<details>
<summary>Does Infinite Stamina also cover the stamina cost of charged heavy attacks and dodges?</summary>
Yes. Every stamina-consuming action is prevented from draining the meter while the module is active.
</details>

<details>
<summary>Can Infinite Health and Movement Speed ×2.5 be used together without side effects?</summary>
Yes. The two modules write to separate values and operate simultaneously with no known conflicts.
</details>

<details>
<summary>Is Instant Self-Revive available in public matches?</summary>
No. The function is limited to private, custom and training sessions to avoid server-side rejection.
</details>

<details>
<summary>Does Freeze Nearby Bots affect real players in a private lobby?</summary>
No. Only AI-controlled bots are frozen. Human players remain fully controllable by their clients.
</details>

### Change Log
- 2026-07-24: Offsets refreshed for the latest JS1 Season client; health, stamina and weapon durability pointers verified.  
- 2026-07-23: Unlimited Grapple Uses added and confirmed.  
- 2026-07-20: Max Soulsmite Charge implemented after mapping the ultimate meter.  
- 2026-07-16: Public release matched to the post-July 16 update binary.  
- 2026-07-10: Movement Speed multiplier tested across current traversal mechanics.  
- 2026-07-05: Core vitality and stamina structures mapped for the current season.

### Closing
This NARAKA: BLADEPOINT Trainer 2026 is calibrated to the current JS1 Myriad Season client. Every listed module has been confirmed operational in private and training sessions. Offset updates required by later season patches will be recorded in the Change Log section.
