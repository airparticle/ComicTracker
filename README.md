# Comic Tracker

Comic Tracker is a simple desktop application for keeping track of comic book collections.  
It provides a graphical interface for adding, viewing, and categorizing comics, with data stored locally for easy retrieval.

## Features
- 📚 **Track comics** by title, issue, and category  
- 🖥️ **User-friendly GUI** built with a standard Python GUI framework  
- 💾 **Persistent storage** using JSON files (data is saved on exit and reloaded on startup)  
- 🔎 **Basic organization** into lists and categories  

## How it Works
- The app’s GUI allows you to enter comic details into categorized lists.  
- Data is serialized to a JSON file so your collection is preserved between sessions.  
- On launch, the app reloads the stored JSON file and restores your collection.  

## Installation & Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/comic-tracker.git
   cd comic-tracker
   ```

2. **Create a virtual environment (recommended)**  
   ```bash
   python -m venv venv
   source venv/bin/activate   # On macOS/Linux
   venv\Scripts\activate    # On Windows
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**  
   ```bash
   python main.py
   ```

## Limitations (Current Scope)
- No advanced data operations (searching, filtering, editing in bulk).  
- Storage is JSON-only (no database integration yet).  
- Mostly focused on UI functionality rather than business logic.  

## Future Improvements
Some ideas for next steps:
- Add a search or filter function  
- Support editing or deleting entries  
- Switch to SQLite/Postgres for more robust storage  
- Package the app for distribution (installer or executable)  
- Add unit tests for data handling  

---
