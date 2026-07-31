# Privacy Policy for Offline AI Gallery

**Last Updated: July 31, 2026**

---

## Introduction

Welcome to Offline AI Gallery ("we," "our," or "us"). This Privacy Policy explains how we handle your information when you use our mobile application Offline AI Gallery (the "App"). We are committed to protecting your privacy and keeping your personal data secure.

---

## Our Privacy Commitment

**Offline AI Gallery is designed with privacy-first principles. All AI processing happens entirely on your device.** We do not upload, transmit, or store your photos, videos, or audio files to any external servers.

---

## Information We Collect

### 1. Device Permissions

The App requires the following permissions to function:

| Permission | Purpose |
|------------|---------|
| **All Files Access (MANAGE_EXTERNAL_STORAGE)** | Access and manage ALL media files across your device, including folders from WhatsApp, Telegram, Downloads, and custom camera apps. Required for comprehensive folder discovery, cross-directory file management, custom albums, and duplicate detection. |
| **Camera** | Capture new photos and videos (optional) |
| **Microphone** | Voice search, voice commands, and audio recording |
| **Biometric/Fingerprint** | Optional app lock and secure vault authentication |
| **Internet** | Download AI models, serve ads (free tier), verify Pro purchases, and optional user-initiated features |
| **Notifications** | Notify you when background AI analysis is complete |
| **Foreground Service** | Run AI processing in background |
| **Advertising ID (AD_ID)** | Used by Google AdMob to serve and measure ads in the free version of the App |

### 2. On-Device AI Processing

Offline AI Gallery uses on-device artificial intelligence to enhance your media experience:

| Feature | Technology | Data Handling |
|---------|------------|---------------|
| **Photo Categorization** | Google ML Kit Image Labeling | Processed locally, never uploaded |
| **Text Recognition (OCR)** | Google ML Kit + Tesseract | Processed locally, never uploaded |
| **Speech Transcription** | Whisper (English) / Vosk (Arabic) | Processed locally, never uploaded |
| **Portrait Mode Blur** | Google ML Kit Selfie Segmentation | Processed locally, never uploaded |
| **Image Enhancement** | FFmpeg filters | Processed locally, never uploaded |

### 3. AI Model Downloads

When you choose to enable speech transcription features, the App may download AI models from the following sources:

- **Whisper models** from Hugging Face (huggingface.co)
- **Vosk models** from AlphaCephei (alphacephei.com) and Hugging Face

> **Note:** These downloads are optional and user-initiated. We only download the AI models themselves - your personal data is never transmitted.

### 4. Locally Stored Data

The App stores the following data **locally on your device only**:

- Media file metadata and AI-generated tags (stored in encrypted Isar database)
- App settings and preferences (using SharedPreferences)
- Vault-protected files (encrypted with AES-256 encryption)
- PIN codes and authentication settings (stored in secure encrypted storage)
- Pro purchase status (cached locally after Google Play verification)

---

## Security Features

Offline AI Gallery implements robust security measures to protect your sensitive data:

| Feature | Description |
|---------|-------------|
| **Secure Vault** | Hide sensitive files with AES-256-CBC encryption |
| **Biometric Lock** | Protect app access with fingerprint or face recognition |
| **PIN Protection** | Alternative 4-8 digit PIN for app access |
| **Encrypted Storage** | Sensitive settings stored in Flutter Secure Storage |

---

## Third-Party Services

### Services Used

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| Google ML Kit | On-device image analysis and OCR | **None** - all processing is local |
| FFmpeg | Video/audio processing and filters | **None** - all processing is local |
| Tesseract OCR | Text recognition in images | **None** - all processing is local |
| **Google AdMob** | Display ads in the free version | Device advertising ID, IP address, app interaction data (no photos/videos/audio) |
| **AppLovin** (via AdMob mediation) | Additional ad inventory | Same as AdMob — no personal media |
| **Unity Ads** (via AdMob mediation) | Additional ad inventory | Same as AdMob — no personal media |
| **Firebase Crashlytics** | Anonymous crash reports to improve stability | Device model, OS version, stack traces (no photos, chat, or personal content) |
| **Google Play Billing** | Pro purchase and subscription verification | Purchase tokens via Google Play (no personal media) |

### What We Do NOT Do

- We do **not** upload your photos, videos, or audio to any server
- We do **not** sell your personal data
- We do **not** use cloud AI models for your content
- We do **not** share your media files with advertisers

### Advertising (Free Version)

The free version of the App displays advertisements through Google AdMob and its mediation partners (AppLovin, Unity Ads):

- Advertisers do **NOT** have access to your photos, videos, or personal files
- Your media files are **NEVER** shared with advertising networks
- All AI processing remains 100% local regardless of ads
- You can remove ads by purchasing **Ai-Gallery Pro** (monthly subscription or lifetime one-time purchase)
- In the European Economic Area (EEA), UK, and Switzerland, we use Google's User Messaging Platform (UMP) to obtain your consent before serving personalized ads. You can change your ad privacy preferences at any time in **Settings → How we protect your privacy → Ad Privacy Preferences**

---

## Data Sharing

**We do not share your personal media with anyone.**

- Your photos, videos, and audio files never leave your device
- AI analysis results are stored locally and never transmitted
- We do not sell, rent, or share your personal media with third parties

Third-party SDKs listed above may collect limited technical data (device type, advertising ID, crash logs) as described in their respective privacy policies:
- [Google Privacy Policy](https://policies.google.com/privacy)
- [AppLovin Privacy Policy](https://www.applovin.com/privacy/)
- [Unity Privacy Policy](https://unity.com/legal/privacy-policy)

---

## Children's Privacy

This App is intended for a general audience and is **not directed at children under 13**. We do not knowingly collect personal information from children. If you believe a child has provided us information, please contact us and we will delete it.

---

## Your Rights and Control

Since all media data stays on your device, you have complete control:

| Right | How to Exercise |
|-------|-----------------|
| **Access** | View all your data directly within the App |
| **Delete** | Delete files directly, clear app data, or uninstall |
| **Export** | Share or export files using the system share feature |
| **Vault Access** | Move files in/out of the encrypted vault at any time |
| **Disable AI** | Turn off AI analysis in Settings at any time |
| **Ad Preferences** | Modify or revoke ad personalization consent in Settings → Ad Privacy Preferences |
| **Remove Ads** | Purchase Ai-Gallery Pro or restore a previous purchase |

---

## Data Retention

- **On-device data**: Retained until you delete it or uninstall the App
- **AI models**: Stored locally until you delete them or uninstall the App
- **Crash reports**: Retained by Firebase per Google's retention policy (typically 90 days)
- **No cloud retention of your media**: We have no servers that store your personal files

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last Updated" date at the top of this policy
- Providing in-app notification for significant changes

---

## Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our privacy practices, please contact us at:

**Email:** a.m.m.alshami78@gmail.com

**Developer:** Offline AI Gallery Team

---

## Summary

| Question | Answer |
|----------|--------|
| Do you upload my photos? | No, never |
| Is AI processing local? | Yes, 100% on-device |
| Do you use analytics? | Crashlytics only (anonymous crashes, no personal content) |
| Do you show ads? | Yes, in the free version via AdMob (removable with Pro) |
| Is my data sold? | Never |
| Can I delete my data? | Yes, full control |
| Is my vault secure? | Yes, AES-256 encrypted |
| Can I opt out of personalized ads? | Yes, via Ad Privacy Preferences in Settings |

---

© 2026 Offline AI Gallery. All rights reserved.
