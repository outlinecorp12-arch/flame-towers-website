# Flame Towers Website - Design & Brand Guide

## 🎨 Design System

### Color Psychology & Usage

#### Primary Colors

**Deep Navy Blue (#1a2238)**
- Represents: Luxury, professionalism, stability, trust
- Usage: Main backgrounds, headers, primary navigation
- Psychology: Creates a sense of premium quality and reliability
- Cultural Fit: Aligns with Azerbaijani aesthetic preferences

**Rich Gold (#bfa14b)**
- Represents: Wealth, exclusivity, success, opulence
- Usage: Accents, CTA buttons, highlights, section dividers
- Psychology: Creates aspirational, premium feel
- Cultural Fit: Reflects prosperity and luxury concepts in Azerbaijan

#### Secondary Colors

**Charcoal Gray (#2d2d2d)**
- Represents: Sophistication, modernity, neutrality
- Usage: Text, cards, secondary backgrounds, footer
- Pairing: Works well with gold and navy

**Cream White (#f8f7f3)**
- Represents: Elegance, cleanliness, premium feel
- Usage: Main backgrounds, content areas, breathing room
- Effect: Makes other colors pop, prevents visual fatigue

#### Accent Colors

**Turquoise (#14a6b8)**
- Represents: Innovation, energy, modernity
- Usage: Interactive elements, links, hover states
- Cultural Fit: Inspired by Azerbaijani carpet patterns

**Emerald Green (#009879)**
- Represents: Growth, nature, prosperity
- Usage: Special highlights, wellness section
- Cultural Fit: References Azerbaijan's natural beauty

## 📚 Visual Hierarchy

### Typography Scale

**Headings (Playfair Display - Serif)**
- H1 (Hero Title): 64px, Bold, Gold color
- H2 (Section Title): 48px, Bold, Navy color
- H3 (Card Title): 28px, Bold, Navy/Gold
- H4 (Subsection): 20px, Bold
- H5 (Label): 16px, Semibold

**Body Text (Montserrat - Sans-Serif)**
- Paragraph: 14px, Regular, 1.6 line-height
- Small Text: 12px, Regular
- Label: 12px, Semibold, Uppercase

### Weight Usage
- 300 (Light): Subtitles, secondary information
- 400 (Regular): Body copy, descriptions
- 600 (Semibold): Labels, emphasis
- 700 (Bold): Titles, headlines

## 🎯 Component Design

### Buttons

**Primary Button (Gold)**
```
Background: #bfa14b
Text: #1a2238
Padding: 15px 35px
Border-radius: 4px
Hover: Background #b87333, lift effect
```

**Secondary Button (Transparent)**
```
Background: Transparent
Border: 2px solid #bfa14b
Text: #ffffff
Hover: Fill with gold
```

**Outline Button (Navy)**
```
Background: Transparent
Border: 2px solid #1a2238
Text: #1a2238
Hover: Fill with navy
```

### Cards

**Property Card**
- Background: White
- Shadow: 0 10px 40px rgba(0,0,0,0.15)
- Hover: Lift 10px, enhanced shadow
- Image: 250px height, 3:2 aspect ratio
- Border-radius: 8px

**Amenity Card**
- Background: Transparent/Semi-transparent
- Border-left: 4px solid #14a6b8
- Padding: 30px
- Hover: Background lighten, translate effect

### Forms

**Input Fields**
- Background: rgba(248, 247, 243, 0.05)
- Border: 2px solid #2d2d2d
- Focus Border: #bfa14b
- Focus Background: rgba(191, 161, 75, 0.1)
- Text Color: #ffffff
- Padding: 15px

## 📐 Layout Guidelines

### Grid System
- **Container Max-width**: 1200px
- **Padding**: 20px on sides (mobile-friendly)
- **Column Gap**: 30-60px depending on section
- **Section Padding**: 100px vertical (60px on mobile)

### Spacing
- **Extra Small**: 8px
- **Small**: 12px
- **Medium**: 20px
- **Large**: 30px
- **Extra Large**: 60px

### Breakpoints
- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px

## 📸 Image Guidelines

### Hero Image
- **Dimensions**: 1920x1080 (16:9)
- **Content**: Flame Towers at night with LED displays
- **Overlay**: 50% dark semi-transparent
- **Optimization**: JPG, compressed to <500KB

### Property Images
- **Dimensions**: 400x300 (4:3) for cards
- **Content**: Luxury interiors, city views, amenities
- **Format**: JPG or WebP
- **Quality**: High resolution (72 DPI for web)

### Section Images
- **Consistency**: Maintain similar photography style
- **Lighting**: Professional, well-lit
- **Color Balance**: Warm tones, professionally edited
- **Subject**: Clean, clutter-free compositions

## ✨ Animation & Interactions

### Transitions
- **Default**: 0.3s ease
- **Hover Effects**: Smooth 0.3s transition
- **Button Hover**: Background change + 3px lift
- **Card Hover**: 10px translate + shadow enhance

### Micro-interactions
- Smooth scroll behavior
- Hover state color changes
- Form focus highlights
- Button press feedback
- Link underline effects

## 📱 Mobile Optimization

### Navigation
- Sticky header remains at top
- Navigation becomes vertical on mobile
- Hamburger menu recommended for phones
- Touch-friendly tap targets (48px min)

### Typography Scaling
- Hero Title: 64px → 42px → 32px
- Section Title: 48px → 36px → 28px
- Body Text: Remains readable at all sizes

### Layout Changes
- 3-column grid → 2-column → 1-column
- Side-by-side content → Stacked
- Horizontal cards → Vertical
- Flex direction: row → column

## 🌏 Cultural Considerations

### Azerbaijan-Inspired Elements

**Color References**
- Gold references wealth and prosperity
- Navy represents trust and stability
- Turquoise inspired by traditional carpet patterns
- Green references natural beauty and growth

**Symbolism**
- Flame motif connects to "Land of Fire" heritage
- Architecture represents modernity and progress
- Mixed-use concept reflects contemporary urban lifestyle

## ♿ Accessibility Standards

### Color Contrast
- Text on background: WCAG AA minimum (4.5:1)
- Large text: WCAG AA minimum (3:1)
- All buttons meet contrast requirements

### Semantic HTML
- Proper heading hierarchy (H1 → H6)
- Form labels properly associated
- Alt text for all images
- ARIA labels for interactive elements

### Keyboard Navigation
- All buttons focusable with Tab
- Visible focus indicators
- Skip navigation links
- Logical tab order

## 📈 Performance Targets

- **Page Load Time**: < 3 seconds
- **Lighthouse Score**: > 90
- **Mobile Performance**: > 85
- **SEO Score**: > 90
- **Accessibility Score**: > 95