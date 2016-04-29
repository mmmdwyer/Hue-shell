`Hue-shell` is a collection of shell scripts to control the Hue lamps
from Philips. 

```
                    _________________________
                   /                         \
                  +    ___________________    +
                  |   /                   \   |                      .
                  |   + _$ hue set 1 --on  +  |            .    +    ,
                  |   |                    |  |             \   '   /
  ,+.             |   +                    +  |              ` ,+. '
 (   )            |   \___________________/   |           +-+ (   ) +-+
  \ /     -->     +  /+\               _      +     -->        \ /
 _+=+_             \_________________________/                _+=+_
+_____+              !______________________!                +_____+

```



It is designed for embedded operating systems with very
limited resources (successfully tested on the old and outdated wifi
router "Linksys WRT54GL").

`Hue-shell` runs on many shells (sh, dash,
ash, bash) and many UNIX operating systems (Linux, MacOS X, FreeBSD,
OpenWRT). `Hue-shell` works well in a small BusyBox environment. Out 
of the box `Hue-shell` runs on many single-board computer like 
Raspberry Pi, Cubieboard, BeagleBone etc.

For further documentation please visit the project site:

http://josef-friedrich.github.io/Hue-shell/


    __________________________    ____________________________
   /                          \  /                            \
  |    ___________________    ||    ______________________    |
  |   /                    \  ||   /                      \   |
  |   | _ $ hue set 1 --on |  ||   |                      |   |
  |   |                    |  ||   |                      |   |
  |   |                    |  ||   |                      |   |
  |   \___________________/   ||   \______________________/   |
  |  /|\               _      ||  /|\ ATARI  SC1224      _    |
   \_________________________/  \____________________________/
     !______________________!      !________________________!


                                           .
                                 .    +    ,
                                  \   '   /
    ,+.                            ` ,+. '
   (   )                        +-+ (   ) +-+
    \ /  --> $ hue set 1 --on -->    \ /
   _+=+_                            _+=+_
  +_____+                          +_____+
