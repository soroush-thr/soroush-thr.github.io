# Soroush Taheri - Data Scientist & ML Engineer Portfolio

A modern, professional portfolio website showcasing expertise in Data Science, Machine Learning, and research achievements. Built with a focus on clean design, smooth animations, comprehensive SEO/structured data, and professional presentation.

## 🚀 Live Demo

Visit the live portfolio: [https://soroush-thr.github.io](https://soroush-thr.github.io)

## 📋 Features

- **Multi-Page Architecture**: Dedicated pages for Home, About, Experience, Projects, Services, Education, Research, and Contact
- **Dark/Light Theme Toggle**: User preference-based theme switching with persistent storage
- **Professional Design**: Modern, clean interface with sophisticated color scheme and typography
- **Responsive Layout**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scroll animations, publication filtering, and dynamic navigation
- **Comprehensive Showcase**: Research publications, professional experience, services, and technical achievements
- **Performance Optimized**: Compressed/lazy-loaded images, preconnected fonts, and efficient code
- **SEO & AI-Search Optimized**: Unique meta/OG/Twitter tags, canonical URLs, JSON-LD structured data (Person, BreadcrumbList, ScholarlyArticle, Service), `llms.txt`, and an accurate `sitemap.xml`/`robots.txt`
- **Accessibility**: Keyboard navigation, semantic HTML (one `<h1>` per page), and screen reader friendly
- **Contact Integration**: Direct links to professional profiles and contact information

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with proper accessibility features and JSON-LD structured data
- **CSS3**: Advanced styling with CSS Grid, Flexbox, custom properties, and smooth animations
- **JavaScript (ES6+)**: Interactive functionality, scroll effects, and form handling
- **Font Awesome 6.0**: Professional icon library
- **Google Fonts**: Inter font family for modern, readable typography
- **GitHub Pages**: Free hosting and automatic deployment

## 📁 Project Structure

```
portfolio/
├── index.html          # Home page - Main landing page (Person JSON-LD)
├── about.html          # About page - Personal summary and professional highlights
├── experience.html     # Experience page - Professional experience and achievements
├── projects.html       # Projects page - Portfolio of technical projects
├── services.html       # Services page - Consulting/development services & pricing (Service JSON-LD)
├── education.html      # Education page - Academic background and certifications
├── research.html       # Research page - Publications and research work (ScholarlyArticle JSON-LD)
├── contact.html         # Contact page - Contact information and social links
├── 404.html            # Custom not-found page
├── styles.css          # Comprehensive CSS with modern design system and dark/light theme
├── script.js           # JavaScript functionality, theme toggle, and interactions
├── robots.txt          # Robots file, including explicit allow rules for AI/LLM crawlers
├── sitemap.xml         # XML sitemap listing the site's actual pages
├── llms.txt            # Plain-text summary of the site for AI assistants/LLM crawlers
├── README.md           # Project documentation
└── images/
    ├── personal.jpg          # Profile photo (500x500, optimized)
    ├── thumbnail.png         # Site logo (used in the nav bar)
    ├── favicon-16.png        # 16x16 favicon
    ├── favicon-32.png        # 32x32 favicon
    ├── apple-touch-icon.png  # 180x180 iOS home-screen icon
    ├── og-image.jpg          # 1200x630 Open Graph / social share image
    └── projects/             # Project thumbnails (compressed PNGs)
```

## 🎯 Portfolio Pages

1. **Home (index.html)**: Landing page with hero section, key statistics, and overview
2. **About (about.html)**: Personal summary, professional highlights, and expertise
3. **Experience (experience.html)**: Professional experience timeline and key achievements
4. **Projects (projects.html)**: Portfolio of technical projects with descriptions and links
5. **Services (services.html)**: Data science/ML consulting services offered, with pricing
6. **Education (education.html)**: Academic background, relevant coursework, and certifications
7. **Research (research.html)**: Research publications with filtering (Journal Articles, Conference Papers)
8. **Contact (contact.html)**: Professional contact information and social media links

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- GitHub account (for hosting)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/soroush-thr/soroush-thr.github.io.git
   ```

2. Navigate to the project directory:
   ```bash
   cd soroush-thr.github.io
   ```

3. Open `index.html` in your web browser or serve locally:
   ```bash
   # Using Node.js
   npx serve .

   # Using Python
   python -m http.server 8000

   # Using PHP
   php -S localhost:8000
   ```

## 🌐 GitHub Pages Deployment

This portfolio is automatically deployed using GitHub Pages:

1. Repository name must be `username.github.io` (where username is your GitHub username)
2. Push your code to the `main` branch
3. Go to repository Settings > Pages
4. Select "Deploy from a branch" and choose `main`
5. Your site will be available at `https://username.github.io`

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- **Desktop**: 1200px+ (Full layout with side-by-side content)
- **Tablet**: 768px - 1199px (Adjusted grid layouts and spacing)
- **Mobile**: 320px - 767px (Single column layout with optimized navigation)

## 🎨 Design System

### Color Palette

The site ships two themes, toggled via `[data-theme]` on `<html>` and persisted in `localStorage`.

```css
/* Dark theme (default) */
:root {
    --primary-color: #4A90E2;
    --secondary-color: #5BA3F5;
    --accent-color: #6BB6FF;
    --text-primary: #E8F0F8;
    --text-secondary: #B8D4F0;
    --background-primary: #0A1929;
    --background-secondary: #132F4C;
}

/* Light theme */
[data-theme="light"] {
    --primary-color: #1E3A8A;
    --secondary-color: #2563EB;
    --accent-color: #3B82F6;
    --text-primary: #1E293B;
    --text-secondary: #475569;
    --background-primary: #FFFFFF;
    --background-secondary: #F8FAFC;
}
```

### Typography
- **Primary Font**: Inter (Google Fonts)
- **Font Weights**: 300, 400, 500, 600, 700
- **Responsive Sizing**: Fluid typography with clamp() functions

### Components
- **Cards**: Rounded corners with subtle shadows and hover effects
- **Buttons**: Gradient backgrounds with smooth transitions
- **Navigation**: Fixed header with backdrop blur, smooth scrolling, and active page highlighting
- **Theme Toggle**: Dark/light mode switcher with persistent user preference
- **Timeline**: Visual timeline with animated markers and content cards
- **Project Grid**: Responsive grid layout for project showcase

## 🎨 Customization

### Personal Information
- Update content across all HTML pages (`index.html`, `about.html`, `experience.html`, etc.)
- Modify professional experience in `experience.html`
- Add or remove projects in `projects.html`
- Update services and pricing in `services.html`
- Update publications in `research.html`
- Modify education and certifications in `education.html`
- Update contact information in `contact.html`
- Keep `llms.txt`, `sitemap.xml`, and each page's JSON-LD block in sync when adding/removing pages or facts

### Visual Styling
- Modify CSS custom properties in `styles.css`
- Adjust color scheme and typography
- Customize animations and transitions
- Update spacing and layout parameters

### Functionality
- Theme toggle functionality in `script.js` (dark/light mode)
- Enhance JavaScript interactions and animations
- Add additional filters or interactive features
- Implement contact form with EmailJS integration
- Add analytics tracking (Google Analytics, etc.)

## 📊 Performance Features

- **Optimized Images**: Project thumbnails and the site logo are compressed PNGs (~60-70% smaller than source); the profile photo and favicons are generated at their actual display size
- **Lazy Loading**: Below-the-fold project thumbnails use `loading="lazy"`; above-the-fold images ship explicit `width`/`height` to avoid layout shift
- **Preconnected Assets**: `preconnect` hints for Google Fonts and the Font Awesome CDN
- **Smooth Animations**: Hardware-accelerated CSS transitions
- **Mobile-First**: Responsive design with mobile optimization
- **Accessibility**: Semantic HTML and keyboard navigation support

## 🔎 SEO & AI Search

- **Structured data (JSON-LD)**: `Person` on the homepage (with `sameAs` links to GitHub, LinkedIn, Scholar, ORCID, ResearchGate, Web of Science), `BreadcrumbList` on every subpage, `ScholarlyArticle` for each publication, and `Service`/`Offer` for each service listed
- **Meta tags**: unique `<title>`/description, `canonical`, Open Graph, and Twitter Card tags on every page, with a dedicated 1200×630 `og-image.jpg`
- **`llms.txt`**: a plain-text summary of the site for AI assistants and LLM-based search crawlers
- **`robots.txt`**: explicitly allows major AI crawlers (GPTBot, ClaudeBot, PerplexityBot, Google-Extended, etc.) in addition to standard search engines
- **`sitemap.xml`**: lists the site's actual pages with accurate `lastmod` dates (kept in sync manually when pages change)

## 🔧 Browser Support

- **Chrome**: 90+ (Full support)
- **Firefox**: 88+ (Full support)
- **Safari**: 14+ (Full support)
- **Edge**: 90+ (Full support)
- **Mobile Browsers**: iOS Safari, Chrome Mobile, Samsung Internet

## 📊 Key Features & Achievements

### Professional Highlights
- **8+ Years Experience** in Data Science and Machine Learning
- **4 Peer-Reviewed Publications** in high-impact journals including Scientometrics
- **25% RMSE Improvement** in predictive analytics models
- **7% Cost Reduction** achieved through energy forecasting systems
- **99.8% System Uptime** for production ML pipelines
- **18% Accuracy Boost** in NLP topic relationship detection

### Technical Expertise
- **Machine Learning**: Deep Learning, Neural Networks, LSTM, BERT
- **Computer Vision**: CNNs, Transfer Learning, 3D Image Analysis
- **NLP**: BERT-based embeddings, Topic Modeling, Sentiment Analysis
- **Data Science**: Predictive Analytics, Time Series, Statistical Modeling
- **Cloud & MLOps**: AWS, Scalable Pipelines, Production Deployment
- **Programming**: Python, R, SQL, JavaScript, HTML/CSS

## 📄 License

The code in this repository (HTML/CSS/JS) is available under the [MIT License](LICENSE). The content — text, photos, publication data, and personal information — belongs to Soroush Taheri and is not covered by that license.

## 📞 Contact

**Soroush Taheri**
*Data Scientist & ML Engineer*

- **Email**: [soroush.thr@gmail.com](mailto:soroush.thr@gmail.com)
- **LinkedIn**: [linkedin.com/in/soroush-thr](https://www.linkedin.com/in/soroush-thr)
- **GitHub**: [github.com/soroush-thr](https://github.com/soroush-thr)
- **Google Scholar**: [View Profile](https://scholar.google.com/citations?hl=en&user=hhoL598AAAAJ)
- **ORCID**: [0000-0002-5885-3036](https://orcid.org/my-orcid?orcid=0000-0002-5885-3036)
- **ResearchGate**: [Profile](https://www.researchgate.net/profile/Soroush_Taheri)

## 🙏 Acknowledgments

- **Design Inspiration**: Modern portfolio templates and professional web design trends
- **Icons**: Font Awesome 6.0 for comprehensive icon library
- **Typography**: Google Fonts (Inter) for modern, readable typography
- **Hosting**: GitHub Pages for reliable, free hosting
- **Responsive Design**: Modern CSS Grid and Flexbox techniques
- **Performance**: Optimized animations and efficient code practices

## 🔄 Recent Updates

- ✅ **SEO & Structured Data Overhaul**: Fixed sitemap.xml, expanded robots.txt for AI crawlers, added canonical/OG/Twitter tags and JSON-LD (Person, BreadcrumbList, ScholarlyArticle, Service) to every page, added `llms.txt` and `404.html`
- ✅ **Image Optimization**: Compressed all project thumbnails and the site logo (~60-70% smaller), resized the profile photo to its display size, generated a proper favicon set (16/32/180) and a dedicated 1200×630 social share image, and added lazy-loading to below-the-fold images
- ✅ **Services Page**: Added a dedicated Services page listing consulting offerings and pricing
- ✅ **Multi-Page Architecture**: Converted to dedicated pages for better organization and SEO
- ✅ **Dark/Light Theme**: Implemented theme toggle with persistent user preference storage
- ✅ **Professional Design System**: Comprehensive CSS variables and modern styling
- ✅ **Enhanced Responsiveness**: Optimized for all device sizes with mobile-first approach
- ✅ **Interactive Features**: Smooth animations, scroll effects, and dynamic navigation
- ✅ **Content Organization**: Structured pages for publications, experience, projects, services, and achievements

---

**Built with ❤️ by Soroush Taheri**
*Last Updated: September 2026*
