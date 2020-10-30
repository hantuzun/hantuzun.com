---
title: "Section"
date: 2020-01-29T09:11:18+03:00
draft: true
---

Tufte CSS provides tools to style web articles using the ideas demonstrated by
Edward Tufte's books and handouts. Tufte's style is known for its simplicity,
extensive use of sidenotes, tight integration of graphics with text, and
carefully chosen typography.

Tufte CSS was created by [Dave Liepmann][dl] and is now an Edward Tufte project.
The original idea was cribbed from
[Tufte-<span class="latex">L<span class="latex-sup">a</span>T<span
class="latex-sub">e</span>X</span>][tufte-latex] and [R Markdown's Tufte Handout
format][r-markdown]. We give hearty thanks to all the people who have
contributed to those projects.

[dl]: http://www.daveliepmann.com
[tufte-latex]: https://tufte-latex.github.io/tufte-latex/
[r-markdown]: http://rmarkdown.rstudio.com/tufte_handout_format.html

If you see anything that Tufte CSS could improve, we welcome your contribution
in the form of an issue or pull request on the GitHub project: [tufte-css].
Please note the [contribution guidelines][contrib].

[tufte-css]: https://github.com/edwardtufte/tufte-css
[contrib]: https://github.com/edwardtufte/tufte-css#contributing

Finally, a reminder about the goal of this project. The web is not print.
Webpages are not books. Therefore, the goal of Tufte CSS is not to say
"websites should look like this interpretation of Tufte's books" but rather
"here are some techniques Tufte developed that we've found useful in print;
maybe you can find a way to make them useful on the web". Tufte CSS is merely
a sketch of one way to implement this particular set of ideas. It should be a
starting point, not a design goal, because any project should present their
information as best suits their particular circumstances.


## Getting Started

To use Tufte CSS, copy `tufte.css` and the `et-book` directory of font files to
your project directory, then add the following to your HTML document's `head`
block:

```
<link rel="stylesheet" href="tufte.css"/>
```

Now you just have to use the provided CSS rules, and the Tufte CSS conventions
described in this document. For best results, View Source and Inspect Element
frequently.


## Fundamentals

### Sections and Headings

Organize your document with an `article` element inside your `body` tag. Inside
that, use `section` tags around each logical grouping of text and headings.

Tufte CSS uses `h1` for the document title, `p` with class `subtitle` for the
document subtitle, `h2` for section headings, and `h3` for low-level headings.
More specific headings are not supported. If you feel the urge to reach for a
heading of level 4 or greater, consider redesigning your document:

> [It is] notable that the Feynman lectures (3 volumes) write about all of
> physics in 1800 pages, using only 2 levels of hierarchical headings: chapters
> and A-level heads in the text. It also uses the methodology of
> <em>sentences</em> which then cumulate sequentially into <em>paragraphs</em>,
> rather than the grunts of bullet points. Undergraduate Caltech physics is very
> complicated material, but it didn't require an elaborate hierarchy to
> organize.
>
> <footer>
> [Edward Tufte, forum post, 'Book design: advice and examples' thread][quote-cite]
> </footer>

[quote-cite]: http://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0000hB

As a bonus, this excerpt regarding the use of headings provides an example of
block quotes. In Tufte CSS they are just lightly styled, semantically correct
HTML using `blockquote` and `footer` elements. See page 20 of [The Visual
Display of Quantitative Information][vdqi] for an example in print.

[vdqi]: https://www.edwardtufte.com/tufte/books_vdqi

<span class="newthought">In his later books</span>[^1], Tufte starts each
section with a bit of vertical space, a non-indented paragraph, and the first
few words of the sentence set in small caps. For this we use a span with the
class `newthought`, as demonstrated at the beginning of this paragraph. Vertical
spacing is accomplished separately through `<section>` tags. Be consistent:
though we do so in this paragraph for the purpose of demonstration, do not
alternate use of header elements and the `newthought` technique. Pick one
approach and stick to it.

[^1]: [Beautiful Evidence](http://www.edwardtufte.com/tufte/books_be)

### Text
