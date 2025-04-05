This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

# Crypto Weather Nexus 🌦️💰

## 📦 Setup Instructions
1. Clone the repository
2. Run `npm install`
3. Start with `npm run dev`

## 🚀 Live Site
[https://crypto-weather-nexus.vercel.app](https://crypto-weather-nexus.vercel.app)

## 🧠 Design Decisions
- Next.js 13+ with App Router
- TailwindCSS for styling
- CoinGecko API for crypto prices
- OpenWeather API for weather
- GNews API for news
- Recharts for analytics graphs
- SSE for real-time notifications

## 🧩 Challenges & Resolutions
- **SSE setup in Next.js** was tricky → Solved with custom `/api/notifications`
- **CoinGecko rate limits** → Added delay + fallback handling
- **Linting errors** → Installed specific TypeScript version (4.9.5)

## 📄 Hint Report
- 0 errors, 1 warning, 13 hints
- Stored in: `hint-report/file--D--Projects-CryptoWeather.html`


You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
