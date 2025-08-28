# 🍳 Recipe Remix Hub

**Transform your ingredients into delicious recipes instantly!**

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://ace1440.github.io/Recipe-Remix-Hub/)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue)](https://pages.github.com/)

## 🌟 Features

- **🥘 Instant Recipe Generation** - Enter your ingredients and get recipes immediately
- **💾 Save Recipes** - Keep your favorite recipes for later
- **📱 Mobile Responsive** - Works perfectly on all devices
- **🎨 Beautiful Design** - Modern black and light blue theme
- **⚡ Fast Performance** - No loading delays, instant results
- **🔒 Privacy Focused** - All data stored locally in your browser
- **Shopping List Generator**: Auto-generate shopping lists for missing ingredients
- **User-Friendly Interface**: Clean, responsive design optimized for all devices

## Tech Stack

- **Frontend**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Modern CSS with CSS Grid and Flexbox
- **Icons**: Emoji-based iconography for better accessibility

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository or download the project files
2. Navigate to the project directory
3. Install dependencies:

```bash
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

Open your browser and visit `http://localhost:5173` to see the application.

### Building for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
src/
├── components/           # React components
│   ├── Header.tsx       # App header with branding
│   ├── IngredientInput.tsx  # Ingredient input form
│   └── RecipeDisplay.tsx    # Recipe cards and display
├── App.tsx              # Main application component
├── App.css              # Component styles
├── main.tsx             # React application entry point
└── index.css            # Global styles and CSS variables
```

## Features in Detail

### Ingredient Input
- Add ingredients one by one
- Visual ingredient tags with remove functionality
- Form validation and duplicate prevention
- Responsive design for mobile devices

### Recipe Display
- Loading states with animated spinner
- Recipe cards with difficulty indicators
- Cooking time display
- Ingredient availability highlighting
- Action buttons for shopping lists and saving

### Styling
- Modern CSS with custom properties (CSS variables)
- Responsive design with CSS Grid and Flexbox
- Smooth animations and hover effects
- Accessible color scheme with proper contrast

## Future Enhancements

- Integration with actual recipe APIs
- User authentication and saved recipes
- Shopping list management
- Recipe rating and reviews
- Video tutorial integration
- Dietary restriction filters
- Nutritional information display

## Contributing

Feel free to contribute to this project by:
- Adding new features
- Improving the UI/UX
- Fixing bugs
- Adding tests
- Improving documentation

## License

This project is open source and available under the MIT License.
