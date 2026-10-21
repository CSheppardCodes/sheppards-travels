# SheppardsTravels 🌍 — setup (free, ~10 minutes, no Claude account needed)

## 1. Put the website on GitHub Pages
1. Make a free account at github.com, then click **New repository**. Name it `sheppards-travels`, set it to **Public**, tick "Add a README", and create it.
2. **Add file → Upload files**, drag in `index.html`, then **Commit changes**.
3. Go to **Settings → Pages**. Under "Branch" pick `main` and `/ (root)`, then **Save**.
4. After about a minute your site is live at `https://YOURNAME.github.io/sheppards-travels/`. Open it on your phone and use **Add to Home Screen**.

The site is public, but it contains only code. Your photos never go in this repo.

## 2. Make a private repo for your photos (free cloud storage)
1. **New repository**, name it `travel-photos`, set it to **Private**, tick "Add a README", and create it.
2. Go to **Settings (your profile) → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
3. Set the repository access to **Only select repositories → travel-photos**, and under Permissions set **Contents: Read and write**. Generate and copy the token.
4. Open your site, tap **☁️ Sync**, enter `YOURNAME/travel-photos` and the token, then tap **Save & sync**.

The token is stored only in that browser. Repeat step 4 on each device and your photos will appear everywhere.

## Good to know
- Photos are shrunk to 1600px, so a GitHub repo holds thousands for free (stay under about 1 GB).
- Deleting a photo removes it from the map, but the file stays in the private repo.
- Without Sync, photos stay only in that browser.
- iPhone: in the photo picker tap **Options** and turn on **Location**, or iOS strips the GPS.

## Password
The site opens with a password screen (password: `Passw0rd`; change it by replacing the long `PH` hash at the top of the script in `index.html`). This is a casual lock: someone who knows how to read page code could get past it. Your photos stay safe because they live in the **private** repo and only load with your token.

## Other ways to put the website on GitHub
- **github.dev:** open your repo and press the `.` key, drag `index.html` into the file list, then use Source Control to commit.
- **GitHub Desktop** (free app): clone the repo, drop in `index.html`, commit and push.
- **Phone:** the GitHub website in a browser (Add file → Upload files) works too.
