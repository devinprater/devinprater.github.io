---
tags:
- open-source
- blindness
- advocacy
date: "2020-02-16T20:11:04Z"
title: open source blindness
---

What if all of your software were free, like NVDA? What if the only
thing asked of you by software makers was to donate or contribute? How
would this effect your life, and the lives of developers? In this
article, I will explain what open source is, what it is currently used
for, my experiences with it, and how you can make it better.

What is Open Source?
====================

Open source is a splinter of the [Free Software
movement](https://en.wikipedia.org/wiki/Free_software_movement). The
Free Software movement believes that everyone should be able to view a
program's code, and modify it if needed. The thing which sets open
source apart is that it doesn't mind working with companies which create
closed source, or proprietary, software which cannot be modified or have
its source code seen by the user.

When free and open source spokespeople talk about freedom, they mean
free as in free speech, not as in free things. This talk of freedom
upsets business, so the term "open source" is used instead. Much open
source software is free of cost, with the developers asking for donation
instead of demanding payment.

What is Open Source used for?
=============================

Open source software is just about everywhere, and often comes with a
tightly knit community of users. Examples of open source in the blind
community include [NVDA](https://www.nvaccess.org/about-nvda/),
[LibreOffice](https://www.libreoffice.org), [Orca Screen
Reader](https://wiki.gnome.org/Projects/Orca), [Braille
Blaster](https://brailleblaster.org), [Liblouis](http://liblouis.org),
and [Emacspeak](https://github.com/tvraman/emacspeak). Examples of
closed source include [JAWS for Windows](https://www.freedomscientific.com/products/software/jaws/), [Narrator](https://support.microsoft.com/en-us/help/17173/windows-10-hear-text-read-aloud), [VoiceOver](https://www.apple.com/accessibility/iphone/vision/), the latest
version of
[TalkBack](https://support.google.com/accessibility/android/answer/6283677?hl=en),
[Duxberry Braille translator](https://duxburysystems.com), iOS, Windows, and plenty of apps you may have on
your iPhone or Android phone.

Interestingly, some projects are a mixture of both. JAWS incorporates
Liblouis for braille translation, and so do Narrator and VoiceOver.
Apple uses plenty of open source tools: Python, command line shells, and
many command line tools on MacOS. Microsoft makes BRLTTY and Liblouis
available for download to interface with Narrator.

Linux, which founded many offshoots, is an entire operating system built
on open source ideals. Blind people began customizing Linux for use with
speech, and work is ongoing to make Linux an accessible operating
system. This began with [Vinux](https://wiki.vinuxproject.org). It
started up talking, something no other system had done before. One could
use it with speech or braille, and used the eSpeak voices.

That operating system, or distribution of Linux as they are called, is
now abandoned, not having been updated in years. Another project, [Sonar
Gnu Linux](https://distrowatch.com/table.php?distribution=sonar), also
came and went. It was based on Arch Linux, and was my favorite
distribution. People now use [Talking
Arch](https://talkingarch.info/download.html), or
[Tarch](https://tarch.org), if they are adventurous and [Slint
Linux](https://slint.fr/wiki/doku.php?id=en:installation) if they
aren't. These are the most popular Linux distributions for those who are
blind. If I've missed anything, let me know. Some distributions which
were not made for the blind are also accessible.
[Fedora](https://getfedora.org), [Trisquel](https://trisquel.info),
[Debian](https://www.debian.org), and [Ubuntu](https://ubuntu.com) are
also able to be installed, but the user must know the correct keyboard
command to turn on the screen reader.

Most open source software can be found on [Github](https://github.com).
That's where NVDA, Orca, and many other tools, even for the blind, are.
But how reliable are these tools? What about the operating system? Could
one get rid of Windows with this software founded on ideals?

My experiences with Open Source
===============================

Linux
-----

Accessibility is a software issue, so the root of software, the
operating system, will make or break any accessibility. My experiences
with Linux began, mainly, with an old operating system called
[Vinux](https://wiki.vinuxproject.org). I didn't stick with it for long,
and soon forgot about it, and it is now abandoned. Linux can run many
different desktops, which give users the major system functions of
accessing apps and system utilities. Gnome and Mate are accessible, just
about everything else, for now, including KDE, isn't. Vinux used Gnome
2, which is basically what Mate is now.

I came back to Linux for a short while with Sonar. I really liked it,
but missed the games and speech options Windows had. I liked all the
software that we have access to on Windows, and browsing the Internet
with Linux wasn't that good back then. I soon got into the Apple
ecosystem with an iPhone and such, and already had a Mac for quite a
while. Still, Linux called to me.

I'm never satisfied with the workflow I have. I always want to be more
efficient, more quick, more capable in what I do. I always want better
sound, even if 3D effects and virtual surround sound aren't actually
necessary or real. Like a sighted person wants great graphics, I want
great sound. On Linux, there is a way to enable virtual surround sound,
but it offers little reward, and much configuration, crackling in audio,
and doesn't augment stereo audio as options on other systems does. The
Mac has a third-party option, [Boom
3D](https://www.globaldelight.com/boom/), and Windows has [Windows Sonic
for
Headphones](https://www.windowscentral.com/how-use-windows-sonic-windows-10-creators-update).
Both of these require nearly no configuration, augments much more audio,
and only Boom 3D causes a bit of sluggishness.

I also want a faster way of doing things. Many keyboard shortcuts,
letter navigation of items in lists and menus, and ways of only getting
the information I want. I have much of this on the Mac, with the Mail
app allowing me, through table navigation, to speed through subjects
instead of having to hear the row titles and contents and all before
what I really want to hear, and being able to go to the previous or next
message in a thread without needing to close the window. Linux has some
of this, but many times things are unclear, with Orca, the Linux screen
reader, just speaking the items, and not what type of item it is. This
is clear in the area of Audacious settings where you choose sound
effects.

Even so, Linux has such an appeal to me. I have tried Fedora Linux,
[Slint](https://slint.fr/wiki/doku.php?id=:en:start), Ubuntu, Debian, Arch, and found that there is always something
missing. Accessibility isn't that good in the graphical interface, and
much still takes a lot of configuring and asking the community. And I
really hate asking for help.

Recently, the [Mate desktop](https://mate-desktop.org) team has
released a version with accessibility fixes. This is important, as
many companies, like app developers, Apple, and Google, rarely share
that there are accessibility fixes in minor updates, and don't even
share all the new features in major releases. This gives me some hope
that the open source community at large just needs more blind people
telling them about our needs. Then again, this is probably just
another of my excuses to bash my head against the hardened wall of
Linux, yet again. Plus, everything in the open source moves slowly,
and this is doubly true for open source assistive technology.

There are, however, blind people who use Linux, just as there are some
in the blind community who use Android. In fact, there is an entire
[Linux Accessibility Site](https://linux-a11y.org). However, the site
does have links to abandoned software, and doesn't link to all
accessibility initiatives, like [Stormux](https://stormux.org). Both
Linux-a11y and Stormux ask for donations, so there is also duplicated
effort and decentralization even in the blind Linux user community.

Now, I use a Mac. It contains enough open source technology to support
[Homebrew](https://brew.sh), a [package
manager](https://en.wikipedia.org/wiki/Package_manager). I can run
Emacs, with Emacspeak on it, along with just about any command line
program I'd use on Linux. The Mac's graphical interface is good enough
for mail and some web browsing, just not so good with Google Docs, and I
can probably do anything on it that a Linux user can do.

And yet, sometimes, Linux calls to me still. VoiceOver isn't the best
screen reader out there, and Linux has the appeal of being run by
people, not corporations. And yet, looking at the [GNU accessibility
statement](https://www.gnu.org/accessibility/accessibility.en.html),
you'd think it was updated in 2006 or so. It may have been, which is a
slap in the face for any accessibility advocate. The GNU project, with
this statement, says to us that we're only worth putting up a quick
page, detailing the inaccessibility of old technologies and not
maintaining it. It tells us that we're a good poster to hang up in their
trophy room of "people aided by our courageous stand for the minorities
who desperately need our help," but then discarded for the "community"
to handle. After all, the GNU don't know anything about helping the
blind, do they? Can the GNU be expected to enforce accessibility among
their projects? Doesn't the government take care of the poor blind
people? Blind people have their Vinux and Sonar, why not just use those?
No, that is definitely not segregation, not at all!

Open Source Programs
--------------------

I began using NVDA around high school. No one had ever heard of it at
that point, in a day when people called all screen readers either "JAWS"
or "Microsoft." I've not stopped using it ever sense. Its features have
grown, its users growing even faster. It now has a community of
programmers, translators, and writers. It is, in my opinion, the most
versatile Windows screen reader. JAWS still works okay for some things,
like malformed spreadsheets, but for everything else on Windows, I use
NVDA.

Braille Blaster is also a great project, making braille translation,
embossing, and transcription free. I use it for translating EBooks into
good, formatted braille files for reading on my iPhone using the BARD
Mobile app. Now, I don't even use Duxberry, even though it is provided
on my work computer.

I've found that open source programs, built upon closed source operating
systems, are the best compromise. NVDA, BrailleBlaster, TDSR, and many
other tools built for the blind community run on Windows or Mac. Having
a great foundation in accessibility makes all the difference for users.

How can You help?
===============

Github, as stated earlier, is a hub of open source projects. One great
thing about the service is that anyone can contribute. Just make an
account, and you're ready to help.

If you can program, you can [collaborate by modifying
code](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
If you try the software and find accessibility problems, you can tell
developers about [bugs or
features](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue)
that need fixing or adding. If you find a project you like, they may
have a Patreon to which you can donate, or you can simply spread the
word.

One large project which has become accessible through efforts of the
blind reaching out is Retroarch. An issue was created asking for
accessibility, and it was released in the very next version, and even
more work is being done to make even more games accessible. Open source
collaboration is great for even more than just programming. See projects
I'm working on, all text, on [the About page of my original
blog](https://devinprater.github.io/about/).

Another bit of news is that GTK, a way for programs to be displayed
and written, has had a
[Hackfest](https://blog.gtk.org/2020/02/17/gtk-hackfest-2020-roadmap-and-accessibility/),
where accessibility was extensively discussed. It is hoped that this means
that accessibility will become a larger issue in Linux, and that blind
people will one day be able to use Linux as confidently as they use
Windows and Mac now.

Conclusion
==========

As time goes by, I find myself drawn to open source. its promise of a
better way of making software, the community of helpful people, and the
freedom give me hope. While the Linux operating system does not come
close to satisfying the hope I have for accessibility, programs and
initiatives on top of Windows and Mac have thrived. While the poor
accessibility statement of the GNU project shows that the community at
large does not yet care much about accessibility, the community of blind
people working for our own future, rather than that of a corporation,
gives me hope of a bright future of digital accessibility for blind
people.

What do you think, reader? Does open source call to you as well? Do you
just use whatever system you're given? Have you made peace with Linux's
shortcomings around accessibility? Please, let me know. I am glad to
receive feedback. If you'd like, you may even suggest, via email or
Twitter, articles for which you feel passionate about that need
coverage. I will consider all that you send me, and thank you for
reading.
