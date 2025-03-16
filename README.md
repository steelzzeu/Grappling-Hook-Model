### **README - Steelzz Grappling Hook Model for FiveM**  

#### **Description**  
This resource replaces the **Compact Grenade Launcher (`WEAPON_COMPACTLAUNCHER`)** with a custom model to be used with the **Steelzz Grappling Hook script**. The model is sourced from GTA5-Mods and has been configured to work seamlessly in FiveM.  

#### **Model Source**  
📌 **Original Model:** [Bak Gadgets Pack I](https://www.gta5-mods.com/weapons/bak-gadgets-pack-i)  
📌 **Converted & Optimized for FiveM by:** Steelzz  

---

### **Installation Instructions**  

#### **1. Add the Resource to Your Server**  
1. **Extract the `grapplegun` folder** into your FiveM `resources/` directory.  
   ```
   resources/
   ├── [weapons]/
   │   ├── grapplegun/
   │   │   ├── fxmanifest.lua
   │   │   ├── stream/
   │   │   │   ├── w_lr_compactgl.ydr
   │   │   │   ├── w_lr_compactgl_hi.ydr
   │   │   │   ├── w_lr_compactgl.ytd
   │   │   │   ├── w_lr_compactgl+hi.ytd
   │   │   ├── data/
   │   │   │   ├── weapon.meta
   │   │   │   ├── weaponarchetypes.meta
   │   │   │   ├── weaponanimations.meta
   │   │   │   ├── weaponcomponents.meta
   │   │   │   ├── shop_weapon.meta
   ```
   
2. **Ensure the Resource is Loaded**  
   - Open `server.cfg` and **add the following line**:
     ```
     ensure grapplegun
     ```

3. **Restart Your FiveM Server**  
   - Either restart the entire server or use the command:  
     ```
     restart grapplegun
     ```

---

### **How to Use the Grappling Hook in FiveM**  
- This resource **only replaces the weapon model**.  
- To use it as a **grappling hook**, install the **Steelzz Grappling Hook script** (separate script).  
- Equip the **Compact Grenade Launcher** in-game, and it will be visually replaced with the grappling hook.

---

### **Troubleshooting & FAQ**  
#### ❓ The weapon model is not replacing correctly  
✅ **Fix:** Ensure the correct file names are used (`w_lr_compactgl.ydr`, etc.), and clear FiveM cache before restarting the server.

#### ❓ The weapon is invisible  
✅ **Fix:** Double-check the `fxmanifest.lua` file to ensure the **`stream/` folder is referenced correctly** and **meta files are properly loaded**.

#### ❓ The weapon does not function as a grappling hook  
✅ **Fix:** This is a **model replacement only**. You need to install the **Steelzz Grappling Hook script** separately.

---

### **Credits**  
- **Model Creator:** Bak Gadgets Pack I ([GTA5-Mods Link](https://www.gta5-mods.com/weapons/bak-gadgets-pack-i))  
- **FiveM Conversion & Integration:** Steelzz  
- **GTA V & FiveM API References:** [FiveM Documentation](https://docs.fivem.net/docs/)  

---

### **License & Usage**  
This model is **not owned** by Steelzz. It has been **sourced from GTA5-Mods** and is being used for FiveM purposes under fair use. Please support the original creator by visiting their **GTA5-Mods page**.  

---

Enjoy the grappling hook experience! 🚀 If you have any issues, feel free to reach out. 😊
