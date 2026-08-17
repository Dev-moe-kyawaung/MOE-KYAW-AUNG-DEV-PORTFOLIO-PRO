# Install deployment package
npm install --save-dev gh-pages

# Add to package.json
{
  "homepage": "https://dev-moe-kyawaung.github.io/portfolio",
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  }
}

# Deploy
npm run deploy
