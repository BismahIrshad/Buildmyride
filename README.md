# BuildMyRide: 3D Car Customization Studio

BuildMyRide is a web-based 3D car customization platform developed as a group Final Year Project (FYP). It allows users to personalize vehicles with interactive 3D models, explore different modifications, and receive AI-powered design suggestions.

## Features

* **3D Car Customization:** Interactive 3D vehicle visualization and customization.
* **Vehicle Modifications:** Change car colors, wheels, spoilers, bumpers, and other parts.
* **AI Design Advisor:** Get AI-generated suggestions for vehicle colors and styling.
* **Save Designs:** Save and revisit customized vehicle designs.
* **AR Preview:** Preview vehicle customizations using augmented reality.

## Tech Stack

* **Frontend:** Next.js, React, Material UI
* **3D Visualization:** Three.js, React Three Fiber, Drei
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** NextAuth.js, JWT
* **AI:** Google Gemini API
* **AR / Computer Vision:** ONNX Runtime Web, YOLOv8

## Project Structure

* `public/models/` — 3D vehicle models and assets
* `src/` — Frontend application and components
* `docs/` — Project documentation

## Getting Started

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Configure the required environment variables.
4. Run the development server using `npm run dev`.

## Project Context

Developed as a group Final Year Project for the BS Computer Science degree at the University of Central Punjab.

## License

This project was developed for academic purposes. Contact the project contributors for permission before reuse or redistribution.

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
