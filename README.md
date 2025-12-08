# Şahî Chess & Shatranj Font (chess piece icon set)
A culturally inclusive, educational, and cross-platform SVG icon font for chess, shatranj, and historic variants.
ŞAHÎ (SHAHI) chess/shatranj icons - available free for personal or commercial use with no-modification, no-derivatives, no-removal-of-branding license

The **Şahî (Shahi) Font** is a vector-based chess & shatranj piece set designed by **Tamer Karatekin** (DeepSeaChess LLC).  
It combines modern clarity with historical authenticity and cultural neutrality, making it suitable for:

- educational materials, including books and videos
- school programs and STEAM curricula  
- chess & shatranj software  
- websites and game engines  
- Lichess-compatible variants  
- academic, cultural, and historical presentations
- online tournament broadcasting, social media posting

This repository contains the original, unmodified SVG and font files in **versioned folders** (`v1/` and `v2/`).

---

## ✨ Design Philosophy

The Şahî (Shahi) Font is built on four core principles:

### 1. Cultural and Spiritual Inclusivity
The designs intentionally avoid sectarian or religious symbolism, presenting chess imagery in a universal, welcoming form. This supports multilingual, multicultural, and multi-faith educational environments and reflects the global heritage shared by chess players in Europe, Asia, Africa, and beyond.

### 2. Historical Authenticity
The artwork draws inspiration from a broad spectrum of historic chess traditions, including:
- early shatranj and Middle Eastern – Central Asian designs,
- medieval and Renaissance European chess sets,
- archaeological and museum-documented piece styles from multiple regions.

While historically grounded, each icon is refined for clarity, readability, and consistency in modern digital usage. For example, the rook piece has been historically called 4 different names: chariot, tower, cannon, boat. The design of the Şahî (Shahi) rook physical piece and its corresponding icon have elements of the wheel from the chariot, bricks from the tower, barrel of a cannon, and the anchor of a boat. The vizier piece has a military helmet as the commander of the army, which can also be viewed as the tip of a pen of a statesman. The shah piece has the dome under the which the ruler lives and its wise headwrap, which looks like a rose with petals, symbolizing life and fragility of the shah (king) piece. The elephant piece is inspired by the Charlemagne-Abbas elephant.

### 3. Modern Utility
The vector-based SVG format and clean outlines ensure compatibility with:
- online chess platforms and real-time game interfaces,
- websites and front-end frameworks,
- mobile and desktop applications,
- game engines and graphical toolkits,
- software that uses scalable icon systems.

The font is optimized for on-screen display, retaining shape clarity at any resolution.

### 4. Educational Purpose
The Şahî Font is used across the Shatranj.ai curriculum and STEAM programs that connect chess logic with mathematics, coding, and artificial intelligence. It supports teachers, researchers, and curriculum designers who require culturally neutral and historically informed visual material.

---

## 📦 Repository Structure

```text
shahi-chess-shatranj-font/
│
├── LICENSE.txt
│
├── shahi-ivory-brown/              # Theme 1: Ivory vs Brown pieces
│   └── svg/
│       ├── shah-ivory.svg
│       ├── vizier-ivory.svg
│       ├── rukh-ivory.svg
│       ├── elephant-ivory.svg
│       ├── horse-ivory.svg
│       ├── pawn-ivory.svg
│       ├── shah-brown.svg
│       ├── vizier-brown.svg
│       ├── rukh-brown.svg
│       ├── elephant-brown.svg
│       ├── horse-brown.svg
│       └── pawn-brown.svg
│
├── shahi-black-white/              # Theme 2: Black vs White pieces
│   └── svg/
│       ├── shah-white.svg
│       ├── vizier-white.svg
│       ├── rukh-white.svg
│       ├── elephant-white.svg
│       ├── horse-white.svg
│       ├── pawn-white.svg
│       ├── shah-black.svg
│       ├── vizier-black.svg
│       ├── rukh-black.svg
│       ├── elephant-black.svg
│       ├── horse-black.svg
│       └── pawn-black.svg
│
└── previews/                       # (optional) PNG sample images
```

---

## 🖼 Preview (recommended)

You can include PNG previews of the pieces here:

```
previews/
   rook.png
   elephant.png
   horse.png
```

This helps developers understand the style at a glance.

---

## 🔤 Naming & Terminology

The Şahî Font supports both:

### • Modern International Chess  
(King, Queen, Rook, Bishop, Knight, Pawn)

### • Historical Shatranj / Cultural Terminology  
Preferred English teaching terms used by the creator:

- **Shah** → King  
- **Vizier** → Queen  
- **Rook** → Rook  
- **Elephant** → Bishop  
- **Horse** → Knight  
- **Pawn** → Pawn  

These names reflect common usage across world languages and highlight the non-sectarian origins of chess.

For more detail, see Section 12 of the license. Full license:  
See [LICENSE.txt](LICENSE.txt) for complete terms.


---

## 📥 Installation & Usage

### Use as SVG icons  
Copy any SVG from `v1/svg/` or `v2/svg/` directly into your project.

### Use as a web font  
Example:

```html
<link rel="stylesheet" href="shahi.ttf">

<i class="shahi shahi-rook"></i>
```

(You can generate your own CSS class mapping based on the codepoints.)

### Use in apps  
- Import the TTF/WOFF2 font  
- Map glyphs to UI icons  
- Ensure no modification of SVG paths (required by license)

---

## 📜 License Summary  

The Şahî Font is **free for personal, educational, non-profit, and commercial use**, as long as the files remain **unmodified**.

Key points from the full license:

- **No modification** of the vector artwork  
- **No derivative fonts**  
- **No removal of branding or metadata**  
- **No AI training datasets**  
- **Redistribution allowed only unmodified**  
- **Physical Şahî Chess Set is a separate copyrighted work**  
- **Cultural terminology is recommended but not required**  

Full license:  
See [LICENSE.txt](LICENSE.txt) for complete terms.


---

## 🌐 Related Projects & Links

- **Şahî Master Set (Physical Chess Set):**  
  https://www.shahimasterset.com  

- **Design Philosophy & Cultural Background (TEDx Talk):**  
  “Chess: Bridging Cultures, Inspiring AI, and Redefining Education”  
  https://www.youtube.com/watch?v=BDLiXo_acLg  

- **Shatranj Curriculum Project:**  
  https://www.shatranj.ai  

- **DeepSeaChess:**  
  https://www.deepseachess.com/shahi  

---

## 🤝 Contributing

Because this is a protected artwork project, **modifications and pull requests altering the icons cannot be accepted**.

However:

- bug reports,  
- documentation updates,  
- educational integrations, and  
- usage examples  

are always welcome.

---

## 💬 Contact

For licensing questions or usage permissions:

**Tamer Karatekin**  
DeepSeaChess LLC  
www.deepseachess.com/shahi  
www.shahimasterset.com  

---

If you'd like, I can:

• insert your preview images once you upload them  
• generate CSS mapping for the font  
• generate a `package.json` for npm distribution  
• write a “How to use in Lichess” section  

Just tell me!
