# Better-Firefox ✨

A custom `userChrome.css` file to give the Firefox UI a modern, clean, and transparent look.


## Installation

1.  **Enable Legacy Customizations:**
    *   Go to `about:config` in Firefox.
    *   Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.

2.  **Find Your Profile Folder:**
    *   Go to `about:support`.
    *   Find the "Profile Folder" row and click "Open Folder".

3.  **Create the `chrome` folder:**
    *   Inside your profile folder, create a new folder named `chrome`.
    *   Place this `userChrome.css` file inside the new `chrome` folder.

4.  **Restart Firefox.**

The final file path should be: `<Your_Firefox_Profile>/chrome/userChrome.css`.

## Customization

You can easily edit this theme by inspecting the browser's UI.

1.  Press `Ctrl+Shift+Alt+I` (or `Cmd+Opt+Shift+I` on Mac) to open the **Browser Toolbox**.
2.  Click the element inspector icon (a square with a cursor).
3.  Click any element in the Firefox UI to find its `id` or `class`.
4.  Use these selectors to add or change styles in the `userChrome.css` file.

Enjoy your new Firefox look