# Sidebar Navigation - Pure CSS

A beautiful, responsive sidebar navigation menu built entirely with HTML and CSS - no JavaScript required! This project demonstrates the power of CSS-only solutions using the checkbox hack technique to create interactive UI components.

## 🎯 Features

- **Pure CSS Implementation** - No JavaScript needed for toggle functionality
- **Smooth Animations** - Elegant slide-in/slide-out transitions
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Modern UI** - Clean, glassmorphic design with backdrop effects
- **Font Awesome Icons** - Beautiful icons for navigation items and social media
- **Hover Effects** - Interactive hover states for better user experience

## 🚀 How It Works

This project uses the **CSS checkbox hack** technique to create toggle functionality without JavaScript:

1. A hidden checkbox (`#check`) is used as the state controller
2. The hamburger menu button is a label that toggles the checkbox
3. CSS `:checked` pseudo-class controls the sidebar visibility
4. CSS transitions provide smooth animations

When the checkbox is checked, the sidebar slides in from the left. When unchecked (via the close button), it slides back out.

## 📁 Project Structure

```
sidebar-navigation/
├── index.html          # Main HTML file
├── style.css           # All styling and animations
├── photo.jpg           # Background image
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Advanced styling, transitions, and pseudo-classes
- **Font Awesome 6.4.0** - Icon library
- **Google Fonts (Poppins)** - Typography

## 📦 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/mantramehta/CSS-Projects.git
   ```

2. Navigate to the project directory:
   ```bash
   cd CSS-Projects
   ```

3. Open `index.html` in your web browser - that's it! No build process or dependencies required.

## 🎨 Customization

You can easily customize this sidebar by modifying the CSS variables and styles:

- **Sidebar Width**: Change the `width` property in `.sidebar_menu`
- **Colors**: Modify the `background-color` and `color` properties
- **Animation Speed**: Adjust the `transition` duration values
- **Menu Items**: Update the navigation links in `index.html`
- **Background**: Replace `photo.jpg` with your own image

## 📱 Responsive Design

The sidebar automatically adjusts for smaller screens:
- Sidebar width reduces to 250px on screens smaller than 600px
- Font sizes scale down appropriately
- All functionality remains intact

## 🔧 Browser Support

Works on all modern browsers that support:
- CSS3 transitions
- `:checked` pseudo-class
- CSS positioning

## 👤 Author

**Mantra Mehta**

- GitHub: [@mantramehta](https://github.com/mantramehta)
- LinkedIn: [mantra-mehta](https://www.linkedin.com/in/mantra-mehta/)

## 📝 License

This project is open source and available for educational purposes. Feel free to use and modify as needed.

## 🙏 Acknowledgments

- Font Awesome for the icon library
- Google Fonts for the Poppins font family

---

⭐ If you find this project helpful, consider giving it a star!

