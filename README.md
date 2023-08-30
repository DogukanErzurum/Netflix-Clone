# Building a Fullstack Netflix Clone with React, TailwindCSS and Prisma
![image](https://user-images.githubusercontent.com/23248726/220005380-ede4fb14-0b8d-4582-a063-3cc4beeccfb7.png)

In this project I made a FullStack Netflix clone using React TailwindCSS and Prisma

Project Features:
- Environment, Typescript, NextJS Setup
- Create Database with MongoDB and Prisma connection
- Authentication with NextAuth, Google and Github Login
- Full responsiveness on all pages
- Cookie-based authentication
- API controls have been created.
- Made detail-oriented effects and animations with TailwindCSS.
- React SWR data fetching
- Zustand state management

  ### Necessity

**Node version 14.x**

### Cloning the repository

```shell
https://github.com/DogukanErzurum/netflix-clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file

This is the section where the person hashes the registration status given by google github and my own system after registration. It is personalized!

```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_JWT_SECRET=
NEXTAUTH_SECRET=
```

### Start the app

npm run dev starts the application at localhost:3000.

```shell
npm run dev
```
