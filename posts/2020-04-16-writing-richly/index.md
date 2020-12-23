---
tags:
- blindness
- apple
- text
date: "2020-04-16T01:47:34Z"
title: Writing Richly
description: Why Markdown system wide can improve writing and reading
---

Whenever you read a text message, forum post, Tweet, or Facebook
status, have you ever seen some one surround a word with stars, like
`*this*`? Have you noticed some one surround a phrase with two stars?
This is Markdown, a form of formatting text for web usage.

I believe, however, that Markdown deserves more than just web usage. I
can write in Markdown in this blog, I can use it on Github, and even
in a few social networks. But wouldn’t it be even more useful
everywhere? If we could write in Markdown throughout the whole
operating system, couldn’t we be more expressive? And for
accessibility issues, Markdown is great because a blind person can
just write to format, instead of having to deal with clunky, slow
interfaces.

So, in this article, I will discuss the importance of rich text, how
Markdown could empower people with disabilities, and how it could work
system-wide throughout all computers, even the ones in our pockets.

## What’s this rich text and who needs all that?

Have you ever written in Notepad? It’s pretty plain, isn’t it? That is
plain text. No bold, no italics, no underline, nothing. Just, if you
like that, plain, simple text. If you don’t like plain text, you find
yourself wanting more power, more ability to link things together,
more ways to describe your text and make the medium, in some ways, a
way to get the message across.

Because of this need, rich text was created. One can use this in Word
Pad, Microsoft Word, Google Docs, LibreOffice, or any other word
processor worth something. When I speak of rich text, to make things
simple, I mean anything that is not plain text, including HTML, as it
describes rich text. Rich text is in a lot of places now, yes, but it
is not everywhere, and is not the same in the places that it is in.

So, who needs all that? Why not just stick with plain text? I mean
come on man, you’re blind! You can’t see the rich text. In a way, this
is true. I cannot see the richness of text, but in a moment, we’ll get
to how that can be done. But for sighted people, which text message is
better?

Okay, but how’s your day going?

Okay, but how’s *your* day going?

	Okay, but how’s *your* day going?

For blind people, the second message has the word “your” italicized.
Sure, we may have gotten used to stars surrounding words meaning
something, but that is a workaround, and not nearly the optimal
outcome of rich text.

So what can you do with Markdown? You can do plenty of stuff. You
could use it for simply using one blank line between blocks of text to
show paragraphs in your journal. You could use it to create headings
for chapters in your book. You could use it to make links to websites
in your email. You could even simply use it to italicize an emphasized
word in a text. Markdown can be as little or as much as you need it
to. And if you don’t add any stars, hashes, dashes, brackets, or HTML
markup, it’s just as it is, plain text.

Also, it doesn’t have to be hard. Even Emacs, an advanced text editor,
gives you questions when you add a link, like “Link text,” “Link
address,” and so on. Questions like that can be asked of you, and you
simply fill in the information, and the Markdown is created for you.

## Okay but what about us blind people?

To put it simply, Markdown shows us rich text. In the next section,
I’ll talk about how, but for now, let’s focus on why. With nearly all
screen readers, text formatting is not shown to us. Only Narrator on
Windows 10 shows formatting with minimal configuration, and JAWS can
be used to show formatting using much configuration of speech and
sound schemes.

But, do we want that kind of information? I think so. Why wouldn’t we
want to know exactly what a sighted person sees, in a way that we can
easily, and quickly, understand? Why would we not want to know what an
author intended us to know in a book? We accept formatting symbols in
Braille, and even expect it. So, why not in digital form?

NVDA on Windows can be set to speak formatting information as we read,
but it can be bold on quite arduous to hear italics on all this
italics off as we read what we write bold off. Orca can speak
formatting like NVDA, as well. VoiceOver on the Mac can be set to
speak formatting, like NVDA, and also has the ability to make a small
sound when it encounters formatting. This is better, but how would one
distinguish bold, italics, or underline from a simple color change?

Even VoiceOver on iOS, which arguably gets much more attention than
its Mac sibling, cannot read formatting information. The closest we
get is the phrase separated from the rest of the paragraph into its
own item, showing that it’s different, in Safari and other web apps.
But how is it different? What formatting was applied to this
“different” text? Otherwise, text is plain, so no blind people even
know that there is a possibility of formatting, let alone that that
formatting isn’t made known to us by the program tasked with giving us
this information. In some apps, like notes, one can get some
formatting information by reading line by line in the Note text field,
but what if one simply wants to read the whole thing?

