LINE Group Invitation Page
==========================

Files
-----
- index.html : bilingual invitation landing page
- cover.png  : approved promotional cover artwork
- profile.png: matching square avatar

Already configured
------------------
- Existing LINE invitation URL
- Traditional Chinese + English copy
- Mobile-friendly layout
- Open Graph and Twitter Card metadata

IMPORTANT: Set the public image URL after hosting
-------------------------------------------------
The social preview image needs an absolute public HTTPS URL. In index.html,
replace BOTH occurrences of:

  https://YOUR-SITE-DOMAIN/cover.png

with the actual public URL of cover.png after deployment.

Example:
  https://yourname.github.io/line-invitation/cover.png

Hosting with GitHub Pages
-------------------------
1. Sign in to GitHub and create a new PUBLIC repository, for example:
   line-invitation
2. Upload index.html, cover.png, and profile.png to the repository's root.
3. Open the repository's Settings > Pages.
4. Under Build and deployment, choose "Deploy from a branch".
5. Choose the main branch and /(root), then Save.
6. Wait for GitHub Pages to publish the site. Its address will look like:
   https://YOUR-USERNAME.github.io/line-invitation/
7. Replace the placeholder image URLs in index.html with:
   https://YOUR-USERNAME.github.io/line-invitation/cover.png
8. Commit the change and wait for the site to update.

After publishing
----------------
- Open the page on a phone and test the Join LINE Group button.
- Share the page URL in a test chat to inspect the preview.
- Social platforms may cache previews. If an old preview remains, use the
  platform's link-preview debugger or wait for its cache to refresh.

Note
----
The landing page does not change your LINE group or invitation URL.
The cover artwork shown on this page is also separate from LINE's own
group cover image.
