relephant
=========

My personal ultimate note-taking/task manager thing

## Setup

  1. `git clone git@github.com:espy/relephant.git`
  2. `cd relephant`
  3. `bower install`
  4. Open as localhost dir or do `python -m SimpleHTTPServer` to see it on `0.0.0.0:8000`

## What is this?

It's a fork of [Markdown Editor](https://github.com/jbt/markdown-editor), massively expanded to inlcude:
  - Sublime Text shortcuts
  - Clickable checkbox graphics and checkbox variants (type `- [ ]` to start a new task, other available tasks are `- [>]`,  `- [<]`, `- [!]` and `- [x]` for completed tasks)
  - Code folding: Press `cmd-shift-a` anywhere to toggle the block you're in
  - Completing a task's sub-tasks completes that task automatically
  - Enter at the end of a list continues that list
  - Tabbing in an empty task indents it

This originally included storing the whole text data inside the URL, which I've disabled, and dropping text files onto the page to load them into the editor, which I've probably broken.
