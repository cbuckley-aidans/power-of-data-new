# CLAUDE.md - Development Guidelines

## Content Style Guidelines

### Language Standards
- **Use Australian English** for all front-facing content (user interface text, instructions, descriptions)
- This includes spellings like: "colour" (not "color"), "centre" (not "center"), "analyse" (not "analyze"), "realise" (not "realize")
- HTML attributes, CSS properties, and JavaScript code should remain in US English as per web standards
- Comments in code can use Australian English where appropriate

### Design Consistency
- Always use the original colour scheme from the power-of-data-main project
- Primary accent colour: `#002654` (dark blue)
- Maintain consistency with the established visual design patterns
- Follow the chunk-and-chew educational structure when appropriate

### Educational Structure
- Chunk = Teacher-led content sections
- Chew = Student practice/activity sections
- Use interactive data labs for hands-on learning
- Implement buckles reward system for gamification
- Include progress tracking and achievement feedback

## Technical Standards
- Use the existing CSS framework from `/CSS/styles.css`
- Maintain responsive design principles
- Ensure accessibility with proper semantic HTML
- Include interactive JavaScript components for educational engagement

## Design System Analysis (Based on variables.html)

### Key Design Elements
- **Card-based Layout**: Content organized in cards with prominent borders (`2px solid var(--outline-color)`)
- **Element Headers**: Numbered sections with colored backgrounds and negative margins for visual impact
- **Bold Drop Shadows**: Uses `var(--shadow-sm)` and `var(--shadow-md)` for strong visual depth
- **Icon Integration**: FontAwesome icons used extensively throughout for visual hierarchy
- **Color-coded Badges**: Chunk badges (blue), chew badges (green), timer badges for clear section identification
- **Interactive Cards**: Nested card structures with element numbering (1, 2, 3...)
- **Grid Layouts**: Uses `elements-grid` and `two-column-grid` for organized content presentation

### Typography System
- **Large Headers**: H1 at 2.7em with full-width underlines in accent color
- **Consistent Spacing**: Margin-bottom patterns of 30px, 20px, 15px for hierarchy
- **Icon Spacing**: Standard 15px margin-left for header icons, 12px margin-right for list icons
- **Letter Spacing**: Negative letter-spacing (-0.02em) for modern, tight typography

### Visual Hierarchy
- **Section Types**: Light sections (white bg), dark sections (secondary bg) for alternating rhythm
- **Badge System**: Colored badges for TEACHER CHUNK, STUDENT ACTIVITY, etc.
- **Element Numbering**: Circular numbered elements (1, 2, 3) for step-by-step progression
- **Color Coding**: Consistent use of accent color (#002654) for interactive elements

### Interactive Elements
- **Hover Effects**: Transform translateY(-0.15em) for buttons and interactive cards
- **Transition System**: 0.15s transitions for smooth interactions
- **Shadow Depth**: Multi-level shadow system for visual affordance
- **Border Radius**: Consistent 0.6em border radius for friendly, modern appearance

### Content Structure
- **Sidebar Navigation**: Fixed 160px sidebar with tab-based navigation
- **Main Content**: Responsive main area with consistent padding (40px 60px)
- **Nested Layouts**: Cards within sections, headers within cards for clear organization
- **Icon Grids**: Structured icon + text combinations for feature explanations

## Project-Specific Notes
- This is an educational web platform focused on data skills
- Target audience: Students learning Excel and data analysis
- Emphasise practical, hands-on learning through interactive exercises
- Maintain professional appearance suitable for educational settings
- Apply variables.html design system consistently across all pages