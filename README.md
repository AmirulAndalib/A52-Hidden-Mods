![a52banner](https://i.imgur.com/Xp3zFk2.png)
# A52-Hidden-Mods

Credit goes to the original creator UltraHQ [Github](https://github.com/UltraHQ) and Sloobot [Github](https://github.com/Sloobot) for porting to the A52. This is a continuation on Sloobot's work.

### Installation:
1. Download the module from the releases
2. Open the magisk app and go to modules
3. Click the "Install from storage" button and select the .zip you just downloaded 

> Note: It should only be used on the Galaxy A52 (SM-A526B) running the corresponding Android security patch version as written in the releases. Trying on other devices is at your own risk.<br/>The changes are always reversable, by simply removing the module in Magisk.

### Troubleshooting:
- If camera app crashes (or other issues like error on 64MP mode) please clear camera app data.
- If system apps start crashing, boot into your Recovery and on
  <details open>
  <summary>Stock recovery</summary>
  1. Wipe cache partition</br>2. Repair apps
  </details>
  <details open>
  <summary>TWRP recovery</summary>
  1. Wipe cache partition</br>2. Wipe dalvik cache
  </details>
- To make Object / Shadow / Reflection Eraser show, update [Samsung Photo Editor](https://www.apkmirror.com/apk/samsung-electronics-co-ltd/samsung-photo-editor/) by installing the latest APK.
- To fix Samsung Health root detection, I recommend using [SamsungAppsPatcher](https://adil.hanney.org/SamsungAppsPatcher/)

### Known bugs:
- None. Please report, if you find any

#### Added OS Features:
- Added Native AppLock (To open the app download Activity Launcher search for applock and open activity .settings.AppLockSettingsActivity)
- Higher Audio Quality (Disabled DRC, which deeply compresses audio)
- Disabled Samsung Marketing
- High-End Animations
- Enhanced CPU Responsiveness
- Added High Performance mode (also known as Enhanced Processing mode)
- Voice Recorder Interview mode
- AOD to Lockscreen Transition
- Full Edge Lighting
- Fixed Smart View (Normally broken on rooted devices)
- Enhance Photo Feature in Gallery
- S-Series Gallery Object Capture
- Codec support for APE, DSD and HDR10+ content
- Camera Privacy Toggle
- ADPS (Wi-Fi Power Saving)
- Enabled mDNIe
- Enabled Resolution changing (FHD, HD - only visible in Bixby Routines)
- Setting to limit battery charge to 85%
- Smart Widgets
- Samsung Smart Suggestions (Smart Calendar, Smart Widgets Auto Rotation, ..)
- Low Heat Mode
- Color Lens support
- HDR Effect support
- DSP Volume Monitoring
- Added Hearing aid compatibility
- Added S-Pen hovering detachment support

#### Added Camera Features:
- Extended pro (video) mode features: Histogram, Focus peaking, Zoom, Reset button, Expanded shutter speed
- Unlimited Video File Size
- EIS Support / Video stabilization @ 4K (Disable energy saving mode to avoid lag)
- AI Detail Enhancer feature (64MP mode)
- Object/Shadow/Reflection Eraser (Update [Samsung Photo Editor](https://www.apkmirror.com/apk/samsung-electronics-co-ltd/samsung-photo-editor/) to make it work, by installing the latest APK)
- Full Beauty features (Beauty in Live Focus, Beauty Brighten, Body Beauty, change skin tone)
- Torch Flash in Live Focus
- Review feature
- Audio Input Control (In pro video mode - Limitation: Only internal microphone)
- Improved Scene Detection
- S-Series AI-Models & AI Features
- Video Audio Zoom
- Full Intelligent Recognition (like Smart Scan Text Extraction)
- Full Live Focus (all S-Series effects)
- [Galaxy Watch Camera Controller](https://www.samsung.com/us/support/answer/ANS00084676/)
- Higher Gallery Zoom Quality
- Video Auto FPS
- Enabled Logical Camera
- Many, not worth to mention, additions
