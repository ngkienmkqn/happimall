# Happi Mall Website

A premium dropshipping and print-on-demand platform website, cloned from MadeMine and rebranded for **Happi Mall** by Articulat Private Limited.

## 🚀 Features

- **Modern Design**: Clean, responsive design with vibrant green (#00c16a) brand colors
- **Full Responsiveness**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Navigation**: Mega menus and dropdown navigation
- **Smooth Animations**: Scroll-triggered animations and smooth transitions
- **SEO Optimized**: Proper meta tags, semantic HTML, and structured content
- **Fast Loading**: Optimized images and minimal dependencies

## 🏢 Company Information

**Articulat Private Limited**  
8 BURN ROAD, #04-04, TRIVEX  
Singapore 369977  
Email: info@happimall.com

## 📁 Project Structure

```
Articulat Private Limited/
├── index.html          # Homepage
├── about.html          # About & Contact page
├── policies.html       # Terms of Service & Privacy Policy
├── styles/
│   ├── main.css       # Main stylesheet
│   └── navigation.css # Navigation styles
├── scripts/
│   └── main.js        # JavaScript functionality
├── images/
│   ├── logo.png       # Happi Mall logo
│   ├── hero-banner.png
│   ├── products-showcase.png
│   └── value-props.png
├── netlify.toml       # Netlify configuration
└── README.md          # This file
```

## 🌐 Deploying to Netlify

### Method 1: Netlify CLI (Recommended)

1. **Install Netlify CLI** (if not already installed):
   ```bash
   npm install -g netlify-cli
   ```

2. **Navigate to project directory**:
   ```bash
   cd "C:\Users\TheHuman\Desktop\web\Articulat Private Limited"
   ```

3. **Login to Netlify**:
   ```bash
   netlify login
   ```

4. **Initialize and deploy**:
   ```bash
   netlify init
   ```
   
   Follow the prompts:
   - Create & configure a new site
   - Choose your team
   - Site name: `happimall` (or your preferred name)
   - Build command: (leave empty)
   - Publish directory: `.` (current directory)

5. **Deploy**:
   ```bash
   netlify deploy --prod
   ```

### Method 2: Netlify Web Interface

1. **Go to** [Netlify](https://app.netlify.com/)
2. **Sign in** or create an account
3. **Click** "Add new site" → "Deploy manually"
4. **Drag and drop** the entire project folder
5. **Your site will be live** at `https://random-name.netlify.app`

### Method 3: GitHub + Netlify (Continuous Deployment)

1. **Create a GitHub repository**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Happi Mall website"
   git branch -M main
   git remote add origin https://github.com/yourusername/happimall.git
   git push -u origin main
   ```

2. **Connect to Netlify**:
   - Go to [Netlify](https://app.netlify.com/)
   - Click "Add new site" → "Import an existing project"
   - Choose GitHub and select your repository
   - Build settings:
     - Build command: (leave empty)
     - Publish directory: `.`
   - Click "Deploy site"

3. **Automatic deployments**: Every push to `main` will trigger a new deployment

## 🛠️ Local Development

To view the website locally:

1. **Simple Method** (using browser):
   - Open `index.html` in your web browser
   - Note: Some features may not work due to CORS restrictions

2. **Local Server** (recommended):
   
   Using Python:
   ```bash
   python -m http.server 8000
   ```
   
   Using Node.js (http-server):
   ```bash
   npx http-server -p 8000
   ```
   
   Then visit `http://localhost:8000`

## 🎨 Customization

### Changing Colors

Edit `styles/main.css` and modify the CSS variables:

```css
:root {
  --color-primary: #00c16a;        /* Main brand color */
  --color-primary-dark: #00a559;   /* Darker shade */
  --color-primary-light: #00d674;  /* Lighter shade */
  --color-accent: #FFD700;         /* Accent color */
}
```

### Adding New Pages

1. Create a new HTML file (e.g., `new-page.html`)
2. Copy the structure from `about.html`
3. Update the content
4. Add links to the navigation in all pages

### Updating Images

Replace the images in the `images/` folder with your own. Make sure to use the same filenames or update the references in the HTML files.

## 📋 Pages Overview

- **index.html**: Homepage with hero section, features, product showcase, and integrations
- **about.html**: Company information, mission, values, and contact details
- **policies.html**: Legal information including Terms of Service and Privacy Policy

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with variables, flexbox, and grid
- **Vanilla JavaScript**: No frameworks, pure JS for better performance
- **Google Fonts**: Inter and Outfit font families
- **Responsive Design**: Mobile-first approach

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 License

This website is proprietary to Articulat Private Limited.

## 🤝 Support

For questions or support, contact us at:
- Email: info@happimall.com
- Address: 8 BURN ROAD, #04-04, TRIVEX, Singapore 369977

---

**Built with ❤️ for Happi Mall**
