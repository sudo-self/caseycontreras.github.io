# GitHub Pages Full Setup Guide

This guide walks you through creating a GitHub Pages site from scratch, including renaming your repo, adding an `index.html`, and enabling Pages.

---

## 1. Rename This Repository

```text
caseycontreras.github.io
```

---

## 2. Create `index.html` in the Root

Create a file named `index.html` in the root of your repository.

---

## 3. Add the Following Content to `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Casey’s GitHub Pages</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 5em;
      background-color: #f0f4f8;
      color: #0d47a1;
    }
    h1 {
      font-size: 2.5em;
    }
    p {
      font-size: 1.2em;
      color: #333;
    }
  </style>
</head>
<body>
  <h1>Hello World 👋</h1>
  <p>Welcome to Casey’s GitHub Pages site!</p>
</body>
</html>
```

---

## 4. Save and Commit Changes

```bash
git add index.html
git commit -m "Add initial GitHub Pages site"
git push origin main
```

---

## 5. Enable GitHub Pages

1. Go to **Settings → Pages**.  
2. Under **Source**, select:
   - **Branch:** `main`
   - **Folder:** `/root`  
3. Click **Save**.

---

## 6. Visit Your Website

After a couple of minutes, your site will be live at:  
[https://caseycontreras.github.io](https://caseycontreras.github.io)

---

## 7. Optional: Full GitHub Pages Documentation

For more details, visit the official GitHub Pages quickstart guide:  
[https://docs.github.com/en/pages/quickstart](https://docs.github.com/en/pages/quickstart)

---

## 8. Enable Deployment from a Branch (Optional Extra Step)

1. Go to **Settings → Pages**.  
2. Under **Build and deployment**, select **Deploy from a branch**.  
3. Choose the branch (e.g., `main`) and folder (e.g., `/root`).  
4. Click **Save**.  
5. Wait a few minutes for the site to be deployed.
