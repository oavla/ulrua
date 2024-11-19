<p align="center">
  <img src="./banner.png" alt="Logo">
</p>

<p align="center" style="font-weight: bold; color: purple;">
  A sleek, fast, and modern proxy.
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/oavla/oav?style=social" alt="Stars">
  <img src="https://img.shields.io/github/forks/oavla/oav?style=social" alt="Forks">
  <img src="https://img.shields.io/github/issues/oavla/oav" alt="Issues">
</p>

<p align="center">
  <a href="https://pxy.oav.icu">https://pxy.oav.icu</a>
</p>

---

> [!IMPORTANT]
> you can NOT deploy this project on any static hosting site like Github Pages, Cloudflare Pages, Netlify, etc.

---

# Deploy this project:

[![Deploy to Railway](https://railway.app/button.svg)](https://railway.app/new/template?template_url=https://github.com/oavla/oav)  [![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/oavla/oav)  
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/oavla/oav)  [![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/oavla/oav)

---
---

# Setting Ulrua up on a server:

```bash
sudo git clone https://github.com/oavla/oav.git /var/www/oav

cd /var/www/oav

sh setup.sh
```

---
---

# Setting up Ulrua on Github Codespaces:

```bash
npm install express

sudo npm install pm2 -g

pm2 start index.mjs
```

When the process completes, a pop-up will appear. Click ‘Public’ to proceed.

---
---

> [!NOTE]
> Consider giving this repository a ⭐️ if you do fork and use Ulrua!
