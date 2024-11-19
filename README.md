### Simone

This program is very similar to the Simon(TM) game by Milton Bradley that was
created in 1978.

Playing `Simone` is identical to playing Simon. Open `simone.html` (or
`simone.min.html`) in your browser and press the start (S) button. A note will
play, and light its corresponding pad. Press the pad that was lit. Two notes
will then play, lighting their corresponding pads. Repeat the note-sequence
that was played by pressing pads in the same order. Each time you successfully
repeat the note-sequence, another note will be appended to the note-sequence
and the new note-sequence will be played.

`Simone` has a `Blind` mode which allows playing the game without having to
look at the screen.

`Simone` can be played using mouse, touch-screen, or keyboard. When pressing a
pad via a mouse-click, touch, or arrow-key, the pad can be held down
indefinitely (except for the last element in the note-sequence).


`Simone` does not need or use an Internet connection.


| Key |  Description |
|--------|-----------|
| ?      | Show help text. |
| 1      | Level 1. Repeat eight notes to win. |
| 2      | Level 2. Repeat fourteen notes to win. |
| 3      | Level 3. Repeat twenty notes to win. |
| 4      | Level 4. Repeat thirty-one notes to win. |
| B      | Blind mode. This is intended for playing on a phone. After pressing 'S', the screen will be replaced with large rectangular buttons on a black background and the game will begin. Notes will be played with no visual effects. With practice, the game can be played without looking at the phone. |
| F      | Freeplay mode. Any number of notes can be played in any order. |
| M      | Mute sounds. (In Blind mode, the Mute setting is ignored.) |
| R      | Replay the previous sequence. If you successfully repeat it, the game will continue. |
| S      | Start the game. |
| X      | Rotate all four pads 45 degrees. (No UI element is shown.) |
| Arrows | Each arrow-key presses one of the four pads. |


Depending on your browser and/or phone, there may be a small, but noticeable
lag between touching a pad and its activation.

[Reverse Engineering an MB Electronic Simon Game](https://www.waitingforfriday.com/?p=586)
was used as a reference. The [Segment7](https://fontlibrary.org/en/font/segment7)
font was used for the 7-segment LED counter.

If desired, a minified version of `Simone` can be built:

    ./minify.sh        Builds simone.min.html, a minified version of simone.html


This program is free software; you can distribute it and/or modify it under
the terms of the [GNU General Public License](https://www.gnu.org/licenses/) version 2.

