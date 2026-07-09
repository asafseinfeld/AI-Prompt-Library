# AI Prompt Library

A searchable library of AI prompt templates for common work tasks — email writing, meeting summaries, Excel help, strategy docs (SWOT, competitor analysis), presentations, HR, and customer support.

Employees can search or filter by category, click a prompt to see the full template, and copy it with one click to paste into ChatGPT, Claude, or any AI tool.

## Features
- Search by keyword across all prompts
- Filter by category (Email, Meetings, Excel, Strategy, Presentations, Analysis, HR/People, Customer)
- Click any prompt card to view the full template
- One-click "Copy Prompt" button

## 1. Run it locally (optional)

```bash
npm install
npm start
```

Open http://localhost:3000

## 2. Push it to GitHub

```bash
git init
git add .
git commit -m "First commit - AI prompt library"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

## 3. Deploy on Railway

1. Go to https://railway.app and sign in with GitHub.
2. **New Project** → **Deploy from GitHub repo** → select this repo.
3. Railway auto-detects Node, installs dependencies, runs `npm start`.
4. Under Settings, click **Generate Domain** for a public URL.

## 4. Adding your own prompts

All prompts live in `public/index.html`, inside the `var prompts = [...]` array near the top of the `<script>` section. Each entry looks like:

```js
{
  category: "Email",
  title: "Professional Email",
  template: "Write a professional email to [recipient/role] about [topic]..."
}
```

Add a new object to the array (matching that format) to add a new prompt. New categories are picked up automatically — no other code changes needed.
