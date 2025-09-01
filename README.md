# 🎬 Video Frame Extractor

A powerful, browser-based tool for extracting sequential frames from video files with precision and ease. Built entirely with vanilla JavaScript, HTML5, and CSS3.

## ✨ Features

- **Drag & Drop Interface**: Simply drag your video files into the browser
- **Multiple Video Formats**: Supports MP4, AVI, MOV, WebM, and more
- **Precise Time Control**: Set custom start time, end time, and frame intervals
- **Quality Options**: Choose from Original, High (80%), Medium (60%), or Low (40%) quality
- **Real-time Preview**: See extracted frames immediately with hover effects
- **Selective Download**: Click frames to select specific ones for download
- **Batch Download**: Download all frames or selected frames as ZIP archives
- **Progress Tracking**: Real-time progress bar during extraction
- **Responsive Design**: Works on desktop and mobile devices
- **No Server Required**: Runs entirely in the browser using HTML5 Canvas API

## 🚀 Demo

Simply open the HTML file in any modern web browser - no installation required!

## 📖 How to Use

1. **Upload Video**: Drag and drop a video file or click to browse
2. **Set Parameters**: 
   - Interval: Time between frame extractions (in seconds)
   - Start Time: When to begin extraction
   - End Time: When to stop extraction
   - Quality: Image quality for extracted frames
3. **Extract Frames**: Click "Extract Frames" and watch the progress
4. **Select Frames**: Click on individual frames to select them (optional)
5. **Download**: Choose to download all frames or just selected ones as ZIP

## 🛠️ Technical Details

### Built With
- **HTML5 Canvas API** - For video frame extraction
- **JavaScript ES6+** - Modern class-based architecture
- **CSS3** - Responsive design with gradients and animations
- **JSZip Library** - For creating downloadable ZIP archives

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

### File Support
Supports all video formats that can be played in HTML5 video elements:
- MP4 (H.264, H.265)
- WebM (VP8, VP9)
- AVI
- MOV
- MKV
- And more...

## 📁 Project Structure

```
video-frame-extractor/
├── index.html          # Main application file
├── README.md           # This file
```

## 🔧 Installation

No installation required! This is a client-side application.

1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start extracting frames from your videos

```bash
git clone https://github.com/amar-verma/video-frame-extractor.git
cd video-frame-extractor
# Open index.html in your browser
```

## 💡 Use Cases

- **Animation Reference**: Extract frames for rotoscoping or animation studies
- **Video Analysis**: Break down video content frame by frame
- **Thumbnail Creation**: Generate multiple thumbnails from video content
- **Quality Control**: Inspect video quality at specific intervals
- **Content Creation**: Extract frames for social media or presentations
- **Research**: Analyze motion, objects, or changes over time

## ⚡ Performance Features

- **Efficient Memory Management**: Automatic cleanup of blob URLs
- **Progress Tracking**: Real-time feedback during extraction
- **Non-blocking UI**: Async processing prevents browser freezing
- **Optimized Canvas Rendering**: Matches original video dimensions
- **Quality Control**: Adjustable JPEG compression for file size management

## 🎨 Design Features

- **Modern UI**: Gradient backgrounds and smooth animations
- **Responsive Layout**: Adapts to different screen sizes
- **Interactive Elements**: Hover effects and visual feedback
- **Intuitive Controls**: Clean, user-friendly interface
- **Visual Progress**: Beautiful progress bars and status updates

## 📝 License

This project is for personal use. Feel free to modify and adapt for your own needs.

## 🤖 AI Generated

This project was created entirely using AI assistance for educational and personal use purposes. The code demonstrates modern web development techniques for client-side video processing.

## 🐛 Known Limitations

- Large video files may consume significant memory
- Extraction speed depends on video resolution and browser performance
- Very high frame rates may slow down the extraction process
- Browser memory limits may affect very long videos

## 🔮 Future Enhancements

- [ ] Add frame rate detection and optimization
- [ ] Support for batch video processing
- [ ] Custom resolution scaling options
- [ ] Frame comparison and duplicate detection
- [ ] Export to different image formats (PNG, WebP)
- [ ] Advanced filtering and frame selection tools

## 📞 Support

This is a personal project created for individual use. Feel free to fork and modify according to your needs.

---

**Note**: This tool processes videos entirely in your browser - no data is uploaded to any servers, ensuring complete privacy of your video content.
