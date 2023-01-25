# DFM Senior Assesment

This repository contains an assessment for the Department of Family Medicine's Senioe Software Developer position, written in January 2023.

This project consists of two parts:
- A [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).
- A .Net core project coming with the default minimal weatherforecast API.
## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Description

This repository contains an Next app that uses Tailwind CSS and Markdown to host blogs.

Blogs have 7 different properties: 
- A title
- A date
- An excerpt
- A cover image
- An author
- An author image

## Task

Your task for this assessment will be:

- Dockerize the application (Client & backend) and deploy it
- Adding a post action to add a new summary (weather status); should be persisted in-memory no need for setting DB server
- Fetching the weatherforecast and redering the result in About page
- Posting a new weatherforecast summary from with the About page (simple form)
- The containers deployed should not exceed 100 mb of memory usage when deployed (bonus: the container has less than 50 mb when deployed).
- You will have to deploy the images on a virtual server hosted on the cloud (for example, an EC2 instance on AWS or GCE on GCP).

Once you have written your implementation, create another repository and send the link to [aelachka@uottawa.ca](mailto:aelachka@uottawa.ca). This should be finished before your interview. Your submission will be evaluated based on code organization, efficiency, documentation, and style.
