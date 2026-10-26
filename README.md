# 📸 Pixel 8 Pro GCam Ultra Mod

[![Device: Pixel 8 Pro](https://img.shields.io/badge/Device-Pixel%208%20Pro-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod)
[![Base: GCam v11.1](https://img.shields.io/badge/Base-Google%20Camera%2011.1-34A853?style=for-the-badge&logo=android&logoColor=white)](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod)
[![Status: Tested & Working](https://img.shields.io/badge/Status-Tested%20%26%20Working-FBBC05?style=for-the-badge)](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod)
[![License: Open Mod](https://img.shields.io/badge/License-Community%20Mod-EA4335?style=for-the-badge)](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod)

Hey everyone! 👋

Welcome to **Pixel 8 Pro GCam Ultra Mod**! 

I put a ton of love, late nights, and hands-on testing on my own **Pixel 8 Pro** to build this mod. Google’s stock camera is great, but they artificially restricted so many amazing hardware features (like locking cinematic blur to 2x, or giving us slow portrait processing). This mod unlocks those hidden capabilities and even ports over features from newer generation Pixels so we can get the most out of our cameras!

If you enjoy using this mod and it makes your camera experience better, **please drop a Star ⭐ on this repo** — it really means a lot and keeps me motivated to continue improving it for everyone! ❤️

---

## 🎯 The 10,000 Stars Goal — Support for Other Pixels Coming THIS WEEK!

> **Want this on your Pixel 7, 7 Pro, Pixel 6 / 6 Pro, or regular Pixel 8?**  
> Right now, every feature is tailored and live-tested specifically for the **Pixel 8 Pro**. However, I am ready to bring full support and custom tuning for **other Pixel devices THIS VERY WEEK** if this repo reaches **10,000 Stars ⭐**!  
> 
> Smash that star button at the top right, share it in your Pixel telegram groups, subreddits, and with your friends. Once we cross the milestone, multi-device builds are dropping immediately! 🚀🔥

---

## 🌟 What's New & Unlocked?

Here is what I've unlocked and tested live on the Pixel 8 Pro:

### 🎬 1. 5x Telephoto Cinematic Blur (Portrait Video)
- **The Problem:** By default, Google locks Cinematic Blur (Portrait Video) to digital zoom under 2x. You could never use the dedicated 5x telephoto periscope lens for cinematic video.
- **The Fix:** Unlocked the zoom cap up to 10x! Now when you record in Cinematic Blur mode, you can tap **5x** and shoot with the real optical periscope camera. The natural depth of field combined with AI bokeh looks straight out of a DSLR movie camera.

### ⚡ 2. Instant Portrait Processing
- **The Problem:** When snapping 5x or 2x portrait photos, the viewfinder thumbnail would freeze or show a blank white screen in Google Photos for 10 to 15 seconds while depth maps were calculating.
- **The Fix:** Shifted depth processing from slow CPU computation to high-speed GPU graphics acceleration. Your portraits now process smoothly in the background, and photos open smoothly when you tap the thumbnail!

### ✂️ 3. Next-Gen Bilateral Edge Detection
- Tuned the edge detection pipeline so fine hair strands, glasses frames, and complex clothing outlines stay sharp and natural without that artificial "halo" or smeared edges.

### 👥 4. Pixel 9 "Add Me" Mode Backported!
- Yes, the popular **"Add Me"** feature is right here in the camera mode switcher! Take a group shot, swap places with someone, take the second shot, and the built-in AI will seamlessly blend you into the group photo so nobody is left behind.

### 🌙 5. Night Sight Video & Low-Light Video Controls
- Easily accessible Night Sight video toggle right from the video mode options, giving you enhanced low-light clarity and tone mapping in dark environments.

### 📹 6. 4K 60FPS on All Cameras
- Unlocked 60 frames per second at 4K resolution on the front selfie camera and auxiliary sensors for ultra-smooth video recording.

### 🎙️ 7. Directional Audio Zoom & Wind Noise Masking
- Takes full advantage of the Pixel 8 Pro's 3 studio microphones. As you zoom in on a subject, the audio automatically focuses on their voice while suppressing background wind and city rumble.

### 🔍 8. Macro Focus Active Tracking
- When shooting macro close-ups using the Ultra-Wide lens, autofocus now dynamically locks on and tracks moving subjects (like insects or flowers swaying in the breeze).

### 🌌 9. Astrophotography Panorama
- Celestial panorama stitching in Night Sight mode for capturing wide starry night skies and the Milky Way.

### 🔢 10. Clean Viewfinder Zoom Stops
- Clean, convenient quick-tap zoom stops: **`.5`**, **`1x`**, **`1.5`**, **`2x`**, **`5`**, and **`10`**.

---

## 💡 Quick Heads Up After Shooting (Important — Don't Panic!)

> **A friendly tip after taking photos or videos:**  
> Right after snapping a high-resolution portrait or recording a video clip, **give it a quick couple of seconds before immediately tapping the gallery circle to view it**.  
> 
> Because this mod processes advanced neural depth maps, bilateral edge segmentation, and high-dynamic-range HDR+ tone mapping right on your device, it takes just a short moment to finalize rendering in the background. **This is completely normal and NOT a bug**, so don't worry if the thumbnail takes a brief moment to show the finished shot!

---

## ⚠️ Known Quirks & Work in Progress

- ⚠️ **Save to Project:** Currently, the *"Save to project"* option is not working as expected. Everything else (saving to Photos/Gallery, RAW, HDR+, Portrait, Video, etc.) works 100% fine. I am actively looking into this and will push a fix in the next update!

---

## 📲 How to Install (Easy Step-by-Step Guide)

You don't need root, and you **do NOT** need to uninstall your original camera! This mod is packaged to install completely independently alongside your stock Pixel camera without touching or overriding anything.

1. **Download:** Head over to the **[Releases](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod/releases)** tab on the right side of this page and download the latest `.apk` file.
2. **Install:** Tap on the downloaded APK file in your notification bar or Files app.
   - *If your phone asks for permission to install from unknown sources, tap **Settings** and toggle **Allow from this source**.*
3. **Open & Grant Permissions:** Launch the newly installed **Camera** app and grant standard permissions (Camera, Microphone, and Photos & Videos) so it can save your shots.
4. **Enjoy:** You're all set! Start shooting with unlocked 5x cinematic blur, instant portraits, and Add Me mode.

---

## 🐛 Found a Bug or Have a Suggestion?

Tested thoroughly on Pixel 8 Pro running the latest Android updates. If you run into any weird glitches, crashes, or have a cool feature idea, please open an **[Issue](https://github.com/mohdamaan1/Pixel8Pro-GCam-UltraMod/issues)** on GitHub. I read every single issue and will fix them in the upcoming releases!

If you like this project, **don't forget to star ⭐ this repository**! Enjoy taking photos! 📸✨

---
*Created with care by Mohd Amaan for the Pixel community.*
