# <div align="center">🎵 HTML Audio & Video</div>

<div align="center">

![HTML](https://img.shields.io/badge/HTML5-Multimedia-orange?style=for-the-badge&logo=html5)
![Level](https://img.shields.io/badge/Level-Intermediate-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Practice-Completed-blue?style=for-the-badge)

</div>

---

# 📖 About

This folder contains practice programs related to HTML multimedia elements.

HTML5 provides built-in support for audio and video playback without needing external plugins.

---

# 🎯 Objectives

✅ Learn how to add audio in webpages  
✅ Learn how to embed videos  
✅ Practice multimedia integration  
✅ Understand iframe usage  
✅ Create interactive multimedia webpages  

---

# 📂 Files Included

```text
07_audio_video/
│
├── index.html
├── sample-audio.mp3
├── sample-video.mp4
└── README.md
```

---

# 📚 Concepts Used

| Tag / Attribute | Purpose |
|---|---|
| `<audio>` | Add audio player |
| `<video>` | Add video player |
| `<source>` | Define media source |
| `controls` | Display media controls |
| `<iframe>` | Embed external content |
| `width` | Set media width |
| `allowfullscreen` | Enable fullscreen mode |

---

# 💻 HTML Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Audio and Video</title>
</head>
<body>

    <h1>HTML Audio Example</h1>

    <audio controls>
        <source src="sample-audio.mp3" type="audio/mpeg">
        Your browser does not support audio.
    </audio>

    <hr>

    <h1>HTML Video Example</h1>

    <video width="400" controls>
        <source src="sample-video.mp4" type="video/mp4">
        Your browser does not support video.
    </video>

    <hr>

    <h1>YouTube Video Embed</h1>

    <iframe 
        width="560" 
        height="315"
        src="https://www.youtube.com/embed/dQw4w9WgXcQ"
        title="YouTube video player"
        frameborder="0"
        allowfullscreen>
    </iframe>

</body>
</html>
```

---

# 🖥 Output

The webpage displays:

- Audio player
- Video player
- Embedded YouTube video
- Multimedia controls

---

# 💡 What I Learned

✔ Embedding audio in webpages  
✔ Adding videos using HTML5  
✔ Using multimedia controls  
✔ Embedding YouTube videos  
✔ Creating interactive webpage content  

---

# ⚡ Git Commands Used

```bash
git add .
git commit -m "Added HTML audio and video examples"
git push origin main
```

---

# 🚀 Future Improvements

- Add custom media controls
- Style multimedia players with CSS
- Create music player UI
- Build video gallery webpage
- Add autoplay and loop features

---

<div align="center">

# ⭐ HTML Multimedia Completed ⭐

</div>