Okay but what about writing rich text? I mean, you just hit a hotkey
and it works, so what could be better than that? First, when you press
Control + I to italicize, there is no guarantee that “italics on” will
be spoken. In fact, that is the case in LibreOffice for Windows: you
do not know if the toggle key toggled the formatting on or off. You
could write some text, select it, then format it, but again, you don’t
know if you just italicized that text, or removed the italics. You may
be able to check formatting with your screen reader’s command, but
that’s slow, and you would hate to do that all throughout the
document. Furthermore, dealing with spoken formatting as it is, it
takes some time to read your formatted text. Hearing descriptions of
formatting changes tires the mind, as it must interpret the fast-paced
speech, get a sense of formatting flipped from off to on, and quickly
return to interpreting text instead of text formatting instruction.
Also, because all text formatting changes are spoken like the text
surrounding it, you may have to slow down your speech just to get
somewhat ahead of things enough to not grow tired from the relentless
text streaming through your mind. This could be the case with star
star bold or italics star star, and if screen readers would use more
fine control of the pauses of a speech synthesizer, a lot of the
exhausting sifting through of information which is rapidly fired at us
would be lessened, but I don’t see much of that happening any time
soon.

Even on iOS, where things are simpler, one must deal with the same
problems as on other systems, except knowing if formatting is turned
on or off before writing. There is also the problem of using the touch
screen, using menus just to select to format a heading. This can be
worked around using a Bluetooth keyboard, if the program you’re
working in even has a keyboard command to make a heading, but not
everyone has, or wants, one of those.

Markdown fixes, at least, most of this. We can *write* in Markdown,
controlling our formatting exactly, and *read* in Markdown, getting
much more information than we ever have before, while also getting
less excessive textual information, hearing “star” instead of “italics
on” and “italics off” does make a difference. “Star” is not usually
read surrounding words, and has already become, in a sense, a
formatting term. “Italics on” sounds like plain text, is not a symbol,
and while it is a formatting term, has many syllables, and just takes
time to say. Coupled with the helpfulness of Markdown for people
without disabilities, adding it across an entire operating system
would be useful for *everyone*; not just the few people with
disabilities, and not just for the majority without.

## So, how could this work?

Operating systems, the programs which sit between you and the programs
you run, has many layers and parts working together to make the
experience as smooth as the programmers know how. In order for
Markdown to be understood, there must be a part of the operating
system that translates it into something that the thing that displays
text understands. Furthermore, this thing must be able to display the
resulting rich text, or Markdown interpretation, throughout the whole
system, not just in Google Docs, not just in Pages, not just in Word,
but in Note Pad, in Messages, in Notes, in a search box.

With that implemented, though, how should it be used? I think that
there should be options. It’s about time some companies released their
customers from the “one size fits all” mentality anyway. There should
be an option to replace formatting done with Markdown with rich text
unless the line the formatting is on has input focus, a mode for
simply showing the Markdown only and no rich text, and an option for
showing both.

For sighted people, I imagine seeing Markdown would be distracting.
They want to see a heading, not the hash mark that makes the line a
heading. So, hide Markdown unless that heading line is navigated to.

For blind people, or for people who find plain text easier to work
with, and for whom the display of text in different sizes and font
faces is jarring or distracting, having Markdown only would be great,
while being translated for others to see as rich text. Blind people
could write in Markdown, and others can see it as rich text, while the
blind person sees simply what they wrote, in Markdown.

For some people, being able to see both would be great. Being able to
see the Markdown they write, along with the text that it produces,
could be a great way for users to become more comfortable with
Markdown. It could be used for beginners to rich text editing, as
well.

### But, which version of Markdown should be used?

As with every open source, or heatedly debated, thing in this world,
there are many ways of doing things. Markdown is no different. There
is [strict Markdown](https://github.com/mmark-md/mmark), [Common
Mark](https://commonmark.org), [Github Flavored
Markdown](https://github.github.com/gfm/), [Swift
Markdown](https://nshipster.com/swift-documentation/), [Pandoc
Markdown](https://pandoc.org/MANUAL.html), and probably many others. I
think that Pandoc’s Markdown would be the best, most extended variant
to use, but I know that most operating system developers will stick
with their own. Apple will stick with Swift Markdown, Microsoft may
stick with Github Markdown, and the Linux developers may use Pandoc,
if Pandoc is available as a package on the user’s architecture, and if
not, then it’s some one else’s issue.

## Conclusion

In this article, I have attempted to communicate the importance of
rich text, why Markdown would make editing rich text easy for
everyone, including people with disabilities, and how it could be
implemented. So now, what do you all think? Would Markdown be helpful
for you? Would writing blog posts, term papers, journal entries, text
messages, notes, or Facebook posts be enhanced by Markdown rich text?
For blind people, would reading books, articles, or other text, and
hearing the Markdown for bold, italics, and other such formatting make
the text stand out more, make it more beautiful to you, or just get in
your way? For developers, what would it take to add Markdown support
to an operating system, or even your writing app? How hard will it be?

Please, let me know your thoughts, using the contact info, or replying
to the posts on social media made about this article. And, as always,
thank you so much for reading this post.
