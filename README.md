# YourDigitalHub - Ad Monetization Website

A modern, responsive landing page website designed for **Google AdSense monetization**. This template comes with ready-to-use ad slots and all the necessary pages for AdSense approval.

## 📋 Pages Included

- **index.html** - Main landing page with hero, features, articles, newsletter
- **about.html** - About page with mission, vision, and values
- **contact.html** - Contact page with form
- **privacy-policy.html** - Privacy Policy (required for AdSense)
- **terms.html** - Terms of Service (required for AdSense)

## 📢 Ad Slots Included

The website includes **3 ad slots** ready for Google AdSense:

1. **Top Banner Ad** (below hero section) - Leaderboard format
2. **In-Content Ad** (between features and articles) - Responsive format
3. **Bottom Banner Ad** (above newsletter section) - Leaderboard format

## 🚀 Quick Start

### 1. Get Google AdSense Approval
1. Go to [Google AdSense](https://adsense.google.com) and sign up
2. Submit your website URL for review
3. Wait for approval (can take 1-2 weeks)

### 2. Add Your AdSense Code
Once approved, replace the placeholder values in all HTML files:

**In the `<head>` section** (every page):
```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
```
Replace `ca-pub-XXXXXXXXXXXXXXXX` with your actual Publisher ID.

**In each ad slot** (replace `ca-pub-XXXXXXXXXXXXXXXX` and `XXXXXXXXXX`):
```html
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
     data-ad-slot="XXXXXXXXXX"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>
```

### 3. Deploy to GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload all files
3. Go to **Settings → Pages**
4. Under **Branch**, select `main` and `/ (root)`
5. Click **Save**
6. Your site will be live at `https://[username].github.io/[repo-name]/`

### 4. Deploy to Vercel (Free)
1. Go to [Vercel](https://vercel.com)
2. Click **New Project**
3. Import your GitHub repository
4. Click **Deploy**

## 💡 Tips for AdSense Approval

- ✅ Add more original content (articles, blog posts) to your site
- ✅ Make sure your site has a clear purpose and is easy to navigate
- ✅ Include a Privacy Policy and Terms of Service (already included)
- ✅ Add an About page with real information about you (already included)
- ✅ Add a Contact page (already included)
- ✅ Ensure your site has a professional design (already done!)
- ❌ Don't use copyrighted content
- ❌ Don't launch with empty pages

## 📄 License

MIT License - Free for personal and commercial use.

## 🛠️ Tech Stack

- HTML5
- CSS3 (custom, responsive)
- JavaScript (vanilla)
- Font Awesome icons
- Google AdSense ready

---

**Made with ❤️ for digital creators**
