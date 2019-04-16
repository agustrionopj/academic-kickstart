+++
# Slider widget.
widget = "slider"  # Do not modify this line!
active = true  # Activate this widget? true/false
headless = true

# Order that this section will appear in.
weight = 1

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "400px"

#[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "**Selamat Datang**"
  content = ""
  align = "center"  # Choose `center`, `left`, or `right`.

  #title = "Hello"
  #content = "I am center aligned :smile:"
  #align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/m31.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Tentang Kami"
  cta_url = "#about"
  cta_icon_pack = "fas"
  cta_icon = "user-check"

#  [design.background]
#    text_color_light = true

[[item]]
  title = "**Penelitian**"
  content = "Observasi, Pengembangan Instrumen & Sistem,  Publikasi"
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/research.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.6  # Darken the image. Value in range 0-1.

  cta_label = "Detail"
  cta_url = "/penelitian/"
  cta_icon_pack = "fas"
  cta_icon = "user-astronaut"

[[item]]
  title = "**Pendidikan**"
  content = "Praktikum, Kerja Praktik, Kerjasama Non-Astronomi"
  align = "left"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "headers/akademik.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.6  # Darken the image. Value in range 0-1.

  cta_label = "Detail"
  cta_url = "/akademik/"
  cta_icon_pack = "fas"
  cta_icon = "book-open"

[[item]]
  title = "**Layanan**"
  content = "Kunjungan Publik & Khusus, Pelatihan, Pengamatan Hilal"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "headers/kunjungan.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.6  # Darken the image. Value in range 0-1.

  cta_label = "Detail"
  cta_url = "/layanan/"
  cta_icon_pack = "fas"
  cta_icon = "users"

+++
