# Plex Public Domain Streams 🎬

This repository shows how to add *public-domain movies* from the [Internet Archive](https://archive.org) into *Plex Media Server* using lightweight .strm files.

Instead of downloading large video files, .strm files point Plex directly to a streaming URL — saving space while keeping your library full of content.

---

## 📖 Features
- Integrates *public-domain films* directly into Plex
- .strm files act like bookmarks but appear as normal Plex items
- Works with *Remote Access* so you can stream outside your home network
- No need for third-party plugins — pure Plex functionality

---

## 🛠️ Setup

### 1. Get a direct stream URL
1. Go to a movie’s page on the [Internet Archive](https://archive.org).  
2. Click *“SHOW ALL”* under *Download Options*.  
3. Right-click a video file (e.g., .mp4) → *Copy link address*.

---

### 2. Create a .strm file
Make a file ending in .strm and paste the direct URL inside. Example:

```text
https://archive.org/download/night-of-the-living-dead-1968_202110/night_of_the_living_dead.mp4

```
Save it as:
```
examples/night_of_the_living_dead.strm
[16:41, 30/09/2025] Emmanuel D: 3. Add to Plex
```
Create a new folder for streams, e.g., ~/plex-streams.

Copy your .strm files into it.

In Plex Web UI → Libraries → Add Library, point it to that folder.

### 4. Enable Remote Access

Go to Settings → Remote Access in Plex.

Enable Remote Access (may require port forwarding 32400/TCP).

Test from another network to confirm.

### 🎥 Example

This repo includes a working .strm file for:

Night of the Living Dead (1968) — Internet Archive

### ⚖️ Legal Note

This project is for public-domain content only. Please respect copyright laws and only stream media that is free to distribute.

### 📂 Repository Structure
```
examples/      → Ready-to-use .strm files
guides/        → Setup guides
README.md      → Documentation
LICENSE        → MIT license
```

### 🤝 Contributing

Add more .strm files pointing to public-domain videos.

Share additional setup tips for Plex users.

Submit pull requests with improvements.

### 📜 License

MIT License
