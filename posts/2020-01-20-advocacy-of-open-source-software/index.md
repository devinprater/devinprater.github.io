---
tags: ["open-source", "blindness"]
date: "2020-01-20T00:00:00Z"
title: Advocacy of open source software
---

In this post, I’ll detail my experiences of advocating for
accessibility in open source software, why it is important, and how
others can help. I’ve not been doing it for long, but at least now,
I’ve done a bit. I’ll also touch upon why I think open source
software, on all operating systems, is important, and what closed
source and closed feedback systems cannot offer, which open source
grants. On the other hand, there are things which closed source
somewhat grants, but which has faltered slightly in recent days. I
will attempt to denote what is fact and what is opinion, this goes for
any post of a commentary of informative nature.


The Appeal of Open Source
-------------------------

Open source, or free software, basically means that a person can view
and change the source code of software that they download or own.
While this doesn’t mean much to users, it does mean that many
different people can work on a project to make it better. This has no
value on its own, see the "heartbleed" [SSL
bug](http://heartbleed.com) and its
[Aftermath](https://www.securityweek.com/evolution-openssl-security-after-heartbleed),
but as with SSL, things can obviously improve when given an incentive.

For now, open source technology is used in many closed source
operating systems. For example, the
[Liblouis](https://github.com/liblouis/liblouis) braille tables are
used in
[iOS](https://www.applevis.com/blog/whats-new-ios-13-accessibility-individuals-who-are-blind-or-deaf-blind),
[macOS](https://www.applevis.com/blog/new-features-changes-improvements-and-bugs-macos-catalina-blind-and-low-vision-users),
and most Linux distributions through [BRLTTY](https://brltty.app).
While the software is not perfect, it is often made for more than one
operating system, has a helpful community of users, and, greatest for
accessibility, developers who are more likely to consider
accessibility. This is greatly improved with platforms for open source
development, like Github and Gitlab, which allow users to post
"issues" on projects, including accessibility ones.

The Appeal of Closed Source
---------------------------

People like getting paid. I should know, as a working blind person who
does love getting paid for time and effort well spent. People love
keeping things hidden while being worked on. I wouldn’t want a reader
reading an incomplete blog post, after all, and spreading the word
that "Devin just kind of wrote a few words and that’s all I got. from
the blog." People love being able to claim their work as theirs,
instead of having to share the credits with other people or companies.
I don’t have direct experience with this, because I need all the help
I can get, but in my opinion, it is a factor in choosing to create on
your own, as a user or a company. Another great thing about closed
source is that your competitors can’t copy what you’re doing, as you
do it, and when you’re an important company, with allegiance to your
shareholders, you must do anything to keep making money. But, what
about accessibility?

Open Source Accessibility
-------------------------

Accessibility of open source projects vary a lot. For example, before
Retroarch was [made
accessible](https://www.libretro.com/index.php/retroarch-1-8-2-coming-soon-accessibility-features-for-blind-people/),
its interface was not usable by blind people. Now, though, I can use
it easily. However, current versions of the [KDE Plasma
desktop](https://kde.org/plasma-desktop) do not work well with [the
Orca screen reader](https://help.gnome.org/users/orca/stable/). The
following quote is from the release notes for KDE’s latest desktop
version:

> KDE is an international technology team that creates free and open
> source software for desktop and portable computing. Among KDE's
> products are a modern desktop system for Linux and UNIX platforms,
> comprehensive office productivity and groupware suites and hundreds
> of software titles in many categories including Internet and web
> applications, multimedia, entertainment, educational, graphics and
> software development. KDE software is translated into more than 60
> languages and is built with ease of use and modern accessibility
> principles in mind. KDE's full-featured applications run natively on
> Linux, BSD, Solaris, Windows and Mac OS X.

-- [Source](https://kde.org/announcements/plasma-5.17.0.php)

"Modern accessibility principals," you say? In my opinion, we seem to
be talking about different definitions of "accessibility." Yes, there
are multiple definitions. One is accessibility in the sense of being
able to be accessed, another is the ability to be found, and the
ability of being easy to deal with. As stated in the About section of
the site, I use accessibility to mean being able to be used
*completely* by blind people. This carries with it the implication
that every single function, and all needed visual information, can be
conveyed to a blind person in order for it to be accessible. This
rules out the "good enough" approach that so many blind people accept
as the status quo. Luckily for blind people who would love to use KDE,
there is [work being
done](https://blogs.fsfe.org/gladhorn/2018/10/14/screen-reader-accessibility-for-the-plasma-desktop/)
on this issue. Gnu, the project behind much of Linux, also has an
[accessibility statement](https://www.gnu.org/accessibility/), which
does seem to be very out of date, as it references flash player and
Silverlight, which are no longer in common use, and does not reference
Apple’s iOS, Google’s Android, and other modern technologies which are
not open source, but which include assistive technologies. I encourage every adventurous blind person to make
themselves available for testing open source software and operating
systems; user testing was mentioned by the KDE team as something blind
people could do to help.
Believe me, having an operating system which is a "joy to use" is a
*dream* of mine.

Gnome, and Mate, accessibility are okay, but they do not come close to
the accessibility of Windows and Mac systems. For a good example, if
you press Alt + F1 in Gnome, and probably Mate too, you may only hear
"window." Advanced users will know to type something in Gnome, or use
the Arrow Keys in Mate, but regular users should not have to learn to
hunt around due to bad accessibility, and the fact that less
technically inclined users use Linux is a testament to blind people’s
ingenuity and ability to adapt, rather than the accessibility of the
platform.

Open source accessibility is so hit and miss because there are so many
standards. There is the GTK framework for building graphical apps,
which does have some accessibility support, but developers must label
the items in their programs with text. There is the QT framework,
which seems to have more poor accessibility support. Basically,
developers can do anything they want, which is good for freedom, but
often is not great for accessibility. Also, much of the community has
not heard of accessibility practices, do not know that blind people
use computers, or think that we must use braille interfaces to
interact with computers and digital devices. This is a failure on our
part, as we do not "get out there" on the Internet enough. With the
advent of an [accessible Reddit
client](https://www.reddit.com/r/DystopiaForReddit/), this may begin
to change. Further work must be done to give blind users an accessible
Reddit interface on the web for users to use on computers, not
iPhones. However, Github is very accessible, and there is nothing
stopping one from submitting issues.

Closed Source Accessibility
---------------------------

"Okay but what about Windows? And Apple? You like Apple, right?"
Basically, it’s hard to tell. Software doesn’t write itself, it is
written, for now, by people. People can make mistakes, ignore
guidelines, or simply not care about accessibility. However, those
guidelines do exist, and are usually one standard, like the iOS
accessibility standard. This means that companies can develop
accessible software easily, and are held accountable by managers to
uphold accessibility. But, even the best of accessible companies do
not always do the right thing. Apple, for example, has created two
services, Apple Arcade and Apple Research. Apple Arcade contains *no*
games which a blind gamer can play without expending much more effort
than a sighted gamer. Apple Research contains some questions with
answer buttons which are not labeled, or cannot be activated. Does
Apple think that blind people do not want to game, or that we don’t
care about our hearing, heart, or for women, their reproductive
health? Apple has also created Swift Playgrounds, an app for children
to learn to code. This is accessible. But what about adults? Shouldn’t
blind adults, who are usually technically inclined enough, be given a
chance to learn to code? I’ll probably rant about this in a future
article.

Microsoft has been on an accessibility journey for a few years now,
but even they have a few problems. First, the voices in Windows 10 are
poor for screen reading tasks. They pause way too long at the end of
clauses and sentences, leading me, at least, to press Down Arrow to
move to the next line before the last line was actually done being
spoken, all because it paused just long enough to make me think that
there was no more text to speak. Microsoft’s XBox Game Pass is great,
but I could not find any accessible games in the free rotations. Sure,
there’s Killer Instinct that many blind people can enjoy playing, but
I found it not only inaccessible, as the menus do not speak, but
boring, as the characters all seemed to simply do the same thing. I
know that games do not have to be accessible to be fun, but I expect
companies who showcase games, like Apple with Arcade, to have at least
one accessible game for blind people to enjoy. And I also know that
neither Apple nor Microsoft makes these games, but they do choose to
advertise them, endorse them even, and it shows that, for Apple Arcade
at least, video games are not something which they expect blind people
to play. Microsoft is proving them wrong, with the
release of Halo with screen reader usability in menus, and the
possibility that the new Halo game will be accessible.

Another problem with Microsoft is that not all of their teams are
onboard. Like Apple with Arcade and Research, Microsoft has the
Rewards team. Their quizzes require one to move items around to
reorder answers to get the quiz correct. This may be easy, and perhaps
fun, for sighted people, but are simply frustrating for blind people.
Other problems include the release of the new Microsoft Edge, which,
for most users of screen readers, require that the user turn off UI
Automation in order to read some items on the web. Otherwise, if
Microsoft’s upcoming foldable phone comes with greatly enhanced
accessibility relative to pure Android, and the Narrator screen
reader, optimized and made great and enjoyable for a mobile
experience, I think that Microsoft could take plenty of market share back
from Apple of mobile phone users. They already have most general
purpose computer users who are blind, so taking from Apple would be a
huge win for them regarding accessibility. But, on that, we’ll have to
wait and see how far Microsoft takes their commitment to
accessibility. The more cynical side of me says that Microsoft will
simply slap Android on a folding phone and release it, because why
fight Apple.

Reporting Bugs
--------------

So, what can we do to make accessibility better? Just about all open
source software, including the stuff making up this blog, is hosted on
Github. Just about all companies, of closed source software, claim to
want your feedback. So, I recommend giving them any feedback you have.
I know that giving feedback to Apple is like throwing $100 bills into
the ocean, giving your valuable time to something which may offer no
results, and just gives you the robotic "thanks" message. I know that
sometimes talking to Microsoft’s accessibility team may seem
unproductive, because they lead you from Twitter to one of a number of
feedback locations. I know that feedback to open source software
projects may take a lot of time and explaining and promoting
accessibility to a community which has never considered it before, but
it all may help.

For a great, and successful, Github issue regarding accessibility, see
[this issue on accessibility of
Retroarch](https://github.com/libretro/RetroArch/issues/9661). You can
see that I approached the Retroarch team respectfully, with knowledge
of basic accessibility and computer terminology. Note that I gave what
should happen, what is happening, and what can be done to fix the
problem. As the saying goes, if you do not contribute to a solution to
a problem, you are a part of the problem. Blind people will need to
remember to give solutions, not just whine about something not working
and can’t play Poke A Man like everyone else.

Also, share links to your feedback with other blind people who can
vote, thumb up, or comment on it. Remember, if you do comment, please
remember that feedback does not net instant results. I’m still waiting
on [Webcamoid to have an accessible
interface](https://github.com/webcamoid/webcamoid/issues/211), and
[Adding Active Accessibility into Games for
Retroarch](https://github.com/libretro/RetroArch/issues/9920), and
[This Delta
issue](https://github.com/rileytestut/DeltaCore/issues/13). But, at
least I’ll know when something changes, and I could even [Pay for
features to be implemented](https://www.bountysource.com).

This is opposed to the closed source model, where feedback is "passed
on to the team," or you are thanked, by your iPhone, for your
feedback, but do not hear anything back from developers, and you most
definitely can not pay for specific features to be worked on, or
donate to projects that you feel deserve it. You must hope and have
faith that large companies with more than one billion users cares
enough to hear you. For perspective, if every blind person stopped
using an iPhone, Apple would not miss many lost sales, compared to the
billions of sighted users. However, the engineers who work on iOS
accessibility are people too, with deadlines, lives, and feelings, and
we should also respect that they are probably tightly restricted in
answering feedback, fixing bugs, and creating new, exciting features.

------

As for me, I will continue to support open source software. I’ll keep
using this mac and iPhone because they work the best for me and what I
do for work and writing. But, believe me, when something better comes
along, I’ll jump ship quickly. As blind people, I feel, we cannot
afford to develop brand loyalty. Apple, Microsoft, or Google, I think,
could
drop accessibility tomorrow, and there we’d be, left in the cold. I
highly doubt they will. They may let it lie stagnant, but they
probably won’t remove it. I do not write this to scare you in the
least, but to make you think about how much control you actually have
over what you use, how companies and developers view us, and how we
can improve the situation for ourselves. if sighted people notice a
bug or want a feature in iOS or Windows, they can gather their tech
press and pressure Apple or Microsoft. If we find an accessibility
bug, do we have enough clout, or unity, to pressure these companies?
Writing feedback, testing software, trying new things, writing guides
and fixing documentation, or, if able, translating software into other
languages are all things that *any* blind person can do. I’m not
saying that I’m perfect at any of this. I just think that we as a
community can grow tremendously if we strike out from our comfortable
Windows PC’s, Microsoft Word, audio games, TeamTalk, and old speech
synthesizers.

I’ll give some projects you could try out and give feedback on:

- [Riot IM, for text and voice chatting in groups, like TeamTalk](https://marcozehe.de/2019/12/20/how-to-get-around-matrix-and-riot-with-a-screen-reader/)
- 
