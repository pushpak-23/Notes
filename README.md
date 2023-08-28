# Vue.js Notes App

This is a simple Vue.js notes app that allows you to add and display notes with random background colors. You can add notes with a minimum length of 10 characters, and each note is assigned a unique background color.

## Features

- Add notes with a minimum length of 10 characters.
- Each note has a unique random background color.
- Notes are displayed in a visually appealing card format.
- Easy-to-use interface with a "+" button to add new notes.

## Technologies Used

- [Vue.js](https://vuejs.org/): The JavaScript framework used to build the app.
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML): For structuring the web page.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS): For styling the app.
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript): For dynamic functionality.

## Setup

1. Clone the repository to your local machine.
2. Open the `index.html` file in your web browser.

## Usage

1. Click the "+" button in the header to open the note input modal.
2. Enter your note text in the textarea.
3. Click the "Add Note" button to add the note.
4. Notes will be displayed with random background colors.

## App Structure

- The app is built using Vue 3 Composition API.
- Notes are stored in the `notes` array, and each note has a unique background color generated using the `getRandomColor` function.
- The `showModal` variable controls the visibility of the note input modal.
- Input validation ensures that notes are at least 10 characters long.
- The app uses CSS for styling, with scoped styles to avoid global conflicts.

## Folder Structure

- `index.html`: The main HTML file.
- `script.js`: The Vue 3 script with setup, data, and methods.
- `styles.css`: The CSS file for styling the app.

## Screenshots

![App Screenshot](screenshot.png)

## Contributions

Contributions to this project are welcome. Feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
