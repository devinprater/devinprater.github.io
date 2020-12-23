---
title: What I want to see at WWDC
date: June 1 2020
description: With WWDC just around the corner, here's what I want to see at Apple's developer conference
---

WWDC is Apple's "World Wide Developer Conference." It's where developers
come to learn about what will be new in Apple's operating systems (iOS,
iPad OS, MacOS, ETC.), and learn how to make the best of Apple's walled
garden of tools to program apps. Tech reporters also come to the event,
to gather all the news and distill it into the expected bite-sized,
simple pieces. Be assured, my readers, that I will not hold anything
back from you in my analysis of the event.

WWDC is not here just yet. I know, many news sites are predicting and
yammering and getting all giddy with "what if" excitement. I won't bore
you with such useless speculation just to fill the headlines and
homepages. I fear that I lack the imagination and incentive to create
such pieces. Besides, I'm more interested in what a device can *do*, and
less about how it looks or feels.

However, I am Invested in Apple's operating systems. I do want to see
Apple succeed in accessibility and think that, if they put enough work
into it, and gave the accessibility team more freedom and staff, that
accessibility would greatly improve. It is in that spirit that I give
you my hopes, not predictions, for WWDC 2020. This "wishlist" will be
separated into headings based on the operating system, and further
divided into subsections of that operating system. After WWDC, I will
revisit this post, and updated it with notes on WWDC if things change on
the wishlist, and then do a post containing more notes and findings from
the event.

## MacOS

MacOS is Apple's general computer (desktop/laptop) operating system.
With much tried and true frameworks and programs, it is a reliable
system for most people. It even has functions that Windows doesn't, like
the ability to select text anywhere and have that text spoken
immediately, not screen reader needed, and remap keyboard modifier keys,
and system wide spell checking. These help me greatly in all of my work.

Its screen reader is VoiceOver. It's like VoiceOver on the iPhone, but
made for a complex operating system, and has some complex keyboard
commands. Accessibility, like anywhere else, is not perfect on the Mac.
There are bugs that have stood for a long time, and new bugs that I fear
will hang around. There are also features that I'd love to see added, to
make the Mac even better.

In short, MacOS accessibility isn't a toy. I want the Mac to be treated
like it's worth something . From the many bugs, to missing features, the
Mac really needs some love accessibility-wise. Many tech "reporters" say
that the Mac is a grown and stable operating system. For blind people,
though, the Mac is shriveled and stale.

### Catalyst needs an accessibility boost

"Catalyst" is Apple's bridge between iPad apps and Mac apps. It allows
developers, Apple included, to bring iPad apps to the Mac. Started in
MacOS Mojave with Apple's own apps, Catalyst accessibility was...
serviceable. It wasn't great, but there wasn't anything we couldn't do
with the apps. It just wasn't the best experience. The apps were very
flat, and one needed to use the VoiceOver custom actions menu, without
the ability to use letter navigation, to select actions like one would
using the "actions" rotor on the iPad.

Now, in Catalina, the Catalyst technology is available for third-party
developers, but accessibility issues still remain. The apps don't feel
like Mac apps at all, not even Apple's own apps. So, in MacOS 10.16, I
hope to see at least Apple's own apps be much more accessible,
especially if the Messages app will be an iPad catalyst app.

### VoiceOver needs a queue

Screen readers convey information through speech, usually. This isn't
new for people who are blind, but what may be new is that they manage
what is spoken using a queue. This means that when you're playing a game
and new text appears, the screen reader doesn't interrupt itself from
speaking the important description of the environment just to speak that
an unimportant NPC just came into the area.

