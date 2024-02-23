This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started
# ![logo-text](https://github.com/sohomofficial/imaginify/assets/93909798/0fbe7ca7-676a-46b2-a25a-0aaa7cafff4d)
A Software-as-a-Service app with AI features and payments & credits system built using Next.js 14, Clerk, MongoDB, Cloudinary AI, and Stripe.

First, run the development server:
## Features

- **Authentication and Authorization:** Secure user access with registration, login, and route protection.

- **Community Image Showcase:** Explore user transformations with easy navigation using pagination

- **Advanced Image Search:** Find images by content or objects present inside the image quickly and accurately

- **Image Restoration:** Revive old or damaged images effortlessly

- **Image Recoloring:** Customize images by replacing objects with desired colors easily

- **Image Generative Fill:** Fill in missing areas of images seamlessly

- **Object Removal:** Clean up images by removing unwanted objects with precision

- **Background Removal:** Extract objects from backgrounds with ease

- **Download Transformed Images:** Save and share AI-transformed images conveniently

- **Transformed Image Details:** View details of transformations for each image

- **Transformation Management:** Control over deletion and updates of transformations

- **Credits System:** Earn or purchase credits for image transformations

- **Profile Page:** Access transformed images and credit information personally

- **Credits Purchase:** Securely buy credits via Stripe for uninterrupted use

- **Responsive UI/UX:** A seamless experience across devices with a user-friendly interface

and many more, including code architecture and reusability


## Environment Variables

To run this project, you will need to add the following environment variables to your .env.local file.

```sh
#NEXT
NEXT_PUBLIC_SERVER_URL=

#MONGODB
MONGODB_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#CLOUDINARY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=

```



## Run Locally

Clone the project

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
  git clone https://github.com/aryan-who-codes/imaginify.git
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
Go to the project directory

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.
```bash
  cd YOUR_DIRECTORY_NAME
```

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.
Install dependencies

## Learn More
```bash
  npm i
```

Start the server

```bash
  npm run dev
```

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
## Credits

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
 - [Adrian Hajdin - JS Mastery](https://github.com/adrianhajdin)
 - [Build and Deploy a Full Stack AI SaaS Platform with Next js 14, TypeScript, Stripe](https://youtu.be/Ahwoks_dawU?si=ykCanyhrGzChgT5Y)

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
