# CV LaTeX Template

This is my template for an academic CV. It's actually just a regular `article` with some packages. I always end up having to hack existing templates to my taste, and find the cv-specific macros too restrictive, so I thought I would just structure my CV like a normal article and do some slight aesthetic changes in the preamble. Nothing in the actual document is non-standard. Just some normal sections and a list or two. For pushing things to the right, I just use `\hfill` (usually dates).

Check the [pdf file](cv.pdf) for a preview.

## Description

The following packages are used:

- `libertine` - nice font (although it looks pretty good with the default font as well)
- `fontenc` and `inputenc` - for diacritics, funny letters, etc.
- `geometry` - I use 2cm margins all around.
- `fancyhdr` - for custom footer (basically, page number to the right)
- `lastpage` - so that I can refer to the last page in the footer (i.e. "1/5")
- `doi` - for easy input of doi numbers (good if you list publications)
- `enumitem` - for customized lists. I use it to add square brackets to the numbered lists, and more importantly to be able to resume counters (with the `resume*` option when beginning a list). For example, if I want to "count" all my publications, but they are spread across different subsections (e.g. Papers, Chapters), I want the counter to continue and not start over.
- `titlesec` - customized section headers (format, size, spacing)
- `xcolor` - I use color in the section headers
- `titling` - customized title block. A bit of overkill (could just do the same without using `\maketitle`)

Also, I set paragraph indentation to 0 em (no indentation) and spacing between paragraphs to 0.5 em. This makes it easier to list things that don't necessarily look like lists, by simply writing one entry per line.
