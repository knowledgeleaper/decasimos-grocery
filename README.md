# 🛒 DeCasimos - Fresh Groceries & Market

A modern, responsive grocery website deployed via FastAPI and GitHub Actions to Cloudflare Pages.

## 🌐 Live Website

Visit: [https://decasimos.pages.dev](https://decasimos.pages.dev)

## 🚀 Deployed via FastAPI

This website was automatically generated and deployed using the DeCasimos FastAPI deployment service.

**Deployment ID:** `cf2a23e1-8066-4829-b2ab-312bb181bff2`  
**Generated:** `2025-08-01 20:31:06`

## ✨ Features

- 🥬 **Dynamic Promotions** - Updated via API calls
- 📱 **Mobile Responsive** - Optimized for all devices
- 🚀 **Fast Loading** - Hosted on Cloudflare's global CDN
- 🎨 **Modern Design** - Professional grocery store aesthetic
- ⚡ **Emergency Banners** - Flash sale and urgent announcements
- 🔄 **Auto-Deploy** - Automatic deployment via GitHub Actions

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Backend:** FastAPI (Python)
- **Hosting:** Cloudflare Pages
- **CI/CD:** GitHub Actions
- **Version Control:** Git

## 📡 API Deployment

This website is deployed using a FastAPI service that accepts:

```json
{
  "github_username": "your-username",
  "github_token": "your-token",
  "promotions": [
    {
      "title": "Organic Apples",
      "discount": "50% OFF",
      "description": "Fresh organic apples from local farms",
      "link": "#organic-apples",
      "button_text": "Shop Now"
    }
  ],
  "emergency_banner": {
    "show": true,
    "message": "🎉 Weekend Special: 40% OFF Everything!"
  }
}
```

## 🔄 Auto-Deployment Workflow

1. **API Request** → FastAPI receives deployment request
2. **GitHub Repository** → Creates/updates repository automatically
3. **GitHub Actions** → Triggers deployment workflow
4. **Cloudflare Pages** → Builds and deploys automatically
5. **Live Site** → Updates within 30 seconds

## 📊 Performance

- ⚡ **Lighthouse Score:** 95+ (Performance, Accessibility, Best Practices, SEO)
- 🌍 **Global CDN:** Served from 300+ Cloudflare data centers worldwide
- 📱 **Mobile Optimized:** Fast loading on all devices

## 🛒 Grocery Categories

- 🥬 **Produce** (Green theme) - Fruits, vegetables, organic items
- 🥛 **Dairy** (Blue theme) - Milk, cheese, eggs, dairy products
- 🍞 **Bakery** (Pink/Yellow theme) - Bread, pastries, desserts
- 🥩 **Meat** (Red theme) - Beef, chicken, seafood, deli items

---

*Built with 💚 for fresh, local grocery shopping*  
*Powered by FastAPI + GitHub Actions + Cloudflare Pages*
