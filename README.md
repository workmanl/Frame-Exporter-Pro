# Frame Exporter Pro

A professional video frame extraction tool with an Adobe Premiere Pro-inspired interface. Extract high-quality frames from your videos with precision and ease.

## Features

### Core Functionality
- **Precision Frame Extraction** - Scrub through videos frame-by-frame and export exactly the frame you need
- **Multiple Export Formats** - Save frames as JPEG, PNG, or WebP with adjustable quality settings
- **Real-time Preview** - See frames instantly as you scrub through the timeline
- **Smart File Size Estimation** - Get accurate file size predictions based on format and quality settings
- **Professional Timeline** - Frame-accurate scrubbing with FPS and timecode display

### Advanced Features
- **Drag & Drop Support** - Simply drag video files into the application
- **High Resolution Support** - Handle videos up to 8K (7680x4320) resolution
- **Copy to Clipboard** - Quickly copy frames for immediate use
- **Fullscreen Mode** - Maximize your workspace for detailed frame inspection
- **Keyboard Shortcuts** - Efficient workflow with comprehensive keyboard navigation

### Professional UI
- **Three-Panel Layout** - Organized workspace inspired by professional video editing software
- **Top Menu Bar** - File, Edit, Window, and Help menus for easy access to all features
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Dark Theme** - Easy on the eyes during extended work sessions

## Installation

No installation required! Frame Exporter Pro is a self-contained web application.

### Quick Start

1. **Download** the `index.html` file
2. **Open** it in any modern web browser
3. **Start extracting** frames immediately

That's it! No build process, no dependencies, no configuration needed.

## Usage

### Basic Workflow

1. **Load a Video**
   - Click "Choose File" or drag and drop a video file into the drop zone
   - Supported formats: MP4, WebM, MOV, and other browser-supported formats
   - Maximum file size: 500MB

2. **Navigate the Timeline**
   - Use the scrubber slider to navigate through your video
   - Frame number and timecode are displayed in real-time
   - Use keyboard arrow keys for precise control

3. **Adjust Export Settings**
   - Select your preferred format (JPEG, PNG, or WebP)
   - Adjust quality using the slider (10-100%)
   - View estimated file size in real-time

4. **Export Your Frame**
   - Click "Export Frame" to download
   - Or use "Copy Frame" to copy to clipboard
   - Files are automatically named: `[video-name]_frame_[number]_[timestamp].[ext]`

### Keyboard Shortcuts

- **Arrow Keys** - Frame-by-frame navigation
- **Space** - Play/Pause (when video playback is supported)
- **F** - Toggle fullscreen
- **Ctrl/Cmd + O** - Open file
- **Ctrl/Cmd + E** - Export current frame
- **Ctrl/Cmd + C** - Copy frame to clipboard

## Technical Details

### Architecture
- **Single-file application** - Entire app contained in one HTML file
- **Zero dependencies** - Built with pure HTML5, CSS3, and Vanilla JavaScript
- **ES6+ Class-based** - Modern object-oriented design
- **Memory efficient** - Proper resource cleanup and blob URL management

### Browser Requirements

**Minimum Requirements:**
- HTML5 Video API support
- Canvas API support
- File API support
- Modern browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)

**Recommended:**
- Latest version of Chrome, Firefox, Safari, or Edge
- Hardware acceleration enabled for best performance

### Technology Stack

- **HTML5** - Semantic markup with ARIA accessibility
- **CSS3** - Modern styling with CSS Grid, Flexbox, and Variables
- **JavaScript ES6+** - No frameworks or libraries
- **Browser APIs**:
  - Video API (playback and frame access)
  - Canvas API (frame capture)
  - File API (video file handling)
  - Blob API (image export)
  - Clipboard API (copy functionality)

### Accessibility

Frame Exporter Pro is built with accessibility in mind:
- **WCAG 2.1 AA compliant**
- Full keyboard navigation support
- Screen reader optimized with ARIA labels and roles
- High contrast UI elements
- Focus indicators for all interactive elements

### Performance Optimizations

- Efficient canvas rendering
- Smart memory management with automatic cleanup
- Debounced scrubber updates for smooth performance
- Lazy loading and on-demand processing
- Optimized for videos up to 8K resolution

## File Size Limits

- **Maximum video size**: 500MB
- **Supported resolutions**: Up to 8K (7680x4320)
- **Export formats**:
  - JPEG (lossy, smallest file size)
  - PNG (lossless, larger file size)
  - WebP (modern format, balanced quality/size)

## Browser Compatibility

| Browser | Minimum Version | Recommended |
|---------|----------------|-------------|
| Chrome | 90+ | Latest |
| Firefox | 88+ | Latest |
| Safari | 14+ | Latest |
| Edge | 90+ | Latest |

**Note**: Older browsers may work but are not officially supported.

## Troubleshooting

### Video won't load
- Check that your video file is under 500MB
- Ensure the video format is supported by your browser
- Try a different video format (MP4 is most widely supported)

### Export not working
- Check that you have sufficient disk space
- Ensure pop-up blockers aren't preventing downloads
- Try a different export format

### Performance issues
- Close other browser tabs to free up memory
- Try a lower resolution video
- Ensure hardware acceleration is enabled in your browser

## Development

### Project Structure
```
Frame-Exporter-Pro/
├── index.html          # Complete application (2,681 lines)
└── README.md          # This file
```

### Code Organization
The entire application is organized within a single `FrameExporterPro` class:
- Initialization and setup
- File handling and validation
- Video processing and playback
- Frame capture and export
- UI state management
- Menu system and shortcuts
- Utility methods

### Contributing

Contributions are welcome! Since this is a single-file application:
1. Fork the repository
2. Make your changes to `index.html`
3. Test thoroughly in multiple browsers
4. Submit a pull request with a clear description of changes

## Version History

- **v0.1** - Initial release
  - Core frame extraction functionality
  - Multi-format export support
  - Professional UI with three-panel layout
  - Accessibility features
  - Comprehensive error handling

## Author

Created by [github.com/workmanl](https://github.com/workmanl)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

Copyright 2025 [github.com/workmanl](https://github.com/workmanl)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Acknowledgments

- UI design inspired by Adobe Premiere Pro
- Built with modern web standards and best practices

## Support

For bug reports and feature requests, please use the "Report a Bug" feature in the Help menu or contact the repository maintainer.

---

**Frame Exporter Pro** - Professional frame extraction made simple.
