# Learning Hub - Design Specification

## 1. Overview

The Learning Hub is an interactive educational platform that presents legal concepts through an engaging, map-based interface. It follows our established design system while incorporating unique interactive elements for an optimal learning experience.

## 2. Visual Design

### Color Scheme
- **Primary**: `#153A1D` (Dark Green) - For primary actions and highlights
- **Secondary**: `#2E8B57` (Seagreen) - For secondary actions and accents
- **Background**: `#FFFFFF` (White) - Main background
- **Text Primary**: `#333333` (Dark Gray)
- **Text Secondary**: `#666666` (Medium Gray)
- **Success/Completion**: `#2E8B57` (Matching our secondary color)

### Typography
- **Headings**: Poppins (Bold)
- **Body Text**: Inter (Regular)
- **Code/Quotes**: Fira Code (Monospace)

## 3. Core Components

### 3.1 Learning Map (Homepage)

#### Visual Elements
- Interactive hexagonal grid background
- Each hexagon represents a legal topic
- Subtle animation on hover (slight elevation + color shift)
- Connection lines between related topics

#### States
- **Default**: Subtle fill with outline
- **Hover**: Slight elevation + primary color highlight
- **Completed**: Filled with primary color + checkmark icon
- **In Progress**: Partially filled with progress indicator
- **Locked**: Grayed out with lock icon

### 3.2 Topic Modal

#### Layout
- Slides up from bottom (mobile-first)
- Takes 90% viewport height on mobile, 80% on desktop
- Smooth transition with backdrop blur

#### Sections
1. **Header**
   - Topic title (H1)
   - Close button (X in top-right)
   - Progress indicator (e.g., "2/5 lessons completed")

2. **Overview**
   - Brief description (2-3 sentences)
   - Estimated time to complete
   - Difficulty level
   - Certificate availability

3. **Learning Objectives**
   - Bulleted list of key takeaways
   - Icons for visual scanning

4. **Pathway Preview**
   - Visual flow of lessons
   - Current position highlighted
   - Locked/unlocked states

5. **CTA Buttons**
   - Primary: "Start Learning" / "Continue"
   - Secondary: "Save for Later"

### 3.3 Lesson Interface

#### Layout
- Full-viewport height
- Fixed header with progress bar
- Main content area (scrollable)
- Fixed footer with navigation

#### Components
1. **Header**
   - Back button
   - Progress indicator
   - Menu/settings (optional)

2. **Content Area**
   - Lesson title
   - Interactive elements (tabs, toggles, etc.)
   - Media (images, videos, interactive diagrams)
   - Key points highlighted

3. **Navigation**
   - Previous/Next buttons
   - Table of Contents dropdown
   - Complete & Continue button

### 3.4 Interactive Elements

#### Hexagon Grid
- Responsive layout
- Smooth transitions between states
- Touch and click support
- Keyboard navigable

#### Progress Indicators
- Circular progress for individual lessons
- Linear progress for modules
- Visual completion states

#### Knowledge Checks
- Interactive quizzes
- Immediate feedback
- Option to review

## 4. User Flow

### 4.1 First-time User
1. Views learning map
2. Sees recommended starting point
3. Clicks on starting topic
4. Views topic overview
5. Begins first lesson

### 4.2 Returning User
1. Sees progress on learning map
2. Continues from last lesson
3. Or selects new topic from map

### 4.3 Lesson Completion
1. Completes final knowledge check
2. Sees completion animation
3. Receives option to:
   - Return to map
   - Continue to next topic
   - Share achievement

## 5. Responsive Behavior

### Mobile
- Single-column layout
- Larger tap targets
- Simplified navigation
- Optimized media loading

### Tablet
- Two-column layout where appropriate
- Larger typography
- Adjusted spacing

### Desktop
- Full learning map visible
- Multi-column content
- Hover states active

## 6. Accessibility

### Keyboard Navigation
- Tab through interactive elements
- Arrow keys for map navigation
- Enter/Space to select

### Screen Readers
- ARIA labels for all interactive elements
- Proper heading hierarchy
- Alt text for all images

### Color Contrast
- Minimum 4.5:1 for text
- 3:1 for interactive elements
- Color-independent indicators

## 7. Technical Implementation

### Frontend
- React for component structure
- Framer Motion for animations
- CSS Grid/Flexbox for layouts
- SVG for the learning map

### State Management
- Context API for global state
- Local storage for progress
- API integration for content

### Performance
- Lazy loading for media
- Code splitting
- Optimized animations

## 8. Future Enhancements

### Phase 1 (MVP)
- Basic learning map
- Core lesson content
- Progress tracking

### Phase 2
- Gamification elements
- Community features
- Advanced analytics

### Phase 3
- AI-powered recommendations
- Interactive case studies
- Certification system