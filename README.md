# Eleventy Blog Template for Keith

Project notes here with original README below. Then I'll rewrite this if it works. Initially, I want to deploy to Cloudflare Pages. Then add PWA capabilities, including push notifications (OneSignal).

## 210519a 1st Config
As per Configuration notes from original below (edit `src/_data/`).
- author.json
- menu.json
- site.js


***

## Original Vredeburg Readme
[![Netlify Status](https://api.netlify.com/api/v1/badges/a1d36fc9-4471-4679-902c-337449ccb59d/deploy-status)](https://app.netlify.com/sites/vredeburg/deploys)

A simple starter project to create a blog using Eleventy and Tailwind CSS

<details>
  <summary>Screenshot</summary>
  
  ![](https://i.imgur.com/wGj2YZD.jpg)
</details>

See demo [here](https://vredeburg.netlify.app)!

## Getting Started
1. Clone this repository
```bash
git clone https://github.com/dafiulh/vredeburg.git blog-name
```
2. Navigate to the directory
```bash
cd blog-name
```
3. Install dependencies
```bash
npm install
```

### Use in development
```bash
npm start
```

### Build for production
```bash
npm run build
```

### For debugging purposes
```bash
npm run debug
```

## Configuration
To change the title, description, author data, menu/nav item, etc, go to `src/_data/`.
