# 🐻 Cub 
## Small, self-hosted bear

A tiny, self-hostable blogging system inspired by [Bear Blog](https://bearblog.dev/).  
Zero JavaScript. No tracking. No bloat. Just words.

---

## ✨ About

**Cub** is a minimalist, static-style blog generator built with **Flask**.  
It lets you write posts in Markdown and publish a clean, fast, privacy-friendly blog that you can host anywhere.

Think of it as a self-hosted alternative inspired by Bear Blog’s simplicity.

> ⚠️ Note: [Bear Blog](https://bearblog.dev/) is doing incredible work as a hosted platform - 
> if you don’t need self-hosting, you should definitely consider using Bear itself.

---

## 🧱 Features (v1)

- Markdown → HTML rendering  
- Minimal CSS (inline, no external files)  
- Automatic index page  
- Zero JavaScript  
- No database — posts are files  
- Can serve locally or export static HTML  

---

## 🗂️ Folder structure

cub/
├── app.py
├── content/
│ ├── first-post.md
│ └── about.md
├── templates/
│ ├── base.html
│ └── post.html
├── static/ # optional assets
├── config.yaml
├── README.md
└── requirements.txt

---

## 🚀 Usage

```bash
# 1. Clone repo
git clone https://github.com/Siddharth1India/cub.git
cd cub

# 2. Install deps
pip install -r requirements.txt

# 3. Run local server
python app.py

# 4. Visit
http://127.0.0.1:5000
