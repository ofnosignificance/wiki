**I\'m writing this article instead of continuing work on my own
emulator, thus don\'t take it too seriously what I say here, it might as
well be all wrong. This text is written just so I can learn myself from
documenting what I \"know\" here.**

## Hitchhiker\'s guide to emulator development (not good advice) {#hitchhikers_guide_to_emulator_development_not_good_advice}

Within this document I\'ll try to lay out what I think are the most
important things to know for developing an emulator of any kind. It\'s
constantly work in progress, hence don\'t be surprised if this isn\'t
finished.

### Required Knowledge {#required_knowledge}

Unless you are writing code for a fantasy console or some very unusual
device, the most important skill to have is knowing the **assembly
language** of your target to emulate. Don\'t bother until you know at
least a little bit, because otherwise you cannot test anything with
custom programs, cannot understand the underlying principles of the
software, neither can you do anything else really. Other than that, you
need to know some high-level systems programming language such as C,
C++, or Rust for developing the emulator itself. You can write it in
more high-level languages too, like Java, C#, Go, or whatever your
innermost heart\'s desire is, but beware that it should have at least
sufficient speed to cope with the resource demands of a software like
that. Last but not least, you should be well read on the hardware
you\'re emulating. Read manuals (search on archive.org, they usually
have good resources) and familiarize yourself with the device. If
possible, buy the hardware and try writing programs for it first. Don\'t
feel discouraged if you\'re dirt poor and can\'t afford some abandonware
from the last century, you can also write programs for existing
emulators and learn how the hardware works that way, albeit it might
miss some idiosyncrasies like undocumented opcodes or any unexpected
hardware-related behavior.

If you **tried to write an emulator and feel like you don\'t understand
shit, it might be worth considering programming a disassembler first**,
as in concept every emulator includes a part that is basically a
disassembler. It\'s easier and this way you can get familiar with the
opcodes and the instructions appertaining to them.

### Required Reading {#required_reading}

Before writing your own emulator, I highly **recommend reading other
people\'s emulators code first.** Not only will this give you an idea
how your project can be approached i.e. in design, but also give you an
idea how you can solve some of the more tricky stuff. As always with
code snippets from the Internet, try to understand them thoroughly if
before `<s>`{=html}shamelessly ripping them off`</s>`{=html} getting
inspired by them. You should read the code of multiple emulators for the
same system, not completely of course, just the important bits, since
this will give you an idea what ways of doing it are particular to that
software and what is rather usual. To do anything
