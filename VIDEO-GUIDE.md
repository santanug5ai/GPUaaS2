# 🎬 Video Integration Guide

## Local Video Player for AI-Factory

---

## 📹 Supported Formats

- **MP4** (H.264 codec) - Recommended
- **WebM** (VP8/VP9 codec)
- **OGG** (Theora codec)

### Specifications
- **Resolution**: Up to 4K (3840x2160)
- **Frame Rate**: 24fps, 30fps, or 60fps
- **Bitrate**: 5-15 Mbps recommended
- **Max File Size**: 500MB per video

---

## 📁 Directory Structure

Place your videos in:
```
AI-Factory/assets/videos/
```

### Recommended Videos

1. **platform-overview.mp4** - Platform introduction
2. **gpu-deployment.mp4** - Infrastructure demo
3. **service-catalog.mp4** - Services walkthrough
4. **admin-dashboard.mp4** - Admin features
5. **api-tutorial.mp4** - Developer guide

---

## 🔧 Adding Videos

### Method 1: Upload via Interface
1. Open any page with video support
2. Click "Choose Video File" button
3. Select your MP4/WebM/OGG file
4. Video plays automatically

### Method 2: Direct Placement
1. Place videos in `assets/videos/` directory
2. Videos will be available for playback

### Method 3: Update HTML
```html
<video controls>
    <source src="assets/videos/your-video.mp4" type="video/mp4">
</video>
```

---

## 🎥 AI Video Generation Tools

Create professional videos using:

- **Runway Gen-2/Gen-3** - Text/image to video
- **Pika Labs** - AI video generation
- **Synthesia** - AI avatar videos
- **D-ID** - Talking head videos
- **HeyGen** - Professional presenters

---

## 📝 Naming Convention

Use lowercase with hyphens:
```
platform-overview.mp4
gpu-deployment-demo.mp4
service-catalog-tour.mp4
```

---

## 💡 Tips

- Keep videos under 3 minutes
- Use 1080p or higher resolution
- Add captions for accessibility
- Optimize file size with compression
- Test playback on multiple browsers

---

## 🎨 Video Content Ideas

### Platform Overview (2-3 min)
- Introduction to AI-Factory
- Key features highlight
- Value proposition

### Technical Demo (1-2 min)
- GPU allocation
- Service deployment
- Performance metrics

### Tutorial (3-5 min)
- API integration
- Code examples
- Best practices

---

## 🔄 Updating Videos

To replace videos:
1. Delete old file from `assets/videos/`
2. Add new file with same name
3. Refresh browser to see changes

---

*AI-Factory - Professional Video Integration*
