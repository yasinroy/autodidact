# Autodidactism

Teach yourself anything. Autodidactism is a free, interactive map of 939 topics, each with a guide of the best links for learning it.

## What's inside

- **An interactive map of every topic.** Hover a topic to light up its connections, drag topics around, scroll or pinch to zoom, and type in "I want to learn" to filter the map.
- **130,032 curated links** across 939 topics, from programming and math to fashion design, emotional intelligence and engineering.
- **Search across everything** with ⌘K / Ctrl K, link-type filters (videos, courses, papers, code…), and related topics on each page.
- **Track your learning.** Mark topics and links as To Learn, Learning or Learned, keep notes and add your own links. This is saved in your browser only.
- Light and dark themes, and layouts for phones as well as desktop.

The whole site is one file, `index.html`. It has no build step and no server code, and it doesn't call any APIs. Fonts load from Google Fonts.

## Put it on GitHub Pages

1. Create a new repository on GitHub (for example `autodidactism`).
2. Click **Add file → Upload files**, drag in `index.html` and `README.md`, then click **Commit changes**.
3. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, and click **Save**.
4. After a minute or two, your site is live at `https://<your-username>.github.io/<repository-name>/`.

## Put it on Vercel

1. Make sure `index.html` sits at the top level of the repository, not inside a folder. If you open the repository on GitHub, you should see `index.html` in the file list right away.
2. On [vercel.com](https://vercel.com), click **Add New → Project** and import the repository.
3. Set **Framework Preset** to **Other**. Leave **Build Command** and **Output Directory** empty, and leave **Root Directory** as `./`.
4. Click **Deploy**.

If you get a 404 "page not found" error, `index.html` is almost always inside a folder. Either move it to the top level of the repository, or open **Project Settings → Build and Deployment**, set **Root Directory** to that folder, and redeploy.

To view it without GitHub, double-click `index.html` to open it in your browser.
