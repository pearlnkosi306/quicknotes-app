# QuickNotes

QuickNotes is a simple note-taking web app built with HTML, CSS and JavaScript. You can add short notes, sort them into Personal, Work or Study categories, search through them and delete the ones you no longer need. Notes are saved in the browser, so they are still there after a page refresh.

## Features

- Add notes with a category (Personal, Work or Study)
- Input validation: empty notes and notes over 200 characters are rejected
- Delete individual notes
- Live search that is not case-sensitive
- Note count message for zero, one or many notes
- Notes saved with localStorage
- "Clear all" button with a confirmation before deleting everything
- Responsive layout that stacks the form on small screens

## How to run locally

1. Clone the repository:
   `git clone https://github.com/YOUR-USERNAME/quicknotes-app.git`
2. Open the `quicknotes-app` folder.
3. Double-click `index.html` to open it in your browser. No installation needed.

## What I learned

- How to use `createElement` and `textContent` to build the page safely instead of `innerHTML`.
- How to save and load an array of objects using `localStorage`, `JSON.stringify` and `JSON.parse`.
- How to use Git commits and pushes to track my progress one task at a time.
- How Flexbox and a media query make a layout work on small screens.

