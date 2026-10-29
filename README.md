# Nature Care Trust — Unified Management Dashboard

> **Dynamic Management & Publishing Suite for Nature Care Trust**  
> Subdomain application designed for `dashboard.naturecaretrust.com` to dynamically manage site content, publish blog journals, upload media, and fine-tune Google search SEO metadata with real-time SERP snippet previews.

---

## ⚡ Key Modules

### 1. 📝 Content & Vitals Hub
- **Hero Banner Management**: Live update the main hero headline, subheadline, and exploration CTAs without writing a single line of code.
- **Sanctuary Vitals Counters**: Dynamically update live impact statistics (Native Canopy Trees, Elders Supported, Barrier-Free Trails %, Protected Flora Species).
- **Trust Coordinates**: Update public office helpline, inquiry email, and sanctuary address.

### 2. 📰 Blog & Field Chronicles Studio
- **Publish Field Notes**: Full publishing modal supporting title, slug generation, category, author, read time, excerpt, and markdown/HTML body content.
- **Article Lifecycle**: Full live editing, previewing, and deleting of published field stories.
- **Instant Sync**: Updates immediately reflect on `naturecaretrust.com/blog/` and individual article pages.

### 3. 🔍 SEO & Meta Keyword Control Center
- **Per-Page Tuning**: Optimize all 5 site pages (`Home`, `About Us`, `Living Programs`, `Blog`, `Contact & Visit`).
- **Google Search Guidelines**:
  - **Meta Title** with 60-character optimal range indicator.
  - **Meta Description** with 160-character optimal snippet indicator.
  - **Focus Keyword** with automated keyword density and presence analysis.
  - **Canonical URL & OpenGraph Image URL** management.
- **Live Google SERP Preview**: Interactive simulation of how Google displays your snippet on **Desktop** and **Mobile** search result screens.

### 4. 🖼️ Images & Media Hub
- **Direct Upload**: Multipart file uploader saving JPG, PNG, WEBP, and SVG assets straight to server media directories.
- **Media Gallery**: Thumbnail previews with file size and timestamp metadata.
- **1-Click Copy Link**: Instant clipboard copy to easily paste URLs into blog articles or pages.

---

## 🚀 Subdomain Setup (Hostinger)

1. In Hostinger hPanel, navigate to **Domains** -> **Subdomains**.
2. Create subdomain:
   - **Subdomain Name**: `dashboard`
   - **Document Root**: `/public_html/dashboard` (or dedicated subdomain directory)
3. Clone or upload this repository into that directory:
   ```bash
   git clone https://github.com/samachakri/nature-care-trust-dashboard.git .
   ```
4. Access the dashboard at **`https://dashboard.naturecaretrust.com`**!

---

## 🛡️ Authentication
- **Default Administrator**: `samachakriofficial@gmail.com`
- Session-based access with remember-token in localStorage.
