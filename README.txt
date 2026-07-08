THE ROUGH MIX ARCHIVE — HOW TO USE
====================================

This is a self-contained webpage. No server, no install, no internet
connection required. Just open index.html in any browser (double-click it,
or drag it into a browser window).

ADDING A NEW SUBMISSION
------------------------
1. Drop the audio file into this /audio folder.
   Supported formats: mp3, wav, m4a, ogg (mp3 is the safest bet).

2. Open index.html in a text editor (TextEdit, Notepad, VS Code, etc.
   — anything that edits plain text works fine).

3. Find the section that says "const SUBMISSIONS = [" — this is a list
   of entries. Copy one existing entry block (the { ... } part),
   paste it in as a new one, and fill in:

     title        — the piece's title
     author       — the author's name or handle
     table        — optional, e.g. "Table 3"
     prompt       — which prompt they used (this also becomes a filter tag)
     description  — one or two sentences
     file         — the exact filename you put in /audio, e.g. "kettle.mp3"

4. Save index.html and refresh the page in your browser. That's it.

REMOVING THE SAMPLE ENTRIES
-----------------------------
There are two placeholder entries in the list to start ("Sample Entry —
Replace Me"). Delete those two blocks once you've added real submissions.

TIPS
----
- Keep filenames simple: lowercase, no spaces, e.g. kettle-then-silence.mp3
  (spaces in filenames can sometimes cause issues — use a dash or underscore
  instead).
- If a card shows "Couldn't load audio," double check the filename in the
  SUBMISSIONS list matches the file in /audio exactly, including the
  extension (.mp3 vs .wav etc).
- The page has a dark/light mode toggle in the top right, and defaults to
  dark mode.
- To share this archive with others, you can upload the whole folder
  (index.html + audio folder together) to any free static host — sharing
  the specifics is a separate step, just ask if you want help with that
  when you're ready.
