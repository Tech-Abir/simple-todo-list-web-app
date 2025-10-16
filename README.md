# My To-Do List

## Overview
My To-Do List is a simple, static web page that lets you add and manage tasks directly in your browser. It requires no backend or build step—just open the HTML file and start using it.

Key features:
- Prominent header “My To-Do List”
- Task input box and an Add button
- Client-side only; no data leaves your browser
- Keyboard-friendly and accessible (Enter to add, visible focus, ARIA labels)

## Setup
No installation is required.

Option 1: Double-click index.html to open it in your default browser.

Option 2 (recommended for older browsers or stricter environments):
- Serve the folder with a simple static server (any one of these):
  - Python: python3 -m http.server
  - Node: npx serve
  - VS Code Live Server extension
- Visit the local URL (e.g., http://localhost:8000).

## Usage
- Type a task into the input box and click Add (or press Enter).
- Click the checkbox to mark a task as completed.
- Click × to remove a task.
- Your tasks live for the current session in memory. No account or server is involved.

## License
MIT License

Copyright (c) 2025 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.