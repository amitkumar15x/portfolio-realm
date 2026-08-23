# Portfolio Realm

Amit Kumar's personal developer portfolio — a Game of Thrones–themed single-page site showcasing projects, skills, and contact details. Built with plain HTML, CSS, and JavaScript, no build step required.

## Features

- Fully responsive layout that adapts to desktop, tablet, and mobile
- Cinematic hero section with scroll-driven animations
- Dedicated sections highlighting featured projects and technical skills
- Live GitHub stats, top languages, and trophies
- Contact section with direct links to Email, GitHub, LinkedIn, and Twitter/X

## Project Structure

```
portfolio-realm/
├── index_3.html      # Main entry point — the entire site
└── README.md         # Project documentation
```

`index_3.html` is self-contained: all styles and scripts are included directly in the file, so no additional assets or dependencies are required to run it.

## Running Locally

**Option 1 — Clone and open directly**

```bash
git clone https://github.com/amitkumar15x/portfolio-realm.git
cd portfolio-realm
```

Then open `index_3.html` in your browser (double-click the file, or drag it into a browser window).

**Option 2 — VS Code with Live Server**

1. Open the project folder in VS Code
2. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension
3. Right-click `index_3.html` and select **Open with Live Server**

## Deployment

### GitHub Pages

1. Push the repository to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select the `main` branch and `/ (root)` folder
4. Save — your site will be live at:

```
https://amitkumar15x.github.io/portfolio-realm/
```

> Note: GitHub Pages serves `index.html` by default. Either rename `index_3.html` to `index.html`, or add a redirect `index.html` that points to `index_3.html`.

### Vercel

1. Add a `vercel.json` file to the project root:

```json
{
  "cleanUrls": true,
  "rewrites": [
    { "source": "/", "destination": "/index_3.html" }
  ]
}
```

2. Install the Vercel CLI and deploy:

```bash
npm install -g vercel
vercel login
vercel --prod
```

3. Follow the CLI prompts to link the project — Vercel will deploy the site and provide a live URL.

## Contact

- **Email:** [amitkumar155x@gmail.com](mailto:amitkumar155x@gmail.com)
- **GitHub:** [github.com/amitkumar15x](https://github.com/amitkumar15x)
- **LinkedIn:** [linkedin.com/in/amitkumar15x](https://linkedin.com/in/amitkumar15x)
- **Twitter/X:** [x.com/amitchauhan15x](https://x.com/amitchauhan15x)
---
⭐ Always Learning • Always Building • Always Improving ⭐
