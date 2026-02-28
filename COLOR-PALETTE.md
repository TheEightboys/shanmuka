# Color Palette & Animation Guide

## Color Scheme

Your website now uses a warm, elegant color palette:

### Primary Colors
- **#ecf8f8** - Soft mint (Background primary)
- **#eee4e1** - Light cream (Background secondary)
- **#e7d8c9** - Warm sand (Warm cream, borders)
- **#e6beae** - Peachy tan (Accent light)
- **#b2967d** - Rich tan (Main accent)

### Derived Colors
- **Text Primary**: `#3d3d3d` (dark gray)
- **Text Secondary**: `#6b5d54` (warm brown)
- **Text Muted**: `#9a8a7d` (light brown)
- **Accent Hover**: `#9a7f64` (darker tan)

## Animations Implemented

### 1. **Navigation**
- Smooth background blur on scroll
- Link hover with lift effect (`translateY(-2px)`)
- Active link indicator with slide-in animation
- Mobile menu slide from right

### 2. **Buttons**
- Ripple effect on click (`.btn::before`)
- Lift and scale on hover (`translateY(-3px) scale(1.02)`)
- Enhanced shadow on hover

### 3. **Hero Sections**
- Floating title animation (moves up/down)
- Gradient overlay pulse effect
- Smooth background image transitions

### 4. **Resume Page**
- Section titles with sliding underline
- Entry cards slide in from left on hover
- Staggered bullet point animations
- Skill tags pop in sequentially
- Publication cards expand on hover

### 5. **Contact Page**
- Form cards lift on hover with shadow enhancement
- Input fields rise and glow on focus
- Icon cards with rotating icon on hover
- Gradient sweep effect on cards (shimmer)
- Success/error messages slide down

### 6. **General**
- Page load fade-in
- Scroll-triggered fade-up animations
- Smooth scrolling
- Custom scrollbar with accent colors
- Link underline slide animations

## Animation Timing
- **Transitions**: 0.4s cubic-bezier (smooth)
- **Bounce effects**: 0.6s cubic-bezier (1.56 for overshoot)
- **Stagger delays**: 0.05-0.1s increments

## Background Effects
- Subtle radial gradients on body
- Gradient footer with shimmer top border
- Card backgrounds with gradient on hover

## Interactive Elements Enhanced
✓ Navigation links
✓ Buttons (primary & outline)
✓ Form inputs & textareas
✓ Contact cards
✓ Resume entries
✓ Skill tags
✓ Publication references
✓ Footer links

All animations are optimized for performance using CSS transforms and GPU acceleration.
