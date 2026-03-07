# 👟 Nike Store UI Clone

A learning project — building a Nike online store layout using **HTML + CSS**.  
It includes three pages: a homepage, a product catalog, and a login/registration form.  
All styles are stored in a single file `one.css`.

## 📂 Project Structure
- `index.html` — homepage (banner, Air Max section, gallery, footer)
- `men.html` — product catalog (cards with prices and descriptions)
- `registr.html` — login/registration form
- `one.css` — global styles
- `/images` — logos, product images, icons

## ✨ Main Sections
### Homepage (`index.html`)
- Header with navigation and search
- Hero banner featuring **Nike Air Max Pulse**
- *Best of Air Max* section (product cards)
- *The Essentials* gallery
- Footer with useful links and social media

### Catalog (`men.html`)
- Category filter (Shoes, Tops, Hoodies, etc.)
- Product grid:
  - **Nike Air Force 1 Mid '07** — ₹10,795
  - **Nike Court Vision Low Next Nature** — ₹4,995
  - **Air Jordan 1 Elevate Low** — ₹11,895
  - and more
- Each card includes: image, name, category, color options, price

### Registration (`registr.html`)
- Login form:
  - Fields: *Login*, *Password*
  - Checkbox: *Keep me signed in*
  - Link: *Forgotten your password?*
- **Submit** button
- Text with Nike’s Privacy Policy and Terms of Use
- Footer with navigation and social media

## 🎨 Styles (`one.css`)
- **Fonts**: Merriweather, Oswald, Titan One (Google Fonts)
- **Variables**: `--color-bg`, `--color-primary`
- **Layout & Containers**:
  - `.container` — max width 1200px
  - `.grid-footer` — footer grid (3 columns + social block)
  - `.container-card` — product grid (3 columns)
- **Navigation**:
  - `.menu` — horizontal menu with spacing
  - `.marker` — search and icons block
- **Core Sections**:
  - `.apg` — banner image
  - `.one` — central block with title and buttons
  - `.card` and `.like` — product cards and gallery
- **Registration Form**:
  - `.registr` — centered form
  - `.block` — form container
  - `.group` — input fields
  - `.btn` — submit button
  - `.part` — checkbox + link
- **Responsive Design**:
  - Media query for screens ≥768px (larger titles, grid adjustments)
 
  -  https://d11per.github.io/Nike-Storefront-Clone/

