<p align="center">
 <img width="138" height="138" alt="image_resized (13)" src="https://github.com/user-attachments/assets/e0cbbfe0-1091-4447-9b70-11b449128300" />


</p>

<h1 align="center">AudioStore 🎵</h1>

<p align="center">
  <strong>A flagship-level, ad-free Android music streaming and offline playback experience.</strong>
</p>

<p align="center">
  <a href="https://github.com/Shreyas445/AudioStore/releases"><img src="https://img.shields.io/github/v/release/Shreyas445/Audio-Store-App?color=13CA5C&style=for-the-badge" alt="Release"></a>
  <img src="https://img.shields.io/badge/Kotlin-1.9+-blue.svg?logo=kotlin&style=for-the-badge" alt="Kotlin">
  <img src="https://img.shields.io/badge/Jetpack%20Compose-Material%203-4285F4?logo=android&style=for-the-badge" alt="Compose">
  <img src="https://img.shields.io/badge/Media3-ExoPlayer-FF0000?logo=youtube&style=for-the-badge" alt="Media3">
</p>

---

## 📖 About The Project

**AudioStore** is an open-source based, premium Android music player built entirely with Jetpack Compose and AndroidX Media3. It seamlessly blends remote YouTube audio streaming with pristine iTunes metadata, offering a beautiful, fluid, state-aware, and completely ad-free user experience.

Built for audiophiles and engineered for performance, it features 1:1 physics-based gestures, deep state persistence, and a custom "Metadata Scrubber" that transforms raw streaming data into a flawless local library.

<br>
<br>

<p align="center">
  <a href="https://github.com/Shreyas445/Audio-Store-App/releases/download/v1.0.0/AudioStore.apk">
    <strong>⬇️ Download AudioStore App</strong>
  </a>
</p>

<br>

## ✨ Key Features

### 🎨 Flagship UI & UX
* **Dynamic Contextual Theming:** Extracts the dominant color from the current album art via the Palette API to generate a Spotify-style fading mesh gradient.
* **1:1 Physics-Based Gestures:** Custom math-driven Animatable UI for the full-screen player and "Up Next" drawer. Swipe down to minimize, flick up to reveal the queue—zero frame drops on 120Hz displays.
* **Glassmorphic Mini-Player:** An edge-to-edge floating player that perfectly syncs progress with the background service.
* **Pill Navigation:** A modern, custom-built bottom navigation bar with smooth expansion animations.

### 🎧 Advanced Playback Engine
* **Media3 & ExoPlayer:** Bulletproof background playback with full Android 13+ Notification and Lock Screen control support.
* **Auto-Radio Queue:** Automatically fetches similar tracks (via Last.fm & YouTube Related) to keep the music playing infinitely.
* **Live Audio Control:** Supports Shuffle, Repeat (All/One), and live Playback Speed adjustment (0.5x to 2.0x).
* **Drag-and-Drop Reordering:** Long-press and drag any track in the queue to instantly reorder your listening session.

### 🧹 The "Metadata Scrubber"
AudioStore intercepts raw YouTube video titles and channels, cross-referencing them with the iTunes API. This system automatically:
* Strips out clickbait tags (e.g., "[OFFICIAL VIDEO]", "Lyrics").
* Injects high-resolution 600x600 square album art.
* Restores pristine Artist and Title formatting.

### 💾 Local Library & Offline Persistence
* **Deep State Memory:** Uses Kotlin Preferences DataStore to remember your exact Queue, Current Track, and Last Session across app restarts.
* **Secret Offline Downloads:** Invisibly fetches raw `.m4a` audio and `.jpg` thumbnails, bypassing the network entirely for local playback.
* **Smart Search:** YouTube-powered search with live debouncing, auto-keyboard focus, and persistent search history.

---

## 📸 Screenshots



<p align="center">
  <img width="22%" alt="WhatsApp Image 2026-06-22 at 2 18 41 AM" src="https://github.com/user-attachments/assets/4097e26f-d3c6-437e-a4b5-581dd1db9079" /> &nbsp;
 <img width="22%" height="1600" alt="WhatsApp Image 2026-06-22 at 3 06 12 AM" src="https://github.com/user-attachments/assets/71c687c2-c45f-4fe8-805b-902bbe26f3cc" /> &nbsp;
  <img width="22%" alt="WhatsApp Image 2026-06-22 at 2 18 47 AM" src="https://github.com/user-attachments/assets/cdac664a-2b58-46f1-bdaf-0143b5d4b7ba" /> &nbsp;
  <img width="22%" alt="WhatsApp Image 2026-06-22 at 2 18 57 AM" src="https://github.com/user-attachments/assets/7ed19985-d0dc-4a68-8f2e-8d4458f52d48" />



 
</p>

---

## 🛠️ Tech Stack & Architecture

AudioStore is built using modern Android development practices:

* **UI Toolkit:** [Jetpack Compose](https://developer.android.com/jetpack/compose) & Material 3
* **Media Engine:** [AndroidX Media3](https://developer.android.com/guide/topics/media/media3) (ExoPlayer & MediaSessionService)
* **Image Loading:** [Coil](https://coil-kt.github.io/coil/) & AndroidX Palette API
* **Network & Data:** [OkHttp3](https://square.github.io/okhttp/), Gson, and [NewPipe Extractor](https://github.com/TeamNewPipe/NewPipeExtractor)
* **Local Storage:** Kotlin Preferences DataStore
* **Concurrency:** Kotlin Coroutines & Flow

---


