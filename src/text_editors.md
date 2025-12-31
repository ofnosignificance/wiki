# Text editors

This page is dedicated to some text editors and my experience with them.

## Acme

I don\'t remember much from fiddling around with Acme. I like it
conceptually with all it\'s piping mechanism and mouse gimmicks, though
I never bothered using it for any real programming tasks besides trying
it out, thus my opinion on it is worthless. If I check it out some time
(together with all the other Plan9/9front stuff like Sam), then I\'ll
document my experience here.

## e3

e3 caught my attention when I was looking for an editor with Emacs
keybindings fast and small enough to use alongside Emacs for config file
editing. The first thing I noticed while reading through the description
on the Gentoo Wiki was that it was written in assembly language (NASM to
be exact), albeit still worked on various Unix-like operating systems,
such as Gentoo, which also had it in the repos. It\'s quite fast, even
more so than other editors comparable to it feauture-wise, but is not
very configurable, something I wished it had, because I wanted to
disable backup files. Besides Emacs it can also use key binds for
Wordstar or vi, both of which seem redundant when you could also use vi
without any real performance compromises.

## Emacs

I **really** tried to like Emacs, not because something in Emacs itself,
but because of SLIME/Sly and Common Lisp. For a certain point in time I
was fascinated by Common Lisp and there really isn\'t a way around Emacs
(or an editor which resembles Emacs in design). Furthermore, I enjoyed
the REPL and SLIME\'s way of writing programs, it\'s unlike any other
editor or IDE I\'ve tried and can\'t be compared to the usual modus
operandi you got with languages that don\'t rely as much on the REPL as
Common Lisp does. The problems for me lies in what basically everyone
laments who has had used Emacs: that being the issue that you can\'t
really just use 30% of what Emacs has to offer, if you do Emacs, you
have to go all in, as doing otherwise will only slow you down in your
workflow. Either you use the editor, the file manager, and the shell,
the keybinds for things like compilation and debugging, or you don\'t do
it at all. This terrible inefficiency caused by having only a part of
your programming tasks rely on Emacs was the turning point for me. With
other editors, mere, mortal editors, there is more modularity in regards
to what tools you use and how you use them. With Emacs you use all Emacs
features and all extensions, which can result in being more efficient,
it\'s just not for me. I stopped programming Common Lisp shortly after I
discontinued my usage of Emacs, so now there\'s not really an incentive
to use Emacs at all anymore.

## JOE

I discovered JOE in the OpenBSD\'s ports tree after looking through it
out of boredom. I suppose it has all the features one might need,
besides it not having any functional syntax highlighting for Rust and
other smaller languages. C and C++ are supported though. After learning
the keybindings, the same as those in the Borland IDEs, which is easy
because you can trigger a help menu akin to these in pico and nano (and
you can close it afterwards, so slightly less annoying than the one in
the aforementioned editors), I used it to write almost all of my Code,
Python and C at the time, thus I think I\'ve got a bit of experience
with it, and can say it\'s fine for what it is. Sufficient for
everything I do? Probably. Useful when Vim exists? Definitely not.

## OpenBSD\'s mg {#openbsds_mg}

I tried this one for the same reasons as with e3 (wanting a tiny,
additional editor to edit config files with). It\'s fast, yet lacking in
syntax highlighting and some editing capabilities, otherwise it\'s fine.
For what I wanted back then it was perfect. Now that I don\'t use Emacs
anymore, I also don\'t need an additional editor with Emacs keybinds.

## Sublime Text {#sublime_text}

I used Sublime Text for quite some time without ever purchasing a
license. It was among the first code editors I used, so back then I
couldn\'t really tell what I liked in an editor other than the most
basic requirements working. It\'s fast, you can customize it
extensively, and it has addons for almost everything. The problem is not
only the license fee, rather than it being non-free software and thus
always being at the will of whoever makes Sublime Text. This is not to
say that Sublime Text doesn\'t have sane defaults and sane decisions, it
has, the issue is that this might change, or he might decide to
discontinue the editor, or a multitude of other problems that non-free
software has inherent to it. I have to say, however, that Sublime Text
doesn\'t have as much of a corporate feeling to it as do editors similar
to it. Boring tangent. Moreover, I think it integrates better than other
graphical editors like Emacs into my workflow as it is just a text
editor and not trying to be everything and the kitchen sink, as they
say. It\'s a good example that not all graphical editors are shit and
it\'s by far better than any of the Electron-based editors like VSCode.
I suppose I\'ll have to look into again at some point, as this is a
close second place after Vim in terms of my preferences; too bad
Vi-keybindings emulation still sucks, as it does in almost everything
that wasn\'t planned from the ground up to have those.

## Neovim

## vi

Vi obviously has many incarnations; busybox vi is very different from
nvi which is also different from OpenBSD\'s vi and what appears in
Debian when you type vi. In any case this is the editor I\'m most
familiar with, as at this point I have almost a decade of Vi muscle
memory. It\'s very simple and kind of limited, but it just werks. It\'s
nice for taking notes and writing small text documents, whereas I would
use Vim for more serious bizniz.

## Vim

WIP
