# Personal CV Website

A responsive digital resume built with HTML, CSS, and JavaScript. Features dark/light mode toggle and a clean, professional interface.

## Features

- Fully responsive design for all devices
- Dark/light theme toggle with smooth transitions
- Downloadable PDF version
- Project portfolio showcase with 11 individual projects
- Modern UI with hover effects

## Project Structure

```
RESUME/
│
├── Achievements/              # Project portfolio (11 projects)
│   ├── project1.html - project11.html
│   └── style.css
│
├── Pdf Resume/
│   └── My Resume.pdf         # Downloadable CV
│
├── Photo/
│   └── pack.jpg              # Profile picture
│
├── index.html                # Main CV page
└── style.css                 # Styling and themes
```

## Technologies

- HTML5
- CSS3 (Custom Properties)
- Vanilla JavaScript

## Content Sections

- Profile: Ali Al-ojeely - Junior Software Developer
- Contact: Email and social links (LinkedIn, GitHub)
- Education: Bachelor's Degree in Information Technology
- Technical Skills: HTML, CSS, React.js, C++
- Projects: 11 showcased projects
- PDF Resume: Direct download link

## Getting Started

1. Clone or download the repository
2. Open `index.html` in a browser
3. Use the dark mode toggle in the header to switch themes

## Customization

**Update Content:**
- Replace `pack.jpg` in `Photo/` folder
- Edit `index.html` with your information
- Update `My Resume.pdf` in `Pdf Resume/` folder

**Change Colors:**
Edit CSS variables in `style.css`:
```css
--mainTextColor-light: #000;
--mainLinkColor-light: #0da2b8;
--mainBgColor-light: rgb(249, 250, 251);
```

**Add Projects:**
Create new HTML files in `Acheviments/` folder and link from main page.

## Responsive Design

- Mobile: < 600px
- Tablet: 600px - 1024px
- Desktop: > 1024px

## Deployment

Host on GitHub Pages, Netlify, Vercel, or any static hosting platform.

## License

Open source - free for personal and commercial use.

---

Built with HTML, CSS & JavaScript