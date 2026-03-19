# Shining Star Cleaning – Landing Site

Modern, mobile‑first static website for **Shining Star Cleaning**, a residential and commercial deep‑cleaning service.  
The site is built with pure **HTML5**, **CSS3**, and a tiny amount of **vanilla JavaScript** for the mobile navigation.

## Project overview

- **Type**: Portfolio + business landing page  
- **Goal**: Generate leads from homeowners and businesses looking for deep‑cleaning services  
- **Key sections**:
  - Sticky navbar with logo and smooth mobile menu
  - Hero section with headline, subheadline, and primary CTA
  - Services grid for all cleaning offerings
  - About section with value proposition and quick stats
  - Optional testimonials section
  - Contact section with lead‑capture form (UI only, no backend)
  - Footer with quick links and basic company info

Tech highlights:

- Single modern Google Font (Poppins)
- Custom teal/blue + yellow palette inspired by existing marketing material
- Flexbox and CSS Grid layouts
- Mobile‑first responsive design with breakpoints around **480px**, **768px**, and **1024px**

## Folder structure

```text
.
├── index.html        # Main landing page
├── styles.css        # Global styles and responsive layout
├── README.md         # Project documentation
└── assets/
    └── images/       # Optional images (hero, gallery, etc.)
```

> Note: One sample flyer image is referenced in `styles.css` for the hero background.  
> Replace this with your own production assets as needed.

## How to run locally

No build step is required; this is a static site.

1. **Clone or download** this folder to your machine.
2. Open the project directory:

   ```bash
   cd deep-cleaning-web
   ```

3. Open `index.html` in your browser:

   - Option A: Double‑click `index.html` in your file explorer, or  
   - Option B (recommended): Serve via a simple local web server, for example with Python:

     ```bash
     python -m http.server 8000
     ```

     Then visit `http://localhost:8000` in your browser.

## Customisation tips

- Update contact details and service descriptions directly in `index.html`.
- Adjust colours and spacing via CSS variables at the top of `styles.css`.
- Replace hero background images with your own visuals in the `.hero-image-main` and `.hero-image-secondary` rules.

