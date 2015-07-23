---
layout: post
title: Easy PDF Presentations With Pandoc
category: education
tags: education latex beamer markdown emacs text presentations
---

As a dedicated Emacs and Linux user, I find my life much simpler when
I can live in plain text as much as possible. This allows me to
leverage the experience I've built up with my favorite editor, version
content and collaborate painlessly with git, and avoid proprietary
formats and applications. As a researcher and student, I've preferred
$$\LaTeX$$ for writing reports and papers for these reasons, as well
as its renowned typesetting capabilities. I've dabbled with using the
Beamer package for presentations, but ultimately while LaTeX is great
for formatting documents, it can be very tedious to typeset your
presentations. This is where Pandoc comes in.

Pandoc is a highly flexible program for processing Markdown and
converting it to many formats. Conveniently, one of the formats that
it supports is Beamer presentations. The lightweight nature of
Markdown allows me to focus on content in my presentations as opposed
to formatting.

This summer I've been teaching
[CSE30: Computer Organization and Systems Programming](http://cseweb.ucsd.edu/classes/su15/cse30-a/index.html). In
the past, I've not really spent much time preparing for discussion
section because few students regularly show up, but in an effort to
improve my teaching and presentation skills I've decided to come to
class prepared with a detailed presentation. It's debatable whether
this is better than having less structure, talking more off-script,
and using the blackboard. For me, since I still get nervous when
presenting, I find that having a lot of text helps me stay calm. I
still struggle with maintaining eye contact and not reading off
slides, but I think having a coherent presentation is a good first
step to developing my teaching experience.

The awesome thing about the Pandoc-Beamer-PDF workflow is that I can
just type up my points in outline form and format them using
Markdown's intuitive syntax, allowing me to focus on content vs
presentation. I have a simple Makefile that converts my Markdown file
to PDF using pandoc. When I need to specify some more complex
formatting rules or equations, I can insert LaTeX which is passed
through directly to LaTeX.

One of the "issues" with Beamer is that the default templates are
rather bland and dated. While it's arguably not important for the
presentation to be "hip" and "modern" as long as the content is good,
having a visually pleasing presentation never hurts, and thankfully
there's an alternative Beamer theme named
[Metropolis](https://github.com/matze/mtheme/) which features
an excellent modern font (Mozilla's Fira Sans) and clean layout. Using
it is as simple as specifying a TeX header file when calling Pandoc.

For full details, check out
[the code](https://github.com/ibrahima/cse30/tree/master/disc4) for
one of my discussion section presentations.
