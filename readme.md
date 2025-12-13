open tex file in visual studio code
To open and work with a .tex file in Visual Studio Code, you need a local LaTeX installation and a specific VS Code extension. 
Prerequisites
Install a LaTeX distribution on your system. This provides the necessary tools to compile .tex files into viewable documents (like PDFs).
Windows: Install MiKTeX or TeX Live.
macOS: Install MacTeX.
Linux: Install TeX Live.
Install Visual Studio Code if you haven't already.
Ensure the LaTeX binaries are in your system's PATH environment variable (often done automatically by the installer). 
Setup VS Code
Open VS Code and go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X).
Search for LaTeX Workshop (authored by James Yu).
Click Install. 
Open and Compile the .tex File
Open your .tex file in VS Code. You can either use the File > Open File menu or use the Explorer to open the folder containing your project files.
The .tex file is a plain text file and will open in the editor.
To compile the file (generate the output, usually a PDF), use one of the following methods:
Use the keyboard shortcut Ctrl+Alt+B (Windows/Linux) or Cmd+Option+B (macOS).
Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P) and run the command LaTeX Workshop: Build with Recipe.
To view the resulting PDF, use one of the following methods:
Use the keyboard shortcut Ctrl+Alt+V (Windows/Linux) or Cmd+Option+V (macOS).
Click the "View LaTeX PDF" button (often a magnifying glass icon) in the top-right corner of the editor.
This will typically open a live-updating preview of the PDF right inside a new VS Code tab. 