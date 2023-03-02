---
title: Getting Started
description: Get started with your new project on Neorepo
---

# Environment

In this step, we'll set up your environment.

## Clone the repository

```bash
git clone https://github.com/neorepohq/neorepo.git
```

## Install dependencies

```bash
yarn
```

## Start the development server

```bash
yarn dev
```

## Push to GitHub

Create a new repository on GitHub and push your project to it.

```bash
git add .
git commit -m "Initial commit"
git push
```

## Deploy to Vercel

Neorepo is designed to be deployed to Vercel.

First, create a new project on Vercel. Then, link your GitHub repository to Vercel. Finally, deploy your project.

To deploy your project, use the Vercel CLI:

To install the Vercel CLI, run the following command:

```bash
npm i -g vercel
```

Use the following command to login to Vercel:

```bash
vercel login
```

Link your project to Vercel:

```bash
vercel link
```
