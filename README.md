# JOIminator

JOIminator is a web-based tool that lets you overlay customizable jerk off instructions on any embedded video. With user-defined instructions, adjustable timing, and randomized display, JOIminator transforms your video-watching experience into something uniquely tailored. Perfect for personal use with a simple, intuitive interface.

## Features

- **Universal Video Embedding**: Embed videos from platforms like YouTube, Vimeo, or others using iframe embed codes.
- **Custom Instructions**: Add your own jerk off instructions, displayed as overlays on the video.
- **Timing Control**: Set how often (interval) and how long (duration) instructions appear.
- **Randomized Overlays**: Instructions are randomly selected from your list for variety.
- **Responsive Design**: Adjusts to the video's dimensions for a seamless fit.

## Demo

Try JOIminator by opening `index.html` in a browser or hosting it on a local server. Paste a video embed code, add instructions, set timing, and hit "Start" to see it in action!

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/joiminator/joiminator.git
   cd jominator
   ```

2. **Open the Project**:
   - No dependencies or build steps are required! Simply open `index.html` in a modern web browser (Chrome, Firefox, Edge, etc.).
   - Alternatively, host the files on a local server (e.g., using Python's HTTP server):
     ```bash
     python -m http.server 8000
     ```
     Then visit `http://localhost:8000` in your browser.

## Usage

1. **Prepare a Video Embed Code**:
   - Copy an iframe embed code from a video platform (e.g., YouTube). Example:
     ```html
     <iframe width="640" height="360" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
     ```

2. **Launch JOIminator**:
   - Open `index.html` in a browser.
   - Paste the embed code into the "Video Embed Code" textarea.
   - Enter instructions (one per line) in the "Instructions" textarea (e.g., `Stroke slowly`, `Speed up`).
   - Set the interval (seconds between overlays) and duration (seconds each overlay shows).
   - Click the "Start" button to load the video and begin overlaying instructions.

3. **Customize**:
   - Adjust the interval and duration for faster or slower pacing.
   - Add more instructions for greater variety.
   - The overlays will randomly select from your instructions list.

## Example

**Inputs**:
- Embed Code: `<iframe width="640" height="360" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>`
- Instructions:
  Stroke slowly
  Speed up
  Take a break
- Interval: 10 seconds
- Duration: 5 seconds

**Result**: The video plays, and every 10 seconds, a random instruction (e.g., "Speed up") appears for 5 seconds.

## Limitations

- **Full-Screen Mode**: Overlays may not appear in full-screen due to browser restrictions.
- **Video Restrictions**: Some videos may not embed due to platform policies (e.g., restricted embedding settings).
- **Browser Compatibility**: Tested on modern browsers; older browsers may have issues with dynamic iframes or CSS.

## Contributing

We welcome contributions to make JOIminator even better! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m 'Add your feature'`).
4. Push to your branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

**Ideas for Contributions**:
- Add animations to overlay transitions.
- Support for syncing instructions with video timestamps.
- Save/load instruction sets for reuse.
- Enhance styling for mobile responsiveness.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

Have questions or suggestions? Open an issue on GitHub.

---

Built with ❤️ by JOIminator. Enjoy responsibly!
