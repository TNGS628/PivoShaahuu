# 🍺 Beer Time Website

A fun, interactive website to invite someone for a beer! The "Nah" button shrinks while the "HELL YEAH!" button grows with each click, making it harder to say no!

## ✨ Features

- Animated beer mug buttons with foam and bubbles
- Rising bubble background animation
- Interactive buttons that change size dynamically
- Persuasive text changes when clicking "Nah"
- Toast celebration animation when "HELL YEAH!" is clicked
- Fully responsive design for mobile and desktop
- Smooth animations and beer-themed effects

## 🚀 Deploy to GitHub Pages

### Option 1: Quick Deploy (Easiest)

1. **Create a new GitHub repository**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it something like `beer-invitation` or `grab-a-beer`
   - Keep it public (or private if you have GitHub Pro)

2. **Upload the file**
   - Click "uploading an existing file" link
   - Drag and drop the `index.html` file (rename `beer-index.html` to `index.html`)
   - Commit the changes

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Select `main` branch and `/ (root)` folder
   - Click Save

4. **Access your site**
   - Your site will be live at: `https://YOUR-USERNAME.github.io/REPO-NAME/`
   - It may take 1-2 minutes to deploy

### Option 2: Using Git (Command Line)

```bash
# Create a new repository on GitHub first, then:

git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
cd REPO-NAME

# Rename and copy the file
cp beer-index.html index.html

git add index.html
git commit -m "Add beer invitation website"
git push origin main

# Then enable GitHub Pages in repository settings
```

### Option 3: Using GitHub Desktop

1. Create a new repository in GitHub Desktop
2. Rename `beer-index.html` to `index.html`
3. Add the `index.html` file to the repository folder
4. Commit and push to GitHub
5. Enable GitHub Pages in repository settings

## 📱 Sharing Your Site

Once deployed, share the link with your buddy:
- `https://YOUR-USERNAME.github.io/REPO-NAME/`

You can also:
- Shorten the URL using [bit.ly](https://bitly.com) or similar services
- Send via text, email, or social media
- Share in group chats

## 🎨 Customization

Feel free to customize the website by editing the HTML file:

- **Colors**: Change the gradient colors in the `background` CSS property
- **Text**: Modify the question text and success message
- **Button behavior**: Adjust the shrinking/growing speed in the JavaScript
- **Emojis**: Replace with your favorite beer emojis
- **Fonts**: Change the Google Fonts imported at the top
- **Beer mug style**: Modify the glass colors and foam effects

## 💡 Tips

- Test the site locally by opening the HTML file in your browser
- The "Nah" button becomes progressively harder to click
- After several "Nah" clicks, the button starts fading
- The site is fully responsive and works on phones
- Beer mugs have animated bubbles inside!

## 🍻 Have Fun!

Cheers and enjoy your beer with your buddy! 

---

Made with 🍺 and a little bit of friendly persuasion
