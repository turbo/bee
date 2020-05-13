A while ago, I started writing a text editor in Bash. Bash 3. As an IDE for a Lisp dialect, also implemented in Bash. Bash 3. 

I have stopped. This is how far I went.

Backspace isn't implemented. Neither is Delete. 

But Tab is. Converted to spaces of course. 

Also, keyboard navigation (arrow keys). With up/down jumping to the start or end of the first/last line. As they should.

Oh, and a custom draw call system for partial redraws.

And line numbers. In a gutter. That auto-expands the longer the buffer gets.

And Return's there, too! It can even break lines in the middle. A true luxury.

Have I mentioned that the active line is highlighted? No? Well, it is.

And there's an info bar! And a cursor position indicator!

Watch a demo:

[![asciicast](https://asciinema.org/a/d3E2A4myjbuc3bBQIm85WYyFI.svg)](https://asciinema.org/a/d3E2A4myjbuc3bBQIm85WYyFI)

Or try it yourself by running `./bee` in Bash (3 or later).

The `bee` file is a (Bash 3 compatible) script. Feel free to read through it, ya know - to check for malicious stuff. But I can't promise that it won't cause your eyes to bleed or brain to liquify. Or both (in the state of California).

<hr>

<sub>PS: don't try to write something larger than the screen in either direction - it scares the editor!</sub>
