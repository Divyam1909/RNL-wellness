# 🌿 Ritesh Natural Life Wellness

A modern, responsive e-commerce website for Ayurvedic and herbal wellness products.

![Ayurveda](https://img.shields.io/badge/Ayurveda-Wellness-2F5233?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- **🛒 Shopping Cart** - Add products, adjust quantities, and place orders via WhatsApp
- **🔍 Search & Filter** - Search products by name or filter by category
- **🌙 Dark Mode** - Toggle between light and dark themes with preference saved
- **📱 Responsive Design** - Works beautifully on mobile, tablet, and desktop
- **💬 WhatsApp Integration** - Direct order placement and consultation via WhatsApp
- **👤 User Info Collection** - Collects customer name and age before order submission
- **🎨 Modern UI** - Glassmorphism effects, golden accents, and smooth animations

## 🏷️ Product Categories

- 💪 **Immunity** - Curcumin, Neem, Tulsi
- 🌱 **Energy & Vitality** - Moringa, Eco Ensulin, Anjalika
- 🧘 **Stress Relief** - Ashwagandha
- 🍃 **Detox & Cleanse** - Wheat Grass, Spirulina
- ✨ **Skin & Beauty** - Sea Buckthorn, Haridra
- 🫚 **Digestive Health** - Aloevera, Herbal Infusion

## 🚀 Quick Start

1. Clone the repository
```bash
git clone https://github.com/yourusername/RNL-wellness.git
```

2. Open `index.html` in your browser, or start a local server:
```bash
python -m http.server 8080
```

3. Visit `http://localhost:8080`

## 📁 Project Structure

```
RNL-wellness/
├── index.html          # Main website
├── drive-converter.html # Google Drive link converter tool
└── README.md           # This file
```

## ⚙️ Configuration

Edit the configuration section in `index.html` to customize:

```javascript
// WhatsApp Phone Number (Country code + Number, no + sign)
const WA_PHONE = "919661660000"; 

// Custom Messages
const MSG_ORDER_PREFIX = "Namaste Dr. Ritesh, I would like to place an order...";
const MSG_CONSULT = "Namaste, I am browsing your catalog...";

// Currency Symbol
const CURRENCY = "₹";
```

## 🛠️ Tools Included

### Google Drive Image Converter
A utility tool (`drive-converter.html`) to convert Google Drive share links to direct embeddable image URLs.

**Supported formats:**
- `https://drive.google.com/file/d/FILE_ID/view?usp=sharing`
- `https://drive.google.com/open?id=FILE_ID`

**Output format:**
- `https://lh3.googleusercontent.com/d/FILE_ID`

## 🎨 Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** (CDN) - Utility-first styling
- **Lucide Icons** - Beautiful icon set
- **Vanilla JavaScript** - No framework dependencies
- **Google Fonts** - Merriweather & Open Sans

## 📱 WhatsApp Order Flow

1. Customer browses products and adds to cart
2. Customer clicks "Place Order on WhatsApp"
3. Popup collects customer name and age
4. Order details formatted and sent via WhatsApp
5. Business receives complete order with customer info

## 🌐 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge

## 📄 License

This project is proprietary to Ritesh Natural Life Wellness.

---

<p align="center">
  Made with 💚 for natural wellness
</p>
