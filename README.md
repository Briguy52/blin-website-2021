# React-Static - Basic Template

To use this template, run `react-static create` and use the `basic` template.

# Netlify

Okay let's try ditching all the GitHub Pages junk and just use Netlify!



# Sources

Base code from [React-Static](https://github.com/react-static/react-static)

GitHub Pages config from [react-gh-pages](https://github.com/gitname/react-gh-pages)

# GH Pages Config

Added these lines to the `package.json`:

```
  "homepage": "http://briguy52.github.io/blin-website-2021",
```

```
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
```

Note: `dist` needs to match whatever folder the static files get generated into

# Running Locally

`npm run start` to run locally to port `3000`.

# Deploying

`npm run deploy` will deploy your changes in the `main` branch to the remote `gh-pages` branch automatically (no need to merge or push anything other than `main` to preserve your work remotely)