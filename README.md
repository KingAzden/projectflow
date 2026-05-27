# ProjectFlow

A modern, high-performance project management dashboard built with the Kinetic Noir design system.

## Features

- **Pipeline Management** - Visualize and manage project workflows
- **Team Insights** - Real-time performance metrics and analytics
- **Task Distribution** - Track work across teams and projects
- **Responsive Design** - Optimized for desktop, tablet, and mobile
- **Dark Theme** - Professional dark mode with high-contrast accents

## Design System

Built on **Kinetic Noir** - a sophisticated design system combining:
- Deep carbon navy backgrounds (#0C1320)
- Vibrant kinetic red accents (#FF5352)
- Inter typography
- 8px base unit grid system
- Accessibility-first approach

## Quick Start

### Local Development
```bash
npm install
npm run dev
```

Visit `http://localhost:3000`

## Project Structure

```
├── index.html
├── kinetic_noir/           # Design system documentation
│   └── DESIGN.md
├── screens/                # Component screens
│   ├── project_pipeline_*.html
│   ├── team_insights_*.html
│   ├── project_settings/
│   └── ...
└── styles/                 # Global styles
```

## Deployment

### GitHub Pages
```bash
git push origin main
# Enable GitHub Pages in repository settings
```

### Vercel
```bash
npm install -g vercel
vercel
```

### Netlify
```bash
npm install -g netlify-cli
netlify deploy --prod --dir .
```

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## License

MIT © ProjectFlow Inc.
