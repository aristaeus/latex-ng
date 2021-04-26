LaTeX is a great typesetting system, but with great power comes great
responsibility. When writing a thesis or paper it sometimes feels like we're
wrestling with the typesetting system more than doing science. (La)TeX is a
relic from 40 years ago, and while it has served its purpose extremely well, in
2021 we can do better.

Things LaTeX does well:
* Bibliography/reference management. Is bibtex sufficiently isolated that we
    can use it as-is?
* Related: automatic numbering, labelling and referencing of sections, figures,
    tables, and other insets.
* Small scale maths rendering. We all have the minutia of LaTeX syntax burned
    into our brains. I don't want to relearn this, nor do I want to redesign
    it. I doubt we can make a significant improvement here.

Things we can do better:
* LaTeX code is not pretty to look at. This might seem like a small gripe, but
    having plain text that is easy to read makes it easier to write. Markdown
    has become the defacto standard for text entry everywhere else, and with
    the addition of inline/block maths, I don't see why it can't replace LaTeX.
* In principle it is easy to change global properties of a LaTeX document
    easily. In practice this isn't the case - from personal experience it is
    difficult to change the fonts, or adjust the page layout to fit on an
    ereader. This is because LaTeX allows too much formatting inline. I don't
    want so much power, and by taking it away the typesetting system can do
    more work. There should be a clearly defined template (either provided, or
    modified by the user), and styling defined in "CSS".

Antigoals:
* Tikz is a full blown diagram/graphing suite. I think replicating this is
    totally out of scope at this stage, but it would be nice to have something
    integrated (e.g. matplotlib).


LaTeX is many things to many people. It can be used to produce papers, posters,
books, and anything in between. We will initially limit our scope to papers,
i.e.\ A4 documents of short to medium length. Documents will usually be
compiled into a PDF, but it would be nice to occasionally compile into an HTML
document for the web.
