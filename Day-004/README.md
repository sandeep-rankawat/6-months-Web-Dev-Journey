# Day 4 | HTML Phase 2

This project contains example code showcasing how to use various multimedia and interactive HTML tags including images, audio, video, maps, and embedded iframes.

## Multimedia tags

### Chapter 5: Image and Picture Tags

- **Image Tag (`<img>`)**: Displays a simple image with the `src` attribute and descriptive `alt` text.
- **Picture Tag (`<picture>`)**: Implements responsive images, allowing different sources based on media queries such as orientation.
- **Figure Tag (`<figure>`)**:
  - Displays an image.
  - Displays an image with a caption using the `<figcaption>` element.

### Chapter 6: Audio and Video Tags

- **Audio Tag (`<audio>`)**: Embeds audio with controls; demonstrates attributes like `src`, `autoplay`, `controls`, `muted`, and `loop`.
- **Video Tag (`<video>`)**: Embeds video with controls, supporting multiple source formats for broader compatibility (WebM and MP4). Also provides download links for the videos.

### Chapter 7: Map, Area, and iframe Tags

- **Map and Area Tags (`<map>` and `<area>`)**: Defines a clickable image map with polygon shaped hotspots linking to external documentation for HTML, CSS, and JavaScript.
- **Image with usemap attribute**: Associates the image with the defined image map.
- **iframe Tag (`<iframe>`)**: Embeds a YouTube video player with various security and playback attributes enabled.

## Usage

To see the examples in action, open the HTML file in a modern web browser. Multimedia content requires an internet connection for external sources like YouTube and MDN links.

## File References

- Images are loaded from local paths or shared asset URLs.
- Audio and video sources are linked from shared asset directories.
- External links for documentation and YouTube are embedded for interactivity.

## Notes

- Make sure file paths like `/Day-004/image.png` and `/shared-assets/` are valid and accessible relative to the HTML file location.
- Supported media formats include common image (PNG, JPG), audio (MP3), and video (WebM, MP4) files.
- The example uses polygonal clickable areas in the image map demonstrating advanced interactive image features.

---

This example is ideal for learning about embedding multimedia and interactive elements in HTML5 webpages.
