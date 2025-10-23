# 🌌 Ascension 3.3.5a – Bronzebeard Ultra-HD Mod Pack

Complete Ultra-HD overhaul for **Ascension 3.3.5a (Bronzebeard & Classless)**.
Features textures and models beyond Ascension’s default HD pack, with fully upscaled assets, advanced lighting, and much more.

<p align="center">
  <img src="https://i.imgur.com/s1qI9Ue.png" width="32%" />
  <img src="https://imgur.com/NyXAqvX.png" width="32%" />
  <img src="https://i.imgur.com/p4TZUaG.png" width="32%" />
</p>
<p align="center">
  <img src="https://imgur.com/w4hpjGK.png" width="32%" />
  <img src="https://imgur.com/a/Xy5nUSf" width="32%" />
</p>

You **must have Ascension’s HD patch enabled** in the launcher.

**DXVK is highly recommended enabled** in the launcher.

Changelog: **[Version 2.0](https://github.com/fueryin/BRONZEBEARD-ULTRA-HD-MOD-PACK/blob/Changelog/Changelog.md)**

---

## 🧩 Patch Loadout

These are the **custom patches**, `.MPQ` mods that enhance visuals, audio, and gameplay — all stored in your game’s `\Data` folder:

```
Patch-4.MPQ – Abilities & Spells
Patch-5.MPQ – Ascension's HD file (from launcher)
Patch-6.MPQ – Ascension's HD file (from launcher)
Patch-ZZ10.MPQ – Reznik's Shaders
Patch-ZZ11.MPQ – Reznik's Blood Mod
Patch-ZZ12.MPQ – Old World Music Rescore
Patch-ZZ20.MPQ – Some Texture upscales
Patch-ZZ21.MPQ – Appletrey’s HD models
Patch-ZZ22.MPQ – Shadowlands downports
Patch-ZZ30.MPQ – Fire eye of the storm
Patch-ZZ40.MPQ – HD Skyboxes
Patch-ZZ50.MPQ – x2 Fishing Bobbler
Patch-ZZ60.MPQ – Kingdom of Stormwind Reskin
Patch-ZZ70.MPQ – Lord of the Rings Soundtrack
```

✅ **Works with any 3.3.5a client** — just remove Ascension’s HD files `Patch-5.MPQ` and `Patch-6.MPQ` before installing.

---

## 🖼️ Extra Content

* **HD Icons** – Sharper UI icons (`Interface` folder)
* **Custom ReShade Preset** – MXAO + sharpening (requires ReShade *addon* build)
* **Config File** – Maxed graphics / view distance (ensure `SET gxResolution` matches your display)
* **Optional Addons** – Blood-on-crit effect, dance music, Leatrix Plus
* **Updated DXVK and custom .conf file** – Optimized for smoother gameplay and Alt-Tab stability

---

## 📥 Installation

Place all files into:

```
C:\Program Files\Ascension Launcher\resources\client\
```

✅ Overwrite existing files when prompted.

---

### 🎨 ReShade Setup (Optional)

1. Download 👉 **ReShade_Setup_6.6.1_Addon.exe**: [https://reshade.me/downloads/ReShade_Setup_6.6.1_Addon.exe](https://reshade.me/downloads/ReShade_Setup_6.6.1_Addon.exe)
2. Target `Ascension.exe`
3. Choose **Vulkan** (with DXVK) or **DirectX9** (without)
4. Check *all shaders*
5. Launch Bronzebeard → press **HOME** → select preset

---

### 🧭 Pixel Perfect Scaling (Optional)

For sharper UI at high resolutions:
Right-click `Ascension.exe` → **Properties → Compatibility → Change high DPI settings**,
then enable **Override high DPI scaling behavior** and set it to **Application**.

---

### ⚙️ Disable Admin Rights (Optional)

If **Discord push-to-talk** doesn’t work while Ascension is open, it’s because the launcher runs with admin rights.
Fake normal privileges for the launcher with this one-time tweak:

```powershell
$exe = "C:\path\to\Ascension Launcher.exe"
$key = "HKCU:\Software\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Layers"
New-Item -Path $key -Force | Out-Null
New-ItemProperty -Path $key -Name $exe -Value "RunAsInvoker" -PropertyType String -Force | Out-Null
"Set RunAsInvoker for $exe"
```

Open **Windows PowerShell ISE** (not as admin), **View → Show Script Panel**, paste, and click the **green run** button.
You only need to do this once.

---

## 🔗 Download

📦 **Google Drive Download**
[https://drive.google.com/drive/folders/1OPvNFYb5IZxqbhy1khCDNsqNG0Oa1gAq?usp=drive_link](https://drive.google.com/drive/folders/1OPvNFYb5IZxqbhy1khCDNsqNG0Oa1gAq?usp=drive_link)

**If Google reports a download limit:**

```text
1) Create a new folder in your Google Drive.
2) Open the download folder, right-click the file, select “Add shortcut to Drive”,
   and choose the folder you just created.
3) Go back to My Drive, right-click your new folder, and select Download.
```

⚠️ Sometimes Google renames files on download — ensure names are correct

---

## 🎖️ Credits

All credit goes to the **original mod authors** and the amazing **WoW modding community** that keeps these alive.

---

💬 I’m open to collaboration — reach me on Discord: **akuru_001**

---

<h2 align="center">⚡ <b>THIS SETUP IS COMPLETELY SAFE TO USE</b> ⚡</h2>

<p align="center"><b>
Custom .MPQ patches have been part of World of Warcraft modding for over a decade and are UNDETECTABLE by the Ascension client.<br>
YOU CANNOT BE BANNED FOR USING THEM.
</b></p>
