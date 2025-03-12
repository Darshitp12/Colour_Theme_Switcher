# Theme Switcher

## Overview
This project demonstrates a theme switcher that toggles between light and dark modes. It provides a smooth user experience by saving the theme preference in `localStorage`, ensuring the selected mode persists across sessions.

## Features
- Toggle between **light** and **dark** themes.
- Smooth transitions using CSS animations.
- Theme preference is stored in `localStorage`.
- Auto-detects system preference for light or dark mode.
- Responsive and accessible design.

## Technologies Used
- HTML
- CSS (CSS Variables for theming)
- JavaScript (Vanilla JS for theme switching and `localStorage`)

## Installation & Usage
1. Download or clone this repository:
   ```sh
   git clone <repository-url>
   ```
2. Open `index.html` in a web browser.
3. Use the theme toggle switch to change between light and dark mode.
4. The theme preference will be saved and applied automatically on the next visit.

## File Structure
```
📂 Theme Switcher
│── index.html  # Main HTML file
│── style.css   # Styling with CSS variables
│── script.js   # JavaScript logic for theme switching
│── README.md   # Documentation (this file)
```

## How It Works
1. **Toggling the Theme**
   - Clicking the toggle switch updates the theme and saves the preference.
2. **Saving User Preference**
   - The script stores the user's choice in `localStorage`.
3. **Auto-Detecting System Theme**
   - If no preference is saved, the system’s theme setting is applied.

## Live Demo
To host the theme switcher on GitHub Pages:
1. Push this repository to GitHub.
2. Go to **Settings** > **Pages**.
3. Select the `main` branch and save.
4. Your live demo will be available at:
   ```
   https://your-username.github.io/repository-name/
   ```

## Future Enhancements
- Add more themes (e.g., sepia, high contrast, custom colors).
- Improve animations for smoother transitions.
- Store theme settings using browser cookies.

## License
This project is open-source and free to use under the MIT License.

