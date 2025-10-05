# Social Tinder Swipe

A modern social media post swiper application with a Tinder-like interface for browsing and interacting with social media content.

![Social Tinder Swipe Preview](./public/social-tinder-swipe.png)

**Live Demo:** [https://social-tinder-swipe.bjornleonhenry.com](https://social-tinder-swipe.bjornleonhenry.com)

## Overview

Social Tinder Swipe brings the familiar swipe interface of dating apps to social media browsing. Users can swipe through posts, like or dislike them, and interact with content in an engaging, mobile-first interface. The application features a clean, modern design built with React and Next.js.

## Features

- **Swipe Interface**: Intuitive swipe gestures for navigating through posts
- **Interactive Cards**: Engage with social media content using familiar swipe actions
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Modern UI**: Clean interface built with Tailwind CSS and Radix UI components
- **TypeScript**: Full type safety for better development experience
- **Performance Optimized**: Built with Next.js for optimal loading and SEO

## Tech Stack

- **Framework**: Next.js 15
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI
- **Icons**: Lucide React
- **Build Tool**: Turbopack
- **Package Manager**: pnpm

## Getting Started

### Prerequisites

- Node.js 18+ 
- pnpm (recommended) or npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/bjornleonhenry/social-tinder-swipe.git
cd social-tinder-swipe
```

2. Install dependencies:
```bash
pnpm install
```

3. Start the development server:
```bash
pnpm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
pnpm run build
pnpm run start
```

## Project Structure

```
├── app/                 # Next.js app directory
├── components/          # React components
│   ├── ui/             # Reusable UI components
│   └── shitpost-swiper.tsx  # Main swiper component
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
├── public/             # Static assets
└── styles/             # Global styles
```

## Development

This project uses modern web development practices:

- **TypeScript** for type safety
- **Tailwind CSS** for utility-first styling
- **Radix UI** for accessible component primitives
- **ESLint** and **Prettier** for code quality
- **Next.js App Router** for routing and SSR

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

**Bjorn Leon Henry** (bjornleonhenry)

- Website: [bjornleonhenry.com](https://bjornleonhenry.com)
- GitHub: [@bjornleonhenry](https://github.com/bjornleonhenry)

---

Built with care for the modern web development community.