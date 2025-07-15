# 🚀 CieloWeb on Google Play Store

CieloWeb is now available as a Progressive Web App (PWA) installable directly from the Google Play Store!

This page documents the process of preparing and publishing CieloWeb as a Trusted Web Activity (TWA) using open tools like PWABuilder, Firebase Studio, and Vercel.

---

## ✅ Why a Play Store App?

We wanted to give users:
- A native-feeling Android experience
- Easy access to tools from the home screen
- Automatic updates via the Play Store
- A fast, tracker-free alternative to bloated apps

---

## 🧩 Tech Stack Overview

- **Framework:** Next.js
- **Hosting:** Vercel (Frontend), Firebase (Backend Studio + Hosting)
- **App Shell:** PWA (manifest, service worker)
- **Android Wrapper:** Trusted Web Activity (TWA)
- **Build Tool:** [PWABuilder](https://www.pwabuilder.com/)

---

## 🛠 Steps to Publish on Play Store

1. **PWA Setup**
   - Created a complete `manifest.json` with maskable icons, shortcuts, and share targets
   - Verified the app is installable, offline-capable, and meets PWA standards

2. **PWABuilder Integration**
   - Generated platform-specific icons for Android, Windows, iOS
   - Exported the Android TWA ZIP template

3. **TWA Configuration**
   - Customized `AndroidManifest.xml` to point to `https://cieloweb.com`
   - Added asset links (`assetlinks.json`) to verify domain ownership via Firebase

4. **Firebase Studio + Console**
   - Used Firebase Hosting and `firebase.json` to configure proper headers for PWA support
   - Verified domain using `assetlinks.json` hosted at `/.well-known/assetlinks.json`

5. **Testing & Optimization**
   - Tested the app on multiple devices
   - Optimized page speed, PWA compliance, and offline fallback

6. **Play Store Prep**
   - Created app icon (512x512), feature graphic (1024x500), and screenshots
   - Filled in metadata, privacy policy, and content rating

7. **Final Deployment**
   - Uploaded AAB via Google Play Console
   - Passed all Play Store reviews and published as `CieloWeb – Tools for a Better Web`

---

## 📱 Get the App (Coming Soon)

Play Store Link: _Coming soon..._
Meanwhile you can download the apk at: https://drive.google.com/file/d/1alfDVmqdvOvvNiiDX5Xvlx1Ldx-VN9ix/view?usp=sharing
---

## 🧪 Learn More

- [https://cieloweb.com](https://cieloweb.com) — Homepage
- [info@cielowe]()
