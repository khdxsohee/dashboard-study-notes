# 📚 Study Notes Dashboard

A simple and interactive HTML dashboard to manage and access subject-wise study notes. This project lets students and educators organize their notes (PDFs) by subject and quickly search through them using a built-in search bar.

## 🔗 Live Demo

👉 [Click here to view the live demo](https://khalid-randhawa.web.app/apps-projects/study-notes-dashboard/dashboard.html)


## ✨ Features

- Clean and responsive layout
- Subject-wise categorization (English, Biology, Chemistry, Physics)
- 📄 View and ⬇️ Download links for each note
- 🔍 Real-time search functionality to filter notes
- Easy to extend with more subjects or notes

## 📁 Folder Structure

### study-notes-dashboard/
- │
- ├── dashboard.html             - # Main HTML file
- ├── style.css              - # Custom CSS styles
- ├── README.md              - # Project info and usage
- │
- ├── notes/                  # All study notes organized by subject
- │   ├── english/
- │   │   ├── grammar.pdf
- │   │   ├── essay.pdf
- │   │   └── story.pdf
- │   │
- │   ├── biology/
- │   │   ├── cell.pdf
- │   │   ├── body.pdf
- │   │   ├── animal-body.pdf
- │   │   └── bird-body.pdf
- │   │
- │   ├── chemistry/
- │   │   ├── atoms.pdf
- │   │   └── reactions.pdf
- │   │
- │   └── physics/
- │       ├── motion.pdf
- │       └── light.pdf

> 📌 **Note:** Make sure to create a folder named `notes` in your project directory. Inside it, create subfolders for each subject (`english`, `biology`, `chemistry`, `physics`, etc.) and place the respective PDF files there. Update the file names in the HTML code accordingly if you change the names.

## 🚀 Getting Started

To run this project locally:

### 1. Clone/Download the repository

```bash
git clone https://github.com/khdxsohee/dashboard-study-notes.git
```
```
cd dashboard-study-notes
```
### 2. Add your PDF notes
- Navigate to the notes/ folder.

- Create subfolders for each subject (e.g., english, biology, etc.).

- Add your PDF files into the appropriate folders.

- Update the links in dashboard.html if your file names are different.

### 3. Open in browser
You can open the dashboard.html file directly in your browser by double-clicking it or right-clicking and choosing Open With > Browser.

### 📌 Customization
> To add a new subject:

- Copy one of the existing .subject sections in dashboard.html.

- Change the subject name and update the data-title and file paths.

- To style the page, modify style.css as needed.

### 💡 Example Notes Entry
```
<div class="note-card" data-title="Motion & Force">
  <p>Motion & Force</p>
  <a href="notes/physics/motion.pdf" target="_blank" class="view">👁️ View</a>
  <a href="notes/physics/motion.pdf" download class="download">⬇️ Download</a>
</div>
```
### 🧠 Tips
- All searches are based on the data-title attribute. Make sure your data-title is descriptive and relevant.

- Use consistent naming for subjects and files to avoid confusion.

### 📃 License
This project is open-source and available under the MIT License.

# Made with ❤️ for students and educators.
