# Awesome Markdown Alternatives
A collection of awesome light-weight markup markdown alternatives (libraries, services, editors, tools, cheatsheets, etc.) 

---

[ANNOUNCEMENT] Looking for the latest news, tools, tips & tricks, and more
about markdown and friends?
Follow along the MundiMark News ([@mundimark](https://github.com/mundimark/awesome-markdown-alternatives)) channel on github for updates.

---


#### _Contributions welcome. Anything missing? Send in a pull request. Thanks._

## Table of Contents

<!--

Generated with [markedpp](#markedpp). Get [nodejs](https://nodejs.org) first

1. $ npm i -g markedpp
2. $ markedpp --github -o README.md README.md

-->

<!-- !toc (minlevel=2 omit="Table of Contents") -->

* [Markdown Syntax Extensions Alternatives](#markdown)
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

### [Djot](https://djot.net/)
Djot is a light markup syntax. It derives most of its features from commonmark, but it fixes a few things that make commonmark's syntax complex and difficult to parse efficiently. It is also much fuller-featured than commonmark, with support for definition lists, footnotes, tables, several new kinds of inline formatting (insert, delete, highlight, superscript, subscript), math, smart punctuation, attributes that can be applied to any element, and generic containers for block-level, inline-level, and raw content. The project began as an attempt to implement some of the ideas I suggested in Beyond Markdown.
```
_This is *regular_ not strong* emphasis
[My link text][]
[My link text]: /url
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

### [reStructuredText (rst, reST)](http://en.wikipedia.org/wiki/ReStructuredText)
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

### [Dendron todo](https://wiki.dendron.so/)
This goes over how we format todo notes at Dendron.

```
- [x] foo task <!-- finished task -->
- [d] foo task <!-- not doing task, no longer relevant -->
- [.n] foo task <!-- got to task but not done, moving to tomorrow. note that statuses can be stacked -->
- [m] foo task <!-- did not get to task, moving to backlog -->
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
Plain text
End a line with two spaces to start a new paragraph.
*italics* and _italics_
**bold** and __bold__
superscript^2^
~~strikethrough~~
[link](www.rstudio.com)
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6 
```

### [foam](https://foambubble.github.io/)
Foam is a personal knowledge management and sharing system inspired by Roam Research, built on Visual Studio Code and GitHub. Foam uses standard Markdown, with a few added twists:
- the title of a note (e.g. in the Graph Visualization) is given by precedence based on:
- the title property (see Note Properties)
- the first # heading 1 of the file
- the file name

### [TodoFlow](https://github.com/bevesce/TodoFlow)
Tools for working with plain text todo lists.
```
project 1:
    - task 1
    - task 2 @today
project 2:
    - task 3
```

### [Plaintodo](https://github.com/ota42y/plaintodo)
plain text based todo list .plaintodo
```
// ./tasks/home_tasks.txt have 3 tasks

home :subTaskFile ./tasks/home_tasks.txt
  task 1 in home_tasks.txt
  task 2 in home_tasks.txt
  task 3 in home_tasks.txt
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
Powerful Asciidoctor alternative with Markdown syntax
```
Absurd claim. [This is some footnote text][^] [Another footnote][^]

@FOOTNOTES
```

### [Raylib_DrawTextStyle](https://github.com/NightenDushi/Raylib_DrawTextStyle)
An alternative DrawText function with basic Markdown and custom line spacing
```
*italic*
**Bold**
~wave animation~
~~crossed~~
__underline__
DrawTextStyle("~Hellooo~ :D", 100,100, DARKGRAY)
```

### [ssmd](https://github.com/machisuji/ssmd)
Speech Synthesis Markdown (SSMD) is a lightweight alternative syntax for SSML
```
require 'ssmd'

ssmd = "hello *SSMD*!"
ssml = SSMD.to_ssml ssmd

puts ssml
# Output: <speak>hello <emphasis>SSMD</emphasis>!</speak>
```

### [johndown](https://github.com/jcinnamond/johndown)
A Markdown alternative
```
~italic~
*bold*

`code`

(link name)http://some/thing

# H1
## H2
### H3
#### H4
##### H5

:code:
Some code
:code:

:quote:
A blockquote
:quote:

:dnf:
Some format
:dnf:

1. Numbered list item
- Unordered list item

----- HR

\* escape
```


### [jot](https://github.com/shbhrsaha/jot)
An alternative Markdown language specially-designed for intuitive, efficient note-taking
```
Your Title Here
Author Name Here

_ Section Title
_ _ Subsection Title
First paragraph stuff goes here.

Leave a blank line to mark the next new paragraph.

- first item in list
- second item in list

_image This is the title of the image (title optional)
graph1.png
This is the image caption

_ Remarks

I should make the following remarks:
```

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
```
- [ ] Todo
- [x] Finished todo
- [>] Migrated from daily log to new monthly log
- [<] Migrated to appropriate month in future log
- [~] Not worth doing
- note
* event
- [[ ]] Important todo
```

### [markdown-bullet-journal](https://github.com/dballard/markdown-bullet-journal)
A digital bullet journal using markdown and daily migrations
```
- Complex task
    - [ ] Subpart A
        - [x] Task 1
```

### [.bulletjournal.md](https://github.com/fulgor/bulletjournal.md)
Bullet Journal in an plain textfile with Markdown formatting
```
.  task [2]
x  done
>  postponed
o  event
a  abandoned
w  waiting for [person | circumstance]
!  adds priority
```

### [SR-Markup-Lang](https://github.com/BluFedora/SR-Markup-Lang)
An alternative to Markdown for my blogging needs
```
@TagWithNoContentOrAttributes

@TagWithNoAttributes { Some Content }

@TagWithNoContent(Attrib = "Hello")

@"Tag With Spaces In The Name"
```

### [Remark](https://github.com/BradSharp/Remark)
A simple backwards-compatible alternative to Markdown. In Remark each modifier has a unique symbol, this avoids any ambiguity when rendering them:

Modifier | Remark | Markdown
--- | --- | ---
Bold | `!!Bold!!` | `**Bold**` or `__Bold__`
Italic | `**Italic**` | `*Italic*` or `_Italic_`
Underline | `__Underline__` | Unsupported
Strikethrough | `~~Strikethrough~~` | `~~Strikethrough~~`
Monospace | ``` ``Monospace`` ``` | `` `Monospace` ``


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

### [bujo](https://github.com/mihaiconstantin/bujo)
Bullet Journal syntax highlighting in VS Code Markdown files. BuJo goes beyond syntax highlighting and taps into time tracking and time blocking methodologies (e.g., Newport, 2016). To this end, BuJo proposes commands and keybindings to effortlessly update task statuses, plan working days, and track the time spent on tasks.
```
- [ ] Represents a task.
- [x] Represents a completed task.
- [>] Represents a task migrated forward.
- [<] Represents a task migrated backward.
- [/] Represents a task in progress.
- [-] Represents a dropped task.
- [o] Represents an event.
- Represents a note. Nothing special about it.
```


### [monthly-planning-files](https://github.com/ryan-p-randall/monthly-planning-files)
Text files to help plan & log whatever it is you do. Bullet journal + pomodoro technique + text editors + cloud syncing = progress.
```
#### 2019-12-03 Tuesday  

1. [x] 10:00am--11:00am | Meeting, Office 110  
2. [ ] 2:00pm--2:30pm | Get over to Main Library  
3. [ ] 2:30pm--5:00pm | Reference Desk Shift, Main Library  

<!-- -->  

- [x] start writing documentation for `monthly-planning-files` project @done(added sections; still need to go into detail about tags, why there are HTML comments, etc)  
  - [x] start a changelog @done(15minutes)  
- [ ] add detail to `monthly-planning-files` documentation  
  - [ ] give tag examples  
  - [ ] explain html comments  
- [ ] proofread documentation
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

### [Bullet journal in plain bash](https://josh.vanderhook.info/2021-03-bullet-journalling.html)
For managing todos, I use bullet journal. Bullet Journalling has become quite a fad lately, with frothing-at-the-mouth reviews like “It will make you a better person!” How can you argue with that simple, artistically drawn ven diagram where it lies at the center of “Why” and “What”?
```
- [ ] water the lawn
- [x] write up analysis for steve
- [>] complete AAS paper revisions
- [>] Add image to Keck report
- [x] take dog on a walk
- [ ] schedule a doctor appointment
- [ ] water the lawn
- [^] cross-compile scheduler 
- [-] runtime reports 
- [v] pick up vitamins
```

## Articles
- [Try AsciiDoc instead of Markdown](https://opensource.com/article/22/8/drop-markdown-asciidoc)
- [Use Plain Text E-mail](https://useplaintext.email/)
- [I still use plain text for everything and I love it](https://lifehacker.com/i-still-use-plain-text-for-everything-and-i-love-it-1758380840)
- [dariubs/awesome-markdown](https://github.com/dariubs/awesome-markdown)
- [Bullet Journal for RPGs](https://bulletjournal.com/blogs/bulletjournalist/bullet-journals-for-rpgs)
- [Markdown for Bloggers](http://andybrandt531.com/2015/03/markdown-for-bloggers-part-6-monster-list-of-markdown-tools/)
- [Other Markdown Tools](https://github.com/adam-p/markdown-here/wiki/Other-Markdown-Tools)
- [GitHub Bullet Journal Research](https://github.com/topics/bullet-journal?o=desc&s=updated)
- [GitHub Bullet Journal Alternatives](https://github.com/topics/bullet-journal?o=desc&s=forks)
- [GitHub Bullet Journal Types](https://github.com/topics/bullet-journal)
- [GitHub Bullet Journal Typescript](https://github.com/topics/bullet-journal?l=typescript)
- [One week bullet journaling with Markdown + Syncthing](https://blog.fibasile.com/one-week-bullet-journaling/)


## Meta

**License**

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Send them along to the markdown-discuss mailing list. Thanks!

## Notes
Add link to Wikipedia light-weight markup languages

Add link to Wiki Matrix ??
