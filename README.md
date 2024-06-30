<h1>Note Project</h1>

This project is a note-taking application developed using TypeScript and React. Users can create notes, filter them by title and tags, and manage their notes.

<h2>Features</h2>

- Create Notes: Users can add new notes.
- Filter Notes: Users can filter notes by title and tags.
- Edit and Delete Notes: Users can edit or delete existing notes.
- Tag Management: Users can add tags to notes and manage tags.
- Responsive Design: The design is responsive, adapting to different screen sizes.

<h2>Usage</h2>

- App Component
  The App component is the main component of the application and contains the routing for all pages.

- Libraries Used
  react-router-dom: For page routing.
  uuid: For generating unique IDs.
  react-bootstrap and react-select: For UI components.

- MainPage Component
  The MainPage component provides the main interface for viewing and filtering notes.

- Props
  notes: An array of Note objects.
  availableTags: An array of Tag objects.

- CreateNote Component
  The CreateNote component is used to create new notes.

- Props
  onSubmit: A function called when a new note is created.
  createTag: A function called when a new tag is created.
  availableTags: A list of existing tags.

- NoteDetail Component
  The NoteDetail component displays the details of a selected note and provides an option to delete the note.

- Props
  deleteNote: A function used to delete the note.

- EditNote Component
  The EditNote component is used to edit an existing note.

- Props
  onSubmit: A function called when a note is edited.
  createTag: A function called when a new tag is created.
  availableTags: A list of existing tags.

- Layout Component
  The Layout component provides a common layout for the note details and editing pages.

Props
notes: An array of Note objects.

<h2>Screenshot</h2>

![](/public/Notes.gif)
# Note-Project