VoiceOver, sadly, does not have this feature, or if it does, it hardly
ever uses it. Now, it looks like the speech synthesis architecture has a
queue [built
in](https://developer.apple.com/documentation/avfoundation/avspeechsynthesizer),
so VoiceOver should be using this to great effect. But it isn't. This
means that doing anything complex in the Terminal app is unproductive.
Even using web apps, which have VoiceOver speak events, can be
frustrating when VoiceOver interrupts itself to say \"loading new
tweets\" and such. It was so bad that the VoiceOver team had to give the
option for a sound to play instead of the \"one row added\" notification
for the mail app.

This is a large oversight, and it has gone on long enough. So, in MacOS
10.16, I desperately hope that VoiceOver can finally manage speech like
a true screen reader, with a speech queue.

### Insertion point at... null

Long time Apple fans may know what the insertion point is. For Windows,
Android, and Linux users, it is the cursor, or Point. It is where you
insert text. On Mac and iOS, VoiceOver calls this the insertion point,
and it appears in text fields. The only problem is, VoiceOver says it
appears on read‐only places, like websites in earlier versions of MacOS
10.15, and emails to this day.

VoiceOver believes that there is an insertion point in the email
somewhere, but says that it is at "null", meaning that it is at 0, or
doesn't exist. That's because there isn't one. This only appears when
you are reading by element, **VO + Right or Left arrow**, and not when
you are reading by line with just the up and down arrows, where there is
a sort of cursor to keep track of where you are. But this cursor is,
most likely, a VoiceOver construct, so it should know that when moving
by element, there practically isn't one besides VoiceOver's own "cursor"
that is focusing on things.

This bug is embarrassing. I wouldn't want my supervisor seeing this kind
of bug in the technology that I use to do professional work. I stress
again that the Mac is *not* a toy. Yes, it has "novelty" voices, and
yes, some blind people talk like them for fun, or use them in daily work
to be silly. I don't, though, because the Mac is my **work** machine.
What's a computer, Apple asks? A Mac, that's what! I rely on this
computer for my job, and if things don't improve, I'll probably move to
Linux, which is the next best option for my workflow. Of course, things
there don't improve much either, but at least the screen reader is
actually used by its creator and testers, so silly bugs like that don't
appear in a **pro** device. So, in MacOS 10.16, I hope that the
accessibility team took a long vacation from adding stuff and spent a
lot of time on fixing MacOS' VoiceOver so that I can be proud to own a
Mac again.

### I need more fingers

The Mac has so many keyboard commands, and letter navigation in all
menus and lists make navigating the Mac a breeze. But some of the
keyboard commands were clearly made for a desktop machine. I have a
MacBook Pro, late 2019 with four Thunderbolt ports, but still the same
Function, Control (remapped to escape), Option, Command, Space, Command,
Option, Capslock (remapped to control because Emacs), keyboard layout.
In order to lock the screen, then, with the normal keyboard layout
(without remapping due to the touch bar and Emacs), I'd have to lock the
screen by holding the command key with my right thumb, hold control with
my left pinkie, and... and... how do I reach the Q? Ah, found it! I
think. That may be A, or 1, though.

My point is, we blind people pretty much **always** use the keyboard.
sure, we can use the track pad, but that's an option, not a requirement
like the touch screen of an iPhone. Keyboard commands should be
ergonomic, for every Mac model, not just the iMac. So, in Mac OS 10.16,
I hope to see more ergonomic keyboard commands for MacBooks. I hope
VoiceOver commands become more ergonomic as well, as pressing **Control
+ Option + Command + 2** or even **Capslock + Command + 2** gets pretty
cramped. I know, the Touchbar means less keys, but my goodness I hate
using those commands when I need to. And no, having us use the VoiceOver
menu isn't a fix. It's a workaround. And no, having us use letter
navigation to lock the screen or do any number of hard keyboard commands
is not a fix, it's a workaround.

### Find and replace Touchbar with Function keys

I've talked about the Touchbar in earlier articles, so I'll just give an
overview here. The Mac does not have a Touchscreen. The Touchscreen is
slower for blind people to use, and so is the Touchbar. We can't even
customize it, as that part of system preferences is seemingly
inaccessible to us. One Mac user said he has answers on how to use it
well, but I asked him about it, and haven't seen a reply to my query.
For now, then, the Touchbar is useless to me, and blind people who, like
me, use their Macs to get work done.

Now, one place it could be good at is in Pages. While in Pages, the
Touchbar acts like a row of formatting buttons. But there are keyboard
commands for almost all of them, except for adding a heading. If the
Touchbar were that useful everywhere else, it may have a place in my
workflow. But I write all of my documents, when I can help it, in
Markdown or Org-mode, inside Emacs or another text editor. So the
Touchbar would be better gone from my MacBook, and replaced by the much
more useful function keys, with tactile buttons that do one thing when
pressed in each context, and I know what they'll do when pressed.

So, in a new model of the MacBook, I want the **option** to use regular
function keys, even if it costs \$20 more. Either that, or give me a
reason to use this useless touch strip that only acts to eliminate keys
that VoiceOver can use and make keyboarding that much more limited. And
no, an external keyboard is not a fix. It's a workaround.

### Text formatting with VoiceOver

This applies to both MacOS and iOS, but it'd be more useful on the Mac,
so I'm putting it here. As I wrote in my *Writing Richly* post,
formatting is important for both reading and writing. I did send Apple
feedback based on this, so I hope that in 10.16, I, and all other blind
people, are able to read and write with as much access to formatting as
sighted people.

### What's that window say?

In MacOS Catalina, Apple added a little‐known feature to VoiceOver: the
ability to get a "caption" from any element, or "control", on the
screen.

## iOS

### There's nothing on the screen

There are many iOS apps that are very accessible. They work well with
VoiceOver, and can be used fine by blind people. However, there are also
many which appear blank to VoiceOver, so cannot easily be used.
VoiceOver could use its already‐good text recognition technology to scan
the entire screen if an element cannot be found with an accessible
label, other than the app title. Then, it could get the location of the
scanned text and items, and allow a user to feel around the screen to
find them.

This could dramatically improve access to everything from games, to
utility apps written in an inaccessible framework, like QT. May QT be
forgotten, forever. So, in iOS 14, I hope that Apple majorly ramps up
its use of AI in VoiceOver. Besides, that would put Google, the AI
company, even further to shame, since they don't use AI at all in
TalkBack to recognize inaccessible items or images.

## Services

### Apple Arcade for *everyone*

Apple Arcade came out some time last year. 100 games were promised
around launch time, and at \$5 per month, it is an amazing deal, as you
can play these games forever; there is no rotation like in XBox Game
Pass. For now, though, there have been no games that blind people can
play, so I just canceled my subscription, my hope in Apple dwindling
further. So, in this year's WWDC, I hope that Apple not only adds
accessible games to Apple Arcade, or even makes a few of their own, but
shows them off. People should *know* that Apple truly cares, as much as
a 1.5 trillion dollar corporation can, about accessibility and people
who are blind, who *cannot* play regular, inaccessible games.

## Conclusion

I hope this article has enlivened your imagination a bit regarding the
soon‐to‐be WWDC 2020. I've detailed what I want to see in MacOS, my most
often used Apple system, iOS, and Apple's services. Now, what do you
want to see? Please, let me know by commenting wherever this article is
shared.

Thanks so much for reading my articles. If you have any suggestions,
corrections, or other comments, please don't hesitate to reach out to
me. I eagerly await your comments.
