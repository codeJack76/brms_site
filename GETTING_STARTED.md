# Getting Started with BRMS in Visual Studio Code

Welcome! This guide will help you get started with developing the Barangay Management System in Visual Studio Code.

## 🎯 What's Been Set Up

Your repository is now ready for Visual Studio Code development with:

- ✅ **Complete project structure** with HTML, CSS, and JavaScript
- ✅ **VS Code configuration** for optimal development experience
- ✅ **Recommended extensions** for web development
- ✅ **Git configuration** with proper .gitignore
- ✅ **Basic web application** with 5 pages (Home, Residents, Certificates, Reports, About)

## 🚀 Quick Start Guide

### Step 1: Open in Visual Studio Code

1. Open Visual Studio Code
2. Click **File** → **Open Folder**
3. Navigate to and select the `brms_site` folder
4. Click **Select Folder**

### Step 2: Install Recommended Extensions

When you open the project, VS Code will show a notification asking if you want to install recommended extensions:

1. Click **Install** on the notification, or
2. Go to the Extensions sidebar (Ctrl+Shift+X)
3. Search for "@recommended" to see the list
4. Install these key extensions:
   - **Prettier**: For code formatting
   - **Live Server**: For live preview
   - **Path Intellisense**: For file path autocomplete
   - **Auto Rename Tag**: For HTML tag editing

### Step 3: View Your Website

**Option A: Using Live Server (Recommended)**
1. Right-click on `index.html` in the Explorer
2. Select **Open with Live Server**
3. Your browser will open with the website
4. Any changes you make will automatically refresh the browser

**Option B: Direct Browser Open**
1. Right-click on `index.html`
2. Select **Reveal in File Explorer** (Windows) or **Reveal in Finder** (Mac)
3. Double-click `index.html` to open in your default browser

**Option C: Using the Debugger**
1. Press **F5** or click **Run** → **Start Debugging**
2. Select **Chrome** when prompted
3. The website will open in Chrome with debugging capabilities

## 📝 Making Your First Edit

Let's make a simple change to see everything working:

1. Open `index.html`
2. Find the line with `<h2>Barangay Management System</h2>` (around line 33)
3. Change it to include your barangay name: `<h2>Barangay [Your Name] Management System</h2>`
4. Save the file (Ctrl+S or Cmd+S)
5. If using Live Server, the browser will automatically refresh
6. See your changes instantly!

## 🎨 Project Structure Explained

```
brms_site/
├── .vscode/                    # VS Code settings (already configured)
├── src/
│   ├── css/
│   │   └── style.css          # All your styles - edit this for design changes
│   ├── js/
│   │   └── main.js            # JavaScript functionality - add interactivity here
│   ├── assets/
│   │   └── images/            # Put your images here
│   └── pages/                 # Additional pages
│       ├── residents.html     # Resident management page
│       ├── certificates.html  # Certificate issuance page
│       ├── reports.html       # Reports and analytics page
│       └── about.html         # About page
├── index.html                 # Main landing page - start here
├── package.json              # Project metadata
├── .gitignore                # Files to exclude from Git
├── .editorconfig             # Editor consistency settings
└── README.md                 # Project documentation
```

## 💡 Development Tips

### Editing HTML
- Open any `.html` file to edit the structure
- Use **Alt+Shift+F** (Windows) or **Option+Shift+F** (Mac) to format the code
- Use **Ctrl+Space** for autocomplete suggestions

### Styling with CSS
- All styles are in `src/css/style.css`
- Colors are defined as CSS variables at the top (`:root`)
- Change `--primary-color: #2563eb;` to change the main theme color

### Adding JavaScript Functionality
- Main JavaScript is in `src/js/main.js`
- Add your functions and event listeners here
- The file is already linked to all HTML pages

### Working with Git
- Your changes are tracked by Git
- Use the Source Control panel (Ctrl+Shift+G) to commit changes
- VS Code shows which files have been modified

## 🔧 Useful VS Code Shortcuts

- **Ctrl+P** (Cmd+P): Quick file open
- **Ctrl+Shift+F** (Cmd+Shift+F): Search in all files
- **Ctrl+`** (Cmd+`): Toggle terminal
- **Ctrl+B** (Cmd+B): Toggle sidebar
- **Alt+Shift+F** (Option+Shift+F): Format document
- **F12**: Go to definition
- **Ctrl+/** (Cmd+/): Toggle comment

## 📚 Next Steps

1. **Customize the design**: Edit colors in `src/css/style.css`
2. **Add content**: Update the HTML files with your barangay's information
3. **Add images**: Place logos or photos in `src/assets/images/`
4. **Add functionality**: Write JavaScript in `src/js/main.js`
5. **Create new pages**: Follow the structure of existing pages

## 🆘 Troubleshooting

### Live Server doesn't work
- Make sure you installed the Live Server extension
- Right-click on `index.html` and look for "Open with Live Server"
- If not available, reload VS Code (Ctrl+R or Cmd+R)

### Changes not showing
- Make sure you saved the file (Ctrl+S or Cmd+S)
- Hard refresh your browser (Ctrl+Shift+R or Cmd+Shift+R)
- Check the browser console for errors (F12)

### Extensions not installing
- Check your internet connection
- Try restarting VS Code
- Manually search and install from the Extensions marketplace

## 🎓 Learning Resources

- [HTML Tutorial](https://www.w3schools.com/html/)
- [CSS Tutorial](https://www.w3schools.com/css/)
- [JavaScript Tutorial](https://www.w3schools.com/js/)
- [VS Code Tips](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)

## 🤝 Need Help?

If you have questions or run into issues:
1. Check the README.md file
2. Look at the existing code for examples
3. Open an issue on GitHub
4. Refer to the official documentation links above

Happy coding! 🚀
