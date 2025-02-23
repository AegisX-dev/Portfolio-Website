# AegisX-Dev Portfolio Website

## Overview
This is a personal portfolio website built to showcase my skills and projects as a Front-End Developer. The site features a modern design with animated gradients, responsive layouts, and interactive elements, demonstrating proficiency in HTML, CSS, and JavaScript.

## Features
- Home Section: A visually striking landing page with an animated gradient background, navigation bar, and wave animation.
- About Me Section: A personal introduction with a profile picture and animated gradient background.
- Projects Section: A grid of project cards showcasing my work, with hover effects and placeholder images.
- Contacts Section: A contact form for visitors to reach out, styled with an animated gradient background.
- Fixed Footer: Social media links and copyright notice, fixed at the bottom of the viewport.
- Responsive Design: Fully responsive layout that adjusts for mobile and desktop screens.
- Shine Effect: Animated shine effect on section headings for visual appeal.

## Technologies Used
- HTML5: Structure of the website.
- CSS3: Styling, animations, and responsive design (including Flexbox and Grid).
- Font Awesome: Icons for social media links in the footer.
- Google Fonts: Custom fonts (Open Sans and Maven Pro) for typography.

## Installation
To run this portfolio website locally, follow these steps:

1. Clone the Repository (if hosted on GitHub or similar):
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
   Replace `your-username` and `your-repo-name` with your actual GitHub details.

2. Navigate to the Project Directory:
   ```bash
   cd your-repo-name
   ```

3. Open the HTML File:
   - Open `index.html` in a web browser (e.g., Chrome, Firefox) by double-clicking it or using a local server.
   - Alternatively, use a local development server like Live Server in VS Code for a better experience.

4. Update Assets:
   - Replace `photo_6057603943246185292_y.jpg` in the "About Me" section with your profile picture. Ensure it’s in the same directory as `index.html` or adjust the path accordingly.
   - Update project images in the "Projects" section with your own project screenshots (replace Unsplash URLs).
   - Update social media links in the footer (`<a href="#" ...>`) with your actual profile URLs.

## Project Structure
```
your-repo-name/
├── index.html          # Main HTML file
├── photo_6057603943246185292_y.jpg  # Profile picture (replace with your own)
└── README.md           # This file
```
- All styles are embedded in the `<style>` tag within `index.html` for simplicity.
- External dependencies (Font Awesome, Google Fonts) are linked via CDNs.

## Usage
- Navigation: Use the top navigation bar to jump between sections (Home, About Me, Projects, Contacts).
- Contact Form: The form is currently static. To make it functional, integrate it with a backend service (e.g., Formspree, Netlify Forms) or server-side scripting (e.g., PHP).
- Customization: Edit the content in each section (e.g., About Me text, project details) to reflect your personal information and portfolio.

## Customization
- Profile Picture: Replace the `src` attribute in `<img src="photo_6057603943246185292_y.jpg">` with your image path or URL.
- Projects: Update the `.project-card` content (images, titles, descriptions) in the "Projects" section.
- Social Links: Replace the `#` in `<a href="#">` tags in the footer with your GitHub, LinkedIn, Twitter, and email links.
- Colors: Modify gradient colors in the CSS (e.g., `#home`, `#about-me`, `#projects`, `#contacts`) to match your branding.
- Animations: Adjust animation durations (e.g., `10s`, `15s`, `12s`, `14s`) or keyframes for different effects.

## Deployment
To host this website online:
1. Upload the files to a web hosting service (e.g., GitHub Pages, Netlify, Vercel).
2. Ensure all image paths are correct (use relative paths or hosted URLs).
3. Test the site in a browser to confirm responsiveness and functionality.

## Credits
- Developer: AegisX-Dev (replace with your name)
- Icons: [Font Awesome](https://fontawesome.com/)
- Fonts: [Google Fonts](https://fonts.google.com/)
- Placeholder Images: [Unsplash](https://unsplash.com/) (used in Projects section)

## License
This project is open-source and available under the [MIT License](LICENSE). Feel free to use and modify it for your own purposes.

## Contact
For questions or collaboration, reach out via:
- GitHub: [your-username](https://github.com/your-username) (replace with your GitHub)
- Email: your.email@example.com (replace with your email)
