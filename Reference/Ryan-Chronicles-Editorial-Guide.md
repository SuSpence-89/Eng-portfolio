# The Ryan Chronicles — editorial and website plan

**Canonical collection name:** The Ryan Chronicles.

This document records Spencer's standing decision for his autobiography/engineering portfolio. Use it when continuing this work in later chats. The source of truth is the website repository `SuSpence-89/Eng-portfolio`.

## Structure we agreed upon

- Keep the main autobiography **chronological** and retain all chapter boundaries. Tell each Ryan memory in the life chapter where it naturally occurred: Rock Creek childhood and high school; first and second weddings; later adventures, etc.
- Maintain **one recurring collection** at `/about/ryan-chronicles/` titled **The Ryan Chronicles**. The page acts as an index **linking to stories in their original chapters**, not a separate replacement chronology or a second copy of all the prose.
- Mark each relevant story section with the recurring blue **A Ryan Chronicle** callout by using `{% include ryan-chronicle-marker.html story="Story title" %}`. The marker links back to the central collection.
- Add a record to `_data/ryan_chronicles.yml` for each published story, with `title`, `era`, `description`, `location`, `page`, and optional `anchor`. The dedicated collection page displays these automatically, so new stories can be added with minimal layout changes.
- Each in-chapter story receives a unique HTML `id`. A hash link such as `/about/#ryan-guitar-lessons` should **automatically open the parent expandable chapter**, and then scroll to the section. This behavior lives in `_includes/about-reading-guide.html`.
- If a memory does not fit a chronological chapter, publish it as an **independent side-story page**, still list it in the Chronicles data file, and keep the chapter text intact. No need to invent a chapter for it.
- Introduce Ryan in Chapter 1 near the end, after “The Books That Stayed With Me” and before “Photos from My Childhood.” Keep the original photo placement and wrapping: clocks, sunglasses, cats, concert selfie.
- Potential future topics: first wedding, second wedding, and unclassifiable side stories. These are only **planned themes**, not finished or factually documented episodes. Do not fabricate details, dates, dialogue, or Ryan's feelings.
- Preserve Spencer's humour and distinctive language, anecdotes, chronological uncertainty, and personal impressions. Record facts only when Spencer supplies them; ask for clarification when uncertain.
- Other significant people may someday get their own cross-chapter collections, but **start with Ryan**.

## Workflow for the next Ryan story

1. Capture Spencer's story and personal details in his voice; distinguish remembered detail from guesses.
2. Decide whether the story belongs in an existing life chapter or as an independent side story.
3. Insert the story in that original location with a stable unique anchor and `ryan-chronicle-marker.html`.
4. Add an entry to `_data/ryan_chronicles.yml` so the story also appears automatically in the central collection.
5. Keep photos relevant to the original story, with responsive layout and descriptive alt text; do not invent identities in ambiguous photos.
6. Check links on both desktop and mobile, verify successful GitHub Pages deployment, and show the live link.

## Existing starting stories

Chapter 1 contains the ghost bike and school bus reunion, the English classroom and gnome, Janelle and high school advice, guitar lessons, and Spencer's reflection on a lasting friendship. Those moments are linked from the collection. This is an **ongoing living autobiography** and not a finished chapter.
