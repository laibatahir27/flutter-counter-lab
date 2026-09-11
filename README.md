# Counter App

**Name:** Laiba Tahir
**Roll Number:** 04072313014

## What I did
- Added a reset button that sets the counter back to 0.
- Added a green message "You're on a roll!" that shows only when the counter goes above 10.
- Added a second counter that counts how many times reset was pressed.
- Changed the theme color to light blue.
- Added my name and roll number at the bottom of the screen.

## Screenshot

![screenshot](screenshot.jpeg)

## Reflection

setState() is what tells Flutter to redraw the screen after something changes. If I just change a variable like the counter without calling setState(), the value does change, but Flutter has no way of knowing it needs to update the screen, so the old number just stays there. Once I put the change inside setState(), Flutter rebuilds that part of the screen and shows the new value. That's why I used it twice in my code, once for increment and once for reset, because each one changes different data and needs its own update.