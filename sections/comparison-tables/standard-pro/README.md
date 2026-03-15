# Custom Liquid Comparison Table (Pro Version)

A high-performance, merchant-friendly Shopify section designed for landing pages and product comparisons.

## 🚀 Key Technical Features
- **Fully Dynamic Schema**: Merchants can toggle between "Check" and "X" icons and edit all text directly in the Shopify Editor.
- **Namespaced Architecture**: Uses `{{ section.id }}` for all CSS classes and JS selectors to prevent style bleeding and allow multiple instances on one page.
- **Mobile-First UX**: Custom JavaScript slider with `scroll-snap` for a native app-like experience on mobile devices.
- **Performance Optimized**: Uses lightweight SVGs instead of heavy image files for icons to maintain high PageSpeed scores.

## 🛠️ How it works
The section uses a `{% for block in section.blocks %}` loop to render product columns. Each block contains a series of boolean toggles (checkboxes) that control the visibility of the "Winner" vs. "Competitor" icons.

## 📂 Installation
1. Create a new section named `comparison-table.liquid`.
2. Paste the code.
3. Customize via the Theme Editor.