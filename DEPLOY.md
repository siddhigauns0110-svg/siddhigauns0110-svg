# Publish the portfolio website

The site is a static HTML/CSS/JavaScript website. It does not need a build step or framework.

## Option 1: GitHub Pages

1. Open the repository: https://github.com/siddhigauns0110-svg/siddhigauns0110-svg
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. Wait for GitHub Pages to publish the site. The expected address is:
   https://siddhigauns0110-svg.github.io/siddhigauns0110-svg/

## Option 2: Vercel

1. Sign in to Vercel and choose **Add New → Project**.
2. Import the GitHub repository **siddhigauns0110-svg/siddhigauns0110-svg**.
3. Keep the project root at the repository root.
4. Choose **Other** / no framework preset. Leave the build command and output directory empty.
5. Deploy. Vercel will serve `index.html` from the root.

The website source is already committed. Publishing it requires connecting the repository and completing one of these hosting setups.
