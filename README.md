# Awesome Series @ Write Kit

[Markdown (Syntax & Extensions, Documentation & Cheat Sheets, Libraries, ...)](https://github.com/writekit/awesome-markdown) • 
[Markdown Editors & (Pre)viewers](https://github.com/writekit/awesome-markdown-editors)  •
[Books (Services, Hand-Written, Auto-Built w/ Open Data, ...)](https://github.com/writekit/awesome-books)

A collection of awesome light-weight markup markdown alternatives (libraries, services, editors, tools, cheatsheets, etc.) 

Note: :octocat: stands for the GitHub page and :gem: stands for the RubyGems page.

---

[ANNOUNCEMENT] Looking for the latest news, tools, tips & tricks, and more
about markdown and friends?
Follow along the Manuscripts News ([@manuscriptsnews](https://twitter.com/manuscriptsnews)) channel on twitter for updates.

---


#### _Contributions welcome. Anything missing? Send in a pull request. Thanks._

## Table of Contents

<!--

Generated with [markedpp](#markedpp). Get [nodejs](https://nodejs.org) first

1. $ npm i -g markedpp
2. $ markedpp --github -o README.md README.md

-->

<!-- !toc (minlevel=2 omit="Table of Contents") -->

* [Markdown Alternatives](#markdown)
* [Markdown Syntax Extensions Alternatives](#markdown-syntax-extensions)
  * [Todo.md (.todo)](#multimarkdown-mmd)
* [Articles](#articles)
* [Meta](#meta)

<!-- toc! -->

# Markdown Syntax Extensions Alternatives

### Wikipedia [Wikitext](http://en.wikipedia.org/wiki/Help:Wiki_markup) / Wikicode
Wiki markup used by Wikipedia and friends

```
= Heading 1 =
== Heading 2 ==
'''bold'''
''italics''
[http://www.wikipedia.org/ Wikipedia]
```

### [Creole](http://en.wikipedia.org/wiki/Creole_(markup))
"Standardized" core Wikitext markup

```
= Heading 1 =
== Heading 2 ==
**bold**
//italics//
[http://www.wikipedia.org/|Wikipedia]
```

### [AsciiDoc](http://en.wikipedia.org/wiki/AsciiDoc)
```
= Heading 1
== Heading 2
**bold**
__italics__
http://www.wikipedia.org/[Wikipedia]
```

### [Textile](http://en.wikipedia.org/wiki/Textile_(markup_language))
```
h1. Heading 1
h2. Heading 2
*bold*
_italics_
"Wikipedia":http://www.wikipedia.org/
```

### reStructuredText (rst, reST)](http://en.wikipedia.org/wiki/ReStructuredText)
```
Heading 1
=========
Heading 2
---------
**bold**
*italics*
.. _Wikipedia: https://www.wikipedia.org/
```

### [BBCode](http://en.wikipedia.org/wiki/BBCode)
Bulletin board code
```
[heading]Heading 1[/heading]
[b]bold[b]
[i]italics[i]
[url=https://www.wikipedia.org/]Wikipedia[/url] 
```

### [Pendown](https://github.com/senselogic/PENDOWN)
Lightweight markup for colored documents

```
! Heading 1
!! Heading 2
**bold**
%%italics%%
@@http://www.wikipedia.org/ Wikipedia@@
```

### [Rmarkdown](https://rmarkdown.rstudio.com/)
Markdown dialect
```
```

### [scroll](https://github.com/publicdomaincompany/scroll)
Extensible alternative to Markdown
```
import header.scroll

wideColumns 1

title Scroll Tutorial

belowAsCode 2
pParser
 extends thoughtParser
 crux p
p We can then make paragraphs using `p`.
```


### [unidok](https://github.com/Aloso/unidok)
Powerful Asciidoctor alternative with Markdown syntax.

### [Raylib_DrawTextStyle](https://github.com/NightenDushi/Raylib_DrawTextStyle)
An alternative DrawText function with basic Markdown and custom line spacing.

### [ssmd](https://github.com/machisuji/ssmd)
Speech Synthesis Markdown (SSMD) is a lightweight alternative syntax for SSML.

### [johndown](https://github.com/jcinnamond/johndown)
A Markdown alternative

### [jot](https://github.com/shbhrsaha/jot)
An alternative Markdown language specially-designed for intuitive, efficient note-taking.

### [alt](https://github.com/qeaml/alt)
Markdown alternative.

### [strawdown](https://github.com/LastCleanShirt/strawdown)
Straw Down Markdown Alternative.

### [mystmd](https://mystmd.org/)
```
MyST makes Markdown more _extensible_ & **powerful** to support an ecosystem of tools for computational narratives, technical documentation, and open scientific communication.

:::{important} Our Values
We believe in a community-driven approach of open-source tools that are composable and extensible.
:::
```

### [markzwei](https://github.com/seiferson/markzwei)
A Markdown alternative
```
 ***
Will produce: <horizontalrule />

    * * * *
Will produce: <horizontalrule />

* *    *
Wil produce: <paragraph>* *    *</paragraph>
(Max 1 space character is allowed between asterisks)
```

### [.bullet](https://github.com/cameronblandford/.bullet)
A Markdown alternative designed for bullet journaling

### [SR-Markup-Lang](https://github.com/BluFedora/SR-Markup-Lang)
An alternative to Markdown for my blogging needs
```
@TagWithNoContentOrAttributes

@TagWithNoAttributes { Some Content }

@TagWithNoContent(Attrib = "Hello")

@"Tag With Spaces In The Name"
```

### [Remark](https://github.com/BradSharp/Remark)
A simple backwards-compatible alternative to Markdown.

### [Todo.md (MMD)](https://github.com/todo-md/todo-md)
Plain text to-do lists todo.md
```
# TODO
This text is not a task.

# DONE
This is task.
- [x] This task is done #prio1
- [-] This task has been declined
```

### [Todo.txt](http://todotxt.org/)
Plain text to-do lists with format todo.txt
```
Really gotta call Mom (A) @phone @someday
(b) Get back to the boss
(B)->Submit TPS report
```

### [Plain Text Accounting](https://plaintextaccounting.org/)
Plain text accounting is a way of doing bookkeeping and accounting with plain text files and scriptable, command-line-friendly software, such as Ledger, hledger, or Beancount.
```
; a comment

2016/1/1 Heading 1
   bold:checking       $500.00
   bold:opening balances

2016/1/5 Heading 2
   bold:groceries     $50.00
   bold:checking
```

## Articles
- [Try AsciiDoc instead of Markdown](https://opensource.com/article/22/8/drop-markdown-asciidoc)
- [Use Plain Text E-mail](https://useplaintext.email/)
- [I still use plain text for everything and I love it](https://lifehacker.com/i-still-use-plain-text-for-everything-and-i-love-it-1758380840)
- [dariubs/awesome-markdown](https://github.com/dariubs/awesome-markdown)
- http://andybrandt531.com/2015/03/markdown-for-bloggers-part-6-monster-list-of-markdown-tools/
- https://github.com/adam-p/markdown-here/wiki/Other-Markdown-Tools

## Meta

**License**

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Send them along to the markdown-discuss mailing list. Thanks!

## Notes
Add link to Wikipedia light-weight markup languages

Add link to Wiki Matrix ??
