This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Docker Deployment

To deploy this application using Docker:

1. **Build the Docker image:**
   ```bash
   docker build -t nextjs-beginner .
   ```

2. **Run the Docker container:**
   ```bash
   docker run -p 3000:3000 nextjs-beginner
   ```

3. **Access the application:**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

### Docker Commands Explanation:
- `docker build -t nextjs-beginner .`: Builds the Docker image with the tag `nextjs-beginner` using the current directory (`.`) as the build context.
- `docker run -p 3000:3000 nextjs-beginner`: Runs the container, mapping port 3000 on your host to port 3000 in the container.

### Prerequisites:
- Docker must be installed on your system. Download from [docker.com](https://www.docker.com/get-started).

### Troubleshooting:
- If you encounter permission issues, you may need to run Docker commands with `sudo`.
- Ensure port 3000 is not already in use on your host machine.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
