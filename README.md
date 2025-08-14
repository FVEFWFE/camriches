# CamRiches.ai Sales Letter - Cyberpunk 2077 Mod

A modern, Notion-like sales letter website with dark mode for a Cyberpunk 2077 mod.

## Features

- 🌙 Dark mode by default with cyberpunk aesthetic
- ✨ Smooth animations and transitions
- 📱 Fully responsive design
- 🎮 Glitch effects and neon accents
- 📊 Interactive stats and feature sections
- 🚀 Single-file deployment (no build required)

## Local Development

### Option 1: Python HTTP Server
```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

### Option 2: Node.js
```bash
npx serve .
# Or
npm run dev
```

### Option 3: VS Code Live Server
Install the "Live Server" extension and right-click on `index.html` → "Open with Live Server"

## Deployment to Vercel

### Method 1: Vercel CLI (Recommended)

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Login to Vercel:
```bash
vercel login
```

3. Deploy:
```bash
vercel --prod
```

### Method 2: GitHub Integration

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy" (no configuration needed)

### Method 3: Drag & Drop

1. Go to [vercel.com](https://vercel.com)
2. Sign in/Sign up
3. Drag the project folder onto the Vercel dashboard
4. Your site will be deployed instantly

## Alternative Deployment Options

### Netlify
1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag the project folder to the deployment area
3. Your site will be live immediately

### GitHub Pages
1. Push to GitHub
2. Go to Settings → Pages
3. Select source branch
4. Your site will be available at `https://[username].github.io/[repo-name]`

### Surge.sh
```bash
npm install -g surge
surge
```

## Project Structure

```
/
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── package.json        # Node.js package configuration
├── vercel.json         # Vercel deployment configuration
├── .gitignore          # Git ignore file
└── README.md           # This file
```

## Technologies Used

- Pure HTML5
- CSS3 with CSS Variables
- Vanilla JavaScript
- No external dependencies or build process required

## Customization

The site uses CSS variables for easy theming. Main variables are defined in the `:root` selector in the `<style>` section of `index.html`:

- `--bg-primary`: Main background color
- `--accent-primary`: Primary accent color (neon green)
- `--text-primary`: Main text color
- And more...

## License

Created for entertainment purposes as part of a Cyberpunk 2077 mod.