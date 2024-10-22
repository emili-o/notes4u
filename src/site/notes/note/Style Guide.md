---
{"dg-publish":true,"permalink":"/note/style-guide/","tags":["note"]}
---


# Style guide for this vault

## Properties

### tags

The `tags` property contains _type_ tags, which indicate what kind of file or block the object is, and _organizing_ tags which are used to categorize by theme/topic/status.

#### type tags

`daily-note`, `note`, `interview`, `meeting`, `index`, `quote`, `one-on-one`, `outline`, `chat`, `chatGPT`, `post`, `track`, `transcription`, `video`, `voicenote`

#### Non-exhaustive list of organizing tags

#javascript 

---
### parent notes

The `up` property indicates the parent note, or the note that lives above it in the hierarchy.

### grade

The `grade` property is used to indicate how much a particular note has been reviewed and/or expanded upon. A 10 indicates a note that was written and hasn't been reviewed, and a 1 indicates a "finished" note.

### obsidian-front-matter-timestamps

The `created` and `updated` metadata values are automatically managed by this plugin.
