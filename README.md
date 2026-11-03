# NovaBuild GC website

A responsive, static one-page website starter for NovaBuild GC.

## Preview locally
Open `index.html` in a browser. An internet connection is needed for the remote Google Fonts and Unsplash images.

## Before publishing
1. Business phone number confirmed: (415) 933-0527.
2. Contact is phone-only for now (no company email yet). If an email becomes available, add it back to the contact panel in `index.html`.
3. Replace inspiration images with real company project photos when available. The current gallery is clearly labeled as inspiration and must not be represented as completed NovaBuild GC work.
4. Review service descriptions and all company/license claims for accuracy.

## Free hosting with Cloudflare Pages
1. Create a GitHub account and a Cloudflare account.
2. Create a new GitHub repository and upload the files in this folder.
3. In Cloudflare, open Workers & Pages → Create → Pages → Connect to Git.
4. Select the repository. Choose no build command and set the output directory to `/` (or `.` if requested).
5. Deploy. Cloudflare provides a free `*.pages.dev` address. A custom domain usually requires purchasing a domain separately.

This is a static site: no database, server, or admin login is required. Content changes are made by editing the files and redeploying.
