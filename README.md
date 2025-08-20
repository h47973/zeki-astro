# Zeki Experts - Modern Website

A complete redesign of the Zeki Experts website built with Astro, featuring modern design, excellent performance, and comprehensive SEO optimization.

## 🚀 Features

- **Modern Design**: Clean, professional design inspired by top tech companies like Vercel and GitHub
- **Fast Performance**: Built with Astro for optimal static site generation
- **Responsive**: Fully responsive design that works on all devices
- **Dark/Light Mode**: Built-in theme switching with user preference persistence
- **SEO Optimized**: Comprehensive SEO with structured data, meta tags, and sitemaps
- **Accessible**: WCAG compliant with proper semantic markup and keyboard navigation
- **Animations**: Subtle, professional animations that enhance the user experience
- **Contact Forms**: Netlify-ready contact forms with spam protection
- **Blog Ready**: Complete blog system with filtering and categorization

## 🛠️ Tech Stack

- **Framework**: Astro
- **Styling**: Tailwind CSS
- **Package Manager**: pnpm
- **Deployment Ready**: Static site generation optimized for any hosting provider

## 🏃‍♂️ Getting Started

### Prerequisites

- Node.js 18+ 
- pnpm (recommended) or npm

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   pnpm install
   ```

### Development

Run the development server:
```bash
pnpm run dev
```

The site will be available at `http://localhost:4321`

### Building

Build for production:
```bash
pnpm run build
```

Preview the built site:
```bash
pnpm run preview
```

## 📁 Project Structure

```
├── public/
│   ├── favicon.svg
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   ├── index.astro       # Homepage
│   │   ├── about.astro       # About page
│   │   ├── portfolio.astro   # Portfolio showcase
│   │   ├── contact.astro     # Contact page with forms
│   │   └── blog.astro        # Blog listing
│   └── styles/
│       └── global.css        # Global styles and utilities
├── astro.config.mjs
├── tailwind.config.mjs
└── package.json
```

## 🎨 Design System

The website uses a carefully crafted design system with:

- **Colors**: Modern gradient-based color palette with primary blue and accent purple
- **Typography**: Inter font family with proper font loading and display fonts
- **Components**: Reusable Tailwind CSS utility classes and components
- **Animations**: Subtle hover effects, slide-up animations, and smooth transitions
- **Responsive**: Mobile-first design with breakpoints at sm, md, lg, xl, and 2xl

## 📄 Pages

### Homepage (`/`)
- Hero section with compelling value proposition
- Services showcase with technology listings
- Process explanation (Discovery → Development → Delivery)
- Client testimonials
- Call-to-action sections

### About (`/about`)
- Company story and mission
- Core values
- Team member profiles
- Service offerings
- Company statistics

### Portfolio (`/portfolio`)
- Project showcase with real project images
- Filterable by category
- Project details with technologies used
- Development process explanation
- Case study format

### Contact (`/contact`)
- Comprehensive contact form with Netlify integration
- Global office information (US, Pakistan, UK)
- Business hours and response time
- FAQ section
- Quick contact options

### Blog (`/blog`)
- Article listing with filtering
- Featured post highlighting
- Author information and reading time
- Newsletter signup
- Category-based organization

## 🔧 Customization

### Colors
Edit the color palette in `tailwind.config.mjs`:
```js
colors: {
  primary: { /* Blue color scale */ },
  accent: { /* Purple color scale */ },
  // ... other colors
}
```

### Content
- Update company information in `BaseLayout.astro`
- Modify service offerings in respective page files
- Replace portfolio project data with your own projects
- Update team member information in `about.astro`

### Branding
- Replace favicon files in `/public/`
- Update manifest.json with your app information
- Modify the logo placeholder in the navigation

## 🚀 Deployment

This site is optimized for deployment on:

- **Netlify**: Forms are ready for Netlify Forms integration
- **Vercel**: Zero-config deployment
- **Cloudflare Pages**: Excellent performance
- **AWS S3 + CloudFront**: Enterprise hosting
- **Any static host**: Fully static output

### Environment Variables

For production deployment, consider setting:
- `SITE_URL`: Your production domain
- Google Analytics ID (currently set to G-N6Y0B7Z4P6)

## 📊 Performance Features

- **Static Generation**: All pages are pre-rendered for maximum speed
- **Image Optimization**: Lazy loading and responsive images
- **CSS Optimization**: Tailwind CSS purging and optimization
- **Font Loading**: Optimized Google Fonts loading
- **Minimal JavaScript**: Only essential interactivity
- **Caching Headers**: Optimized for CDN caching

## 🔍 SEO Features

- **Structured Data**: Rich snippets for business information
- **Meta Tags**: Complete Open Graph and Twitter Card support
- **Sitemap**: Automatic sitemap generation
- **Robots.txt**: Search engine crawling instructions
- **Semantic HTML**: Proper heading structure and ARIA labels
- **Performance**: Core Web Vitals optimization

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📝 License

This project is for Zeki Experts. All rights reserved.

## 🆘 Support

For questions or issues:
- Email: info@zekiexperts.com  
- Phone: +1 (202) 992-5235

---

Built with ❤️ by Zeki Experts
