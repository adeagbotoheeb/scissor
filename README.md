## Scissor
Scissor is a platform for URL shortening that intends to upend the market by offering a quick and effective method of doing it. Numerous capabilities are available on the site, including, custom URLs, URL shortening, QR code creation, and simple analytics.
## Requirements And Implementation Guide:
URL Shortening: By pasting a long URL into the Scissor platform, a shorter URL will be generated automatically, allowing users to shorten URLs. In order to make it simple to share on social media or through other methods, the shortened URL is made to be as brief as possible.

Custom URLs: Scissor also allows users to customize their shortened URLs. Users can choose their own custom domain name and customize the URL to reflect their brand or content. This feature is particularly useful for individuals or small businesses who want to create branded links for their content.

QR Code Generation: Scissor allows users to generate QR codes for shortened URLs. Users can download the QR code image and use it in their promotional materials or on their website. This feature was implemented using a third-party QR code generator API, which was integrated into the Scissor platform.

Analytics: Scissor provides basic analytics that allows users to track their shortened URL's performance. Users can see how many clicks their shortened URL has received and where the clicks are coming from. This feature will be implemented using Firebase's built-in analytics feature.

## Best Practices:
This tool was built and deployed with a scalable codebase with proper code linting and formatting using Prettier and ESLint.

Used TypeScript with NextJS and React, with best SEO practice.

Form validation was done to ensure data integrity and user experience.

MongoDB was used to store user data and implement authentication as well as shortened URLs.

Users of Scissor are able to write content with markdown.

At least 2 unit tests and 3 component tests were added to the codebase.

## To Run the App Live

First, run the development server: then bash Copy code npm run dev

API routes can be accessed at http://localhost:3000/api/hello. This endpoint can be edited in pages/api/hello.ts.

The pages/api directory is mapped to /api/*. Files in this directory are treated as API routes instead of React pages.

You can start editing the page by modifying pages/index.tsx. The page auto-updates as you edit the file.
