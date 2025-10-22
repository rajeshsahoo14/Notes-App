# Notes-App  
A simple task/notes application built with Node.js and Express.  
Allows users to submit tasks (title & details) and view them in a list.  

## 🧰 Features  
- Add a new note/task with a **title** and **details**  
- List existing tasks with a “Read more…” type link  
- Simple UI styled with Tailwind CSS & dark-mode friendly background  

## 🚀 Tech Stack  
- Node.js + Express (server & routing)  
- EJS templates for server-rendered HTML  
- Tailwind CSS (via CDN) for styling  
- File-system or simple storage (based on your current implementation) for tasks  

## 🔧 Getting Started  
### Prerequisites  
- Node.js (v14 or above recommended)  
- npm (or yarn)  
 
### Installation  
```bash
git clone https://github.com/rajeshsahoo14/Notes-App.git  
cd Notes-App  
npm install
```
### Running
```bash
node index.js
```
Then navigate to http://localhost:3000 (or whatever port you set) in your browser.

###📁  Folder Structure
```bash
/
├── index.js          # main entry point  
├── package.json  
├── .gitignore  
└── views/            # EJS templates  
    └── …
```  
###✅ Usage
Open the app in your browser.

In the form, enter a title and details for your task.

Click “Create Task”.

Your new task appears in the list below.

Click “Read more…” to view full details.
