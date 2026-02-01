# Blue House Group Website

A simple, professional website for Blue House Group with a homepage and investor login page.

## Files Included

- `index.html` - Homepage with Blue House Group branding and login button
- `login.html` - Investor login page (non-functional, for display only)
- `styles.css` - Professional blue/grey styling

## Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

1. **Create a GitHub account** (if you don't have one)
   - Go to https://github.com
   - Sign up for free

2. **Create a new repository**
   - Click the '+' icon → 'New repository'
   - Name it: `yourusername.github.io` (replace 'yourusername' with your GitHub username)
   - Make it Public
   - Click 'Create repository'

3. **Upload your files**
   - Click 'uploading an existing file'
   - Drag and drop all three files: `index.html`, `login.html`, `styles.css`
   - Click 'Commit changes'

4. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Under 'Source', select 'main' branch
   - Click Save
   - Your site will be live at: `https://yourusername.github.io`

5. **Connect your custom domain**
   - In Settings → Pages, enter your domain name
   - Update your domain's DNS settings (at your domain registrar):
     - Add a CNAME record: `www` → `yourusername.github.io`
     - Add A records for apex domain pointing to GitHub's IPs:
       - 185.199.108.153
       - 185.199.109.153
       - 185.199.110.153
       - 185.199.111.153
   - Wait 5-10 minutes for DNS to propagate
   - Enable HTTPS in GitHub Pages settings (recommended)

### Option 2: Netlify (Also Free & Easy)

1. **Create a Netlify account**
   - Go to https://www.netlify.com
   - Sign up for free

2. **Deploy your site**
   - Click 'Add new site' → 'Deploy manually'
   - Drag the folder containing all three files into the upload area
   - Site goes live immediately at a random URL

3. **Connect your custom domain**
   - Click 'Domain settings'
   - Click 'Add custom domain'
   - Enter your domain name
   - Follow Netlify's instructions to update your DNS settings
   - Netlify automatically provisions SSL certificate

### Option 3: Vercel (Free Alternative)

1. **Create a Vercel account**
   - Go to https://vercel.com
   - Sign up for free

2. **Deploy**
   - Click 'Add New' → 'Project'
   - Import from Git or drag files
   - Site goes live instantly

3. **Add custom domain**
   - Project Settings → Domains
   - Add your domain and follow DNS instructions

## DNS Configuration Help

### If your domain is at GoDaddy, Namecheap, etc.:

1. Log into your domain registrar
2. Find DNS settings (usually called 'DNS Management' or 'Advanced DNS')
3. Add the records provided by your chosen platform (GitHub Pages, Netlify, or Vercel)
4. Wait 5-60 minutes for changes to take effect

## Testing Locally

To preview the site on your computer before deploying:

1. Open the folder containing the files
2. Double-click `index.html`
3. Your browser will open the site
4. Click around to test the login button and navigation

## Notes

- The login form is **non-functional** - it's purely for display
- No backend or database is needed
- All hosting options above are **completely free**
- SSL/HTTPS is included free with all options

## Support

If you need help deploying:
- GitHub Pages: https://docs.github.com/en/pages
- Netlify: https://docs.netlify.com
- Vercel: https://vercel.com/docs

## Customization

To change colors, text, or styling:
- Edit `styles.css` for colors and design
- Edit `index.html` or `login.html` for content
- Upload the changed files to your hosting platform
