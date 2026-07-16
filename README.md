# Mark Anthony Loterina — Portfolio

A responsive one-page portfolio built with plain HTML, CSS, and JavaScript. It has no build dependencies and can be deployed directly to Vercel.

## Customize before publishing

Open `index.html` and replace these placeholders:

1. `your-email@example.com` with your email address.
2. The LinkedIn link `href="#"` with your LinkedIn profile URL.
3. The GitHub link `href="#"` with your GitHub profile URL.
4. Review project descriptions and employment dates.
5. Optional: replace the initials graphic with your own professional photo.

## Preview locally

You can double-click `index.html`, or run a local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy through GitHub and Vercel

1. Create a new GitHub repository, such as `mark-portfolio`.
2. Upload all files from this folder to the repository.
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the GitHub repository.
5. Keep the default settings. No framework preset or build command is required.
6. Select **Deploy**.

Every future push to the connected GitHub repository will trigger another Vercel deployment.

## Deploy with Vercel CLI

Install the CLI:

```bash
npm install -g vercel
```

From this folder, run:

```bash
vercel
```

Follow the prompts, then run `vercel --prod` when you are ready to publish to production.
