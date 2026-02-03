# Tarun Dev Portfolio

This is a modern, responsive portfolio built with HTML, CSS, and Vanilla JavaScript, designed to showcase my projects, skills, and background as a software developer.

## 🚀 Live Website
https://SJSTARUN14.github.io/Tarun.Dev-Portfolio/

## 🛠️ Technologies Used
- HTML5 / CSS3 (Glassmorphism UI)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Inter & Poppins)

## ✨ Features
- **Dark/Light Mode**: Persistent theme selection.
- **Glassmorphism UI**: Modern aesthetic with blur effects.
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop.
- **Smooth Animations**: Intersection Observer for reveal effects.
- **Reliable Contact Form**: Integration with Web3Forms (no page reloads).

## ✉️ How to Setup the Contact Form

The form is currently set up to use **Web3Forms**. To receive messages in your inbox:

1. Go to [Web3Forms.com](https://web3forms.com/).
2. Enter your email address (`sjstarun8@gmail.com`) to receive your **Access Key**.
3. Check your inbox and copy the key.
4. Open `index.html` and find the line:
   ```html
   <input type="hidden" name="access_key" value="306a805a-b97c-4375-8e61-fb3988299694">
   ```
5. If you ever need to change the key, replace that value with your new one.

## 🚀 Deployment Instructions

### 1. GitHub Pages (Recommended)
This repository is configured with GitHub Actions for automatic deployment.
1. Push your code to the `main` branch.
2. In GitHub, go to **Settings** > **Pages** > **Build and deployment**.
3. Under **Source**, select **GitHub Actions**.
4. Your site will be live at the URL shown in the Pages settings.

### 2. Vercel
You can also deploy instantly by linking this repository to [Vercel](https://vercel.com). Any push to `main` will trigger a new production build.
