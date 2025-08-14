# NoteBookApp
SQLite CLI notes app

🗒 Notesbook (SQLite CLI Notes App)

Notesbook is my first CLI notes app using SQLite.
I am learning SQL by experimenting, reading error messages, and trying repeatedly until I get things right.
This app allows me to create, view, update, delete, and search notes stored in a local SQLite database.


---

✨ Features

📝 Multi-line note creation (END to finish)

📄 View notes sorted newest → oldest or oldest → newest

✏ Update note title or content separately

❌ Delete a single note or all notes (reset IDs automatically)

🔍 Keyword search in title or note content

🔄 Case-insensitive search (COLLATE NOCASE)



---

🛠 Functions Explained

createtable(): Creates the notes table with ID, TITLE, NOTE, DATE.

multiline_input(): Allows multi-line note entry.

create_note(): Inserts a new note with title, content, and timestamp.

view_notes(): Displays notes sorted by date.

delete_note(): Deletes one note or all notes.

update_note(): Updates title or content of a note.

search_notes(): Searches notes by keyword.

home(): Main menu loop for user interaction.



---

💻 Usage

1. Ensure Python 3 and SQLite are installed.


2. Run:



python main.py

3. Choose the action from the menu.


🏆 Encouragement / Follow & Support

If you liked this project or are curious about my learning journey, follow me, give feedback, and keep up with my progress!
With every new note and update, you can be part of this journey and see it grow. 🚀
