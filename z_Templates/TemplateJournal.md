---
NoteIcon: journal
aat-render-enabled: true
fc-category:
  - Event Category 1
fc-display-name: 
sessionstatus:
  - Occured
type: Session Journal
sessionDate: 2000-01-01
players: 3
Status:
  - ⏳
OneLiner: 1 Line Summary
timelines:
  - journal
tags:
  - journal
---

<% await tp.file.move("/1-Session Journals/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewJournal");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Session Number");
    await tp.file.rename("Session " + title);
} else {
    title = tp.file.title;
}
_%>

# Roster 
- [[Barim Bearfoot]]
- [[Alaric Stormrider]]
- [[Timotheus Thal]]
# Recap



# Plan




# DM Notes



