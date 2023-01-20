# keymaster
A repeatable pseudorandom password generator.  

# a what now?

OK, let me back up.

A long time ago, when password managers started to become a thing I wanted to create my own but couldn't decide how to safely solve the storage issue.  Eventually I thought, why not do something with no storage?  I decided to write something that will consistently generate the same pseudorandom password when given the same inputs.  This went through a few iterations, some more embarassing than others.  The first one I started to consistently use was "<a href='https://github.com/madmonk13/passgen'>passgen</a>".

I eventually came to the conclusion that the passgen algorhythm was not nearly "random" enough.  That led to this current iteration.

In addition to the new algorhythm, Keymaster also allows for the disabling or enabling of specific special characters in passwords and choices are saved in html5 webstorage.  You can also export your settings to a text blob that can be easily imported to ensure consistent usage.

# Advanced usage:

1. Every choice you make will alter the resulting password.  Even disabling a special character not in your current password will yield a different result.  Even if someone knows your PIN code, if you've disabled any characters they will not be able to generate your password without knowing what you've disabled.

2. Capitalization will also change the result.  Use upper case in unusual places for extra security.

3. Pad the site name.  For example, instead of "amazon", try "!amazon".

Just remember, this is intended to make complicated passwords easy.  Don't over do it with these methods.  Whatever you decide to do, make sure you can remember to do it every time.

# Demo:
https://madmonk13.github.io/keymaster/

# todo
I'm not in love with the color scheme, maybe do something about that.
