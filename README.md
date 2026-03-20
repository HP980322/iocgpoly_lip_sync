# 🗣️ Blender Lip Sync Addon (Blender 5.0+)

Official Documentation: [docs.cgpoly.io](https://docs.cgpoly.io/lip-sync-documentation)

A powerful **Blender Extension** for automatic lip-syncing based on audio input. Updated for **Blender 5.0**, this version works cross-platform (Windows, macOS, Linux) and supports **~25 languages** out of the box.

⚡ **Optimized for the Blender 5.0 Extensions System.**

---

## 📺 Video Demo

https://github.com/user-attachments/assets/cb90ea7b-02fc-4ca1-b19f-631024cd79cd

https://github.com/user-attachments/assets/57ea3912-2d50-4090-ba49-3035ab673a05

*Animated Character by [Quaternius](https://poly.pizza/m/kKtL4zvS3n) | Wall Art by Jarlan Perez ([CC-BY](https://creativecommons.org/licenses/by/3.0/))*

---

## ✨ Features

- **🎤 Audio-to-Viseme:** Converts voice audio directly into animated mouth shapes.
- **📈 Smooth Interpolation:** Natural lip motion through shape key interpolation.
- **🖼️ Spritesheet Projection:** Projects viseme textures onto your character’s face (comes with a default set, or use your own).
- **🧠 Offline AI:** Uses private, offline speech recognition (**Vosk + Phonemizer + eSpeak**).
- **🖥️ True Cross-Platform:** Includes pre-compiled wheels for Windows, macOS (Intel/M1/M2), and Linux.
- **🔜 Roadmap:** Advanced **Pose-based animation** for complex facial rigs.

---

## 📦 Installation (Blender 5.0)

Blender 5.0 uses the new **Extensions** workflow. 

1. **Download the Release:** Grab the `iocgpoly_lip_sync.zip` from the [Releases](https://github.com/Charley3d/lip-sync/releases) page.
2. **Open Blender 5.0:** Go to `Edit > Preferences > Extensions`.
3. **Install from Disk:** Click the dropdown arrow in the top-right corner and select **Install from Disk...**.
4. **Select Zip:** Choose the downloaded file.

> **Note:** When you select a Language Model for the first time, a model file (~40MB) will be downloaded and cached automatically.

---

## 🛠️ How to Use

1. **Setup:** Import your 3D character and add your audio clip to the **Video Sequencer**.
2. **Access:** Find the **Lip Sync** tab in the **N-panel** (sidebar).
3. **Configure:** Select your language (30 available).
4. **Project:** Click **Add Spritesheet on Selection**.
5. **Define:** In **Edit Mode**, select the faces of the mouth and click **Set Mouth Area**.
6. **Bake:** Click **Analyze Audio**—your character is now synced!

---

## 🧩 Compatibility
- **Blender Version:** 5.0 or newer (uses Python 3.11+ requirements).
- **OS:** Windows x64, macOS (Intel & Silicon), Linux x64.

---

## 📜 License & Credits

- **Original Creator:** [Charley 3D](https://github.com/charley3d)
- **5.0 Port & Maintenance:** [HP3D](https://github.com/HP980322) (rjblwhp@gmail.com)
- **License:** [GNU General Public License v3.0 or later](https://spdx.org/licenses/GPL-3.0-or-later.html)