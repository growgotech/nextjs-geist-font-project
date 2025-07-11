# Growgo Tech - Modern Landing Page

A beautiful, responsive landing page built with Next.js 15, TypeScript, and Tailwind CSS featuring modern animations, gradient designs, and interactive components.

## 🚀 Features

- **Modern Design**: Futuristic, clean, and professional aesthetic
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Custom CSS animations and transitions
- **Interactive Components**: Floating chat button, testimonials carousel, hover effects
- **3D-Style Cards**: Beautiful service cards with gradient backgrounds
- **Testimonials Carousel**: Auto-advancing slider with manual navigation
- **Client Logos Grid**: Responsive showcase of trusted partners
- **Contact Integration**: WhatsApp-style floating chat functionality

## 🛠️ Tech Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: ShadCN/UI
- **Icons**: Custom emoji-based design (no external icon libraries)
- **Images**: Pexels integration for service cards

## 📁 Project Structure

```
growgo-tech-landing-page/
├── public/                 # Static assets
│   ├── file.svg
│   ├── globe.svg
│   ├── next.svg
│   ├── vercel.svg
│   └── window.svg
├── src/
│   ├── app/               # Next.js App Router
│   │   ├── globals.css    # Global styles and animations
│   │   ├── layout.tsx     # Root layout with smooth scrolling
│   │   └── page.tsx       # Main landing page
│   ├── components/        # React components
│   │   ├── HeroSection.tsx           # Hero section with gradient background
│   │   ├── CoreServices.tsx          # Service cards with 3D effects
│   │   ├── WhyChooseGrowgo.tsx       # Animated gradient cards
│   │   ├── TestimonialsCarousel.tsx  # Client testimonials slider
│   │   ├── ClientLogos.tsx           # Client logos grid
│   │   ├── FloatingChatButton.tsx    # WhatsApp-style chat modal
│   │   ├── Footer.tsx                # Footer with company info
│   │   └── ui/                       # ShadCN UI components
│   ├── hooks/             # Custom React hooks
│   │   └── use-mobile.ts
│   └── lib/               # Utility functions
│       └── utils.ts
├── package.json           # Dependencies and scripts
├── next.config.ts         # Next.js configuration
├── tsconfig.json          # TypeScript configuration
├── postcss.config.mjs     # PostCSS configuration
├── components.json        # ShadCN configuration
└── eslint.config.mjs      # ESLint configuration
```

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ installed on your machine
- npm or yarn package manager

### Installation

1. **Extract the project files**
   ```bash
   unzip growgo-tech-landing-page.zip
   cd growgo-tech-landing-page
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to see the landing page

## 📱 Sections Overview

### 1. Hero Section
- Full-width gradient background (slate-900 to purple-900)
- Animated headline with gradient text effect
- Navigation menu with smooth scroll links
- Call-to-action buttons with hover effects
- Floating background elements

### 2. Our Core Services
- Three 3D-style service cards:
  - **MakeMyShop**: E-commerce solutions
  - **Custom Software**: Tailored development
  - **Industries Served**: Sector-specific solutions
- Real images from Pexels with fallback handling
- Gradient buttons with unique colors per service

### 3. Why Choose Growgo
- Five vertically-stretched gradient cards:
  - Agile Delivery (⚡)
  - Tech Expertise (🚀)
  - Innovation Focus (💡)
  - Customer Centric (❤️)
  - Proven Reliability (🛡️)
- Scroll-triggered animations
- Hover effects with scale and shadow

### 4. Testimonials Carousel
- Auto-advancing testimonial slider
- Manual navigation with arrow buttons
- Client avatars with gradient backgrounds
- Dot indicators for slide position
- Statistics showcase (500+ Projects, 98% Satisfaction, etc.)

### 5. Client Logos
- Responsive grid of 12 client companies
- Hover effects on logo cards
- Trust indicators with colored icons
- Final call-to-action section

### 6. Floating Chat Button
- WhatsApp-style floating button
- Interactive chat modal with:
  - Welcome message
  - Message input field
  - Quick action buttons
  - Simulated responses

### 7. Footer
- Company information and branding
- Services list and contact details
- Newsletter signup
- Social media links
- Required "Crafted with ♥ using React + Tailwind" text
- Legal links and back-to-top button

## 🎨 Customization

### Colors and Gradients
The project uses a consistent color scheme with gradients:
- Primary: Blue to Purple gradients
- Service cards: Blue-Cyan, Purple-Pink, Green-Teal
- Strength cards: Various gradient combinations

### Animations
Custom animations are defined in `globals.css`:
- `fadeIn`: Smooth entrance animation
- `slideUp`: Upward slide effect
- `float`: Gentle floating motion

### Responsive Design
Tailwind CSS breakpoints:
- `sm`: 640px and up
- `md`: 768px and up
- `lg`: 1024px and up
- `xl`: 1280px and up

## 🔧 Available Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint
```

## 📦 Dependencies

### Core Dependencies
- `next`: 15.3.2
- `react`: 19.0.0
- `typescript`: 5+
- `tailwindcss`: 4.1.6

### UI Components
- `@radix-ui/*`: Headless UI components
- `class-variance-authority`: Component variants
- `clsx`: Conditional classes
- `tailwind-merge`: Merge Tailwind classes

### Additional Features
- `lucide-react`: Icons (minimal usage)
- `embla-carousel-react`: Carousel functionality
- `next-themes`: Theme support

## 🌟 Key Features Implemented

✅ **Responsive Design**: Works perfectly on all device sizes
✅ **Smooth Scrolling**: Enabled throughout the page
✅ **Modern Animations**: Custom keyframes and transitions
✅ **Interactive Elements**: Hover effects, click handlers
✅ **Accessibility**: Proper ARIA labels and semantic HTML
✅ **Performance**: Optimized images and lazy loading
✅ **SEO Ready**: Proper meta tags and structure
✅ **Type Safe**: Full TypeScript implementation

## 🚀 Deployment

The project is ready for deployment on platforms like:
- **Vercel** (recommended for Next.js)
- **Netlify**
- **AWS Amplify**
- **Digital Ocean**

Simply run `npm run build` and deploy the generated files.

## 📄 License

This project is created for Growgo Tech and includes all modern web development best practices.

## 🤝 Support

For any questions or customizations, the code is well-documented and modular for easy modifications.

---

**Built with ♥ using React + Tailwind**
