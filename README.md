# GitHub Pages Setup

## Files to Add

1. **report.pdf** - Your project report
2. **demo.mp4** - Your video demonstration (or use YouTube embed)
3. **thumbnail.png** - Optional video thumbnail

## Enable GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings** → **Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` (or `master`)
5. Folder: `/docs`
6. Click **Save**

Your site will be live at: `https://YOUR-USERNAME.github.io/wazuh-docker/`

## Alternative: YouTube Video

If your video is too large, upload to YouTube and replace the video section in `index.html`:

```html
<div class="video-wrapper">
    <iframe 
        src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
        frameborder="0" 
        allowfullscreen>
    </iframe>
</div>
```

## Customize

Edit `index.html` to:
- Update the GitHub repository URL
- Change colors/styling
- Add more sections as needed
