# Note Taking Application

## Overview

This is a React-based note-taking application that allows users to create, edit, and manage notes with tags. The application uses TypeScript and React, and leverages React Bootstrap for UI components. It includes features like:

- Creating and managing notes
- Adding and editing tags
- Filtering notes by title and tags
- Persistent storage using `localStorage`

## Features

- **Create Notes:** Add new notes with titles, content, and tags.
- **Edit Notes:** Modify existing notes.
- **Delete Notes:** Remove notes from the list.
- **Tag Management:** Add, update, and delete tags.
- **Search and Filter:** Filter notes by title and tags.

## Getting Started

### Prerequisites

- Node.js (>=14.x)
- npm or yarn

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/your-repository.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd your-repository
    ```

3. **Install dependencies:**

    ```bash
    npm install

4. **Start the development server:**

    ```bash
    npm run dev

    This will start the development server and open the application in your default browser.

### Folder Structure

- `src/`
  - `App.tsx`: Main application component that manages routing and state.
  - `NoteList.tsx`: Displays the list of notes with filtering options.
  - `NewNote.tsx`: Form for creating new notes.
  - `EditNote.tsx`: Form for editing existing notes.
  - `NoteLayout.tsx`: Layout component for displaying individual notes.
  - `Note.tsx`: Component for displaying a single note.
  - `useLocalStorage.ts`: Custom hook for managing local storage.
  - `NoteList.module.css`: CSS module for styling NoteList component.
  - `index.tsx`: Entry point for the React application.

### Usage

1. **Creating a Note:**
   - Select 'Create' button to create a new note.
   - Enter a title, body content, and tags, then save.

2. **Editing a Note:**
   - Click on a note in the list to view it.
   - Select 'Edit' button to modify the note’s content or tags.

3. **Managing Tags:**
   - Edit or delete tags from the note list view.
   - When creating or editing a note, type in the 'Tags' bar, then press enter to create a new tag.

4. **Filtering Notes:**
   - Use the search bar to filter notes by title.
   - Use the tag selector to filter notes by tags.
