# LightSpeed AI Solns Website

This is the static website for **LightSpeed AI Solns**, hosted via GitHub Pages.

## How to Host

1. Create a new GitHub repository (public).  
2. Upload all files from this package into the repository root (make sure `index.html` is at the top level).  
3. Go to **Settings → Pages**.  
   - Source: `main` branch  
   - Folder: `/ (root)`  
   - Save.  
4. Your site will be published at: `https://<username>.github.io/<repo>/`  
5. To use the custom domain `lightspeedaisolns.in`:  
   - Keep the included `CNAME` file in the repo.  
   - In Pages settings, set the custom domain to `lightspeedaisolns.in`.  
   - Add GoDaddy DNS records (4 A records to GitHub IPs + optional www CNAME).  
   - Enable **Enforce HTTPS**.  
