# Parallax Adventure Landing Page

A responsive, CSS-only parallax-scrolling landing page celebrating the thrill of outdoor adventure. Built with semantic HTML5 and modern CSS, this project features a full-screen hero section and immersive panels for biking, paragliding, and surfing.

## Demo

You can view the live demo of this project here: [Adventure Parallax Website Demo](https://nayabkhan123.github.io/ParallaxEffect/)

## Features

- **3D Hero Section**: Layered background and foreground images using CSS `perspective` and `transform-style` for depth.
- **Fixed-Background Panels**: Three full-width sections (`BIKING`, `PARAGLIDING`, `SURFING`) with `background-attachment: fixed` for classic parallax.
- **Responsive Design**: Media queries ensure readability and layout adjustments from mobile (≤480px) to desktop.
- **Favicon Support**: Custom favicon for brand consistency.

## Project Structure

```
├── index.html       # Main landing page with parallax markup
├── website.css      # Stylesheet with parallax, typography, and responsiveness
├── favicon.png      # Site icon displayed in browser tabs
├── background.jpg   # Hero background image
├── fore.png         # Hero foreground image
├── Biking.jpg       # Biking panel background
├── paragliding.jpg  # Paragliding panel background
└── surfingImage.jpg # Surfing panel background
```

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Nayabkhan123/ParallaxEffect.git
   cd parallax-adventure
   ```
2. **Open in browser**
   - Simply open `index.html` in your favorite web browser.

## Usage & Customization

- **Swap Images**: Replace the background assets under project root and update the `background-image` URLs in `website.css`.
- **Adjust Colors & Fonts**: Edit CSS variables or directly change color values and font settings.
- **Add More Panels**: Copy an existing `.bg` block in HTML and define a corresponding CSS class with a new image.
- **Modify Breakpoints**: Tweak media query thresholds in `website.css` to suit your design requirements.


---

_Designed for showcasing adventurous themes and as a customizable template for travel, sports, and outdoor activity websites._

