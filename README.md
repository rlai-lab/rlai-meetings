# RLAI Seminars

## Adding a topic

Edit [meetings.json](meetings.json) and add an entry to the list there.
Leave `abstract` / `slides` / `notes` as `""` until you have them (empty ones are hidden). Topics are shown newest first.
Set a speaker's `website` (e.g. `"https://example.com"`) to make their name a link, or leave it as `""`.

## Adding slides or notes

1. Put the PDF in the `slides/` folder (e.g. `slides/2026-10-14-jane-doe.pdf`).
2. Set `"slides": "slides/2026-10-14-jane-doe.pdf"` on that speaker in `meetings.json`.
3. Do the same for notes
