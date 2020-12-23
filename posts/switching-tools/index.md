---
title: "Switching Tools"
date: 2020-08-07T21:57:53-05:00
draft: false
tags:
- blindness
---

This is basically a test post. I've switched from Emacs to VS Code, and I'll
detail why below. The gist is that Emacs is unhelpful, only easy to set up on Mac
and Linux, and Emacs packages are not standard, and Emacspeak, the speech
extension for Emacs, just can't keep up with extensions like LanguageTool, and
probably won't because coding is Emacs' main use case, not writing.

## Why I used Emacs

Emacs has been my work tool for about a year now. I went along with its strange
commands, and even got to liking them. I memorized strange terminology in order
to get the most of the editor. Don't get me wrong, Emacs is a wonderful tool,
and Emacspeak allows me to use it with confidence and even enjoyment.

Before the end, I was writing blog posts, both here and on a Wordpress blog,
using Git and GitHub, and even reading EBooks. I also adore Org-mode, which I
still find superior to anything else for note taking, compiling quick reports,
and just about anything writing-related. Seriously, being able to export just
one part of a file, instead of the whole large file containing every bit of
work-related notes, is huge, and I'll now have to use folders, subfolders,
and folders under those to come close to achieving that level of
productivity. And no, the Org-mode extension for VS Code doesn't have a third of
the ability of the native Emacs Org-mode.

But, Emacs was founded on the do-it-yourself mentality, and it'll stay that way.
If you don't know what to look for, Emacs will just sit there, without any
guidance for you. I'll get more into that as I compare it with VS Code.

## Making Good out of Bad

One day, my MacBook, which is what I run Emacs on, ran very low on battery. It
was in the morning that day, and I have a Windows computer also, so I decided to
see if I could get things done on it. I'd tried writing on it before, using
Markdown in Word, or even VS Code before. But my screen reader, NVDA, wouldn't
read indentation like Emacspeak did, or pause between reading formatting symbols in Markdown like
Emacspeak did, play sounds for quick alerts of action like Emacspeak did, or
even have a settings interface like Emacs did, and definitely didn't have a
voice like Alex on the Mac. Those were my thoughts when I'd tried it before.
I'll tackle them all, now that I've used VS Code for almost a week.

So, I managed to get Markdown support close to how I used it in Emacs, minus the
quick jumping between headings with a single keyboard command. I still miss
that. The LanguageTool extension works perfectly, although I had to learn that
to access the corrections it gave I have to press **Control + . (period)**.
Every extension I've installed so far has worked with NVDA. I cannot say that
for Emacs with Emacspeak. Since the web is so standardized, there isn't too much
an extension could do to not be accessible. Sometimes I wish the suggestions
didn't pop up all the time in some language modes, but I'll take that any day
over inaccessibility.

So, on with debunking the problems I had at first. Hopefully this will help
newcomers to VS Code, or those who are cynical that basically a web app can do
what they need:

### NVDA doesn't read indentation!

Yes, it can. It can either speak the indentation, or beep, starting at, I
believe, low C for the baseline and moving up tones. Sometimes I have to pay a
bit of attention to notice the difference between no space and one space, but
that's what having it speak is for.

### NVDA doesn't pause between formatting symbols!

This is true, and unavoidable for now. But, unlike Emacspeak, NVDA has the
ability to use a braille display, which makes reading, digesting information,
and learning a lot easier for those whose mind, like mine, is more like a train
than a race car. In the future, NVDA's speech refactoring may make pausing, or
changing pitch for syntax highlighting, a reality.

## VS Code doesn't play sounds!

This is true too, and I've not found a setting or extension to make this happen.
Maybe one day...

## VS Code doesn't even have a settings interface!

Before, I thought one had to edit the JSON file for settings to change them. It
turns out that if you press **Control + , (comma)**, you get a simple, easy,
Windows interface. This is a bit rough around the edges, because you have to Tab
twice from one setting to the next, and you could roam from one section of
settings to another, but it's easier than Emacs.

## But what about the awful Windows voices!

Yes, Windows voices still are dry and boring, or sound fuzzy, but NVDA has many
options for speech now. I've settled on one that I can live with. No, it doesn't
have the seeming contextual awareness of paragraphs like Alex, but it's Windows.
I can't expect *too* much.

## Bonus points for VS Code

### Git

I'm only now starting to get Git. It's a program that allows you to keep
multiple versions of things, so you can roll back your work, or even work on
separate parts of your work in separate branches of the project. Emacs just...
sits there as usual, assuming you have any idea of what you're doing. VS Code,
though, actively tries to help. If you have Git, it offers an extension for
that. If you open a Git repository, it asks if you'd like it to fetch changes
every once in a while to make sure things are up-to-date when you commit your
changes. I was able to commit a pull request in VS Code easily and with minimal
fuss. In Emacs, I didn't even know where to begin. And any program that takes
guessing and meaningless work off my shoulders is a program I'll keep.

### Suggestions while typing

VS Code is pretty good at this. If I'm writing code, it will offer suggestions
as I type. Sometimes they're helpful, sometimes they aren't. In text modes, this
doesn't happen; it appears that this only happens in programming modes. Emacs
would just let you type and type and type, and then browsing Reddit you'd find
out about snippet packages that may or may not work with Emacspeak.

### Standardized

As mentioned before, VS Code is basically a web app. Emacs is a program written
in mostly Emacs Lisp, and a bit written in C. Extensions in VS Code are written
in JavaScript, whereas extensions in Emacs are written in its Lisp dialect.
Since Emacs is completely text based, any kind of fancy interface must be made
manually, which usually means that Emacspeak will not work with it, unless the
author, or a community member, massages the data enough to make it work. This is
a constant battle, and it won't get easier for anyone involved.

VS Code is a graphical tool that has plenty of keyboard commands, and screen
reader support. Its completion, correction, and terminal processes have already
been created, so all extensions have to do is hook into that. This means that a
lot of extensions are accessible, without even knowing it.

## So, any downsides to VS Code?

VS Code is not perfect by any stretch. When screen reader support is enabled, a
few features are actually disabled because Microsoft doesn't know how to convey
them to the user without using sound. Code folding is disabled, which would make
navigating markdown a lot simpler. Word wrapping is disabled, meaning that a
paragraph is on one very long line. I've found Rewrap, a third-party extension
that I can use, so that's fixed. There are no sounds, so the only way I know
there are problems is by going to the next problem, or opening the issues panel.

Overall though, VS Code has impressed me, and I continuously find wonderful,
time-saving, mind-clearing moments where I breathe a sigh of relief that to
create a list in markdown, I can just select lines of text, and choose “toggle
list” from the commands panel, whereas with Emacs I had to mark the list of
lines and remember some strange command like “string-insert-rectangle” and type
“\*” to make all of those list items. These kinds of time-savers make me more
productive, offsetting slightly the lack of features akin to those in Org-mode.

## Conclusion

I didn't expect this post to be so long, but it will be a good test to see if VS
Code's Hugo support is enough to replace Easy-Hugo on Emacs. While VS Code
doesn't have a book reader, at least, not one I think I'd like, or a media
player with Tune-In Radio support made for the blind, and many other packages,
it is a great editor, and does have tools like Hugo extensions that make it
slightly more that an editor. I should branch out more and see what tools
Windows now has for these functions anyways. I already use Foobar2000 for media,
I just have to find a good book reader that doesn't get rid of formatting info.

So, I hope you all have enjoyed reading this long test of VS Code, and an update
on what I've been doing lately when not playing video games and other things.

In other news, I've been using the iOS 14 and macOS 11 public betas. I'll report
on my findings on those when the systems are released this fall.
