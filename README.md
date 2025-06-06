# Recorder
A web application that enables users to record videos with audio, capture still photos, and apply real-time filters, all built using HTML, CSS, and JavaScript.

Features
Record video with microphone audio
Capture high-quality still photos
Apply customizable color filters to video preview
Download recorded videos and captured photos
Live timer display during recording

Technologies Used
HTML5 for structure
CSS3 for styling
JavaScript for functionality and media handling
MediaRecorder API for recording
Canvas API for capturing images and applying filters
How It Works
Accesses user camera and microphone via getUserMedia.
Uses MediaRecorder to record video and audio streams.
Stores media chunks during recording, then compiles and downloads them upon stopping.
Captures static images from the video feed via Canvas API.
Applies color filters to the video preview for visual effects.
Displays a live timer showing recording duration.
Usage Instructions
Open the index.html file in a modern web browser.
Grant camera and microphone access when prompted.
Use the Record button to start/stop video recording.
Use the Capture Photo button to take snapshots.
Select a preferred filter to apply in real-time.
Download your recordings or photos using the provided buttons.
Code Highlights
Video Recording: Starts/stops using MediaRecorder, saves chunks, and creates a downloadable MP4 file.
Photo Capture: Draws current video frame onto a canvas, applies filters, then saves as JPEG.
Filters: Change overlay color dynamically to apply visual effects.
Timer: Counts and displays elapsed recording time with start/stop controls.

Note
Make sure to use this application in browsers supporting MediaRecorder and getUserMedia (latest Chrome, Firefox, Edge, etc.).
Files are temporarily stored; save them immediately after recording.
