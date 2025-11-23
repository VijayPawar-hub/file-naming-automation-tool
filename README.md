# file-naming-automation-tool
The File Naming Automation Tool is a desktop application built with Python and Tkinter designed to simplify the bulk renaming and copying of files. It provides a flexible and powerful graphical interface for users to define complex naming schemes, including sequential numbering, timestamps, case conversion, and character sanitization, with a mandatory preview before execution.
This tool offers extensive control over file naming:
File Selection: Select individual files or an entire directory to process.
Flexible Naming Schemes:
Set a custom Base Name.
Choose between Sequential Numbering (with custom start number and padding) or Keeping Original Numbers.
Optional Timestamp inclusion with customizable format (e.g., %Y%m%d_%H%M%S).
Sanitization and Formatting:
Apply Case Conversion (Lowercase, Uppercase, Title Case).
Automatically replace spaces with underscores.
Optionally remove special characters for cleaner, cross-platform filenames.
Operation Control:
Rename Files: Perform the operation in place (modifies the original files).
Copy Files: Create new, renamed files in a specified Output Folder, leaving the originals untouched.
Safety and Preview: Mandatory Preview pane shows the transformation before execution, and the tool prompts for confirmation before overwriting any existing files.
