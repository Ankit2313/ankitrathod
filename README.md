# Ankit Rathod — Senior Full Stack Engineer Portfolio

Live personal portfolio website built with semantic HTML5, zero-dependency responsive CSS, custom Dark/Light theme switching, and ATS-friendly resume download support.

## 🚀 Features

- **Zero-Dependency Architecture:** Pure HTML, CSS custom properties, and vanilla JavaScript — no build step, bundlers, or external CDNs required.
- **Refined Dark / Light Theme Switch:** Persistent `localStorage` toggle with smooth spring-animated thumb transitions and accessible ARIA attributes.
- **Instant Resume Download:** Pre-bound synchronous download fallback that automatically upgrades to `Ankit_Rathod_Resume.pdf` when hosted over HTTP/HTTPS.
- **Production Case Studies:** Highlights architectural impact across **ControlHippo** (Omni-Channel SaaS, Redis caching, ChargeBee idempotent billing) and **CallHippo** (zero-downtime migration of 5,000+ business accounts, WebSocket telemetry, MongoDB query optimization).

## 📁 Repository Structure

```text
├── index.html                    # Complete portfolio webpage (HTML + CSS + JS)
├── README.md                     # Repository documentation & deployment instructions
└── Ankit_Rathod_Resume.pdf       # (Optional) Place your exported PDF resume here
```

## 🛠️ Local Preview

Open `index.html` directly in any modern browser, or serve locally:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## 🌐 Deploying to GitHub Pages

1. Create a public GitHub repository named `<your-github-username>.github.io`.
2. Upload `index.html`, `README.md`, and (optionally) `Ankit_Rathod_Resume.pdf` to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "feat: deploy developer portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-github-username>/<your-github-username>.github.io.git
   git push -u origin main
   ```
3. Go to **Repository Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
5. Access your live site at `https://<your-github-username>.github.io`.

## 📬 Contact

- **Name:** Ankit Rathod
- **Role:** Senior Full Stack Engineer (Node.js • React.js • TypeScript • MongoDB • Redis)
- **Location:** Ahmedabad, Gujarat, India
- **Email:** [ankit.rathod.2313@gmail.com](mailto:ankit.rathod.2313@gmail.com)
- **LinkedIn:** [linkedin.com/in/ankit-a-rathod](https://linkedin.com/in/ankit-a-rathod)
