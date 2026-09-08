# Privacy Policy for Dhvani

**Effective Date:** September 8, 2026  
**Last Updated:** September 8, 2026  

Dhvani ("we", "our", or "us") is an offline-first, privacy-respecting audio player application. This Privacy Policy describes how Dhvani handles information and permissions on your device.

---

### 1. Data Collection and Usage

**Dhvani does NOT collect, sell, rent, or monetize your personal data.**

- **Offline by Design**: Dhvani operates locally on your device. Your local music library, playlists, listening history, favorites, equalizer presets, and tags are stored strictly in local on-device databases (such as ObjectBox and shared preferences) and are never sent to our servers.
- **No Analytics or Trackers**: We do not integrate any third-party tracking, analytics, or behavioral monitoring SDKs.
- **No Advertisements**: Dhvani contains no advertisements and does not collect advertising IDs.

---

### 2. Device Permissions and Why We Need Them

To function as a media player, Dhvani requests the following permissions:

- **Audio / Media Storage (`READ_MEDIA_AUDIO`, `READ_EXTERNAL_STORAGE`)**:  
  Used solely to scan, index, and playback your locally stored music files and display cover art. Dhvani only reads audio files and does not access your photos, videos, or personal documents.
- **Foreground Service & Media Playback (`FOREGROUND_SERVICE_MEDIA_PLAYBACK`)**:  
  Required by Android to continue playing audio smoothly in the background when the app is minimized or when your screen is locked.
- **Notifications (`POST_NOTIFICATIONS`)**:  
  Used to display playback controls (play, pause, skip, track title, album art) in your device's notification shade and lock screen.
- **Wake Lock (`WAKE_LOCK`)**:  
  Prevents the system CPU from sleeping during active audio playback.

---

### 3. Network Communication

Dhvani requires internet access (`INTERNET`) solely for the following optional feature:

- **Lyrics Retrieval (LRCLIB)**:  
  When you view lyrics or tap "Auto-fetch from LRCLIB", Dhvani sends an anonymous HTTPS query containing only the song's title, artist, and duration to the public LRCLIB API to retrieve synchronized (`.lrc`) or plain text lyrics. No device identifiers, user accounts, or personal information are included in this request.

---

### 4. Children’s Privacy

Dhvani does not knowingly collect or solicit any personal information from children under the age of 13. Since no personal data is collected from any user, Dhvani is safe for all audiences.

---

### 5. Changes to This Policy

If we update our Privacy Policy, changes will be posted in this document and within the application's source repository.

---

### 6. Contact Us

If you have questions or feedback regarding this Privacy Policy, please open an issue on our GitHub repository:  
[https://github.com/1VikashChoudhary/Dhvani](https://github.com/1VikashChoudhary/Dhvani)
