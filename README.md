![apex optimized logo](https://cdn.modrinth.com/data/cached_images/41b49ff81de3b428583987b267386fcfe57c3830.jpeg)
## Apex Optimized Modpack

**Apex Optimized** is a Minecraft modpack made to improve your game’s performance by removing unnecessary mods found in other performance packs like **Fabulously Optimized**. It focuses on providing a smoother and more stable experience while keeping the game fun. This modpack is perfect for players who want to reduce lag and enhance gameplay without extra bloat.


---

### **List of Included Mods**  

<details>  
<summary>Performance Enhancing Mods</summary>  

- **[FerriteCore](https://modrinth.com/mod/ferrite-core)**  
- **[Cubes Without Borders](https://modrinth.com/mod/cubes-without-borders)**  
- **[Alternate Current](https://modrinth.com/mod/alternate-current)**  
- **[Sodium](https://modrinth.com/mod/sodium)**  
- **[ImmediatelyFast](https://modrinth.com/mod/immediatelyfast)**  
- **[Forge Config API Port](https://modrinth.com/mod/forge-config-api-port)**  
- **[No Chat Reports](https://modrinth.com/mod/no-chat-reports)**  
- **[Concurrent Chunk Management Engine (Fabric)](https://modrinth.com/mod/c2me-fabric)**  
- **[Bobby](https://modrinth.com/mod/bobby)**  
- **[ModernFix](https://modrinth.com/mod/modernfix)**  
- **[Remove Reloading Screen](https://modrinth.com/mod/rrls)**  
- **[Entity Culling](https://modrinth.com/mod/entityculling)**  
- **[Chunky](https://modrinth.com/mod/chunky)**  
- **[Mouse Tweaks](https://modrinth.com/mod/mouse-tweaks)**  
- **[Fast Better Grass](https://modrinth.com/resourcepack/fast-better-grass)**  
- **[Reese's Sodium Options](https://modrinth.com/mod/reeses-sodium-options)**  
- **[Better Beds](https://modrinth.com/mod/better-beds)**  
- **[Fast IP Ping](https://modrinth.com/mod/fast-ip-ping)**  

</details>  

<details>  
<summary>Utility & Debugging Mods</summary>  

- **[spark](https://modrinth.com/mod/spark)**  
- **[Mod Menu](https://modrinth.com/mod/modmenu)**  
- **[More Culling](https://modrinth.com/mod/moreculling)**  
- **[Fabric API](https://modrinth.com/mod/fabric-api)**  
- **[Debugify](https://modrinth.com/mod/debugify)**  
- **[BadOptimizations](https://modrinth.com/mod/badoptimizations)**  
- **[Sodium Extra](https://modrinth.com/mod/sodium-extra)**  
- **[Clumps](https://modrinth.com/mod/clumps)**  
- **[Enhanced Block Entities](https://modrinth.com/mod/ebe)**  
- **[bad packets](https://modrinth.com/mod/badpackets)**  
- **[Cloth Config API](https://modrinth.com/mod/cloth-config)**  
- **[Text Placeholder API](https://modrinth.com/mod/placeholder-api)**  
- **[Very Many Players (Fabric)](https://modrinth.com/mod/vmp-fabric)**  
- **[YetAnotherConfigLib (YACL)](https://modrinth.com/mod/yacl)**  

</details>  

<details>  
<summary>Other Performance Mods</summary>  

- **[Cull Leaves](https://modrinth.com/mod/cull-leaves)**  
- **[Lithium](https://modrinth.com/mod/lithium)**  
- **[Krypton](https://modrinth.com/mod/krypton)**  
- **[e4mc](https://modrinth.com/mod/e4mc)**  
- **[Dynamic FPS](https://modrinth.com/mod/dynamic-fps)**  
- **[Noisium](https://modrinth.com/mod/noisium)**  

</details>

---

## benchmark test
Since my personal PC is not powerful enough to run proper benchmarks, I ran the tests at a cybercafe to ensure fair results.
### System Specifications (Cybercafé PC):

**CPU**: Intel Core i5-9400F

**GPU**: NVIDIA GeForce GTX 1050 Ti

**RAM**: 8GB DDR4 2666MHz

**Storage**: SSD 1TB

**OS**: Windows 10 Home


### **Benchmark Results:**

| Test Scenario              | Sodium Only | Apex Optimized |
| -------------------------- | ----------- | -------------- |
| **Spawn Area (FPS)**       | 84 FPS      | 137 FPS        |
| **Exploration (FPS)**      | 73 FPS      | 128 FPS        |
| **High-Entity Area (FPS)** | 46 FPS      | 92 FPS         |
| **RAM Usage (Idle)**       | 2.2GB       | 2.0GB          |
| **RAM Usage (Load)**       | 3.9GB       | 3.5GB          |

---

### **Observations:**

- *Apex Optimized* performs **30-50% better** in FPS tests compared to using *Sodium* alone.
- RAM usage is **low**, so its a better option for lower-end systems.
- Loading times and chunk rendering are significantly improved due to **C2ME** and **Starlight** optimizations.

### How to Install Apex Optimized Modpack

#### **Option 1: Using the Modrinth .mrpack File**
1. **Download the modpack:**
   - Download the **Apex Optimized** `.mrpack` file from the [Modrinth page](https://modrinth.com/modpack/apex-optimized).
2. **Install the Modrinth Launcher (if you don’t have it):**
   - Go to the [installation page](https://modrinth.com/app) and download the **Modrinth Launcher**.
3. **Install the modpack:**
   - Open the Modrinth Launcher.
   - Click on **Add a modpack** and select the `.mrpack` file you downloaded.
   - The launcher will automatically install all the mods included in the pack.
4. **Launch the game:**
   - Once the modpack is installed, select it in the Modrinth Launcher and hit **Play** to start Minecraft with the modpack.

#### **Option 2: Manual Installation (Vanilla Method with .mrpack to .zip conversion)**
1. **Convert the .mrpack file to .zip:**
   - Use one of these sites to convert the `.mrpack` file to a `.zip` file:
     - [mrpack to zip converter](https://fabulously-optimized.github.io/mrpack-to-zip/)
     - [ Jamie Mansfield Converter](https://jamie.codeberg.page/mrpack-to-zip/@master/)
2. **Install Fabric:**
   - Download and install the **Fabric loader** from the [Fabric website](https://fabricmc.net/use/).
   - Ensure you have the **Fabric API** installed (it is included in the modlist).
3. **Extract the modpack:**
   - Once converted to `.zip`, extract the contents of the zip file.
   - Move the extracted folder to your **Minecraft** directory.
4. **Move the mods into the mods folder:**
   - Navigate to your Minecraft installation folder.
   - Open the **mods** folder. If it doesn’t exist, create one.
   - Copy and paste all the extracted `.jar` files into the mods folder.
5. **Launch the game:**
   - Open the Minecraft Launcher.
   - Select the **Fabric profile** and press **Play** to launch Minecraft with the mods.
