# Manuscript Index — We Heralds Of Freedom (Draft Zero)

Source: `We Heralds Of Freedom - Draft Zero.docx`
Indexed by paragraph position (0-based, as returned by `python-docx`'s `Document.paragraphs`).
Boundaries were located by each section's `Heading 1` style paragraph; a section runs from its
heading paragraph through the paragraph immediately preceding the next heading (or end of file).

| # | Section | File | Start¶ | End¶ | ¶ Count | Word Count |
|---|---------|------|-------:|-----:|--------:|-----------:|
| — | Front matter (title/subtitle/epigraph) | `front-matter.md` | 0 | 4 | 5 | 21 |
| 1 | Chapter One – Our Definitions Of Freedom | `chapter-01.md` | 5 | 111 | 107 | 3,232 |
| 2 | Chapter Two – Home Is Not Home | `chapter-02.md` | 112 | 276 | 165 | 4,224 |
| 3 | Chapter Three – Inexorable Machinery Of Empire | `chapter-03.md` | 277 | 364 | 88 | 2,010 |
| 4 | Chapter Four – Great Vagaries Of Homecoming | `chapter-04.md` | 365 | 508 | 144 | 3,871 |
| 5 | Chapter Five – Relentless March Of History | `chapter-05.md` | 509 | 645 | 137 | 3,826 |
| 6 | Chapter Six – Messy Implementations Of Righteousness | `chapter-06.md` | 646 | 752 | 107 | 3,025 |
| 7 | Chapter Seven – When Faith Is Tested | `chapter-07.md` | 753 | 919 | 167 | 3,708 |
| 8 | Chapter Eight – When Faith Is Rewarded | `chapter-08.md` | 920 | 1004 | 85 | 2,351 |
| 9 | Epilogue – Magic Is Self-Actualization | `epilogue.md` | 1005 | 1017 | 13 | 438 |
| 10 | Glossary | `glossary.md` | 1018 | 1060 | 43 | 665 |

**Total manuscript body:** 1,061 paragraphs (indices 0–1060), ~27,371 words across front matter, 8 chapters, epilogue, and glossary.

## How boundaries were located

Each row's start paragraph is the `Heading 1` paragraph bearing that exact title text in the source
`.docx` (confirmed via a direct paragraph-style scan, not a text search):

- `[5] Heading 1` → "Chapter One – Our Definitions Of Freedom"
- `[112] Heading 1` → "Chapter Two – Home Is Not Home"
- `[277] Heading 1` → "Chapter Three – Inexorable Machinery Of Empire"
- `[365] Heading 1` → "Chapter Four – Great Vagaries Of Homecoming"
- `[509] Heading 1` → "Chapter Five – Relentless March Of History"
- `[646] Heading 1` → "Chapter Six – Messy Implementations Of Righteousness"
- `[753] Heading 1` → "Chapter Seven – When Faith Is Tested"
- `[920] Heading 1` → "Chapter Eight - When Faith Is Rewarded"
- `[1005] Heading 1` → "Epilogue – Magic Is Self-Actualization"
- `[1018] Heading 1` → "Glossary"

Each section's end paragraph is simply the next section's start paragraph minus one (or the final
paragraph of the document, index 1060, for the Glossary).

## Files in this directory

Each `.md` file below is a verbatim, formatting-preserved (bold/italic retained as Markdown)
transcription of its corresponding paragraph range — no content has been summarized, compressed,
or altered. These are the version-controllable, diffable counterpart to the source `.docx`.

- `front-matter.md`
- `chapter-01.md` … `chapter-08.md`
- `epilogue.md`
- `glossary.md`
