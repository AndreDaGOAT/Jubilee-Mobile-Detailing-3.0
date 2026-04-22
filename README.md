diff --git a/README.md b/README.md
index 3f51556bdac43f16bf115da8792db6ab1c5d1532..293c9df5574267114631eb84bf791d30432f176b 100644
--- a/README.md
+++ b/README.md
@@ -1,10 +1,55 @@
-- 👋 Hi, I’m @AndreDaGOAT
-- 👀 I’m interested in programming, data analystics, AI coding..
-- 🌱 I’m currently learning Python, AI coding enhancements...
-- 💞️ I’m looking to collaborate on GIS integrations, python best practices, AI enhancing...
-- 📫 How to reach me aarmstrong1234@gmail.com...
-
-<!---
-AndreDaGOAT/AndreDaGOAT is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-You can click the Preview link to take a look at your changes.
---->
+# Mobile Detailing Business System (GitHub-Ready)
+
+A deploy-ready static website for a mobile detailing business.
+
+## What this includes
+
+- ✅ GitHub Pages hosting setup (with GitHub Actions workflow)
+- ✅ Plain HTML/CSS/JS frontend (fastest launch)
+- ✅ Formspree-compatible quote form (or swap with Google Forms)
+- ✅ Calendly booking link (or replace with Square)
+- ✅ CRM flow guidance for HubSpot Free or Google Sheets
+
+## Project structure
+
+- `index.html` — business landing page + quote + booking + CRM sections
+- `styles.css` — responsive styles
+- `script.js` — single settings object for phone/email/Formspree/Calendly
+- `.github/workflows/deploy-pages.yml` — automatic GitHub Pages deployment on `main`
+
+## 5-minute setup
+
+1. **Edit `script.js`**
+   - `phone`
+   - `displayPhone`
+   - `email`
+   - `calendlyUrl`
+   - `formspreeEndpoint`
+
+2. **Push to GitHub**
+   ```bash
+   git add .
+   git commit -m "Configure mobile detailing site"
+   git push origin main
+   ```
+
+3. **Enable Pages in repository settings**
+   - Settings → Pages
+   - Build and deployment source: **GitHub Actions**
+
+4. **Test live website**
+   - Submit quote form
+   - Open booking link
+   - Verify contact links
+
+## Tool choices supported
+
+- Hosting: **GitHub Pages** (free)
+- Frontend: **HTML/CSS** (optional Tailwind later)
+- Forms: **Formspree** or **Google Forms**
+- Booking: **Calendly** or **Square Appointments**
+- CRM: **HubSpot Free** or **Google Sheets**
+
+## Optional upgrade path
+
+- Move hosting/forms to Netlify later if you want easier automation.
