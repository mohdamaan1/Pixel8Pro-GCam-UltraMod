# 📸 Google Pixel GCam Ultra Mod — v1.1 Multi-Device & Log Video Edition

[![Supported: Pixel 6 to 10 Series](https://img.shields.io/badge/Devices-Pixel%206%20to%2010%20Series-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod)
[![Base: GCam v11.1](https://img.shields.io/badge/Base-Google%20Camera%2011.1-34A853?style=for-the-badge&logo=android&logoColor=white)](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod)
[![Version: v1.1 Universal](https://img.shields.io/badge/Version-v1.1%20Universal-FBBC05?style=for-the-badge)](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod/releases)
[![Root: Not Required](https://img.shields.io/badge/Root-Not%20Required-EA4335?style=for-the-badge)](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod)

Hey everyone! 👋

Welcome to **v1.1 of the GCam Ultra Mod**! 

After extensive testing and community feedback on our Pixel 8 Pro release, this update expands the mod into a **Universal Multi-Pixel Build** and unlocks the long-awaited **10-bit Log / Flat Video (Sapphire Engine)** alongside hardware-accelerated portrait depth processing across Google Tensor generations!

If you find this mod useful, **please drop a Star ⭐ on this repository** — it directly fuels continuous development, bugfixes, and tuning for our entire Pixel community! ❤️

---

## 📱 Device Support & Feature Compatibility Matrix

This release includes the new dynamic **Universal Hardware Interceptor (`TomteInitHelper`)**. Whether you are rocking a flagship Pro with a dedicated periscope lens or a compact base/a-series model, features are automatically tuned for your device's camera sensors and Tensor ISP:

| Device Model | Tensor Chip | Dedicated 5x Telephoto | 5x Optical Portrait & Cinematic Blur | 10-bit Log Video (HLG/Rec.2020) | Pixel 9 "Add Me" Mode | GPU OpenCL Instant Portrait |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Pixel 8 Pro** *(Primary Test Device)* | Tensor G3 | ✅ Yes (48MP) | ✅ Unlocked (Up to 10x) | ✅ Full Support | ✅ Active | ✅ Accelerated |
| **Pixel 9 Pro / 9 Pro XL** | Tensor G4 | ✅ Yes (48MP) | ✅ Full Support | ✅ Full Support | ✅ Native | ✅ Accelerated |
| **Pixel 10 Pro / 10 Pro XL** | Tensor G5 | ✅ Yes (48MP) | ✅ Full Support | ✅ Full Support | ✅ Native | ✅ Accelerated |
| **Pixel 7 Pro** | Tensor G2 | ✅ Yes (48MP) | ✅ Unlocked | ✅ Full Support | ✅ Backported | ✅ Accelerated |
| **Pixel 8 / Pixel 8a** | Tensor G3 | ❌ Dual Sensor | 🔹 Super-Res Crop | ✅ Full Support | ✅ Backported | ✅ Accelerated |
| **Pixel 7 / Pixel 7a** | Tensor G2 | ❌ Dual Sensor | 🔹 Super-Res Crop | ✅ Full Support | ✅ Backported | ✅ Accelerated |
| **Pixel 6 / 6 Pro / 6a** | Tensor G1 | 🔹 (4x on 6 Pro) | 🔹 Hardware Dependent | ✅ Full Support | ✅ Backported | ✅ Accelerated |
| **Pixel 9 / Pixel 9a** | Tensor G4 | ❌ Dual Sensor | 🔹 Super-Res Crop | ✅ Full Support | ✅ Backported | ✅ Accelerated |
| **Pixel 10 / Pixel 10a** | Tensor G5 | ❌ Dual Sensor | 🔹 Super-Res Crop | ✅ Full Support | ✅ Backported | ✅ Accelerated |
| **Pixel Fold / 9 Pro Fold** | Tensor G2/G4 | ✅ Telephoto | ✅ Unlocked | ✅ Full Support | ✅ Active | ✅ Accelerated |

> *Note: 5x Optical Telephoto shooting requires devices equipped with physical periscope hardware (Pro series). On dual-camera models (Base & A-series), portrait mode defaults to clean 1x and 2x in-sensor optical crops.*

---

## 🌟 What's Unlocked & New in v1.1?

### 🎬 1. 10-bit Log / Flat Video (Comice & Sapphire Engine)
- **The Magic:** Unlocked Google's internal **`COMICE` + `SAPPHIRE`** video pipeline. Instead of baking in aggressive Rec.709 contrast and crushing your shadows or blowing out sky highlights, the camera records in a flat **10-bit Rec.2020 HLG container**.
- **For Creators:** Perfect for grading in DaVinci Resolve, Final Cut Pro, or Adobe Premiere with your own cinematic LUTs. Full dynamic range preserved directly off the sensor.

### 🔭 2. 5x Optical Telephoto in Portrait Mode & Cinematic Blur
- **The Problem:** Stock Google Camera artificially locks Cinematic Blur (Portrait Video) to digital zoom below 2x, completely disabling the physical 5x periscope telephoto camera.
- **The Fix:** Removed the digital cap and unlocked the telephoto pipeline up to 10x! Now you can shoot cinematic portrait video and portrait photos with real optical compression and genuine optical bokeh.

### ⚡ 3. Instant GPU-Accelerated Portrait Processing
- **The Problem:** Snapping portrait photos previously resulted in a 10 to 15-second thumbnail freeze or white blank screen in Google Photos while CPU computed dense depth maps.
- **The Fix:** Redirected neural depth map generation directly to the **ARM Mali GPU OpenCL pipeline** (`camera.gouda.depth_use_opencl = 1`). Portraits now process seamlessly in the background without locking your gallery.

### ✂️ 4. Pixel 11 Bilateral Edge Segmentation (Firefly Engine)
- Backported the next-gen **Firefly bilateral edge detection** (`camera.gouda.firefly_enabled = 1`). Fine hair strands, spectacles, jewelry, and intricate edge silhouettes are rendered with natural, gradual fall-off rather than harsh cutout borders.

### 👥 5. Pixel 9 "Add Me" Mode Backported
- The headline Pixel 9 AI feature is active across Tensor generations! Take a group picture, swap places with the photographer, take the second picture, and on-device AI blends everyone together into a single flawless shot.

### 🌙 6. Night Sight Video & Astrophotography Panorama
- Quick-toggle Night Sight video directly inside video mode options for cleaner low-light tone mapping, plus panoramic celestial stitching for starry skies and the Milky Way.

### 📹 7. 4K 60FPS Across Sensors
- Unlocked 60 frames per second recording at full 4K UHD resolution across primary, front selfie, and auxiliary lenses.

### 🎙️ 8. Directional Audio Zoom & Noise Shield
- Uses beamforming studio microphone arrays to focus audio directly on your zoomed-in subject while filtering out background wind noise.

### 🔢 9. Clean Quick-Tap Viewfinder Stops
- Fast tactile stops on the viewfinder: **`.5`**, **`1x`**, **`1.5`**, **`2x`**, **`5`**, and **`10`**.

---

## 💡 Quick Heads-Up When Shooting (Important — Don't Panic!)

> **A friendly tip after taking photos or videos:**  
> Right after snapping a high-resolution portrait or recording a high-bitrate video clip, **give it a quick second or two before immediately tapping the gallery thumbnail circle**.  
> 
> Because this mod computes advanced neural depth maps, bilateral edge segmentation, and multi-frame HDR+ tone curves on-device, it takes just a brief moment to finalize rendering in the background. **This is completely normal and NOT a bug**, so don't worry if the thumbnail takes a short moment to show the finished result!

---

## ⚠️ Known Quirks & Ongoing Work

- ⚠️ **Save to Project:** The experimental *"Save to project"* option in the creator tab is currently undergoing refactoring. Standard saving to Google Photos, Gallery, RAW (DNG), HDR+, Portrait, and 4K Video functions 100% reliably.

---

## 📲 How to Install (Zero Root Required)

This mod is signed and packaged with an independent package namespace (`com.google.android.GoogleCamera.amaan`). It **will NOT overwrite or replace your original camera app** — both will happily coexist side-by-side on your phone!

1. **Download:** Go to the **[Releases](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod/releases)** section and download:  
   📦 **`GCam_v11.1_UltraMod_v1.1_AllPixels.apk`**
2. **Install:** Tap the downloaded file in your browser or Files app. If prompted, toggle *Allow installation from this source*.
3. **Launch & Grant Permissions:** Open the app and grant Camera, Audio, and Storage permissions so it can save your captures.
4. **Enjoy:** Start shooting with unlocked 5x portrait zoom, 10-bit Log video, and Add Me mode!

---

## 🎯 10,000 Stars Milestone Goal ⭐

Help our community grow! If this project reaches **10,000 Stars ⭐**, dedicated custom XML config tuners and specialized lens calibration profiles will be released for every individual Pixel device model. Share it with your friends and fellow Pixel users!

---

## 🐛 Issues & Feedback

Found a bug or have a suggestion? Open an **[Issue](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod/issues)** on GitHub. Every issue is reviewed to keep improving the camera experience for all Pixel devices.

*Engineered with passion by Mohd Amaan for the Pixel community.*
