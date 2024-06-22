This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## 0. Project Setup

1. run `npx create-next-app@latest`
2. create a `README.md` file

## 1. Adding First Pages

1. delete the following folder & files
   - `pages\api` folder
   - `styles\Home.module.css` file
   - `pages\index.js` file
   - `pages\_document.js` file
2. create 2 new files
   - `pages\index.js`, which will be your root page, so for `<your-domain>/`
   - `pages\news.js`, for `<your-domain>/news`
3. in those files, create React function components
   - in `pages\index.js`, create a `HomePage` function component
   - in `pages\news.js`, create a `NewsPage` function component
4. in your terminal, run `npm run dev` to start the development server

## 2. Adding Nested Paths & Pages (Nested Routes)

There is an alternative to adding pages like `pages\news.js`, which is mandatory if you want to have a nested path

1. under the `pages` folder, add a `news` folder & in there add an `index.js` file, which would be the root page of the `news` path
2. next to `pages\news\index.js`, add a file called for example `something-important.js`, which would be a nested path
3. or alternitavely, created a `something-important` folder & in there another `index.js` file
