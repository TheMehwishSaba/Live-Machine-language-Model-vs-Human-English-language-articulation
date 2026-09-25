[README.md](https://github.com/user-attachments/files/32635740/README.md)
# Vocal Tract Soundboard — GitHub Pages setup

This folder has exactly one file that matters: `index.html`. GitHub Pages
serves whatever is named `index.html` at the root of your repo as your
site's homepage, so no extra configuration is needed beyond enabling Pages.

## One-time setup (about 5 minutes)

1. **Create a GitHub account** if you don't have one: https://github.com/signup

2. **Create a new repository**
   - Click the **+** in the top-right corner → **New repository**
   - Name it anything, e.g. `vocal-tract-soundboard`
   - Set it to **Public** (required for free GitHub Pages)
   - Leave "Add a README" unchecked (you already have one)
   - Click **Create repository**

3. **Upload the file**
   - On your new repo's page, click **Add file** → **Upload files**
   - Drag in `index.html` from this folder
   - Scroll down, click **Commit changes**

4. **Turn on GitHub Pages**
   - Go to the repo's **Settings** tab
   - In the left sidebar, click **Pages**
   - Under "Build and deployment" → **Source**, choose **Deploy from a branch**
   - Under **Branch**, choose `main` and folder `/ (root)`, then **Save**

5. **Wait about 1–2 minutes**, then refresh that same Pages settings screen.
   GitHub will show a green banner with your live URL, in the form:

   ```
   https://YOUR-USERNAME.github.io/vocal-tract-soundboard/
   ```

That URL is permanent, free, and works on any device — share it with
anyone, embed it in an iframe elsewhere, or bookmark it for yourself.

## Making changes later

Any time you want to update the tool: edit `index.html` (either locally and
re-upload, or directly in GitHub's web editor by clicking the pencil icon
on the file), commit the change, and the live site updates automatically
within a minute or two — no redeploy step needed.

## Notes

- The page pulls its fonts from Google Fonts over the internet, so visitors
  need a normal internet connection the first time they load it (fonts are
  then cached by their browser).
- The "hear it" audio uses the visitor's own browser's built-in speech
  voice — nothing to host or configure for that to work.
