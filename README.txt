SAT Reading & Writing local quiz website

CONTENTS
- index.html: quiz website
- questions.json: 610 questions extracted from your PDF
- source-question-bank.pdf: original PDF, for checking charts/figures and source formatting

HOW TO RUN (Windows)
1. Extract this ZIP file to a folder, for example Desktop\SAT Quiz.
2. Install Python if it is not already installed.
3. Open that folder in File Explorer.
4. Click the address bar, type powershell, and press Enter.
5. Run:
   python -m http.server 8000
6. Open this address in Chrome:
   http://localhost:8000

IMPORTANT
- Keep index.html, questions.json, and source-question-bank.pdf in the same folder.
- Do not double-click index.html; the browser may block loading the JSON file. Use the local server steps above.
- The correct answer and rationale are revealed after the test taker chooses an option or clicks "Reveal answer".
- Use "View source PDF page" for questions that contain charts or visual material; the original PDF is included because extracting PDF text cannot always reproduce graphs and diagrams exactly.
- This is a local static website. It does not upload questions or answers to the internet.
