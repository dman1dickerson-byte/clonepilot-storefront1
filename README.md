# ClonePilot Storefront

A modern, high-performance e-commerce storefront template built with cutting-edge web technologies. Perfect for entrepreneurs, developers, and businesses looking to launch a professional online store quickly.

## Features

- ⚡ **Next.js 16** - Latest React framework with App Router
- 🎨 **Tailwind CSS 4** - Utility-first CSS framework
- 📱 **Fully Responsive** - Mobile-first design
- 🌙 **Dark Mode Support** - Built-in theme switching
- ⚙️ **TypeScript** - Type-safe development
- 🚀 **Production Ready** - Optimized for performance
- 📊 **SEO Friendly** - Metadata and semantic HTML
- 🎯 **Modern UI/UX** - Clean, professional design

## Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| Next.js | 16.2.4 | Framework |
| React | 19.2.4 | UI Library |
| TypeScript | ^5 | Type Safety |
| Tailwind CSS | ^4 | Styling |
| ESLint | ^9 | Code Quality |

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/dman1dickerson-byte/clonepilot-storefront1.git
   cd clonepilot-storefront1
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint checks

## Project Structure

```
clonepilot-storefront1/
├── app/
│   ├── layout.tsx        # Root layout with metadata
│   ├── page.tsx          # Home page with footer
│   └── globals.css       # Global styles
├── public/               # Static assets
├── package.json          # Dependencies and scripts
├── tsconfig.json         # TypeScript configuration
├── tailwind.config.js    # Tailwind configuration
└── next.config.ts        # Next.js configuration
```

## Customization

### Update Site Metadata
Edit `app/layout.tsx`:
```typescript
export const metadata: Metadata = {
  title: "Your Store Name",
  description: "Your store description",
};
```

### Modify Styling
Global styles are in `app/globals.css`. Tailwind utilities are available throughout the project.

### Add Pages
Create new files in the `app/` directory following Next.js App Router conventions:
```
app/
├── page.tsx          # / route
├── products/
│   └── page.tsx      # /products route
└── about/
    └── page.tsx      # /about route
```

## Deployment

### Deploy on Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Vercel auto-detects Next.js and deploys automatically

### Deploy Anywhere

Since this is a standard Next.js app, you can deploy to any Node.js hosting:
- Netlify
- Railway
- Render
- DigitalOcean
- AWS
- Google Cloud
- Azure

## Performance

- ✨ **Optimized Images** - Next.js Image component
- 📦 **Code Splitting** - Automatic route-based splitting
- 🎯 **SEO** - Semantic HTML and metadata
- ⚡ **Fast Builds** - Optimized build pipeline
- 💨 **CSS** - Tailwind's PurgeCSS for minimal bundle

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

- 📖 [Next.js Documentation](https://nextjs.org/docs)
- 🎨 [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- 💬 [GitHub Issues](https://github.com/dman1dickerson-byte/clonepilot-storefront1/issues)

## Roadmap

- [ ] Product catalog page
- [ ] Shopping cart functionality
- [ ] User authentication
- [ ] Payment integration
- [ ] Order management
- [ ] Admin dashboard

## Author

Created by [dman1dickerson-byte](https://github.com/dman1dickerson-byte)

---

**Ready to build your dream storefront?** Get started today with ClonePilot Storefront! 🚀
