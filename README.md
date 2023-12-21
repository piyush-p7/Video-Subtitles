# Video Player with Subtitles

This is a simple web page that demonstrates how to create a video player with subtitles using HTML, CSS, and JavaScript.

## Features

- Video player with controls.
- Subtitles support using WebVTT format.
- Toggle subtitles on and off.
- Responsive design.

## Usage

1. Replace `"your-video.mp4"` with the actual path to your video file.
2. Replace `"your-subtitles.vtt"` with the actual path to your WebVTT subtitle file.

```html
<video id="video" controls>
    <source src="your-video.mp4" type="video/mp4">
    <!-- Include subtitles using the track element -->
    <track kind="subtitles" label="English" srclang="en" src="your-subtitles.vtt" default>
    Your browser does not support the video tag.
</video>
```
## Customization

Adjust the styling in the <style> section of the HTML file to match your design preferences.
Modify the JavaScript functions to add additional features or customize behavior.

## License

This project is licensed under the MIT License