---
tags:
- apple
- blindness
- tech
date: "2020-04-21T12:15:06Z"
title: A Brighter Apple
---

Coding has always been hard for me. I've never been able to get my mind
around loops, if and else, for and while, and break almost breaks me
instead of the code. However, many people make it look easy, and for
them, it probably is. In iOS 14, Apple may loosen their chains upon
their technology enough for developers to explore the boundaries of what
a pocket computer can do.

Apple is very controlling. All of its operating systems can only run
on its own hardware. Its hardware can only be used to practically run
officially sanctioned operating systems, unless a Linux user can get
passed the security on the Mac. And, for a long time, notwithstanding
workarounds that have never been so easy, apps on iOS have only been
usable if they were downloaded through Apple's own App Store. In iOS
14, however, things may change for the better.

Earlier this year, Applevis released a blog post about iOS 14 possibly
gaining [Custom Text to Speech engine
support](https://www.applevis.com/blog/apple-reported-be-exploring-ways-let-developers-provide-custom-text-speech-synthesizers-ios).
While I won't write about it here, as it seems a minor topic to me, I
will say that this is something that the community of blind people
have been asking for since VoiceOver revolutionized our lives.
Furthermore, though, it is greater evidence that Apple is beginning to
open up, just a tad. it isn't, however, the first time we've seen
Apple open up, a bit, for accessibility reasons. Apple allows us, in
iOS 13, to change VoiceOver commands, and it uses the [Liblouis
braille tables](http://liblouis.org) to display languages in Braille
that weren't available before.

In this article, I will discuss and theorize about the availability of
[XCode on
iOS](https://www.macrumors.com/2020/04/21/rumor-mobile-version-of-xcode-for-ipad/),
which is supposedly going to be released this year, and how it can help
people learn to code, bring
[sideloading](https://en.wikipedia.org/wiki/Sideloading) to many more
people, and how it can bring emulation in full force to iOS.

Learning to code on iOS
=======================

As I've said before, coding has never been easy for me. My skills are
still very much at the beginner level. I can write "print" statements in
Python, and maybe in Swift, but languages like Quorum, Java, and C++ are
so verbose and require much more forethought than Python. Swift seems a
bit like Python, although just as complex as Java and more verbose
languages when one becomes more advanced.

With XCode on the Mac, accessibility isn't great. Editing text is okay,
but even viewing output seems impossible on first look, and I'm still
not sure if it can even be done. This means that the [Intro to App
development with Swift](https://books.apple.com/book/id1118575552)
Playground materials are inaccessible. This has been verified today with
the XCode 10 version. Sure, we can read the source code, but cannot
directly activate the "next" link to move to the next page. And no,
workarounds are not equal access. Furthermore, neither teachers nor
students should have to look for workarounds to use a course created by
Apple, one of the richest companies in the world, whose accessibility
team is great, for iOS.

Because of this, I expect XCode for iOS will be a new beginning, of
sorts, for all teams who work on it, not just the accessibility team. It
will be a way for new, young developers to come to coding on their
phone, or more probably, their iPad, without the history of workarounds
that many developers on the Mac who are blind know today. It will also
allow blind developers to create powerful, accessible apps. If it is
true that Macs will run Apple's own "A" processor someday, then perhaps
this XCode for iOS will move to the Mac, as Apple TV is attempting to
do. Hopefully, by then, iOS apps on the Mac will actually be usable,
instead of messes, accessibility-wise.

Windows users also cannot currently officially code for iOS. Most blind
users have a Windows computer and an iPhone. Having XCode on iOS will
allow more blind people, who are good at coding, to try their hand at
developing iOS apps. This could also bring more powerful apps,
as blind Windows users are used to the power of programs like
Foobar2000, NVDA addons, and lots of choice.

Another benefit of having XCode on iOS is that, because of the number
of users, there will be even more people working on open source
projects, which they could easily download and import into XCode. For
example, perhaps [PPSSPP User InterFace
accessibility](https://github.com/hrydgard/ppsspp/issues/11696) could
be improved, or the Delta emulator could become [completely accessible
and
groundbreaking](https://github.com/rileytestut/DeltaCore/issues/13).
Of course, closed source app development could be aided by this as
well, but it is harder to join, or make, a closed source development
team than it is to contribute to an open source one.

Sideloading with XCode
======================

Sideloading is the process of running apps on iOS which are not accepted
by the iOS App Store. These include video game console emulators,
torrent downloaders, and apps which allow users to watch "free" movies
and TV shows. The last set of apps, I agree, shouldn't be on the app
store, but the first two are not illegal, but simply could facilitate
illegal operations; pun intended.

Sideloading can be done in many ways. You can load the XCode project
into XCode for Mac, build it, and send it to your own device. This must
be renewed every seven days, but is the most difficult technically to
do. You can sign up for a third-party app store, which allows you to
download apps which are hosted elsewhere and may not be the latest
version, but there is a good chance that the certificate which they use
to sign the app will be revoked by Apple. Finally, there are a few apps
which automate the signing of apps, and pushes the app to the device.

Two of these methods, however, require a Mac computer. Many people,
especially blind people, only use a Windows computer and an iPhone. This
usually isn't a problem, as most blind people either use their phone for
much of what they do, or use their computer for much of what they do.
However, this means that people who have Windows, but not a Mac, cannot
sideload apps. So, if a blind person creates an extension to alert you
that your screen curtain isn't on, which means that a VoiceOver user
doesn't have a feature enabled so that the screen is blank, that app
cannot be distributed on the App Store, and cannot be sideloaded by
Windows users. And I highly doubt a third-party app store would host
such a niche app.

Emulating with XCode
====================

Emulators were once a legal gray area. They allow gamers to play video
games, from game consoles like the Playstation Portable, on computers,
tablets, or phones. They have become legal, however, due to Sony's
[lawsuits of emulator
developers](https://en.wikipedia.org/wiki/Sony_Computer_Entertainment,_Inc._v._Connectix_Corp.).
While emulation is legal, however, downloading games from the Internet,
unless, some say, you own the game, is not. Steve Jobs himself, at the
1999 MacWorld conference, [showed off an
emulator](https://youtu.be/vN2vxYnAZf0?t=5038), one for playing
Playstation games. Now, emulators are not allowed onto the iOS App
Store, unless they have been made by the developers of the games which
are being emulated.

XCode on iOS would also help in emulator use. The more people use
emulators, the more their use will spread. iPhones are also definitely
powerful enough to run emulators; the newer the iPhone, the faster the
emulation. An iPhone X R, for example, is powerful enough to run a
Playstation Portable game at full speed, even while not being
optimized for the hardware, and being interpreted. It's like running
nearly a PS3 game using Python. [A video I
made](https://www.youtube.com/watch?v=tVkYhCmq-dI) demonstrates this.
The game, Dissidia DuoDecim, isn't as accessible as its predecessor.
However, it runs, as far as I could tell, at full speed. This
spectacularly shows that the computers in our pockets, the ones we use
to drone over Facebook, be riled up by news sites, or play Pokemon Go,
are much more powerful, and are capable of far more than what we use
of them.

Also, since blind people will have access to the code ran with XCode,
fixes to sound, the user interface, and even enhancements to both, are
possible. PSP games could be enhanced using Apple's [3D audio
effects](https://developer.apple.com/audio/). Games could be described
using Apple's [Machine Learning
Vision](https://developer.apple.com/documentation/vision) technology.
This applies to even more than accessibility, however. Since more users
will be learning to code, or finally have the ability to code for iOS,
bugs in iOS ports of open source software can more quickly be resolved.

Conclusion
==========

In this article, I have discussed the possibility of XCode for iOS, and
how it could improve learning to code, sideloading apps, and emulation
of video games. I hope that this information has been informative, and
has enlivened the imaginations of my readers.

Now, what do you all think? Are you a blind person who wants to learn to
code in an accessible environment? Are you a sighted person who wants to
play Final Fantasy VII on your phone? Or are you one who wants to help
fix accessibility issues in apps? Discussion is very welcome, anywhere
this post is shared to. I welcome any feedback, input, or corrections.
And, as always, thank you so much for reading this article.
