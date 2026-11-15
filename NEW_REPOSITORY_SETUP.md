# Mango Stay — New GitHub Repository Setup

This ZIP contains the complete static website, including the 13 villa pages and original photos. Extract it into an EMPTY local folder. Do not upload the ZIP itself as the website.

1. Create a new EMPTY GitHub repository (do not initialize with README, license, or .gitignore).
2. In VS Code, open the extracted folder containing index.html.
3. Run the commands below in that folder, replacing YOUR-NEW-REPO-URL with the HTTPS clone URL from your new GitHub repository:

```bash
git init
git add .
git commit -m "Initial Mango Stay website deployment"
git branch -M main
git remote add origin YOUR-NEW-REPO-URL
git push -u origin main
```

If the folder already has a remote named origin, inspect it using `git remote -v` and update with `git remote set-url origin YOUR-NEW-REPO-URL`. Do not force-push.

Cloudflare: Create a new Workers & Pages project connected to the NEW repository, using main as production branch. Select a static site deployment; publish the directory containing index.html and the villas and assets folders. If you use Workers static assets, configure its asset directory accordingly.

Before sharing, verify homepage, all 3 collection cards, all 13 villas, photos, WhatsApp, maps, and mobile Back behavior. No live browser test is implied by this ZIP.
