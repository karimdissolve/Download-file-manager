# Intelligent Download Section Organizer

Automatically Organize Your Downloads Folder with Built-in Preview

IDSO is a graphical application for Windows designed to bring order to the often chaotic Downloads folder. It automatically sorts files and folders into predefined categories, while providing a clean interface to navigate through them and even preview files quickly.

# Key Features :
+ Smart Auto-Sorting:
+ Monitors your Downloads folder in the background.
+ Automatically detects new files and folders.
+ Checks whether files are "stable" (i.e., the download/copy is complete) before moving them to avoid errors.
+ Sorts items into predefined category folders: Images, Audio, Videos, Scripts, Documents, Archives, Folders (for subdirectories), and Others.
+ Handles naming conflicts by appending a timestamp to duplicates when moving files.
+ Initial Mass Sorting (with Progress Indicator):
+  On first launch, the app offers to sort all existing files in the Downloads folder.

+ A visual progress bar shows the status of this initial sorting process.

+ Intuitive Graphical Interface:
+ Clear visualization of categories with distinct icons and item counts.

+ Easy navigation by category and file extension using a tab system.

+ Detailed file view (Name, Last Modified Date, Size) in sortable lists.

+ Search function to quickly filter files within the selected category.

+ Quick Preview (QuickLook Integration):
+ Press the spacebar on a selected file to instantly preview its contents (text, PDF, image, video, etc.).

+ Requires QuickLook (by QL-Win) to be installed on your system. Integration is done through the included Bridge.exe utility for maximum compatibility.

+ File Management:
Open files directly from the application.

Open the containing folder in Windows Explorer.

Delete files (with confirmation).

Easily move files between managed categories or to any other folder via a "Browse" dialog.

Image Tooltip Preview:
Hover over an image file in the list to display a quick thumbnail tooltip.

Integrated Log Console:
Displays actions performed by the app (folder creation, file movement, errors) for easy tracking.

Stealth Mode:
Can be quickly shown/hidden using the Ctrl + P keyboard shortcut.

The close icon minimizes the app instead of exiting, allowing monitoring to continue in the background.

Purpose
This project aims to simplify the management of the Downloads folder, a location that tends to get disorganized quickly. By automating file sorting and offering fast viewing and preview tools, IDSO helps you locate your files more efficiently.

Requirements
Windows

Python 3.x

Python libraries (installable via pip):

keyboard (for the Ctrl+P shortcut)

Pillow (for icons and image tooltips)

(Optional) pywin32 (only if you want to use advanced window management via the Win32 API for Ctrl+P – not required for previewing with Bridge.exe)

QuickLook (by QL-Win) installed (for the spacebar preview functionality). Make sure the path to Bridge.exe is properly configured in the script.

GitHub README Tips
Replace [placeholder.png] with a real screenshot of your application.

Add an "Installation" section explaining how to clone the repo, install dependencies (pip install -r requirements.txt if you create a requirements file), and configure the DOWNLOADS_FOLDER and BRIDGE_EXECUTABLE paths.

Add a "Usage" section briefly explaining how to run the script and use the key features (selection, spacebar, Ctrl+P, etc.).

Add a "Contributing" section if you're open to external contributions.

Add a "License" section (e.g., MIT, GPL, etc.).

This description should give readers a solid overview of what your application does!
