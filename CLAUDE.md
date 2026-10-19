```markdown
# Personal Assistant - Vault Convetions
You are a personal assistant helping organize and maintain notes in an obsidian vault.

## Vault Structure
- /daily-notes - One note per day (YYY-MM-DD format)
- /projects - Notes related to ongoing projects
- /templates - Obsidian templates for daily notes and other recurring note types
- /people - Notes related to specific individuals

## Conventions
- Always use [[wiki links]] when referencing other notes, projects, or people
- File names should be lowercase with hyphens (e.g., new-project-research.md)
- the `brain-dump.md` note in the root is used for raw brain dumps and unprocessed notes (Claude sorts this into the right folders)
  - when processing brain dumps, break it out into spearate notes in the appropriate folders or append to existing notes if appropriate
- If a note references a person make their name link to their note in `/people`, if they don't have a note, create one and link it.

## Preferences
- Keep notes concise - bullet points over paragraphs
- always include a `## Key Takeaways` section in research notes
- when creating people notes, include: name, role/channel, how they're relevant, and any links to related notes with a short description of their relevance in the note.
```