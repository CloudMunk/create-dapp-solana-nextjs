# Create Solana Dapp with Next.JS


https://user-images.githubusercontent.com/188568/137521416-7274837b-6969-4cfc-ba25-84a560f124df.mov


This project includes:
- Next.JS
- TypeScript
- `@solana` modules for wallet and blockchain calls
- Tailwind CSS (with [daisyUI](https://daisyui.com/))

## Getting Started

First, run the development server:

```bash
yarn
yarn run dev
```

If you deploy new Candy Machine you can update UI config here: `./src/config/candy-machine.config.js`.

## Style

[Tailwind CSS](https://tailwindcss.com/) or [daisyUI](https://daisyui.com/) are selected tools for rapid style development.

You can quickly change theme changing `data-theme` within `src/pages/_document.js:45`.
More info here: https://daisyui.com/docs/default-themes


## Deploy on Vercel

Before push run localy `npm run build` to make sure app can be build succesffully on vercel .

Vercel will automatically create environment and deployment for you if you have vercel account connected to your GitHub account. Go to the vercel.com to connect it.
Then any push to `main` branch will automatically rebuild and redploy app.
