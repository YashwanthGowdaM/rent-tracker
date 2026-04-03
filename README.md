# 🏠 Rent Payment Tracker

Personal rent tracker with auto-loading photo gallery from the same repo.

## 📁 Repo Structure

```
your-repo/
├── index.html      ← Main website
├── config.js       ← Edit this once with your GitHub username & repo name
├── photos/         ← Drop receipt images here — appear on site automatically
│   ├── aug-2024.jpg
│   └── sep-2024.png
└── README.md
```

## 🚀 One-time Setup

### 1. Edit config.js
Open `config.js` and fill in your details:
```js
window.REPO_OWNER  = "john";          // your GitHub username
window.REPO_NAME   = "rent-tracker";  // your repo name
```

### 2. Create the photos folder
In GitHub, create a folder called `photos/` and upload at least one image.

### 3. Deploy on Vercel
vercel.com → New Project → Import your GitHub repo → Deploy. Done.

## 📸 Adding New Photos
Just upload any image to the `photos/` folder on GitHub.
The site fetches them automatically on every visit — no code changes needed.

Supported: `.jpg` `.jpeg` `.png` `.gif` `.webp`
