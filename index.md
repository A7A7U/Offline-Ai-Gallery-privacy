Privacy Policy for AI Gallery
Last Updated: February 6, 2026

Introduction
Welcome to AI Gallery ("we," "our," or "us"). This Privacy Policy explains how we handle your information when you use our mobile application AI Gallery (the "App"). We are committed to protecting your privacy and keeping your personal data secure.

Our Privacy Commitment
AI Gallery is designed with privacy-first principles. All AI processing happens entirely on your device. We do not upload, transmit, or store your photos, videos, or audio files to any external servers.

Information We Collect
1. Device Permissions
The App requires the following permissions to function:

Permission	Purpose
Photos & Videos (READ_MEDIA_IMAGES, READ_MEDIA_VIDEO)	Display and organize your photo and video library with AI-powered categorization and search.
Partial Photo Access (READ_MEDIA_VISUAL_USER_SELECTED)	On Android 14+, allows you to grant access to only selected photos/videos instead of your entire library.
Audio (READ_MEDIA_AUDIO)	Access audio files for organization and playback.
Microphone (RECORD_AUDIO)	Voice search, voice commands, and audio recording for transcription.
Biometric/Fingerprint (USE_BIOMETRIC)	Optional app lock and secure vault authentication.
Internet	Download AI models for speech recognition (optional, user-initiated).
Notifications (POST_NOTIFICATIONS)	Notify you when background AI analysis is complete.
Foreground Service	Run AI processing in background while app is minimized.
Note: On Android 14 and later, you can choose to grant access to only selected photos and videos. The app fully supports this partial access mode.

2. On-Device AI Processing
AI Gallery uses on-device artificial intelligence to enhance your media experience:

Feature	Technology	Data Handling
Photo Categorization	Google ML Kit Image Labeling	Processed locally, never uploaded
Text Recognition (OCR)	Google ML Kit + Tesseract	Processed locally, never uploaded
Speech Transcription	Whisper (English) / Vosk (Arabic)	Processed locally, never uploaded
Portrait Mode Blur	Google ML Kit Selfie Segmentation	Processed locally, never uploaded
Image Enhancement	FFmpeg filters	Processed locally, never uploaded
3. AI Model Downloads
When you choose to enable speech transcription features, the App may download AI models from the following sources:

Whisper models from Hugging Face (huggingface.co)
Vosk models from AlphaCephei (alphacephei.com) and Hugging Face
Note: These downloads are optional and user-initiated. We only download the AI models themselves - your personal data is never transmitted.

4. Locally Stored Data
The App stores the following data locally on your device only:

Media file metadata and AI-generated tags (stored in encrypted Isar database)
App settings and preferences (using SharedPreferences)
Vault-protected files (encrypted with AES-256 encryption)
PIN codes and authentication settings (stored in secure encrypted storage)
Security Features
AI Gallery implements robust security measures to protect your sensitive data:

Feature	Description
Secure Vault	Hide sensitive files with AES-256-CBC encryption
Biometric Lock	Protect app access with fingerprint or face recognition
PIN Protection	Alternative 4-8 digit PIN for app access
Encrypted Storage	Sensitive settings stored in Flutter Secure Storage
Third-Party Services
Services Used
Service	Purpose	Data Shared
Google ML Kit	On-device image analysis and OCR	None - all processing is local
FFmpeg	Video/audio processing and filters	None - all processing is local
Tesseract OCR	Text recognition in images	None - all processing is local
Services NOT Used
We do not use any:

Analytics or user behavior tracking services
Cloud storage services for your personal data
Data brokers or data selling services
Advertising
The app may display advertisements for monetization purposes. However:

Advertisers do NOT have access to your photos, videos, or personal files
Your media files are NEVER shared with advertising networks
All AI processing remains 100% local regardless of ads
Data Sharing
We do not share your personal data with anyone.

Your photos, videos, and audio files never leave your device
AI analysis results are stored locally and never transmitted
We do not sell, rent, or share your data with third parties
Children's Privacy
AI Gallery does not knowingly collect personal information from children under 13 years of age. Since all data processing happens locally on the device and we do not collect any personal information from users, the App is suitable for users of all ages with parental supervision.

Your Rights and Control
Since all data stays on your device, you have complete control:

Right	How to Exercise
Access	View all your data directly within the App
Delete	Delete files directly, clear app data, or uninstall
Export	Share or export files using the system share feature
Vault Access	Move files in/out of the encrypted vault at any time
Disable AI	Turn off AI analysis in Settings at any time
Data Retention
On-device data: Retained until you delete it or uninstall the App
AI models: Stored locally until you delete them or uninstall the App
No cloud retention: We have no servers that store your personal data
Changes to This Policy
We may update this Privacy Policy from time to time. We will notify you of any changes by:

Updating the "Last Updated" date at the top of this policy
Providing in-app notification for significant changes
Contact Us
If you have any questions, concerns, or requests regarding this Privacy Policy or our privacy practices, please contact us at:

Email: 
a.m.m.alshami78@gmail.com

Developer: AI Edge Gallery Team

Summary
Question	Answer
Do you upload my photos?	❌ No, never
Is AI processing local?	✅ Yes, 100% on-device
Do you use analytics?	❌ No tracking whatsoever
Is my data sold?	❌ Never
Can I delete my data?	✅ Yes, full control
Is my vault secure?	✅ Yes, AES-256 encrypted
© 2026 AI Gallery. All rights reserved.
