---
widget: slider
headless: true  # This file represents a page section.
weight: 10
# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 4000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 300px


item:
  - title: Human Centred Computing Group
    content: King's College London
    # Choose `center`, `left`, or `right` alignment.
    align: center
    overlay_color: black  # An HTML color value.
    overlay_img: slider-background.jpg  # Image path relative to your `static/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
  - title: bbbb
    content: 'yello'
    align: center
    overlay_color: '#555'
    overlay_img: slider-background.jpg 
    overlay_filter: 0.4
  - title: ccc
    content: 'hello again'
    align: center
    overlay_color: '#ffffff'
    overlay_img: slider-background.jpg 
    overlay_filter: 0.9
---