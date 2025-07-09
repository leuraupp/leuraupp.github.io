# Leonardo Raupp - Game Developer Portfolio

Personal portfolio showcasing Unity projects and game development experience.

## 📁 Project Structure

```
leuraupp.github.io/
├── index.html              # Main portfolio page
├── assets/
│   └── images/             # All images and media files
│       ├── profile-photo.jpg
│       ├── monsters-and-soldiers.gif
│       └── project-2.gif
├── games/                  # WebGL games (playable)
│   └── [game-name]/
│       ├── index.html
│       ├── Build/
│       └── TemplateData/
└── README.md
```

## 🖼️ Adding Images

### Profile Photo
- **File**: `assets/images/profile-photo.jpg`
- **Recommended size**: 400x400px (will be displayed as 200x200px)
- **Format**: JPG, PNG, or WebP
- **Description**: Your professional headshot

### Project Images/GIFs
- **Files**: `assets/images/project-name.gif`
- **Recommended size**: 800x600px or similar aspect ratio
- **Format**: GIF (for animations), JPG, PNG, or WebP
- **Description**: Screenshots or gameplay GIFs of your projects

## 🎮 Adding WebGL Games

### Game Structure
1. **Create a folder** in `games/` with your game name (e.g., `games/my-awesome-game/`)
2. **Copy your WebGL build** into this folder
3. **Ensure the main file** is named `index.html`

### Example Structure
```
games/
└── my-awesome-game/
    ├── index.html          # Main game file
    ├── Build/              # Unity WebGL build files
    ├── TemplateData/       # Unity template data
    └── favicon.ico         # Game icon (optional)
```

### Updating the Portfolio
1. **Update the game section** in `index.html`:
   - Change `[Nome do Jogo]` to your game name
   - Update `games/[nome-do-jogo]/index.html` to your game path
   - Add game description and controls

### Unity WebGL Build Settings
- **Target Platform**: WebGL
- **Compression Format**: Disabled (for faster loading)
- **Development Build**: Unchecked (for production)
- **Template**: Default (or custom if needed)

## 🚀 Deployment

This portfolio is deployed on GitHub Pages at: `https://leuraupp.github.io`

## 🛠️ Technologies Used

- HTML5
- CSS3 (with modern features like CSS Grid, Flexbox, and CSS Variables)
- JavaScript (vanilla)
- Bootstrap 5
- Font Awesome Icons
- Google Fonts (Poppins)
- Unity WebGL

## 📝 How to Update

1. Add your images to the `assets/images/` folder
2. Add your WebGL games to the `games/` folder
3. Update the image paths and game paths in `index.html` if needed
4. Commit and push to GitHub
5. GitHub Pages will automatically update your site

## 🎨 Customization

The portfolio uses CSS variables for easy customization. Main colors are defined in the `:root` section of the CSS.

## 🎯 Features

- **Responsive Design**: Works on all devices
- **Playable Games**: Direct WebGL game integration
- **Modern UI**: Dark theme with gradients and animations
- **Smooth Scrolling**: Enhanced navigation experience
- **SEO Optimized**: Proper meta tags and structure 