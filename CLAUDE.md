# AI Instructions for Stykka Fælledby Brochure Project

## Project Overview
This is a responsive digital brochure for Stykka kitchens designed specifically for Fælledby residents. The project serves as both a web experience and print-ready brochure showcasing Stykka's circular kitchen philosophy.

## Architecture & Technologies
- **Framework**: Static HTML with Tailwind CSS
- **Icons**: Lucide icons loaded via CDN
- **Fonts**: Inter (Google Fonts) with async loading
- **Deployment**: Vercel static hosting
- **Performance**: Optimized with lazy loading, deferred scripts, resource hints

## Brand Identity
- **Primary Brand**: Stykka (Georgia Bold font for logo)
- **Secondary Brand**: Fælledby 
- **Colors**:
  - Fælledby Orange: `#ab6627` (accent color)
  - Fælledby Green: `#005B3B` (buttons, footer)
  - Warm Background: `#FBF9F7` (section backgrounds)

## File Structure
```
/
├── index.html              # Main brochure page
├── vedligeholdelse.html     # Maintenance guide with interactive elements
├── vercel.json             # Deployment configuration
├── README.md               # Project documentation
├── CLAUDE.md               # This file - AI instructions
└── images/                 # All image assets
```

## Key Features & Components

### Main Page (index.html)
1. **Hero Section**: Kitchen interior with animated scroll prompt
2. **Philosophy Section**: Circular design principles
3. **Responsibility**: Three-pillar sustainability approach
4. **Color Variants**: Interactive blended banner system
5. **Take-Back Program**: Circular economy visualization
6. **Digital Platform**: QR code and platform overview
7. **Service Links**: Navigation to maintenance, upgrades, parts
8. **Partnership Video**: Embedded YouTube content

### Maintenance Page (vedligeholdelse.html)
1. **Materials Showcase**: Hero image of material cube
2. **Interactive Care Guide**: 5 material categories with detailed instructions
   - Krydsfiner (Plywood - UV-lacquered)
   - Linoleum fronts
   - Laminat bordplader (countertops)
   - Stål (Steel - sink & hardware)
   - Mekanik (Mechanical adjustments)
3. **Professional Tips**: Long-term care guidance
4. **Support Contact**: Direct access to experts

## Content Guidelines
- **Language**: Danish throughout
- **Tone**: Professional, warm, sustainable focus
- **Target Audience**: Fælledby residents who received Stykka kitchens
- **Key Messages**: Circularity, quality, longevity, local partnership

## Performance Optimizations
- Lazy loading on all non-critical images
- Deferred loading of Tailwind CSS and Lucide icons
- Async font loading with fallbacks
- Resource hints (preconnect, dns-prefetch, preload)
- Optimized meta tags for SEO

## Interactive Elements
- **Material Selection**: JavaScript-powered buttons on maintenance page
- **Blended Banners**: CSS animations for color variant showcase
- **Smooth Scrolling**: CSS scroll-behavior for navigation
- **Responsive Design**: Mobile-first approach with breakpoints

## External Integrations
- **Upgrade Shop**: https://www.stykka.com/upgrades/fbc4
- **Parts Ordering**: https://www.stykka.com/parts
- **YouTube**: Partnership video embedding
- **QR Codes**: Digital platform access

## Development Workflow
1. Use local server (port 4000 suggested) for development
2. Test responsive design across devices
3. Validate print CSS for brochure functionality
4. Run performance audits before deployment
5. Test all interactive elements

## Deployment
- **Platform**: Vercel
- **Configuration**: Static site hosting via vercel.json
- **Repository**: https://github.com/jarlvindnaes/www_fbc4.git
- **Branch**: main (auto-deploy on push)

## Maintenance & Updates
- **Images**: Store in `/images/` directory, use descriptive names
- **Content Updates**: Maintain Danish language consistency
- **Performance**: Monitor loading times, optimize as needed
- **Interactive Elements**: Test material selection buttons after changes

## Design Principles
- **Left-aligned text** for readability
- **Clean, minimal layout** with generous whitespace
- **Consistent typography** using Inter font family
- **Accessibility** considerations for all interactive elements
- **Print optimization** for brochure use case

## Support & Contact
- **Technical Support**: support@stykka.com
- **Company**: Stykka ApS, Refshalevej 163A, 1432 København K
- **Phone**: +45 12 34 56 78

---
*This project represents Stykka's commitment to circular design and the partnership with Fælledby residents.*