# 💻 Canvas Style Guide for BSCS Online Program 

This repository contains a comprehensive collection of HTML/CSS components and templates designed specifically for use in Canvas LMS. All components follow Canvas technical requirements and accessibility standards.

## ✨ Purpose

This style guide serves as a resource for instructional designers, course developers, and faculty members who are creating or modifying content within Canvas LMS. The standardized components ensure:

- Consistent visual presentation across all courses
- Accessibility compliance (WCAG 2.1 standards)
- Responsive design for all devices
- Streamlined course development

## 🧑‍🔧 Technical Requirements

All code in this repository adheres to the following Canvas LMS constraints:

- **Inline CSS only** - No external stylesheets (Canvas strips these out)
- **No JavaScript** - Canvas removes JavaScript for security reasons
- **ARIA attributes** - Proper implementation for screen reader accessibility
- **Color contrast** - Meets WCAG 2.1 standards
- **Responsive design** - Works on all screen sizes

## 🚀 Getting Started

Each component in this repository includes:

1. Code snippets that can be copied directly into Canvas
2. Usage guidelines and context
3. Customization options
4. Accessibility considerations

To use these components:

1. Navigate to the specific component you need
2. Copy the code snippet needed
3. In Canvas, use the HTML editor (</> button) to paste the code
4. Customize the content and any placeholders (indicated by `[PLACEHOLDER]`)
5. Save your changes in Canvas

## 🧱 Component Categories

The style guide is organized into the following categories:

### Page Structure Components

- [Headers and Banners](components/headers-and-banners.md) - Page headers, section titles, and banner images
- [Content Containers](components/content-containers.md) - Styled containers for organizing page content

### Interactive Elements

- [Navigation Elements](components/navigation.md) - Buttons and links for course navigation
- [Buttons and Links](components/buttons-and-links.md) - Various button and link styles
- [Accordions](components/accordions.md) - Collapsible content sections

### Content Components

- [Cards](components/cards.md) - Information card components
- [Alerts and Notes](components/alerts-and-notes.md) - Warning, info, and tip boxes
- [Lists](components/lists.md) - Formatted list styles

### Guidelines and Patterns

- [Accessibility Guidelines](docs/accessibility.md) - Best practices for screen readers and accessibility
- [Responsive Design Patterns](docs/responsive-design.md) - Layout patterns for different screen sizes

## Examples

The `examples/` directory contains full-page examples showing how components can be combined to create complete Canvas pages:

- [Course Homepage](examples/course-home.md) - Example course homepage layout
- [Syllabus Page](examples/syllabus-page.md) - Example syllabus page layout
- [Module Page](examples/module-page.md) - Example module page layout
- [Resources Page](examples/resources-page.md) - Example resources page layout

## 🧏 Accessibility Focus

All components in this style guide prioritize accessibility with:

- Semantic HTML structure
- Proper ARIA attributes
- Descriptive link text with enhanced aria-labels
- Sufficient color contrast
- Screen reader compatibility
- Keyboard navigation support

## Acknowledgments

- CSUCI TLi team ❤️
- CSUCI Extended University for their support
- CSUCI Computer Science Department feedback
- Web Accessibility Initiative (WAI) for accessibility guidelines
