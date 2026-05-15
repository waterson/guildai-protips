<!-- Local variables: -->
<!-- fill-column: 120 -->
<!-- End: -->

This directory contains a library of "pro tips" meant to share tricks and tips for writing Guild agents.

Each tip is a short, self-contained topic meant to be easily digestible.

- Write in an informal style. Don't be pedantic.
- Assume the reader is busy.
- Assume that your reader is going to stop reading at any point on the page.
- The reader should get the key take-aways early in the article; don't bury the lede.
- Save detailed exposition and nuance for later parts of the document.
- If the topic is coding, make sure that there is a terse code example early in the document.
- Prefer active voice.
- Follow Strunk & White's Elements of Style.

* Structure

Follow this pattern:

1. *Hook* — one sentence stating what the tip is and why it matters.
2. *Code* — a terse, self-contained example (for coding tips).
3. *Explanation* — brief walkthrough of the key moving parts.
4. *Why* — motivation and context for readers who want the deeper story.

* Length

Aim for one screen. If a tip runs longer, split it into two tips rather than letting it sprawl.

* Org-mode conventions

Tips are written in org-mode (=.org=). Use these conventions:

- Top-level headings: =* Heading=
- Code blocks: =#+begin_src typescript= ... =#+end_src=
- Inline code and identifiers: ==like this==

Every tip must end with this boilerplate:

#+begin_src org
  #+HTML_HEAD: <link rel="stylesheet" href="protips.css">
  #+HTML_HEAD: <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@4/tex-mml-chtml.js"></script>
  #+OPTIONS: toc:nil
  #+OPTIONS: num:nil
  #+OPTIONS: ':t
  #+OPTIONS: html-postamble:nil
#+end_src
