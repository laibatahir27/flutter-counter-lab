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

setState() tells Flutter that something has changed and the screen needs to be updated.If I change the counter value without using setState() then value changes in the code but the new value may not appear on the screen.When I use setState() the flutter rebuilds the screen and shows the updated value.I've used setState() in both the increment and reset functions because both functions change the counter.
