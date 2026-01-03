# 🚀 Deployment Guide for IBT Solutions Website

## Quick Deploy to GoDaddy

### Step 1: Access GoDaddy Hosting
1. Go to https://www.godaddy.com/
2. Log in to your account
3. Navigate to **My Products** → **Web Hosting**
4. Click **Manage** next to your hosting plan

### Step 2: Open File Manager
- Click on **File Manager** or **cPanel**
- Navigate to the `public_html` folder (this is your web root)
- Delete any default files (like `index.html` or `coming_soon.html`)

### Step 3: Upload Files
Upload these files maintaining the folder structure:

```
public_html/
├── index.html
├── css/
│   └── style.css
└── js/
    └── script.js
```

**How to Upload:**
- Create `css` and `js` folders first
- Upload `index.html` to `public_html`
- Upload `style.css` to `public_html/css`
- Upload `script.js` to `public_html/js`

### Step 4: Verify Deployment
- Visit https://ibtsolutions.co.in
- Check that all sections load properly
- Test the contact form
- Test mobile navigation

## Alternative: FTP Upload

If you prefer using FTP:

1. **Get FTP Credentials** from GoDaddy (in hosting dashboard)
2. **Use an FTP client** like FileZilla
3. **Connect** using:
   - Host: Your FTP hostname (from GoDaddy)
   - Username: Your FTP username
   - Password: Your FTP password
   - Port: 21
4. **Upload** all files to `public_html`

## Files Ready for Upload

✅ All files in this folder are production-ready
✅ No build process required
✅ No dependencies to install

---

**Need help?** Contact GoDaddy support or check their File Manager documentation.
