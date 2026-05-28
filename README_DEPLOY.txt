Graph Theory Introduction - Web Hosting Package

Use this folder to publish the HTML page as a URL.

Recommended options:
1. Netlify Drop:
   - Go to https://app.netlify.com/drop
   - Drag and drop this entire unzipped folder
   - Netlify will generate a public URL
   - Copy that URL and paste it into LMS

2. GitHub Pages:
   - Create a new GitHub repository
   - Upload index.html
   - Go to Settings > Pages
   - Deploy from main branch/root
   - Copy the GitHub Pages URL and paste it into LMS

3. University Web Server:
   - Upload index.html to any public web folder
   - Use the generated page URL in LMS

LMS iframe embed code:
<iframe src="PASTE_YOUR_PUBLIC_URL_HERE" width="100%" height="900" style="border:0;border-radius:16px;" allowfullscreen></iframe>

Important:
- Python execution uses Pyodide and needs internet access.
- If the LMS blocks scripts inside iframe, open the page as an external URL instead of embedding.
