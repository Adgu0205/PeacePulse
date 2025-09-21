What technologies are used for this project?
This project is built with:
# PeacePulse

## Deploying to Vercel

You can deploy this project to Vercel in two ways:

1) Using the Vercel web UI
	 - Go to vercel.com, import your GitHub repository `Adgu0205/PeacePulse`.
	 - Vercel will detect this is a Vite app. If not, set:
		 - Build command: `npm run build`
		 - Output directory: `dist`
	 - Add any environment variables in the Vercel dashboard (client variables should start with `VITE_`).

2) Using the Vercel CLI
	 - Install the CLI: `npm i -g vercel` or `pnpm i -g vercel`.
	 - From the project root:
		 ```bash
		 vercel login
		 vercel --prod
		 ```

The included `vercel.json` provides a static-build configuration and a simple route that ensures SPA routing works.
# PeacePulse
