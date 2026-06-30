# Malcolm Lismore Photography 📸

A premium, fully responsive, and modern portfolio website for **Malcolm Lismore**, a professional freelance photographer portfolio.
---
## 🌟 Key Features
*   **Sleek Sidebar Navigation:** A modern sidebar layout housing logo branding, page links, and footer licensing, offering seamless navigation.
*   **Comprehensive Gallery:** Categorized portfolios showcasing stunning imagery in wedding, event, wildlife, portrait, and nature categories.
*   **Interactive Review Portal (`Review.html`):**
    *   **Live Rating Breakdown:** Displays the average rating alongside a visual progress bar chart (5-star down to 1-star proportions).
    *   **Categorized Filters:** Instantly filter client reviews by service category (e.g. Wedding, Portrait, Nature).
    *   **Client Review Submission:** Custom form to post reviews. Submissions generate automatic user-initial avatars, calculate timestamps, recalculate star statistics, and persist in **LocalStorage** dynamically.
    *   **Toast Notifications:** A user feedback toast system upon successful review posting.
*   **Clean Package Display:** A clear grid showing photography packages, prices, and photo amounts.
*   **Fully Responsive & Animated Design:** Smooth scroll behaviors, custom page loaders, fade animations (`Animate.css`), and image preview modals (`Magnific Popup`).
*   **Contact & Inquiries Form:** A contact form mapping personal details, package selections, and queries directly to Malcolm's Edinburgh-based studio.
---
## 🛠️ Technology Stack
*   **HTML5 & CSS3/SCSS:** Structuring and styling content with modular Sass code.
*   **Bootstrap 4:** Responsive grid layouts and component structures.
*   **jQuery & Plugins:**
    *   **Owl Carousel:** Smooth slider components.
    *   **Magnific Popup:** Lightbox overlay for zooming in on high-resolution photographs.
    *   **Waypoints & Stellar.js:** Scroll animation trigger anchors and parallax scrolling effects.
*   **Google Maps API:** Interactive studio maps integrated directly on the contact page.
*   **Web Fonts:** Custom typography featuring *Poppins* and *Abril Fatface* loaded via Google Fonts.
---
## 📂 Project Structure
```text
Malcolm Photographer/
├── index.html          # Main landing page featuring photography categories
├── about.html          # Professional background and style introduction
├── gallery.html        # Main categorized gallery page
├── pricing.html        # Photography service pricing plans
├── Review.html         # Live client feedback and dynamic review submission
├── contact.html        # Studio contact details and booking inquiry form
├── contact.php         # Server-side contact mail script (placeholder)
├── gallery.css         # Styling rules specific to the gallery module
├── css/                # Compiled CSS stylesheets
│   ├── style.css       # Core layout stylesheet
│   ├── animate.css     # Element entry animation effects
│   ├── flaticon.css    # Typography icon sets
│   ├── reviews.css     # Styling for review cards, stats, and star ratings
│   └── ...             # Carousel and popup stylesheet integrations
├── scss/               # Source Sass stylesheets for layout customizations
├── js/                 # JavaScript engines
│   ├── main.js         # Navigation controls, animations, and library initializers
│   ├── google-map.js   # Embedded map canvas coordinates configuration
│   └── ...             # Library files (bootstrap, jquery, magnific-popup, etc.)
├── fonts/              # Custom icons and system font packages
└── images/             # High-quality photography assets and user avatars
```
---
## ⚙️ Local Setup Instructions
Follow these simple steps to run the portfolio website on your local machine:
### Option 1: Live Server (Recommended)
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension.
3. Click the **Go Live** button in the status bar at the bottom right corner of VS Code.
4. The site will launch automatically at `http://127.0.5.1:5500/index.html`.
---
```
---
## 📜 Credits
*   **Template Design:** Original starter template design and components by [Colorlib](https://colorlib.com).
*   **Imagery:** High-definition photography assets by Malcolm Lismore.
