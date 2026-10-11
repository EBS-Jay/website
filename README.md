# Elevating Business Solutions website backups

Updated October 10, 2026 with the latest website changes.

## What is included

- Social Media page with Silver ($497/month), Gold ($597/month), and Platinum ($997/month) coaching packages, voice setup details, technical support channels, and the new hero image.
- Homepage Explore buttons linking to their individual service pages.
- About page philosophy icons and removal of the redundant About link.
- Roundtable selective membership messaging, Apply for Membership buttons, and application review process.

## View the saved website

Download **EBS-Saved-Website.zip** and extract the entire ZIP. Open **Saved EBS Website/index.html** in Chrome. Keep the images, styles, scripts, and other pages together in that folder. Embedded Fillout forms and online fonts need internet access.

## Edit the website

Download **EBS-Editable-Website.zip** and extract the entire ZIP. Main page content is in **specification.mjs**, Social Media content is in **social-media-page.mjs**, shared layout is in **site.mjs**, and styles and browser scripts are in **dist/client/**. Keep dist/client: it contains the source images and styles. The other change scripts are historical utilities, not commands to rerun when opening the project.

With Node.js installed, open a terminal in the **Editable EBS Website** folder and run **node build.mjs**, then **node preview.mjs**. Open http://127.0.0.1:4173/.

These ZIP files are saved snapshots. GitHub does not automatically update them after local edits, and storing the ZIPs here does not publish the website. Fillout, Zapier, HoneyBook, and email automation settings are managed separately and are not recreated by extracting these files.
