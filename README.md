# Aroma of Jasmine — Royal Nizami Gastronomy Website

A website for **Aroma of Jasmine** (Donthanpalle, Shankarpalli – Hyderabad Road, near IBS campus, Telangana 501203).

Built following the **Royal Dusk** design system, featuring deep obsidian charcoal tones (`#11100E`), antique burnished brass/gold (`#C9A45C`), warm saffron highlights (`#C87532`), and unbleached jasmine silk cream (`#F4EBDD`).

---

## 🌟 Key Features

1. **Single-Page Application Architecture**:
   - **The Grand Experience (Home)**: High-impact hero section with authentic spice ethos, pure single-origin standards, Nizam's private selection, interactive sanctuary architecture gallery, and instant WhatsApp table reservation strip.
   - **The Culinary Menu (116 Handcrafted Items)**: Complete catalog categorized into:
     - *Biryani, Pulao & Rice (17 items)* (Veg Pulao, Veg Biryani, Paneer Biryani, Kaju Biryani, Kaju Paneer Biryani, Mushroom Biryani, Curd Rice, Plain Rice Basmathi, Tomato Rice, Plain Curd, Egg Biryani Single, Chicken Dum Biryani Single / Family / Jumbo, Mutton Biryani Single / Family / Jumbo)
     - *Veg Fried Rice (8 items)* (Veg Fried Rice, Schezwan Veg Fried Rice, Mix Veg Fried Rice, Veg Manchurian Fried Rice, Paneer Fried Rice, Chilli Garlic Veg Fried Rice, Jeera Fried Rice, Kaju Fried Rice)
     - *Non-Veg Fried Rice (7 items)* (Egg Fried Rice, Schezwan Egg Fried Rice, Chicken Fried Rice, Schezwan Chicken Fried Rice, Chilli Garlic Chicken Fried Rice, Burnt Garlic Chicken Fried Rice, Non Veg Mix Fried Rice)
     - *Veg Noodles (4 items)* (Veg Soft Noodles, Schezwan Veg Noodles, Chilli Garlic Veg Noodles, Veg Hakka Noodles)
     - *Non-Veg Noodles (8 items)* (Egg Noodles, Schezwan Egg Noodles, Egg Hakka Noodles, Chicken Soft Noodles, Schezwan Chicken Noodles, Burnt Garlic Chicken Noodles, Chicken Hakka Noodles, Mix Non Veg Hakka Noodles)
     - *Veg Starters (15 items)* (Veg Manchurian, Veg 65, Gobi Manchuria, Gobi 65, Chilli Gobi, Baby Corn Manchuria, Baby Corn 65, Chilli Babycorn, Paneer Manchuria, Chilli Paneer, Kaju Roast, French Fries, Onion Rings, Crispy Corn, Paneer 65)
     - *Non-Veg Starters (15 items)* (Chicken Manchuria, Chilli Chicken, Chicken Majestic, Chicken 65, Pepper Chicken, Chicken Chips, Dragon Chicken, Chicken 555, Butter Garlic Chicken, Kaju Nuts Chicken, Chicken Lollipop, Egg Omelette, Chicken Drumstick, Egg Manchuria, Chilli Egg)
     - *Veg Curries (18 items)* (Mix Veg Curry, Paneer Butter Masala, Kadai Paneer, Hyderabad Paneer Curry, Telangana Paneer Curry, Kaju Paneer, Kaju Curry, Alu Gobi, Kadhai Veg, Kadai Mushroom, Palak Paneer, Methi Cheman, Dal Fry, Dal Makhani, Dal Tadka, Aloo Jeera Fry, Dal Butter Fry, Gobi Masala)
     - *Non-Veg Curries (16 items)* (Dum Ka Chicken, Butter Chicken, Kadai Chicken, Telangana Chicken Curry, Andhra Chicken Curry, Afghani Chicken, Patiala Chicken, Kaju Chicken, Ginger Chicken, Chicken Masala, Chicken Fry, Mutton Masala, Mutton Fry, Mutton Rogan Josh, Egg Curry, Egg Masala)
     - *Roti's & Breads (8 items)* (Tandoori Roti, Butter Roti, Phulka, Plain Naan, Butter Naan, Garlic Naan, Chilly Garlic Naan, Kothimeera Naan)
   - **Visit, Driving Times & Reservations**: Travel time estimations from Financial District, Kokapet / Neopolis, and IBS campus; Google Maps one-click link, Highway Curbside Handi Desk, and comprehensive table reservation engine.

2. **Interactive Ordering & Tasting Slate**:
   - Slide-out Tasting Slate drawer with live cart items, quantity modifiers, and subtotal calculation.
   - **1-Click WhatsApp Ordering**: Automatically constructs an itemized message dispatched to the restaurant concierge (`+91 97000 97444`).
   - Modal dish detail viewer for every course with ingredient descriptions, serving metrics, and dietary tags.

3. **Ambient Canvas Particles**:
   - Zero-dependency, lightweight 60fps HTML5 canvas simulating warm golden embers and twilight particles.

4. **Multi-device & Mobile First**:
   - Dedicated mobile drawer navigation, sticky bottom quick-action bar for mobile devices (Menu, Reserve, Slate, Direct Call).

---

## 🚀 How to Run Locally

### Option 1: One-Click Launcher
Double-click `launch_website.bat` to instantly open `index.html` in your default browser.

### Option 2: Local HTTP Server
Run the python or node server:
```bash
python -m http.server 8000
```
Then navigate to: **http://localhost:8000**

---

## 🌐 Deploy to GitHub Pages (1-Minute Setup)

1. Create a new public repository on GitHub (e.g. `aroma-of-jasmine`).
2. Upload the files into the repository:
   - `index.html`
   - `images/` folder (containing `logo.png`)
   - `README.md`
3. In your GitHub repository:
   - Go to **Settings** → **Pages**
   - Under **Build and deployment** → **Branch**, select `main` / `/ (root)` and click **Save**.
4. Your website is immediately live at: `https://<your-username>.github.io/<repo-name>/`
