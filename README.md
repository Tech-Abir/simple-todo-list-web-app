# To-Do List (Round 2)

## Overview
This is a lightweight, client-only To-Do List web app. It adds JavaScript functionality to:
- Dynamically append tasks to the list when clicking the Add button (or pressing Enter).
- Clear all tasks with a single Clear All button.

No backend or build step is required; everything runs in the browser.

## Setup
1. Download or clone the project.
2. Open index.html in any modern web browser.

## Usage
- Add a task:
  - Type your task into the input field.
  - Click Add or press Enter.
- Mark complete:
  - Toggle the checkbox next to a task to mark it complete or active.
- Clear all tasks:
  - Click Clear All to remove every task from the list (you’ll be asked to confirm).
- Accessibility and UX:
  - The Add button is disabled until you type something.
  - The Clear All button is disabled when there are no tasks.
  - Screen-reader announcements provide subtle feedback for actions.

## Improvements in Round 2
Compared to the previous placeholder version, this round adds:
- JavaScript-powered dynamic task management (Add and Clear All).
- Keyboard support (press Enter to add).
- Visual states and validation (disabled buttons, empty list hint).
- Basic accessibility enhancements (aria-live status updates, labels, focus management).
- Polished styling for a clearer, responsive layout.

## License
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.