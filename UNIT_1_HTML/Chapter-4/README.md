# Chapter 4 | HTML Phase 2

This phase contains various multimedia and interactive HTML tags including images, audio, video, maps, and embedded iframes.

## 📚 Multimedia tags

### Section A : Image and Picture Tags

1. **Image Tag (`<img>`)**: Displays a simple image with the `src` attribute and descriptive `alt` text.
2. **Picture Tag (`<picture>`)**: Implements responsive images, allowing different sources based on media queries such as orientation.
3. **Figure Tag (`<figure>`)**:
    - Displays an image.
    - Displays an image with a caption using the `<figcaption>` element.

### Section B : Audio and Video Tags

1. **Audio Tag (`<audio>`)**: Embeds audio with controls; demonstrates attributes like `src`, `autoplay`, `controls`, `muted`, and `loop`.
2. **Video Tag (`<video>`)**: Embeds video with controls, supporting multiple source formats for broader compatibility (WebM and MP4). Also provides download links for the videos.

### Section C : Map, Area, and iframe Tags

1. **Map and Area Tags (`<map>` and `<area>`)**: Defines a clickable image map with polygon shaped hotspots linking to external documentation for HTML, CSS, and JavaScript.
2. **Image with usemap attribute**: Associates the image with the defined image map.
3. **iframe Tag (`<iframe>`)**: Embeds a YouTube video player with various security and playback attributes enabled.


## File References

- Images are loaded from local paths or shared asset URLs.
- Audio and video sources are linked from shared asset directories.
- External links for documentation and YouTube are embedded for interactivity.

## Notes

- Make sure file paths like `/Day-004/image.png` and `/shared-assets/` are valid and accessible relative to the HTML file location.
- Supported media formats include common image (PNG, JPG), audio (MP3), and video (WebM, MP4) files.
- The example uses polygonal clickable areas in the image map demonstrating advanced interactive image features.

#