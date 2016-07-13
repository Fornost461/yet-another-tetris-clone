# tetris-clone
A clone of Tetris made with [Lua](http://www.lua.org/) and [LÖVE](https://love2d.org/).

Key|Action
---|--------
**ESC** | exit
**TAB** | pause
**R** | restart
:arrow_left: :arrow_down: :arrow_right: or **A**, **S**, **D** | move
:arrow_up: or **W** | rotate
**space** or **enter** | fall all the way down

You can also use the numpad:

Key|Action
---|--------
**4** | move left
**6** | move right
**2** | move down
**0** | fall all the way down
**1** | move left and down
**3** | move right and down
**8** | rotate
**7** | move left and rotate
**9** | move right and rotate
**5** | move down and rotate

## Installation
You need to have [LÖVE](https://love2d.org/) 0.10.1 installed. This program may or may not work well with other versions of LÖVE.

## Launch
Depending on your system, it may be enough to just double-click the file with a `.love` extension. Otherwise, you may use the command line, in which case you should specify the file with a `.love` extension (or the directory `files`) as an argument to `love`. Here are two examples:

`love tetris-clone/bin/tetris-clone-0.1.0.love`

`love tetris-clone/files`

## License (free!)
![Public domain](http://i.creativecommons.org/p/zero/1.0/88x31.png)
The license is [CC0](http://creativecommons.org/publicdomain/zero/1.0/), which means you can do what you want without my permission and without mentioning me as author of this code. Feel free to copy and build better things from them!
