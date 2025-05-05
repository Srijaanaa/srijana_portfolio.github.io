# Srijana Lohani Portfolio

Welcome to my personal portfolio website! This project showcases my skills, projects, education, volunteering experience, and contact information as an aspiring web developer and programmer. Built with a focus on clean design and responsiveness, it serves as a professional hub for recruiters, collaborators, and visitors.

## Features

- **Responsive Design**: Adapts seamlessly to desktop, tablet, and mobile devices.
- **Dark Mode**: Toggle between light and dark themes with local storage persistence.
- **Hero Section**: Engaging introduction with animated text (via Typed.js) and a background pattern (white-diamond for light mode, dark-mosaic for dark mode).
- **About Me**: Highlights my background with a taller portrait photo and increased text-photo spacing for clarity.
- **Skills Section**: Vertical layout with animated progress bars, percentage labels, and hover effects.
- **Portfolio**: Interactive project cards with hover overlays linking to GitHub repositories.
- **Education & Experience**: Timeline-based education history and concise experience summary.
- **Volunteering**: Dedicated section showcasing community involvement in tech initiatives.
- **Fun Facts**: Engaging tidbits about my interests and passions.
- **Contact Form**: Functional form powered by Web3Forms with success animation.
- **Scroll-to-Top**: Convenient button for easy navigation.
- **SEO Optimized**: Includes meta tags, Open Graph, Twitter Card, and structured data for better visibility.

## Technologies Used

- **HTML5**: Semantic structure for accessibility and SEO.
- **CSS3**: Custom styles with Flexbox, Grid, animations, and responsive media queries.
- **JavaScript**: Interactivity for dark mode, hamburger menu, scroll-to-top, and form handling.
- **Typed.js**: Animated typing effect in the hero section.
- **Font Awesome**: Icons for social media, navigation, and section accents.
- **Web3Forms**: Serverless contact form integration.
- **Google Fonts**: Poppins font for a modern, clean look.

## Project Structure

```
srijana-portfolio/
├── css/
│   └── style.css          # All CSS styles
├── photos/
│   ├── logo.png          # Logo for navbar
│   ├── photo1.jpg        # Hero section photo
│   ├── photo.jpg         # About Me photo
│   ├── project1.jpg      # Portfolio project image
│   ├── project2.jpg      # Portfolio project image
│   ├── project3.jpg      # Portfolio project image
│   └── favicon_io/       # Favicon assets
├── index.html            # Main HTML file
└── README.md             # This file
```

## Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, etc.).
- Optional: A code editor (e.g., VS Code) for customization.
- Optional: Git and a GitHub account for version control.

### Local Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Srijaanaa/srijana-portfolio.git
   cd srijana-portfolio
   ```
2. **Open the Project**:
   - Open `index.html` in a browser to view the site locally, or
   - Use a local server (e.g., VS Code Live Server extension) for a better development experience:
     ```bash
     npx live-server
     ```

### Deployment
To host the site online (e.g., on Netlify, Vercel, or GitHub Pages):
1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial portfolio commit"
   git push origin main
   ```
2. **Deploy**:
   - **GitHub Pages**: Enable GitHub Pages in your repository settings, setting the source to the `main` branch.
   - **Netlify**: Drag and drop the project folder into Netlify’s dashboard or link your GitHub repo for automatic builds.
   - **Vercel**: Import the repo via Vercel’s dashboard and deploy.

3. Update the following in `index.html` with your live domain:
   - `<meta property="og:url">`
   - `<meta property="og:image">`
   - `<meta name="twitter:image">`
   - Structured data (`url` and `sameAs`).

## Customization

- **Update Images**:
  - Replace files in the `photos/` folder with your own (`logo.png`, `photo1.jpg`, `photo.jpg`, `project1.jpg`, etc.).
  - Ensure `photo.jpg` (About Me) is portrait-oriented for the taller aspect ratio (220px × 330px desktop).
- **Portfolio Projects**:
  - Edit the portfolio section in `index.html` to link to your actual GitHub repos or live demos:
    ```html
    <a href="https://github.com/your-username/your-repo" target="_blank" class="portfolio-btn">View Project</a>
    ```
- **Contact Form**:
  - Replace the Web3Forms `access_key` in `index.html` with your own:
    ```html
    <input type="hidden" name="access_key" value="your-access-key">
    ```
  - Get a free key at [Web3Forms](https://web3forms.com/).
- **Volunteering Section**:
  - Update the timeline in `index.html` with your experiences:
    ```html
    <div class="timeline-item">
      <span class="year">Year</span>
      <p>Your Role, Organization</p>
    </div>
    ```
- **SEO**:
  - Customize meta tags (`keywords`, `description`) and social media images for your branding.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for bug fixes, enhancements, or new features.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

- **GitHub**: [Srijaanaa](https://github.com/Srijaanaa)
- **Email**: srijanalohani02@gmail.com
- **Portfolio**: [srijanalohani.com.np](https://www.srijanalohani.com.np/) 

Thank you for visiting my portfolio repository! 🚀
