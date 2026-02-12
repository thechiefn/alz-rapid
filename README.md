# RAPID Matrix Generator

A web-based tool for creating and managing RAPID decision-making matrices with export to Confluence-compatible HTML.

## 🚀 Live Demo

Visit the [RAPID Matrix App](https://alianza-dev.github.io/alz-rapid/)

## 📖 What is RAPID?

RAPID is a decision-making framework that clarifies roles and responsibilities for each activity:

- **R** — **Recommend**: Makes the proposal
- **A** — **Agree**: Has veto power
- **P** — **Perform**: Does the work
- **I** — **Input**: Provides advice
- **D** — **Decide**: Makes the final call

## ✨ Features

- **Interactive Editor**: Add/edit/delete sections, roles, and activities
- **Drag & Drop**: Move badges between cells with visual feedback
- **Sticky Controls**: Toolbar and badge palette stay accessible while scrolling
- **Export to Confluence**: Generate inline-styled HTML for pasting into Confluence
- **JSON Import/Export**: Save and share your matrices
- **Alianza Brand Colors**: Each RAPID badge uses distinct colors from the brand palette

## 🎯 Usage

1. **Start with App**: Open `rapid-matrix-app.html` for a blank template
2. **View Example**: Check `rapid-matrix-example.html` for a fully populated 5-phase matrix
3. **Customize**: Add your sections, columns (teams/functions), and rows (activities)
4. **Assign Roles**: Drag badges from the legend palette onto cells
5. **Export**: Click "Export to Confluence HTML" to get inline-styled HTML

## 🛠️ Files

- `index.html` — Landing page with navigation
- `rapid-matrix-app.html` — Main application (blank starter template)
- `rapid-matrix-example.html` — Full example with sample data
- `alianza-brand-guidelines.md` — Brand color reference

## 📦 Deployment

This site automatically deploys to GitHub Pages via GitHub Actions when you push to the `main` branch.

## 🎨 Customization

The app uses CSS custom properties for easy theming. Edit the `:root` section to adjust:
- Brand colors
- Badge colors (R, A, P, I, D)
- Typography
- Spacing

## 📄 License

Internal tool for Alianza team use.
