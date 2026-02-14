# PrmKitWeb

Official website for [PrmKit](https://github.com/pengyanhua/PrmKit) – AI Prompt Toolkit for Developers.

## 🚀 Deployment

This site is deployed to **Cloudflare Pages**.

### Deploy to Cloudflare Pages

1. **Connect GitHub Repository**
   - Go to [Cloudflare Pages Dashboard](https://dash.cloudflare.com/)
   - Click "Create a project" → "Connect to Git"
   - Select this repository: `pengyanhua/PrmKitWeb`

2. **Build Configuration**
   - Framework preset: **None** (static HTML)
   - Build command: *(leave empty)*
   - Build output directory: `/`
   - Root directory: `/`

3. **Custom Domain** (if applicable)
   - Add your custom domain in Cloudflare Pages settings
   - Update DNS records as instructed

4. **Deploy**
   - Every push to `main` branch triggers automatic deployment
   - Preview deployments for pull requests

## 📁 Project Structure

```
PrmKitWeb/
├── index.html       # Main landing page
└── README.md        # This file
```

## 🛠 Local Development

No build step required! Simply open `index.html` in a browser:

```bash
# Option 1: Use Python's built-in server
python -m http.server 8000

# Option 2: Use Node.js http-server
npx http-server

# Option 3: Use VS Code Live Server extension
# Right-click index.html → "Open with Live Server"
```

Then visit: `http://localhost:8000`

## 🎨 Tech Stack

- **HTML5** + **CSS3** + **Vanilla JS**
- **Tailwind CSS** (CDN)
- **Google Fonts** (Inter)
- No build tools required – deploy directly

## 📝 Content Updates

To update the website content:

1. Edit `index.html`
2. Commit and push to `main` branch
3. Cloudflare Pages will auto-deploy

## 🔗 Links

- **Live Site**: (Add your CF Pages URL here)
- **VS Code Extension**: https://marketplace.visualstudio.com/items?itemName=pengyanhua.prmkit
- **GitHub Repo**: https://github.com/pengyanhua/PrmKit
- **Issues**: https://github.com/pengyanhua/PrmKit/issues

## 📄 License

MIT License - Same as PrmKit extension
