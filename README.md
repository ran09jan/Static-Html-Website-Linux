# Static HTML Website (Linux)

This repository contains a static HTML website that can be deployed on a Linux server using the Apache2/httpd service.
It includes HTML, CSS, JavaScript, and image assets to serve a complete static web page.


## 📦 Project Structure

```plaintext
.
├── images/                          # Image assets used in the site
├── index.html                      # Main HTML file (entry point)
├── templatemo-3d-coverflow.css      # Stylesheet for layout/design
├── templatemo-3d-coverflow-scripts.js # JavaScript for interactive behavior
└── README.md                       # This file                   


## 🚀 Features

* Pure **HTML, CSS & JavaScript** based website
* Designed as a **static web page** deployed using Linux httpd service
* Easy to host locally or on any static web server
  (This type of static architecture is ideal for simple informational sites, landing pages or portfolios)

## 🛠️ Setup & Deployment

You can serve this site **locally** or on a **Linux web server** like Apache:

### 💻 Locally

Use any static HTTP server, for example:

### 🐧 On Linux (Apache httpd)

1. **Install Apache**

```sh
sudo apt update
sudo apt install apache2
```

2. **Copy the site files** to web root (e.g., `/var/www/html`):

```sh
sudo cp -r * /var/www/html/
```

3. **Restart Apache**

```sh
sudo systemctl restart apache2
```

Now the site should be visible at `http://localhost`.

## 📌 Notes

* This is a **static site** — no backend required.
* You can also deploy it for free using **GitHub Pages**, which serves HTML/CSS/JS from your repository automatically (great for static sites like this). 

