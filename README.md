# keymaster
A repeatable pseudorandom password generator.  

# a what now?

OK, let me back up.

A long time ago, when password managers started to become a thing I wanted to create my own but couldn't decide how to safely solve the storage issue.  Eventually I thought, why not do something with no storage?  I decided to write something that will consistently generate the same pseudorandom password when given the same inputs.  This went through a few iterations, some more embarassing than others.  The first one I started to consistently use was "<a href='https://github.com/madmonk13/passgen'>passgen</a>".

I eventually came to the conclusion that the passgen algorhythm was not nearly "random" enough.  That led to this current iteration.

Keymaster takes the following inputs:
Password Length
PIN Code
Site Name

Keymaster also allows for the disabling or enabling of specific special characters in passwords and choices are saved in html5 webstorage.

Demo:
https://madmonk13.github.io/keymaster/
