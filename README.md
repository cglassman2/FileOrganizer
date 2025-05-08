# FileOrganizer
The File Organizer is a Window desktop app (built with PyQt6) that enhances traditional ‎file management. 

📘 File Organizer - Summary
🎯 Purpose
 It’s perfect for users needing to:‎
•	Browse files visually.‎
•	Save and categorize files into lists (a.k.a. sections).‎
•	Add notes.‎
•	Preview documents and images.‎
•	Drag-and-drop both files and text from external sources.‎
________________________________________
🧑‍💻 How to Start
•	From source:‎
pip install PyQt6 python-docx PyMuPDF Pillow  ‎
python fileorgazizer.py‎

🪟 Main Interface Overview
•	Tabs:‎
‎1.‎	File Explorer – Browse directories, sort, bookmark.‎
‎2.‎	Saved Files – View saved content organized by list.‎
________________________________________
🗂️ File Explorer Tab
•	Bookmark folders for quick access.‎
•	Change View: Icon, List, or Table with details.‎
•	Search and Sort files by name or timestamps.‎
•	Save files to lists by selecting and clicking “Save Selected File(s)”.‎
•	Supports drag-and-drop for file import.‎
________________________________________
🏷️ Saved Files Tab
•	Shows all saved files by section.‎
•	Features:‎
o	Editable notes for each file.‎
o	Rich file preview (DOCX, PDF, TXT, Images).‎
o	Search and move files across sections.‎
o	Delete files (no undo available).‎
________________________________________
🧲 Drag & Drop Highlights
•	Dragging files adds them to the current folder.‎
•	Dragging text (e.g., from web pages) prompts for a source, saves as .docx, and adds it to ‎a section.‎
________________________________________
🔐 Storage Details
Data	File/Location
Bookmarks	bookmarks.txt
Notes	notes.txt
File Log	saved_files_all.txt
Lists	lists/<section_name>/‎
Sections	sections.txt
________________________________________
💡 FAQs
•	Undo? No undo; deletion is permanent.‎
•	Preview Excel/PowerPoint? Not supported.‎
•	Supported Previews: DOCX, TXT, PDF, JPG, PNG, GIF.‎
•	Cross-platform? Yes – Windows, macOS, Linux supported.‎
•	Export file lists? Open saved_files_all.txt in Excel/Notepad.‎
•	Duplicate file handling? Appends timestamps to avoid overwrites.‎
________________________________________
‎✅ Why Users Love It
•	Keeps files tidy and grouped thematically.‎
•	Ideal for research, writing, coursework.‎
•	Centralizes file viewing, sorting, and note-taking.‎
•	Easy to use with bulk and smart actions.‎

