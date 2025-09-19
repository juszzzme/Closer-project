# Closer - Design System

## 1. Overall Aesthetic & Mood

### Core Identity
- **Vibe**: Professional, trustworthy, and modern
- **Theme**: Legal technology with a focus on clarity and accessibility
- **Layout**: Single-page, scrolling design with clear section hierarchy
- **Tone**: Professional yet approachable, with clear value propositions

## 2. Color Palette

### Primary Colors
- **Primary Green**: `#153A1D` (Dark Green)
  - Usage: Headers, CTAs, important elements
- **White**: `#FFFFFF`
  - Usage: Backgrounds, card backgrounds, text on dark

### Secondary Colors
- **Light Green/Teal**: `#2E8B57` (Seagreen)
  - Usage: Accents, hover states, highlights
- **Light Gray**: `#F5F5F5`
  - Usage: Secondary backgrounds, subtle UI elements

### Text Colors
- **Primary Text**: `#333333` (Dark Gray)
- **Secondary Text**: `#666666` (Medium Gray)
- **On Dark Text**: `#FFFFFF` (White)

## 3. Typography

### Font Family
- **Headings**: Poppins (Bold/Medium)
  - `font-family: 'Poppins', sans-serif;`
- **Body Text**: Inter (Regular/Medium)
  - `font-family: 'Inter', sans-serif;`

### Type Scale
- **H1**: 3.5rem (56px)
- **H2**: 2.5rem (40px)
- **H3**: 2rem (32px)
- **H4**: 1.5rem (24px)
- **Body**: 1rem (16px)
- **Small Text**: 0.875rem (14px)

## 4. UI Components

### Navigation Bar
- Fixed at top
- Semi-transparent white background with blur effect
- Logo on left, navigation items on right
- Active state indicator
- CTA button with primary green background

### Buttons
#### Primary Button
- Background: `#153A1D`
- Text: White
- Padding: 12px 24px
- Border-radius: 8px
- Hover: Slightly darker green

#### Secondary Button
- Background: Transparent
- Border: 1px solid `#153A1D`
- Text: `#153A1D`
- Hover: Light green background

### Cards
- White background
- Border-radius: 12px
- Subtle shadow: `0 4px 12px rgba(0,0,0,0.05)`
- Hover: Slight elevation with increased shadow
- Padding: 24px

### Form Elements
- Input fields with subtle borders
- Focus state with primary green accent
- Labels above inputs
- Error states in red

## 5. Layout & Grid

### Grid System
- 12-column grid
- Gutter: 24px
- Max-width: 1280px
- Side padding: 24px (mobile) to 64px (desktop)

### Spacing Scale
- Base unit: 8px
- XS: 4px
- S: 8px
- M: 16px
- L: 24px
- XL: 32px
- XXL: 48px
- XXXL: 64px

## 6. Visual Elements

### Icons
- Simple, line-style icons
- Consistent stroke width (2px)
- Primary green or dark gray

### Illustrations
- Clean, minimalist style
- Using primary color palette
- Supportive of content, not distracting

### Animations
- Subtle hover effects
- Smooth transitions (300ms)
- Micro-interactions for feedback

## 7. Component Library

### Hero Section
- Full-height with gradient background
- Clear value proposition
- Primary CTA button
- Subtle animation/mockup

### Feature Cards
- Icon
- Title
- Short description
- Hover effect

### Document Viewer
- Split-pane layout
- Left: Document with highlighted clauses
- Right: Analysis and summary
- Interactive elements

### Chat Interface
- Fixed bottom-right corner
- Expandable card
- Message bubbles
- Input field with send button

## 8. Responsive Behavior

### Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Mobile Navigation
- Hamburger menu
- Full-screen overlay
- Clear hierarchy

## 9. Accessibility

### Contrast Ratios
- Text: Minimum 4.5:1
- UI Components: 3:1

### Keyboard Navigation
- Visible focus states
- Logical tab order
- Skip to content

### ARIA Labels
- For interactive elements
- Form inputs
- Dynamic content