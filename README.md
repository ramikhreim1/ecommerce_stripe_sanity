This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

Successfully deployed to the following URLs:

https://ecommerce-stripe-sanity-alpha.vercel.app/

https://ecommerce-stripe-sanity-git-main-ramikhreim1.vercel.app

https://ecommerce-stripe-sanity-ramikhreim1.vercel.app
building many advanced React & JavaScript topics, as well as i used Stripe for card transactions, and On top of that i used Sanity for the backend CM.  
   

## Getting Started
First, setup the development server:
npx create-next-app
second, run the development server:

```bash
npm run dev
# or
yarn dev
```
T install all packeges in the package.json run:
npm install --legacy-peer-deps

## Setup Stripe (payments gatway) and Sanity backend:

edit .env file on the root and replace the Sanity and Stripe token with your new generated token from sanity.io/stripe.com
NEXT_PUBLIC_SANITY_TOKEN = 
EXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=


Install Sanity Studio
Next, you’ll set up Sanity Studio on your computer. You’ll need node.js for this to work.

Paste this into your command line, and follow the instructions on screen.
npm install -g @sanity/cli && sanity init --template get-started --project uxaowlco --dataset production --provider google


Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
![image](https://user-images.githubusercontent.com/99683327/174653507-22a109c9-4512-4dfc-a4f6-1475305fed08.png)

## Deploy Sanity Studio
sanity deploy 


