# Blog Starter

## Custom Features

### 1. Site Branding
- Customized site title: "My Blog"
- Personalized blog page title: "Blog Posts"
- Custom site description for better SEO

### 2. Content Structure
- Organized blog posts under `/blog` route
- Implemented dynamic routing for blog posts using `[...slug].astro`
- About page with customizable content and hero image support

### 3. Layout System
- Enhanced blog post layout with:
  - Hero image support
  - Publication date display
  - Title and description metadata
  - Responsive design

### 4. Component Organization
- Modular component structure in `/components` directory
- Reusable layouts in `/layouts` directory
- Global styles in `/styles` directory

### 5. Content Management
- Structured content configuration via `content.config.ts`
- Centralized constants in `consts.ts` for easy site-wide updates
- Content collections in `/content` directory

## Getting Started

To modify the theme further:

1. Update site metadata in `src/consts.ts`
2. Modify layouts in `src/layouts` directory
3. Add or update components in `src/components`
4. Create new pages in `src/pages`
5. Add blog posts to the content collection

## File Structure

```
src/
├── components/     # Reusable UI components
├── content/        # Blog posts and content collections
├── layouts/        # Page layouts and templates
├── pages/         # Route pages
├── styles/        # Global styles
├── consts.ts      # Global constants
└── content.config.ts  # Content collection configuration
```

Last updated: January 2, 2025

## Credit

This theme is based off of the lovely [Bear Blog](https://github.com/HermanMartinus/bearblog/).
