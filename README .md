# Congregation Zelichov Website

This repository contains the website for Congregation Zelichov, a synagogue located in Monsey, NY.

## Files Included

- `index.html` - The homepage
- `privacy-policy.html` - Privacy Policy page (for 10DLC compliance)
- `terms-of-service.html` - Terms of Service page (for 10DLC compliance)

## Deployment Instructions for GitHub Pages

Follow these steps to deploy this website on GitHub Pages:

### 1. Create a GitHub Repository

1. Sign in to your GitHub account (or create one at https://github.com/join)
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository `zelichovmonsey.com` (or any name you prefer)
4. Select "Public" visibility
5. Click "Create repository"

### 2. Upload the Website Files

#### Option A: Using the GitHub Web Interface

1. In your new repository, click "Add file" > "Upload files"
2. Drag and drop all the HTML files from this package
3. Click "Commit changes"

#### Option B: Using Git Command Line

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/zelichovmonsey.com.git
   ```
2. Copy all HTML files into the cloned directory
3. Add, commit, and push the files:
   ```
   git add .
   git commit -m "Initial website files"
   git push origin main
   ```

### 3. Configure GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings"
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait a few minutes for your site to deploy

### 4. Set Up Custom Domain (zelichovmonsey.com)

1. First, purchase the domain `zelichovmonsey.com` from a domain registrar (like Namecheap, GoDaddy, etc.)
2. In your repository, go to Settings > Pages
3. Under "Custom domain", enter `zelichovmonsey.com`
4. Click "Save"
5. At your domain registrar, set up the following DNS records:
   - A record: Set your domain to point to the following GitHub Pages IP addresses:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - CNAME record: Create a record for `www` that points to `yourusername.github.io`

6. Back on GitHub, make sure to check "Enforce HTTPS" once the certificate is ready

### 5. Verify Your Website

After deployment is complete (may take up to 10 minutes):
1. Visit `https://zelichovmonsey.com` to confirm your website is working
2. Test all links and pages

## Making Updates

To update your website:
1. Edit the HTML files locally
2. Commit and push changes (if using Git), or upload updated files through the GitHub interface
3. GitHub Pages will automatically redeploy your site with the changes

## Support

If you need assistance with this website, please contact:
- Email: info@zelichovmonsey.com
- Phone: (845) 502-2016