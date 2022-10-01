# Medium 
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)


https://user-images.githubusercontent.com/34170205/193418714-8e8b3bcb-5675-4c4b-8b27-0e8d731bcbb2.mp4


              Medium is built to provide a rich reading experience with moderated comment functionality for a seamless experience
## Features
- Fetches CMS data into a Next.js app using efficient Modern Data Fetching techniques
- Uses Next.js (Incremental Static Regeneration) to speed up page loading and optimize page caching
- Features a responsive user interface that scales to a screen's size
- Robust code production using Typescript
- Node.js package manager to implement additional functionalities
## Tech
- [Sanity](https://www.sanity.io/) - Content Management System to manage structured data
- [Next.JS](https://nextjs.org/) - Production framework for React
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework packed with classes that can be composed in the markup
- [Typescript](https://www.typescriptlang.org/) - Strongly typed programming language that builds on Javascript
- [Node.js](https://nodejs.org/en/) - A Javascript runtime built on Chrome's V8 Javascript engine
## Installation

Install the dependencies in the **main** folder and **mediumSanity** 

```sh
npm install
cd mediumSanity && npm install
```
Spin up the **Development server** in the **main folder** and **Sanity dashboard** in **mediumSanity**
```sh
npm run dev
sanity start
```
For production environments

```sh
NEXT_PUBLIC_SANITY_PROJECT_ID = < Sanity project id >
NEXT_PUbLIC_SANITY_DATASET = < Sanity dataset name >
SANITY_API_TOKEN = < Sanity API key >
```

[![GitHub license](https://img.shields.io/github/license/Verkiya/Let-Us-C-Solutions.svg?style=for-the-badge)](https://github.com/hiverkiya/Medium/blob/main/LICENSE)
