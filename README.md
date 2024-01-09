# Vue.js Test Task

Using Vue 3 + Pinia, implement a small SPA application for making  notes

The application consists of 2 pages.

## Home Page

The main page displays a list of all notes and a form to add new notes. 

## Statistics Page

Contains a simple table with two rows. The first row shows the number of notes. The second row shows the total number of characters in the notes.

## Note

Each note displays the text of the note, the number of characters, and 2 buttons "Edit" and "Delete".

If you click "Edit", a separate URL is opened and besides the note text input field there are two buttons: "Cancel", "Save". After changing the note and pressing "Save" the app makes a redirect to the main page.

If you press "Delete" you get a dialog box with deletion confirmation.

## Adding a Note

You can enter a note by pressing "Save Note" or pressing Ctrl + Enter. Regular Enter is used for line breaks.

## Functionality Requirements

- All actions on the site should take place without reloading the page.
- Confirmation of actions (delete note) is performed using a dialog box.
- The interface should meet usability requirements.
- After reloading the page, the state of the list of notes should be preserved.

## Technical Requirements

- Dialog boxes must be implemented without using "alert", "prompt" and "confirm".
- JavaScript or TypeScript is used as the development language.
- Vite is used as the builder.
- The layout must be implemented without using UI libraries (e.g. Vuetify).
- Adaptivity is not required, but welcome.
- Using of modern CSS Grid Layout, CSS Custom Properties etc is mandatory.
- The application logic should be organized into a reasonable number of self-sufficient Vue components.
- Special attention should be paid to the following points:
	- The code should be written clearly and neatly, observing tabulation and other writing elements, without unnecessary elements and functions that are not relevant to the functionality, provided with clear comments, if necessary.
	- Readability and the existence of elementary architecture.
	- Cleanness and formatting of the code is an equally important factor. The code should be written in a unified style. 
	- Absence of copypaste and duplication of logic.
	- The project should use code linters for static code analysis.

## Deliverables

The test task should be submitted in the following form:

- A link to a public repository (GitHub, GitLab) with the source code.
- If possible, a link to the site for testing the functionality.

Approximate functionality of the application:

[Notes App](https://demo.kovtunos.pro/_vue/notes-app/#/)
