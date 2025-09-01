````
# 🎂 Happy Birthday Webpage 🎉

A fun **HTML + CSS Birthday Greeting Page** with:  
- Floating balloons 🎈  
- Personal message 💌  
- Photo gallery 📸  
- Background music 🎶  

Make your friend’s (or your crush’s 😉) birthday unforgettable with a custom-made webpage instead of a boring WhatsApp forward.

---

## ✨ Features
- 🎨 **Animated Background** → Gradient colors with floating balloons.  
- 📜 **Personal Message Section** → Add your custom text.  
- 📸 **Photo Gallery** → Add multiple images of your choice.  
- 🎶 **Background Music** → Auto-plays your selected `.mp3`.  
- 💻 **Lightweight** → Runs in any browser, no dependencies.  

---

## 🚀 Getting Started

### 1️⃣ Clone this repo
```bash
git clone https://github.com/your-username/happy-birthday-page.git
cd happy-birthday-page
````

### 2️⃣ Open in browser

Simply double-click on `index.html` or open it in Chrome/Edge/Firefox.
That’s it. No servers, no frameworks. Just pure HTML/CSS magic.

---

## 🎨 Customization Guide

### 📝 Change the name

Find this line inside `index.html`:

```html
<h1>Happy Birthday, Name!</h1>
```

Replace `Name` with your friend’s name.

---

### 📸 Add Your Own Photos

Find the **photo gallery section** in the HTML:

```html
<div class="photos">
  <div class="photo" style="background-image: url('link');"></div>
  <div class="photo" style="background-image: url('link');"></div>
  <div class="photo" style="background-image: url('link');"></div>
</div>
```

Replace `'link'` with the **direct image link** or your local image file:

```html
<div class="photo" style="background-image: url('images/friend1.jpg');"></div>
```

💡 Pro tip: Create an `images/` folder in your repo and store photos there.

---

### 🎶 Add Custom Music

Find this block:

```html
<audio autoplay loop>
  <source src="happy-birthday.mp3" type="audio/mpeg">
</audio>
```

Replace `happy-birthday.mp3` with the path to your own `.mp3` file:

```html
<source src="music/party-song.mp3" type="audio/mpeg">
```

💡 Keep your music inside a `music/` folder for organization.
⚠️ Browser won’t autoplay music if muted by user’s system settings.

---

### 🎈 Customize Balloons

Find balloon elements:

```html
<div class="balloon" style="top: 90%; left: 20%; animation-delay: 0s;"></div>
```

* Change `top`/`left` values → control spawn position.
* Change `background: #hex;` → different balloon colors.
* Add more `<div class="balloon">...</div>` for extra balloons.

---

## 📂 Suggested File Structure

```
happy-birthday-page/
│── index.html
│── style.css   (optional, if you split CSS out)
│── images/
│    ├── friend1.jpg
│    ├── friend2.jpg
│── music/
│    ├── happy-birthday.mp3
```

---

## 🌍 Deploy & Share

Want to send it to your friend? Host it for free:

1. Push to GitHub
2. Go to **Settings → Pages → Deploy from branch → main → /root**
3. GitHub will give you a public link like:

   ```
   https://your-username.github.io/happy-birthday-page/
   ```

Now send that link as your digital birthday gift 🎁.

---

## 📸 Demo Screenshot

![Birthday Page Preview](https://via.placeholder.com/800x400?text=Your+Screenshot+Here)

---

## 💡 Ideas to Make It Cooler

* Add confetti animation 🎊
* Add a countdown timer ⏳ until midnight
* Add personal video background 🎥
* Use multiple songs with a playlist 🎶

---

## 🖤 Author

Built with love (and too much coffee ☕).
If you fork this, at least star ⭐ the repo, don’t ghost like your crush.

---


---

```

