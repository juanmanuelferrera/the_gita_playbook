# The Gita Playbook (Situational Gita)

Book project that applies Bhagavad Gita teachings to situations of modern life (anger, depression, fear, loneliness...). Each chapter is a short story-based article on one situation. The repo holds the chapter texts, planning and style documents, and the LaTeX/PDF build of the book.

## Structure

- `kdp_clean.txt` — authoritative source for chapter text and references (see `CLAUDE.md`).
- `chapters/` — the chapters: `md/` (Markdown, `chapter-NN-topic.md`), `txt/` and `es/` (Spanish versions, e.g. `capitulo-04-la-soledad.md`).
- `articles/` — individual generated articles.
- `ALL_TOPICS.md`, `COMPLETE_62_CHAPTERS.md`, `themes_data.json`, `comprehensive_gita_data.json` — list of situations/themes and the data extracted from the original book.
- `bhagavad_gita.txt`, `all_verses.txt` — verse texts.
- `BOOK_STRATEGY.md`, `BOOK_STRUCTURE.md`, `BOOK_TITLE_FINAL.md`, `TITLE_RECOMMENDATION.md` — book planning.
- `AUTHOR_VOICE_GUIDE.md`, `WRITING_STYLE_GUIDE.md`, `SYSTEM_EXPLANATION.md`, `QUICK_START.md`, `COMPLETE_GUIDE.md` — style rules and how the article-generation system works.
- `the_gita_playbook.org`, `situational_gita_book.tex`, `the_gita_playbook.tex` and the PDFs — manuscript sources and typeset output.
- `situational_gita_complete_20251212/` and its `.zip`/`.tar.gz` — packaged snapshot of the original article generator.

## Scripts

- `extract_themes.py` — extracts themes and content from the source text into `comprehensive_gita_data.json`.
- `extract_verses.sh` — extracts verses.
- `export_org_to_latex.sh`, `export_to_pdf.el` — export the Org manuscript to LaTeX/PDF.
- `package_system.sh` — builds a shareable package of the generator.

Articles are written by asking Claude Code for one situation at a time (for example "Generate an article about Anger"), following the style guides; the standalone generator scripts only exist inside the packaged snapshot.

## Status

See `PROGRESS.md`: no open work at the moment; ideas for later (such as a validator of quoted verses against the 1972 edition) are listed there.
