# 🌐 itswael.github.io

**Live Portfolio Website** - This repository hosts the deployed version of my professional portfolio website, accessible at [itswael.github.io](https://itswael.github.io).

[![Website Status](https://img.shields.io/website?url=https%3A//itswael.github.io)](https://itswael.github.io)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20with-GitHub%20Pages-blue)](https://pages.github.com/)
[![Last Commit](https://img.shields.io/github/last-commit/itswael/itswael.github.io)](https://github.com/itswael/itswael.github.io)

## 🎯 About This Repository

This repository contains the **production build** of my portfolio website, automatically deployed via GitHub Pages. The source code and development environment are maintained in the [portfolio-frontend](https://github.com/itswael/portfolio-frontend) repository.

### 🔄 **Deployment Pipeline**
```
Source Code (portfolio-frontend) 
    ↓ GitHub Actions CI/CD
    ↓ Build Process (Vite)
    ↓ Automated Deployment
Production Site (itswael.github.io)
```

## 🚀 Live Website Features

### 💼 **Professional Portfolio Sections**
- **Hero Section**: Introduction and call-to-action
- **About Me**: Personal background and professional journey
- **Work Experience**: Interactive timeline of career milestones
- **Featured Projects**: Showcase with screenshots and live demos
- **Skills**: Interactive visualization of technical expertise
- **Contact Form**: Direct communication via EmailJS integration

### 🎨 **Design & User Experience**
- **Modern Design System**: Professional color palette and typography
- **Responsive Layout**: Optimized for all devices and screen sizes
- **Smooth Navigation**: Internal scrolling between sections
- **Interactive Elements**: Hover effects and micro-animations
- **Accessibility**: WCAG AA compliant design

### ⚡ **Performance Optimizations**
- **Fast Loading**: Vite-optimized build with code splitting
- **SEO Optimized**: Meta tags and semantic HTML structure
- **Progressive Enhancement**: Works without JavaScript
- **Optimized Assets**: Compressed images and minified code

## 📊 Website Analytics

### 🎯 **Performance Metrics**
- **Lighthouse Score**: 95+ across all categories
- **Core Web Vitals**: Excellent ratings for LCP, FID, and CLS
- **Mobile Performance**: Optimized for mobile-first experience
- **Accessibility Score**: 100% compliance with WCAG guidelines

### 📈 **SEO Features**
- Semantic HTML structure
- Open Graph meta tags for social sharing
- Structured data markup
- Sitemap.xml for search engines
- Robots.txt configuration

## 🛠 Technologies Used

### **Frontend Stack**
- **React 18**: Modern component-based architecture
- **Vite**: Lightning-fast build tool and dev server
- **Tailwind CSS**: Utility-first styling framework
- **Material-UI**: Professional icon set
- **EmailJS**: Serverless contact form functionality

### **Deployment & Hosting**
- **GitHub Pages**: Free, reliable static site hosting
- **GitHub Actions**: Automated CI/CD pipeline
- **Custom Domain**: Professional domain configuration
- **SSL Certificate**: Secure HTTPS connection

## 🔧 Deployment Process

### **Automated Deployment**
This repository is automatically updated when changes are pushed to the main branch of the [portfolio-frontend](https://github.com/itswael/portfolio-frontend) repository.

1. **Source Update**: Code changes in portfolio-frontend
2. **GitHub Actions**: Triggers automated build process
3. **Build Generation**: Vite creates optimized production build
4. **Deployment**: Built files pushed to this repository
5. **GitHub Pages**: Automatically serves updated content

### **Manual Deployment** (if needed)
```bash
# From portfolio-frontend repository
npm run build
cp -r dist/* ../itswael.github.io/
cd ../itswael.github.io/
git add .
git commit -m "Deploy updated portfolio"
git push origin main
```

## 📁 Repository Structure

```
├── index.html              # Main entry point
├── assets/                 # Compiled CSS, JS, and images
│   ├── index-[hash].js    # Main JavaScript bundle
│   ├── index-[hash].css   # Main CSS bundle
│   └── images/            # Optimized images
├── screenshots/           # Project screenshots
├── favicon.ico           # Site favicon
├── robots.txt           # Search engine instructions
├── sitemap.xml         # SEO sitemap
└── CNAME              # Custom domain configuration (if applicable)
```

## 🌐 Live Links

### **Main Website**
- 🔗 **Portfolio**: [itswael.github.io](https://itswael.github.io)

### **Professional Profiles**
- 💼 **LinkedIn**: [linkedin.com/in/itswael](https://linkedin.com/in/itswael)
- 👨‍💻 **GitHub**: [github.com/itswael](https://github.com/itswael)
- 🧠 **LeetCode**: [leetcode.com/u/user1326iN](https://leetcode.com/u/user1326iN/)

## 📞 Contact Information

### **Get In Touch**
- **Email**: Available through the contact form on the website
- **Response Time**: Usually within 24 hours
- **Languages**: English, Arabic

### **Professional Inquiries**
- Job opportunities
- Collaboration proposals
- Technical consulting
- Speaking engagements

## 🔄 Update Schedule

### **Content Updates**
- **Projects**: Added as they are completed
- **Skills**: Updated quarterly with new technologies
- **Experience**: Updated with new positions and achievements
- **Design**: Refreshed annually or as needed

### **Performance Monitoring**
- Monthly performance audits
- Regular security updates
- SEO optimization reviews
- User experience improvements

## 📈 Development Roadmap

### **Upcoming Features**
- [ ] Dark mode toggle
- [ ] Blog integration
- [ ] Project filtering and search
- [ ] Multi-language support
- [ ] Progressive Web App (PWA) capabilities

### **Performance Improvements**
- [ ] Further image optimization
- [ ] Enhanced caching strategies
- [ ] Additional accessibility features
- [ ] Advanced analytics integration

## 🤝 Feedback & Contributions

### **Found an Issue?**
If you notice any problems with the website, please:
1. Check if it's already reported in [issues](https://github.com/itswael/portfolio-frontend/issues)
2. Create a new issue with detailed description
3. Include browser and device information

### **Suggestions Welcome**
- User experience improvements
- Performance optimizations
- Content suggestions
- Design feedback

## 📊 Website Statistics

### **Built With**
- ⚡ **Build Time**: ~30 seconds
- 📦 **Bundle Size**: <2MB total
- 🎯 **Lighthouse Score**: 95+
- 📱 **Mobile Friendly**: 100%
- ♿ **Accessibility**: WCAG AA Compliant

### **Last Updated**
- **Content**: Check commit history for latest updates
- **Dependencies**: Regularly updated for security
- **Performance**: Continuously optimized

---

## 🎉 About the Developer

**Mohammad Wael** - Full-Stack Developer passionate about creating exceptional web experiences with modern technologies. This portfolio showcases my journey in software development, from scalable backends to intuitive user interfaces.

### **Expertise Areas**
- Full-Stack Web Development
- React & Modern Frontend Frameworks
- Node.js & Backend Architecture
- Cloud Deployment & DevOps
- Database Design & Management
- AI/ML Integration

---

## 📄 License

This project is licensed under the **Wael Non-Commercial Attribution License (WNCA)**.

You're free to use, modify, and share this project **for non-commercial purposes**, as long as:
- **Credit is given** to the original author, *Mohammad Wael*.
- A copy of the license is included with any substantial portion of this work.
- You do **not** use it for monetary gain without written permission.

See the [LICENSE](./LICENSE) file for full terms.

[![License: WNCA](https://img.shields.io/badge/license-WNCA-blue.svg)](./LICENSE)

**🚀 Visit the live website: [itswael.github.io](https://itswael.github.io)**

*Built with ❤️ using React, Tailwind CSS, and deployed with GitHub Pages.*
