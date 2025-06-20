# 📸 The Moment Maker Films - Premium Wedding Photography Website

## 🌟 Overview

A beautiful, modern, and fully responsive wedding photography website built with Next.js 15, TypeScript, and Tailwind CSS. This website showcases wedding photography services with stunning animations, professional design, and optimal user experience.

## ✨ Features

### 🎨 **Modern Design**
- Beautiful gradient backgrounds and professional color scheme
- Elegant typography with Playfair Display (serif) and Inter (sans-serif)
- Smooth animations powered by AOS (Animate On Scroll)
- Responsive design that works perfectly on all devices

### 📱 **Interactive Components**
- **Hero Carousel**: Auto-sliding hero section with beautiful overlays
- **Floating WhatsApp Button**: Multi-contact options (WhatsApp, Call, Email)
- **Portfolio Gallery**: Filterable portfolio with lightbox modal
- **Contact Forms**: Professional contact forms with validation
- **Testimonials**: Customer reviews with star ratings

### 🚀 **Performance Optimized**
- Built with Next.js 15 for optimal performance
- Static site generation for lightning-fast loading
- Optimized images and lazy loading
- Clean, semantic HTML structure

### 📄 **Complete Pages**
1. **Homepage** - Hero, Services, Portfolio highlights, Testimonials
2. **About** - Company story, team, values, awards
3. **Services** - Detailed service packages with pricing
4. **Portfolio** - Filterable gallery of work
5. **Blog** - Articles and photography tips
6. **Contact** - Contact form, location, business hours

## 🛠️ Tech Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS + Custom CSS
- **Animations**: AOS (Animate On Scroll)
- **Icons**: Heroicons + Lucide React
- **Fonts**: Google Fonts (Playfair Display, Inter)

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/moment-maker-films.git
   cd moment-maker-films
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📋 Available Scripts

```bash
# Development
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint
```

## 🎨 Customization

### **Colors & Branding**
Update your brand colors in `tailwind.config.js`:
```javascript
colors: {
  primary: { dark: "#403F4C" },
  secondary: { dark: "#2C2B3C" },
  accent: { blue: "#1B2432" },
  highlight: { coral: "#B76D68" },
}
```

### **Content Updates**
- **Services**: Edit `src/data/services.ts`
- **Contact Info**: Update `src/components/layout/Footer.tsx`
- **Company Details**: Modify content in page components

### **Images**
Add your images to `public/images/`:
- `hero-1.jpg`, `hero-2.jpg`, `hero-3.jpg` - Hero carousel
- `portfolio-*.jpg` - Portfolio gallery
- `team-*.jpg` - Team member photos

## 📞 Contact Integration

### **WhatsApp Setup**
Update phone number in `src/components/ui/WhatsAppButton.tsx`:
```typescript
phoneNumber = '919876543210' // Replace with your number
```

### **Contact Form**
The contact form in `src/app/contact/page.tsx` includes:
- Name, email, phone validation
- Service selection dropdown
- Event date picker
- Message textarea
- WhatsApp integration

## 🔧 Configuration

### **SEO & Metadata**
Update SEO settings in `src/app/layout.tsx`:
```typescript
export const metadata: Metadata = {
  title: "Your Studio Name - Wedding Photography",
  description: "Your custom description",
  // ... other metadata
};
```

### **Analytics**
Add Google Analytics or other tracking codes in the layout component.

## 📱 Mobile Optimization

- Fully responsive design
- Touch-friendly navigation
- Optimized images for mobile
- Fast loading on slow connections

## 🎯 Features Breakdown

### **Homepage Sections**
1. **Hero Carousel** - Rotating background images with call-to-action
2. **Services** - 3-column service grid with pricing
3. **Portfolio Highlights** - 4-column featured work
4. **Statistics** - Company achievements counter
5. **Testimonials** - Client reviews with ratings
6. **Process** - 4-step workflow explanation
7. **Call-to-Action** - Contact and portfolio links

### **Interactive Elements**
- Smooth scroll animations
- Hover effects on all interactive elements
- Mobile-responsive navigation
- Image galleries with lightbox
- Contact form validation

## 🚀 Deployment

### **Vercel (Recommended)**
1. Push code to GitHub/GitLab
2. Connect your repository to Vercel
3. Deploy automatically

### **Netlify**
1. Build the project: `npm run build`
2. Upload `out` folder to Netlify

### **Custom Server**
1. Build: `npm run build`
2. Start: `npm run start`
3. Configure your web server

## 🐛 Troubleshooting

### **Common Issues**
- **Build Errors**: Run `npm run lint` to check for code issues
- **Missing Images**: Ensure all images exist in `public/images/`
- **Animation Issues**: Check AOS initialization in components

## 📄 License

This project is licensed under the MIT License.

## 🤝 Support

For support or customization requests:
- Email: support@momentmakerfilms.com
- WhatsApp: +91 98765 43210

---

**Built with ❤️ for The Moment Maker Films**

*Capturing life's most precious moments with artistic vision and professional expertise.*
#   m o m e n t - m a k e r - f i l m s  
 