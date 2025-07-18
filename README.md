# Stykka Køkken Brochure - Fælledby

A responsive digital brochure showcasing Stykka kitchens designed specifically for Fælledby residents. This project combines modern web design with print-optimized layouts to serve as both a web experience and printable brochure.

## 🏗️ Project Overview

This digital brochure presents Stykka's circular kitchen philosophy and premium materials through an engaging, interactive web experience. Built with performance and accessibility in mind, it serves as a comprehensive introduction to Stykka kitchens for Fælledby residents.

### Key Features

- **Dual-purpose design**: Optimized for both web viewing and print
- **Responsive layout**: Works seamlessly across all device sizes
- **Interactive elements**: Blended image banners, material selection buttons, and smooth scroll animations
- **Performance optimized**: Fast loading with lazy loading, deferred scripts, and optimized assets
- **Print-friendly**: Specialized print CSS for clean brochure printing

## 📋 Pages & Sections

### Main Page (`index.html`)

1. **Hero Section**: Welcome message with animated scroll prompt
2. **Filosofien**: Circular design philosophy and kitchen detail imagery
3. **Ansvarlighed**: Three-pillar sustainability approach
4. **Farveskift & Opgraderinger**: Interactive blended banner with 4 kitchen color variants
5. **Take-Back Program**: Circular economy process and material lifecycle
6. **Digital Platform**: QR code integration and platform overview
7. **Service Links**: Maintenance, upgrades, and parts ordering
8. **Partnership Video**: Stykka and Fælledby collaboration story

### Maintenance Page (`vedligeholdelse.html`)

1. **Materials Overview**: Interactive cube showcase of premium materials
2. **Care Instructions**: Interactive material selector with 5 categories
3. **Professional Tips**: Long-term care guidance
4. **Support Contact**: Direct access to Stykka experts

## 🎨 Design System

### Brand Colors
- **Fælledby Orange**: `#ab6627` - Primary accent color
- **Fælledby Green**: `#005B3B` - Secondary brand color, buttons
- **Warm Background**: `#FBF9F7` - Section backgrounds
- **Bright Blue**: `#3B82F6` - Notice boxes and highlights

### Typography
- **Primary Font**: Inter (400, 500, 700 weights)
- **Brand Font**: Georgia Bold for "Stykka" logo (now larger in footer)

## 📱 Mobile Responsiveness

### Responsive Features
- **Hamburger Navigation**: Collapsible mobile menu with smooth animations
- **Optimized Spacing**: 1.5rem padding on mobile for better readability
- **Responsive Images**: Adaptive sizing across all screen sizes
- **Touch-Friendly Buttons**: Appropriately sized for mobile interaction
- **Flexible Layouts**: Flexbox ordering for optimal mobile content flow

## 🚀 Performance Optimizations

- **Font Loading**: Async font loading with fallbacks
- **Image Optimization**: Lazy loading on all non-critical images
- **Script Loading**: Synchronous Tailwind CSS for immediate styling
- **Resource Hints**: DNS prefetch and preload for critical resources
- **Glass Morphism**: Backdrop blur effects for premium appearance

## ✨ Interactive Features

### Color Switcher
- **Interactive buttons** in top-left of kitchen banner
- **Auto-cycling** through 4 colors every 4 seconds
- **Manual control** with 10-second pause after user interaction
- **Smooth transitions** between kitchen variants

### Header Transparency
- **Dynamic opacity** changes on scroll
- **Backdrop blur** effects for readability
- **Smooth transitions** for premium feel

### Service Cards
- **Custom PNG icons** (180px) for each service
- **Fælledby orange tint** for brand consistency
- **Hover animations** with lift effects
- **Staggered appearance** animations

## 📁 File Structure

```
Brochure Fælledby/
├── index.html              # Main brochure page
├── vedligeholdelse.html     # Maintenance guide page
├── vercel.json             # Deployment configuration
├── README.md               # Project documentation
├── CLAUDE.md               # AI instructions
└── images/                 # All image assets
```

## 🌐 Deployment

Configured for Vercel deployment with automatic builds on push to main branch.

## 🔗 External Integrations

- **Upgrade Shop**: `https://www.stykka.com/upgrades/fbc4`
- **Parts Ordering**: `https://www.stykka.com/parts`
- **YouTube**: Embedded partnership video

## 🎯 Key Features Added

### Pricing Section
- **Complete kitchen color change**: 11.230 dkk (16 x fronter)
- **Individual upgrades**: Detailed pricing list
- **Service notice**: Blue textured box with installation guarantee

### Textured Footer
- **Custom texture**: Uses `background-texture.jpg` with green overlay
- **Consistent branding**: Applied to both pages with identical styling
- **Larger Stykka logo**: Georgia Bold, removed "ApS" (text-4xl)
- **Enhanced spacing**: 16px padding, 12px gaps, improved typography
- **Layered overlays**: Multiple gradient layers for depth and readability

### Navigation
- **Section-based**: Links to page sections (#tilvalg, #takeback, etc.)
- **Footer links**: External services (upgrades, parts)
- **Proper alignment**: Navigation matches page structure

---

**Built with care for Fælledby residents by Stykka** 