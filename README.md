This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

## Upload.js Demo

A super simple demo of consumign the `upload-js-full` SDK can be found in `pages/index.tsx`.

There's a file input with an `onChange` handler, which when invoked will in turn call the Upload.io `upload` function with the selected file.
