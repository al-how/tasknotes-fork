---
created: 2025-11-06T16:46
updated: 2025-11-06T17:00
tags:
  - personal-projects
status:
  - discovery
summary: Figuring out how to incorporate parts of TaskNotes I like
---
I'm considering making a fork of the TaskNotes plugin (or my own plugin from scratch) to emulate portions of TaskNotes that I liked.
## What I liked about TaskNotes:
- Ability to convert an in-line task into a TaskNote
	- could replicate this action with a hotkey, like cmd+shift+T (which currently opens a recently closed tab). that would create a new task note
	- I don't want to leave the context of the parent note to create a task note
- The agenda view was neat but buggy. 
	- alternative would be a way to generate meeting notes from a calendar ics import. Could imagine a button next to agenda on my daily note - create agenda from day
	- needs to activate templater
	- didn't like the multiple steps it would take to create a meeting note from a calendar event
	- I don't NEED a calendar view in obsidain. Outlook does fine. Really just want a way to create notes from calendar events
	- time blocking was a neat idea, but better to do this in outlook so it's visible to others
- The properties that worked:
	- taskStatus (should be boolean complete/incomplete)
	- project associations *chefs kiss*
	- due (obvs)
- what I'd want to incorporate/omit: 
	- statusDescription good for at a glance where I'm at with a task
	- priority seems too granular. i can decide priority at task assessment breaks
	- the eisenhower matrix from TaskGenius is an itneresting idea, but it would take a UI of bases to replicate (should be rather easy)