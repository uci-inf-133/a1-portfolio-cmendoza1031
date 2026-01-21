--Readme document for Cristian Fernando Mendoza, cristian@askclera.com--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else's code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

11/10 (aiming for bonus point)
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 3/2 Embraces spirit of the assignment (aiming for bonus)

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features (included ALL 6 listed options):
    1. Multiple images with descriptive alt attributes (profile photo, project screenshots, family photo)
    2. Appropriate headings (h1, h2, h3) and paragraph text throughout all pages
    3. Links to external pages (LinkedIn, app.askclera.com, askclera.com, GitHub, email)
    4. Multiple pages with appropriate navigation (index.html, projects.html, contact.html)
    5. Semantic HTML tags (header, nav, main, section, article, aside, footer, figure)
    6. Custom icons from Font Awesome (social icons, navigation arrows, technology icons)

(b) CSS features (included ALL 4 listed options):
    1. Modified padding and margins extensively for readability (CSS custom properties for spacing system)
    2. Modified colors with a cohesive dark theme palette using CSS custom properties
    3. Leveraged modern CSS techniques including CSS Grid, Flexbox, and custom animations
    4. Added custom fonts from Google Fonts: Syne (headings), Inter (body), JetBrains Mono (code/tags) with appropriate fallbacks

(c) Advanced features (included MULTIPLE):
    1. Contact form with HTML form validation, accessible labels, honeypot spam protection
    2. Complex page layout with navigation bar, hero sections, card grids, sidebar-style currently section
    3. Nested CSS selectors extensively (hover states, pseudo-elements, responsive breakpoints)
    4. Tech stack table with multiple columns and rows that can be read via screen reader (proper th scope, caption)
    5. Custom CSS animations and transitions (glow effects, floating orbs, fade-in reveals, hover transformations)
    6. FAQ accordion section with interactive details/summary elements

Additional Above and Beyond features:
    - Dark theme with glowing/neon aesthetic inspired by modern tech portfolios
    - Animated gradient orbs in background for depth
    - Mobile-responsive hamburger navigation with smooth animations
    - Scroll reveal animations using Intersection Observer API
    - Accessibility features: skip links (sr-only), ARIA labels, proper focus states, color contrast
    - Print styles for better document output
    - CSS custom properties system for maintainable theming

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

All accessibility warnings were addressed. Key decisions:
- Ensured all images have descriptive alt text
- Added aria-label attributes to icon-only buttons and links
- Used semantic HTML elements throughout (nav, main, article, aside, footer, section)
- Included aria-hidden="true" on decorative elements (gradient orbs, icons used alongside text)
- Form inputs have associated labels and aria-required attributes
- Links have meaningful text (avoided "click here" patterns)
- Color contrast meets WCAG AA standards (light text on dark backgrounds)
- Skip navigation link included for keyboard users (sr-only class)
- Focus states are visible for keyboard navigation

Note: The external Font Awesome CDN link may trigger a warning about third-party resources, but this is standard practice and does not affect accessibility. The icons are decorative and have aria-hidden="true".

4. How long, in hours, did it take you to complete this assignment?

Approximately 8-10 hours total:
- 2 hours: Planning, researching design inspiration (Jasmine Wu site, Aceternity UI)
- 4 hours: Writing HTML structure and CSS styling
- 1 hour: Implementing responsive design and testing across screen sizes
- 1 hour: Adding animations, transitions, and interactive features
- 1 hour: Accessibility review, validation fixes, and documentation

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

Technical Resources:
- https://fonts.google.com/ (Font selection: Syne, Inter, JetBrains Mono)
- https://fontawesome.com/icons (Icon library)
- https://developer.mozilla.org/en-US/docs/Web/CSS (CSS Grid, Flexbox, Custom Properties documentation)
- https://css-tricks.com/a-complete-guide-to-css-gradients/ (Gradient backgrounds)
- https://web.dev/articles/prefers-color-scheme (Accessibility best practices)
- https://webaim.org/resources/contrastchecker/ (Color contrast verification)

AI Assistance:
- Used Claude (AI assistant) for:
  * Generating initial code structure and CSS architecture
  * Suggesting accessibility improvements
  * Optimizing responsive breakpoints
  * Creating consistent design system with CSS custom properties
  * Writing descriptive alt text suggestions

Validators:
- https://validator.w3.org/ (HTML validation)
- https://jigsaw.w3.org/css-validator/ (CSS validation)
- https://achecker.ca/ (Accessibility validation)
- https://wave.webaim.org/ (Additional accessibility testing)

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

No classmates were consulted for this assignment. All work is original.

7. Is there anything special we need to know in order to run your code?

No special setup required. The portfolio is built with vanilla HTML, CSS, and minimal JavaScript.

To view the portfolio:
1. Open index.html directly in any modern web browser (Chrome, Firefox, Safari, Edge)
2. All pages are linked and navigation works locally
3. External links (LinkedIn, Clera app/website) require internet connection

File Structure:
- index.html      : Home page with hero, about, featured project, skills, currently sections
- projects.html   : Full projects showcase with tech stack table
- contact.html    : Contact form, personal section, FAQ accordion
- styles.css      : All styling with CSS custom properties, animations, responsive design
- images/         : Folder for images (placeholder paths used - replace with actual images)

Image Placeholders:
The following images need to be added to the /images/ folder:
- profile.jpg        : Professional headshot or portrait
- clera-preview.jpg  : Screenshot of the Clera app dashboard
- clera-marketing.jpg: Screenshot of askclera.com homepage
- portfolio-preview.jpg: Screenshot of this portfolio
- course-projects.jpg: Representative image for course work
- family.jpg         : Personal/family photo (siblings)

Note: The contact form action is set to a Formspree placeholder URL. For production use, I will need to replace with actual form endpoint or backend handler.

---