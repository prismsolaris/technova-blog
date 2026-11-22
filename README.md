# TechNova Technology Blog

A responsive static technology blog built with plain HTML, CSS, and JavaScript. No build tools or paid libraries are required.

## Included
- Responsive homepage with article search and category filters
- Six starter articles and topic navigation
- About, Contact, Privacy Policy, and Disclaimer pages
- Dark/light theme toggle (preference saved in browser)
- Mobile navigation
- PropellerAds integration placeholder (not active until you add your own approved tag)

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a browser, or use VS Code Live Server.
3. Replace demo text, contact details, and sample articles with your own reviewed content.

## Publish on a free subdomain
### GitHub Pages
1. Create/sign in to a GitHub account.
2. Create a public repository, for example `technova-blog`.
3. Upload all files and folders from this project (keep `index.html` at the repository root).
4. Open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Your free address will look like `https://YOUR-USERNAME.github.io/technova-blog/`.

You can also deploy the folder using Netlify Drop; its free subdomain availability and terms may change. A free subdomain is not the same as owning a custom domain.

## PropellerAds OnClick / Popunder setup
This project intentionally does **not** include a live ad script. Do not copy a script from another publisher or invent an ad tag.
1. Publish a real website with useful original content and complete the required site verification in your PropellerAds publisher account.
2. In the publisher dashboard, add/select your website and create an **OnClick (Popunder)** zone if the format is available for your account and site.
3. Read the current placement, traffic, consent, and policy requirements shown by PropellerAds.
4. Copy the exact JavaScript tag generated for your own approved zone.
5. Paste it into `index.html` immediately before `</body>` where the comment says `PROPellerAds`. Add it to other pages only if the provider's instructions require it.
6. Test your site and review the provider's reporting. Never force clicks, create fake traffic, use bots, or mislead visitors into clicking. Popunder behavior should follow the provider's rules and applicable local privacy/consent laws.

**Important:** A traffic chart is an estimate, not an activation control or a promise of earnings. Approval, availability, CPM, and revenue are not guaranteed.

## Before going live — checklist
- [ ] Replace `hello@example.com` in `contact.html` with a working email address.
- [ ] Rewrite the privacy policy to accurately describe your host, analytics, ad partners, cookies, and data practices.
- [ ] Review every article, add trustworthy references where appropriate, and publish original useful content.
- [ ] Add your own author/editorial information and update site branding if desired.
- [ ] Check all pages on mobile and desktop.
- [ ] Add your approved PropellerAds tag only after your site and zone are ready.
- [ ] Verify the final site complies with ad-network policies and applicable law.

## Customization
- Colors and layout: `css/style.css`
- Interactions: `js/main.js`
- Homepage and pages: root-level `.html` files
