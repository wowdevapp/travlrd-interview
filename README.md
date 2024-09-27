## Next.js App Router Course - Final

This is the final template for the Next.js App Router Course. It contains the final code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Interview Task Preparation

1. Fork the repository
2. Run `pnpm install`
3. Follow the steps outlined here: https://nextjs.org/learn/dashboard-app/setting-up-your-database#create-a-postgres-database
  - Initialize a new repository and publish it to Github (also make sure to set the repo to public)
  - Sign into your Vercel account and deploy your repository as a new project
  - Install the Vercel CLI: https://vercel.com/docs/cli
  - Run `vercel link` to link your project to the Vercel CLI
  - Create a new Postgres database on Vercel
  - Connect the database to your project via the dashboard (this will automatically add the postgres environment variables to the project)
  - Upload the remaining two environment variables to the Vercel project settings from the `.env.example` file
  - Run `vercel env pull .env.development.local` to make the latest environment variables available to your project locally
  - Run `vercel dev` to start the development server
4. Seed the database by opening `/seed` in your browser. This will create a user account that you can use to log in to the dashboard
5. Complete the interview task
6. Send us the link to your GitHub repo and the link to your deployed app (don't forget to set the repo to public)