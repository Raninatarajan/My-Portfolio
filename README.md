# Rani Natarajan's Portfolio

A modern, responsive portfolio website built with Next.js and Tailwind CSS.

## Features

- Responsive design that works on all devices
- Modern UI with smooth animations
- Sections for:
  - Introduction
  - Education
  - Skills
  - Projects
  - Contact
- Contact form for easy communication
- Smooth scrolling navigation
- Custom styling with Tailwind CSS

## Tech Stack

- Next.js 14
- React
- TypeScript
- Tailwind CSS
- Framer Motion (for animations)

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## Project Structure

```
portfolio/
├── app/
│   ├── components/
│   │   ├── Navigation.tsx
│   │   ├── Education.tsx
│   │   ├── Skills.tsx
│   │   ├── Projects.tsx
│   │   └── Contact.tsx
│   ├── page.tsx
│   ├── layout.tsx
│   └── globals.css
├── public/
│   └── images/
├── package.json
└── README.md
```

## Development

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Deployment

The site can be deployed to any platform that supports Next.js applications, such as:
- Vercel (recommended)
- Netlify
- AWS Amplify

## License

MIT License 