# AI-Powered Study Hacks Blog

A modern, beautifully designed Next.js blog post about using AI for exam preparation.

## Features

- 🎨 Modern, theme-fitting design with gradient headers
- 📱 Fully responsive layout
- 🎯 Well-structured content with step-by-step guides
- 🖼️ Placeholder image sections ready for your screenshots
- ⚡ Built with Next.js 14 (App Router)

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser to see the blog.

## Project Structure

```
Blog_Technical_Writing/
├── app/
│   ├── layout.tsx      # Root layout with metadata
│   ├── page.tsx        # Main blog post page
│   └── globals.css     # Global styles
├── package.json
├── next.config.js
└── tsconfig.json
```

## Adding Your Images

Replace the placeholder image sections in `app/page.tsx` with your actual screenshots. The placeholder is located in the "Step-by-Step Guide" section and is clearly marked.

## Customization

- Colors: Edit CSS variables in `app/globals.css` (--primary-color, --secondary-color, etc.)
- Content: Modify `app/page.tsx` to update the blog content
- Styling: Adjust styles in `app/globals.css`

## Build for Production

```bash
npm run build
npm start
```

## License

This project is open source and available for personal use.

