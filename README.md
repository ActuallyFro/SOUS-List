# 🍽️ SOUS List - Simplified Order Utility for a Shopping List

A web-based meal planning and grocery list generator that helps you organize your weekly dinners and create consolidated shopping lists.

## 🌐 Live Demo

**[Launch SOUS List App](https://actuallyfro.github.io/SOUS-List/)**

## ✨ Features

### 📖 Dinner Dictionary
- Create and manage your collection of favorite meals
- Add detailed ingredients with:
  - Item name
  - Category (customizable)
  - Quantity
  - Aisle number
- Specify cooking method (Griddle, Oven, Slow Cooker, Grill/Griddle, etc.)
- Edit or delete meals anytime

### 📅 Weekly Planner
- Plan up to 26 days of meals (A-Z)
- Add/remove days dynamically
- **Expandable ingredient view** for each day:
  - Mark items you already have
  - Add custom quantities per meal
  - Add personal notes for specific ingredients
- **Quick Add**: Select ingredients from your dictionary and add them to the shopping list
- **New Custom Item**: Add one-off items not in your dictionary

### 🛒 Shopping List Generation
- Generates markdown-formatted shopping lists
- Automatically consolidates duplicate ingredients across meals
- Visual indicators:
  - `||✅||` for items you need
  - `✅` for items you already have
- Includes:
  - Quantities
  - Aisle numbers
  - Personal notes
  - Meal tags (which meals use each ingredient)

### ⚙️ Settings
- **Manage Categories**: Customize grocery categories to match your store's layout
- **Import/Export**: Backup and restore your data as JSON files
- **Versioned Exports**: Add version labels to your backups (auto-dated: `SOUS-List_VERSION_YYYY-MM-DD.json`)
- **Reset**: Clear all data and start fresh

## 🚀 Getting Started

### Online Use
Simply visit **[https://actuallyfro.github.io/SOUS-List/](https://actuallyfro.github.io/SOUS-List/)** - no installation required!

### Local Use
1. Clone this repository:
   ```bash
   git clone https://github.com/ActuallyFro/SOUS-List.git
   ```
2. Open `index.html` in your web browser
3. Start planning your meals!

## 💾 Data Storage

All data is stored locally in your browser using `localStorage`. Your data includes:
- Meal definitions
- Weekly meal plans
- One-off shopping items
- Custom categories
- Day count preferences

**Note**: Data is tied to your browser and device. Use the Export feature to backup or transfer your data.

## 📋 Default Categories

The app comes pre-configured with these categories:
- Boxes/aisles
- Frozen
- Chilled
- Produce
- Breads
- Lunches/snack
- Spices

You can add, edit, or remove categories in the Settings tab.

## 🎯 Usage Tips

1. **Start with the Dinner Dictionary**: Add all your favorite meals and their ingredients
2. **Plan Your Week**: Use the Weekly Planner to select meals for each day
3. **Expand & Customize**: Click the `+` button next to each day to:
   - Adjust quantities for that specific meal
   - Mark items you already have
   - Add special notes (e.g., "get organic", "on sale")
4. **Add Extras**: Use Quick Add or New Custom Item for non-meal items
5. **Generate & Shop**: Click "Generate Markdown Shopping List" and copy the formatted list

## 📱 Mobile Friendly

SOUS List is fully responsive and works great on phones and tablets - perfect for shopping on the go!

## 🤝 Contributing

Found a bug or have a feature suggestion? Feel free to:
- Open an issue on GitHub
- Submit a pull request
- Fork the project and make it your own!

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

Built with vanilla JavaScript, HTML, and CSS - no frameworks required!

---

**Happy Meal Planning! 🎉**
