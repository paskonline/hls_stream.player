Modern HLS Stream Player

A lightweight, responsive, and feature-rich web player designed to stream HTTP Live Streaming (HLS) video formats directly in the browser.

While most modern web browsers (except Safari) cannot natively play .m3u8 playlist files, this player utilizes the powerful hls.js library to decode and play secure streaming links seamlessly. It includes mobile-friendly gesture controls and a built-in stream recording feature.

🚀 Features

Universal Playback: Plays .m3u8 links on any modern web browser by utilizing hls.js or native fallback.

Mobile Touch Gestures: * Horizontal Swipe: Swipe left or right to skip forward or backward by 5 seconds.

Vertical Swipe (Left Side): Swipe up or down on the left side of the video to adjust screen brightness.

Vertical Swipe (Right Side): Swipe up or down on the right side of the video to adjust media volume.

Stream Recording: Click the "Record" button while a stream is playing to capture the video. Click "Stop & Save" to instantly download the recording as a .webm file.

Smart UI/UX: * Real-time loading percentage overlay during stream buffering.

Integrated "Paste" and "Clear" buttons inside the URL input field for quick link management.

Visual feedback pop-ups when using swipe gestures.

Responsive Design: Built with Tailwind CSS, ensuring the player looks perfect on desktop, tablet, and mobile screens.

🛠️ Technology Stack

Frontend: HTML5, standard JavaScript

Styling: Tailwind CSS (via CDN)

Core Video Library: hls.js

📖 How to Use

Host the Project: You can host this single index.html file easily using GitHub Pages. Just push the code to a new repository and enable GitHub Pages in the settings.

Load a Stream: Open the web page, paste a valid .m3u8 streaming link into the input field, and click "Load Stream".

Record: Once the video starts playing, a red "Record" button will appear. Click it to begin capturing the stream.

Important Note on Links: Secure streaming links often contain expiration parameters or are locked to specific IP addresses (CORS restrictions). If a link fails to load, the player will display a specific network or media error.

🧪 Testing

If you need a safe public link to test the player's functionality, you can use this open-source test stream:
https://test-streams.mux.dev/x36xhzz/x36xhzz.m3u8

📄 License

This project is open-source and free to use or modify.
