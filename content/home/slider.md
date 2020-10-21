+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 4000
#false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = 'calc(100vh - 70px)'

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = ""
  content = "[Tumor-vessel interactions](https://cancerres.aacrjournals.org/content/80/19/4288.short)"
  align = "Left"  # Choose `center`, `left`, or `right`.
  
  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = 'cancer-vessel.jpg'
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  #cta_label = "Full text"
  #cta_url = "https://cancerres.aacrjournals.org/content/80/19/4288.short"
  #cta_icon_pack = "fas"
  #cta_icon = "graduation-cap"

[[item]]
  title = "Cool image 2.0"
  content = "I am left aligned :smile:"
  align = "left"

  overlay_img = 'pc-ec_2.jpg'
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = "Bead"
  content = "I am right aligned :smile:"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = 'zoibead.jpg'
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++
