# keen-encoder

!!!!!!!!!!!!!!!!!!!!!!!!!
!! Out of Order        !!
!! Something is Broken !!
!!!!!!!!!!!!!!!!!!!!!!!!!

Note:

I apologize but the SGA-Encoder does not work as expected. It just outputs a bunch of random words. I hope working soon but I am not sure if it converts back to latin text and here is an autohotkey program that does the same using bash.

'''
;;  sga ;;
::sga example::sed 'y/abcdefghijklmnopqrstuvwxyz//' <<< 'the quick brown fox jumps over the lazy dog.'
:o:to-sga::sed 'y/abcdefghijklmnopqrstuvwxyz//' <<< '
:o:from-sga::sed 'y//abcdefghijklmnopqrstuvwxyz/' <<< '
'''

A more convenient way to encode standard galactic unicode is with the Standard Galactic Keyboard.
https://github.com/standardgalactic/alphabet/blob/core/tosga.ahk 

In order to display it correctly, install:
https://github.com/standardgalactic/alphabet/blob/core/Sga-Regular.ttf

End Note

Substitutes letters from lower-ascii character table to unicode representing the galactic standard alphabet found in Commander Keen.

# Command Line

Pass text to be translated as an argument.
`node index your_text_here `

```bash
node index The quick brown fox jumps over the lazy brown dog.
```
Displays         .

<p align="left">
  <img src="text-sample.png" width="1000px"/>
</p>

# Unicode

May not work on all systems.

Uses [upper conscript registry](https://www.kreativekorp.com/ucsur/charts/sga.html) recommendations. Your operating system must have a font that supports displaying the unicode characters returned. That font must be used in the location you are viewing (terminal, code editor, web page) the results or must be installed on the system.

Based on [keen-unicoder](https://github.com/dance-dance-banana-frenzy/keen-unicoder)

View as [ ](./README-keen.md).
=======
# sga-encoder

Substitutes letters from lower-ascii character table to unicode representing the galactic standard alphabet found in Commander Keen.

# Command Line

Pass text to be translated as an argument.
`node index your_text_here `

```bash
node index The quick brown fox jumps over the lazy brown dog.
```
Displays         .

<p align="left">
  <img src="text-sample.png" width="1000px"/>
</p>

# Unicode

May not work on all systems.

Uses [upper conscript registry](https://www.kreativekorp.com/ucsur/charts/sga.html) recommendations. Your operating system must have a font that supports displaying the unicode characters returned. That font must be used in the location you are viewing (terminal, code editor, web page) the results or must be installed on the system.

Based on [keen-unicoder](https://github.com/dance-dance-banana-frenzy/keen-unicoder)

View as [ ](./README-keen.md).
>>>>>>> 590f75c19cf6231e79f27b6012dbcacb86484a92
