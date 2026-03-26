# Appnything GitHub Pages Site

This is a ready-to-upload static website for `appnything.com`.

## Included pages

- `/` → Home page
- `/support/` → Support page
- `/checklist-app/privacy/` → Privacy Policy for Checklist App
- `/templates/privacy-template/` → Reusable privacy page template for future apps

## How to publish on GitHub Pages

1. Create a GitHub repository.
2. Upload all files from this folder to the root of the repository.
3. In GitHub, go to **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder.
6. Save.
7. In your domain provider, point `appnything.com` to GitHub Pages.
8. Keep the included `CNAME` file in the repo root.

## How to add a new app privacy page

1. Copy the folder `templates/privacy-template/`.
2. Rename it to something like `my-new-app/privacy/`.
3. Edit the page text.
4. Add a link to the new privacy page in `index.html`.

## Support email

Current support email used in the site:

`support@appnything.com`

Update it if you want to use a different address.
