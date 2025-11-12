# 🎧 Pick Your Favorite Rapper & Album

A modern, interactive two-page website where users can choose their favorite rapper and then select one of their albums.

## 🌟 Features

- **Two-Page Flow**: Select a rapper, then choose from their albums
- **Modern Design**: Dark theme with vibrant hover effects and smooth transitions
- **Responsive Grid Layout**: Works on all screen sizes
- **No Dependencies**: Pure HTML, CSS, and JavaScript
- **GitHub Pages Ready**: Single `index.html` file with embedded styles and scripts

## 🎵 Artists & Albums

### Travis Scott
- Astroworld
- Rodeo
- Utopia

### Drake
- Take Care
- Scorpion
- Views

### Kanye West
- Graduation
- Donda
- The College Dropout

### Kendrick Lamar
- DAMN.
- To Pimp a Butterfly
- Mr. Morale & The Big Steppers

## 📁 Project Structure

```
Album/
├── index.html          # Main website file
├── README.md          # This file
└── images/            # Image folder (you need to create this)
    ├── travis.jpg
    ├── drake.jpg
    ├── kanye.jpg
    ├── kendrick.jpg
    ├── astroworld.jpg
    ├── rodeo.jpg
    ├── utopia.jpg
    ├── takecare.jpg
    ├── scorpion.jpg
    ├── views.jpg
    ├── graduation.jpg
    ├── donda.jpg
    ├── collegedropout.jpg
    ├── damn.jpg
    ├── tpab.jpg
    └── mmbs.jpg
```

## 🖼️ Adding Your Images

1. **Create an `images` folder** in the same directory as `index.html`:
   ```bash
   mkdir images
   ```

2. **Add rapper images** (4 files):
   - `travis.jpg` - Travis Scott photo
   - `drake.jpg` - Drake photo
   - `kanye.jpg` - Kanye West photo
   - `kendrick.jpg` - Kendrick Lamar photo

3. **Add album cover images** (12 files):

   **Travis Scott:**
   - `astroworld.jpg`
   - `rodeo.jpg`
   - `utopia.jpg`

   **Drake:**
   - `takecare.jpg`
   - `scorpion.jpg`
   - `views.jpg`

   **Kanye West:**
   - `graduation.jpg`
   - `donda.jpg`
   - `collegedropout.jpg`

   **Kendrick Lamar:**
   - `damn.jpg`
   - `tpab.jpg`
   - `mmbs.jpg`

4. **Image Recommendations**:
   - Format: JPG or PNG
   - Recommended size: 500x500px for square images
   - Keep file sizes reasonable (< 500KB each) for fast loading

## 🚀 Deployment to GitHub Pages

1. **Make sure all files are committed**:
   ```bash
   git add .
   git commit -m "Add rapper and album selection website"
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll to **Pages** section
   - Under **Source**, select the branch (usually `main`)
   - Click **Save**

3. **Access your site**:
   - Your site will be available at: `https://[username].github.io/Album/`
   - It may take a few minutes to deploy

## 💻 Local Testing

To test the website locally:

1. Open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000

   # Python 2
   python -m SimpleHTTPServer 8000
   ```
3. Navigate to `http://localhost:8000`

## 🎨 Design Features

- **Gradient backgrounds** and text effects
- **Smooth hover animations** with scale and shadow effects
- **Fade-in transitions** between pages
- **Responsive grid** that adapts to screen size
- **Glass morphism** card design with backdrop blur
- **Fallback text** if images fail to load

## 🛠️ Customization

### Adding More Rappers

Edit the `rappers` object in the JavaScript section of `index.html`:

```javascript
const rappers = {
    newRapper: {
        name: "Rapper Name",
        albums: [
            { name: "Album 1", image: "images/album1.jpg" },
            { name: "Album 2", image: "images/album2.jpg" },
            { name: "Album 3", image: "images/album3.jpg" }
        ]
    }
};
```

Then add a new card in the rapper grid HTML section.

### Changing Colors

Modify the CSS gradient values in the `<style>` section:
- Main gradient: `background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);`
- Accent colors: `#4ecdc4`, `#667eea`, `#764ba2`

## 📝 License

Feel free to use and modify this project as needed!

## 🙋 Support

If you encounter any issues, make sure:
- All image files are in the `images/` folder
- Image file names match exactly (case-sensitive)
- The `index.html` file is in the root directory
