---
tags:
- tech
- blindness
- text
date: "2020-02-23T13:46:56Z"
title: text formatting for the blind
---

Text formatting is used in many areas, from books, newspapers,
articles, websites, and documents. Paragraphs, headings, lists,
italics, bold, and many other characteristics are used to emphasize,
denote chapters, and mark changes in scenes or actions. Sighted users
can use formatting to find points of interest in text. What about
people who are blind? Is formatting effective for us? Can it be
useful?

In this article, I will explore text formatting, and how blind people
use it or dismiss it. Like all of my other articles, this one will
contain opinions. This area is one that I feel should be discussed,
however, because it is an area of inclusion that I feel blind people
have ignored, and sighted people haven’t generally approached.


# Introduction

Text formatting is pretty much just information about text to a
computer. A bolded word, an italicized title, a heading line, or a
list of items are all ways of formatting. Sighted people see all this
in the context of their chosen font, but screen readers only read, by
default, a small set of textual attributes, and only by describing
what the attribute is.

If a screen reader user turns on the reading of styles or formatting,
the screen reader will, italics on describe italics off, the
formatting, which can become verbose, and sometimes doesn’t help
because the screen reader doesn’t pause after speaking formatting
characteristics, meaning that the user has to quickly parse what the
screen reader is saying.

So, is that it? Is the only choice for a user to hear little to no
formatting information, or hear it all in a quick procession of words?
There are other options, better in fact than anything done by most
visual interfaces so far.

# How blind people format text

Blind people have a few ways of formatting text. The visual method
requires users to press a command, write their text, press the command
again, and review formatting with the screen reader. Braille allows
blind people to feel formatting, if supported by the screen reader.
Markup languages allow blind people to type formatting symbols around
text, which they can review with normal text navigation functions.

## Visual

The most popular way of formatting for sighted users, choosing a
formatting attribute from a tool bar, is also how blind people format,
most of the time, using keyboard commands. It is easy because it is
familiar. All word processors support this, using similar keyboard
commands for bold, italics, underline, and indentation. Some word
processors, like LibreOffice on Windows, do not speak when these
keyboard commands are pressed, so users have to trust in their
keyboarding.

The problem with this approach is that one has to turn on the reading
of font information, like styles, for a screen reader user to be sure
when a particular formatting style begins and ends, and that a program
may not speak when formatting commands are pressed. Screen readers do,
usually, read headings and lists without needing settings changes, but
that’s about all. JAWS for Windows can be configured to [speak or play
sounds](https://doccenter.freedomscientific.com/doccenter/doccenter/rs25c51746a0cc/2012-06-20_TextFormatting/02_TextFormatting.htm)
for formatting, but most users do not realize that this feature is
available, and so it is not used.

Not all is lost, however. Narrator now has the ability to read
formatting using different speech settings, like a change in pitch,
volume, or rate. VoiceOver on the Mac can "beep" for formatting
changes, although that doesn’t tell us *which* formatting information
was used. NVDA has begun working on refactoring its speech system, so
in the future, NVDA may be able to do what Narrator does, and more.
Imagine hearing sounds for each text attribute, instead of even having
vocal indications.

## Braille

Braille is a tactile way of reading, and has plenty of standards for
showing formatting. If you get a book from a library in braille, it is
likely to have been formatted very well. Reading braille via screen
reader, however, is often a bland experience, with little to no
formatting information. Screen readers do show abbreviated symbols for
item types like headings, lists, and links, but not italics, bold,
underline, or anything else. One can use Status Cells, dots at the end
of a display used in a few screen readers to show text attributes, but
these are imprecise, as a formatted word would show, on that status
cell, as if the whole line were formatted. iOS uses this technique.
The largest problem with this is that there are standard braille
symbols for formatting, supported by the
[Liblouis](http://liblouis.org) translator at least; they simply
aren’t used. In Safari, formatted text is often placed in its own
item, but that still doesn’t tell us *which* text attribute was used.

The only screen reader that currently shows any text formatting is
NVDA. It can show emphasized text, but that’s all I’ve found. It used
to show more, and why it doesn’t now I don’t know. The Braille
Extender addon adds the ability for NVDA to show paragraph
indentation. All other screen readers just show words, just like
speech, without any trace of formatting.

## Text Markup

Text markup languages, like [Markdown](https://commonmark.org),
[Org-mode](https://orgmode.org), and
[HTML](https://en.wikipedia.org/wiki/HTML) allow the user to write a
document, web page, blog post, or book using formatting that anyone
can read. Screen readers may need to be set to speak most punctuation,
and in the case of Markdown and Org-mode, set to repeat more than
three characters. This is even used in contexts where it is not
supported, like Email, forum posts, and texts.

This type of formatting, for now, is the most accessible. It can be
read using speech or braille, and can often be previewed in a browser
or other format if a user isn’t confident in using the markup style.
Because of this level of accessibility, I believe that Markdown, or
even better, Org-mode, should be a part of text editing, everywhere,
in all operating systems. A user could write in Markdown, and the text
would visually be formatted, allowing all those \*italics\* to not go
to waste. If you use Emacs with
[Emacspeak](http://github.com/tvraman/emacspeak/), you hear formatting
when reading websites, Markdown and Org-mode files, and syntax
highlighting with source code.

# Why blind people dismiss formatting

If you are sighted, imagine a world with no formatting. No italics, no
bold, no underline, just some headings, lists, and block quotes, all
practically the same, and absolutely no color. This is, even using
braille display, what blind people get. There aren’t even any separate
paragraphs, just chunks of text on mobile and Mac, and one long page
with some headings for division on Windows. Would you enjoy this?

If you are blind, you already know this world, and probably don’t
consider the possibility that at least one word on this page is
italicized, because for you, there is no formatting; it simply doesn’t
exist. Blind people don’t particularly like formatting because we
can’t really use it on the most popular system, Windows, with the most
popular screen readers, NVDA and JAWS, without much frustration. We
don’t dismiss it because we  don’t like the idea, we dismiss it
because we don’t have access to that information, and don’t see the
uses for it.

# How formatting can be useful

Let’s start with the obvious. Headings can mark chapters of a book,
sections of an article, and allow quick navigation through a page for
blind people. Lists are useful for itemizing content. Block quotes
are useful for long quotations.

What about the more invisible formatting, at least for blind people?
Italics is great for *emphasizing* things, bold makes things stand
out, and underlining is good for making something notable. If screen
readers spoke these things using differing speech parameters, or even
sounds, I’m sure that most blind people would find that they add some
color to our Grey, lifeless text, and make things we write look much
better to sighted readers.

# Conclusion

What do you think, reader? Do you care about formatting enough to use
[Pandoc](https://pandoc.org) on just about every Word document, like
me, in order to see formatting? Would you rather not know about
formatting on your favorite websites? If you can see, do you not
really notice formatting, or do you find it essential and beautiful?
Please, let me know. I’d love to hear your feedback, whether it come
through Email, Twitter, or even a contribution to my blog’s [Github
repository](https://github.com/devinprater/devinprater.github.io).
Again, thanks for reading!
