📖 Website Documentation
1. Project Overview

This project is a responsive multipage website designed using HTML5, CSS3, and JavaScript.
It contains three core pages:

Home (index.html) — landing page with navigation and optional image slider.

About (about.html) — information about the website/project.

Contact (contact.html) — a contact form with client-side validation.

The website is responsive, adapting to mobile, tablet, and desktop screen sizes.
It has been deployed using GitHub Pages (alternatively Netlify or Vercel can be used).

2. Features Implemented

✅ Responsive design using CSS media queries.

✅ Navigation bar that adapts to small screens (hamburger menu toggle).

✅ JavaScript interactivity:

Contact form validation (checks required fields and email format).

Simple image slider with autoplay and pause-on-hover.

✅ Semantic HTML5 structure (<header>, <main>, <section>, <footer>).

✅ Deployed live with a public URL.

3. Technology Stack

HTML5 → Semantic structure and page content.

CSS3 → Styling, layout, and responsive design.

JavaScript (Vanilla) → Form validation, slider functionality, mobile menu toggle.

GitHub Pages / Netlify / Vercel → Hosting and deployment.

4. File Structure
my-website/
├─ index.html        # Home page
├─ about.html        # About page
├─ contact.html      # Contact page (with form)
├─ styles.css        # CSS styles
├─ script.js         # JavaScript for interactivity
└─ README.md         # Basic project readme

5. How It Works
Navigation

Top navigation bar with links to Home, About, and Contact.

On smaller screens, a hamburger menu button toggles the navigation list.

Contact Form

Fields: Name, Email, Message.

JavaScript validates inputs before submission:

Name must not be empty.

Email must match a valid format.

Message must have a minimum length.

Displays success or error messages inline.

Image Slider

Automatically slides through images every 4 seconds.

Pauses when the user hovers over the slider.

Supports manual navigation if buttons are added.

6. Responsive Design

Layout adjusts based on screen size using CSS media queries.

Navigation collapses into a toggle menu for screens ≤ 768px wide.

Images scale fluidly (100% width).

Text and sections wrap neatly on smaller screens.

7. Deployment

GitHub Pages:

Push project files to GitHub.

Go to Repository → Settings → Pages.

Select branch main and root /.

Website becomes live at https://tiny-horse-ddfaf1.netlify.app/

Alternative: Deploy via Netlify or Vercel by linking your GitHub repo.

8. Live Website URL

👉https://tiny-horse-ddfaf1.netlify.app/


9. Future Improvements

Add a backend (Node.js, PHP, or FastAPI) for handling real form submissions.

Improve accessibility (keyboard navigation, ARIA roles).

Add more pages (e.g., Services, Portfolio).

Enhance design with animations and CSS frameworks (Bootstrap/Tailwind).

10. Author

Name: Joseph Muthui
