# Vette — Prototype Gallery

A single static page (`index.html`) — no build step, no dependencies.

## Deploy to Vercel

**Option A — CLI (fastest)**
```bash
npm i -g vercel   # if you don't have it
cd this-folder
vercel            # first deploy, follow the prompts
vercel --prod     # promote to production
```

**Option B — GitHub import**
1. Push this folder to a GitHub repo.
2. In Vercel: **Add New → Project → Import** the repo.
3. Framework preset: **Other**. Leave build command empty, output directory empty (or `.`).
4. Deploy.

**Option C — Drag and drop**
Go to vercel.com/new, drag this folder onto the page. Done.

No environment variables, no build command, no output directory settings needed — it's plain HTML/CSS/JS.
