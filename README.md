# booklet.rs
Bookmark / snippet tool for saving text to be accessible later on.  

Overview: 
- Bind the tool to keybind for creating new bookmarks and gettign a list of bookmarks.
- On install create config in ~.config/bookletrs and inital bookmark file in ~/.bookletrs/bookmark (avoiding .config for privacy)
- Select text and trigger the keybind to save the text to the file.
- Put cursor where you want to paste bookmark, select keybind for bringing up the bookmark selector, create a new terminal for the bookmarks, allowing the naviation and selection of the bookmarks and when they press enter insert that where the user has their cursor.
