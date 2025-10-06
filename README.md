# dSign - Tailwind Next.js Template

This is a [Next.js](https://nextjs.org/) project with Tailwind CSS, configured for GitHub Pages deployment.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## GitHub Pages Deployment

This project is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setup Instructions:

1. **Push to GitHub**: Push this repository to GitHub under the username `themewagon`
2. **Enable GitHub Pages**: 
   - Go to your repository settings
   - Navigate to "Pages" section
   - Under "Source", select "GitHub Actions"
3. **Deploy**: The site will automatically deploy when you push to the `main` or `master` branch

### Project URL:
The project will be available at: `https://themewagon.github.io/dSign`

### Build Configuration:
- **Static Export**: Configured for static site generation
- **Base Path**: Set to `/dSign` for GitHub Pages
- **Asset Optimization**: Images are unoptimized for static hosting
- **Trailing Slash**: Enabled for better GitHub Pages compatibility

## Local Development

For local development, the base path is not applied, so the site runs normally at `http://localhost:3000`.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
- [Next.js Static Export](https://nextjs.org/docs/advanced-features/static-html-export) - learn about static site generation.
