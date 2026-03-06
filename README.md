# trun106.github.io
# My Github website 

## Setup

### *When begin to code*

* Clone repo:

```bash
git clone https://github.com/trun106/trun106.github.io/
```

* Create new branch:

```bash
git checkout -b <name-of-the-branch>
```



### *Push the code on Git*

Before push.

* Add changes:

```bash
git add .
```

* Commit changes:

```bash
git commit -m "Description"
```

* Push on the created branch:

```bash
git push origin <name-of-the-branch>
```

* In repo page → tab **Pull requests** → **New Pull Request**, in *compare* choose your branch → **Create pull request** → then report to group. When the code accepted, code will be merged into branch `main`.

### **Update from main branch anytime**

```bash
git pull origin main
```

### **The .gitignore you should add (for web dev)**
```
# Node.js
node_modules/
npm-debug.log*

# Build output
dist/
build/
_site/
public/
.cache/
.jekyll-cache/
.nuxt/
.next/

# Local/Editor/System files
.env
.vscode/
.idea/
.DS_Store
Thumbs.db

# SASS/SCSS cache
.sass-cache/
```


