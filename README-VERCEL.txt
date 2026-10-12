CAN MEDIA — Vercel deployment package

Files:
- index.html: main landing page (Vercel root entry)
- can-partner.html: partner registration page
- assets/images/can-media-logo.png: supplied CAN MEDIA logo
- vercel.json: avoids rewriting / to the old HTML filename

How to deploy:
1. Upload/commit the contents of this ZIP to the root of the connected GitHub repository.
2. Make sure index.html is at the repository root (not nested inside another folder).
3. In Vercel, check Project Settings > Build and Deployment > Root Directory points to the folder containing index.html.
4. Redeploy after committing.

Note:
The uploaded files referenced an optional image at images/can-media-brand.png, but that separate banner image was not included in the upload. Its existing onerror handler hides the banner section if the image is absent. Add that banner file to the images/ folder if you want the banner to appear.
