# OpenCode for Everyone - Documentation Website

This is the Nextra-based documentation website for the OpenCode for Everyone Course - an adaptation of Carl Vellotti's Claude Code course for OpenCode users.

## About This Adaptation

This repository is a fork of [carlvellotti/claude-code-everyone-course](https://github.com/carlvellotti/claude-code-everyone-course), adapted for OpenCode users. The course content has been modified to reference OpenCode instead of Claude Code, while maintaining the same learning structure and interactive approach.

## Development

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Open http://localhost:3000
```

## Building

```bash
# Build static site
npm run build

# The build output will be in the `out/` directory
# Pagefind will automatically index the content after build
```

## Deployment to Vercel

### Option 1: Connect via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click "Add New Project"
3. Import the GitHub repository: `yossik-vit/claude-code-everyone-course`
4. Set the Root Directory to `website`
5. Framework Preset: Next.js
6. Build Command: `npm run build`
7. Output Directory: `out`
8. Deploy!

### Option 2: Deploy via Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy from the website directory
cd website
vercel

# For production
vercel --prod
```

## Project Structure

```
website/
├── pages/               # All content pages (MDX)
│   ├── company-context/ # TaskFlow company info
│   ├── getting-started/ # Modules 0.0-0.2
│   ├── fundamentals/    # Modules 1.1-1.7
│   ├── advanced/        # Modules 2.1-2.3
│   ├── _app.jsx         # Next.js app wrapper
│   ├── _meta.ts         # Navigation config
│   ├── index.mdx        # Homepage
│   └── search.mdx       # Search page with Pagefind
├── public/
│   └── images/          # Course images
├── next.config.mjs      # Next.js configuration
├── theme.config.tsx     # Nextra theme configuration
└── package.json         # Dependencies
```

## Content Updates

Content is automatically converted from the main course `lesson-modules/` directory. To update:

1. Edit the OPENCODE.md files in `/lesson-modules/` (adapted from CLAUDE.md)
2. Run the conversion script: `./convert-content.sh`
3. Build and deploy

## Tech Stack

- **Next.js 14** - Static site generation
- **Nextra 3** - Documentation theme
- **Pagefind** - Client-side search
- **MDX** - Markdown with JSX components

## Links

- **Live Site:** TBD (will be deployed to Vercel)
- **Original Course Repository:** https://github.com/carlvellotti/claude-code-pm-course
- **OpenCode Adaptation Repository:** https://github.com/yossik-vit/claude-code-everyone-course
- **Nextra Docs:** https://nextra.site
- **Pagefind Docs:** https://pagefind.app

## Credits

- Original course by [Carl Vellotti](https://www.linkedin.com/in/carlvellotti/)
- OpenCode adaptation by [Yossik Vit](https://github.com/yossik-vit)
