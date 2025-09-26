 Green Earth Landscaping Website 🌱

This is a responsive website project for **Green Earth Landscaping**, developed as part of coursework requirements. The project demonstrates structured HTML, external CSS styling, and responsive design techniques for desktop, tablet, and mobile devices.

 Part 2: Working Through Feedback
Following the release of marks and feedback from **Part 1**, the following corrections and improvements were made:

- Implemented corrections based on feedback regarding HTML structure and navigation consistency.
- Added missing sections (e.g., About, Services, Blog, Contact).
- Improved the CSS styling by separating it into an external `style.css` file and applying consistent design rules.
- Enhanced responsiveness using media queries for desktop, tablet, and mobile.
- Improved accessibility with semantic HTML and descriptive image alt attributes.

All changes are recorded in the **Change Log** below.



 CSS Styling for Desktop Solution

### 2.1 External Stylesheet
- Created an external stylesheet named **`style.css`**.
- Linked the stylesheet to all HTML files in the project for consistent design.

2.2 Base Style
- Applied a global reset to normalize styling across browsers.
- Set a consistent **font family (Arial, sans-serif)**, **font size (16px base)**, and **colour scheme** (green tones for eco-theme).
- Applied margin and padding resets for clean layout.

2.3 Typography Styles
- Used CSS properties such as:
  - `font-family`, `font-size`, `font-weight`, `line-height`, and `letter-spacing`.
- Established a hierarchy with headings, paragraphs, and navigation text.
- Created a harmonious scale for readability.

2.4 Layout Structure
- Used **Flexbox** for navigation menus and responsive alignment.
- Applied **CSS Grid** for the services section and blog previews.
- Ensured that the desktop version is clear, balanced, and easy to navigate.

2.5 Visual Styles
- Applied brand colour scheme (`#2d6a4f`, `#52b788`, `#b7e4c7`).
- Styled buttons with hover and focus states for interactivity.
- Added shadows, borders, and rounded corners for a modern, eco-friendly design.

---

 Responsive Design

3.1 Breakpoints
- Key breakpoints: **desktop (≥1024px)**, **tablet (768px–1023px)**, **mobile (<768px)**.
- Layout changes:
  - Multi-column grid on desktop.
  - Two-column layout on tablets.
  - Single-column stacked layout on mobile.
- Navigation collapses into a simpler layout on small screens.

3.2 Relative Units
- Used **`em`** and **`rem`** for font sizes and spacing.
- Used **%** for flexible widths to adapt across screen sizes.

3.3 Responsive Images
- Used relative max-width for images to scale down on small devices.
- Prepared for `srcset` and `sizes` to optimize image loading if required.



Change Log (Based on Feedback)

| Date       | File(s) Updated           | Change Description                                                                 |
|------------|---------------------------|-----------------------------------------------------------------------------------|
| 2025-09-20 | `index.html`, `style.css` | Moved inline CSS to external stylesheet; established base styles.                  |
| 2025-09-22 | `about.html`              | Expanded "About Us" section with mission statement and team image.                 |
| 2025-09-23 | `services.html`           | Added services grid layout using CSS Grid.                                         |
| 2025-09-24 | `quote.html`              | Designed enquiry form with input validation and clean layout.                      |
| 2025-09-25 | `contact.html`            | Added contact details, styled form, and made it responsive for mobile screens.     |
| 2025-09-26 | All pages                 | Improved navigation links, consistent footer, and responsive typography scaling.   |



 Deployment
This website is hosted via **GitHub Pages**:  
https://github.com/LethaboM-PIXEL/Green-Landscaping-.git

Additional Notes
- Prioritized **content clarity** and **user experience** across devices.
- Tested across different browsers (Chrome, Firefox, Edge).
- Ensured accessible design with semantic tags, alt text for images, and logical heading structure.


