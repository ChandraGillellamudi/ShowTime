# It's ShowTime 🎥

ShowTime displays your taps and gestures on screen, perfect for that demo or presentation. One file is all you need to massively improve your demos.

## Installation

- Step 1: Drop `ShowTime.swift` into your project or copy the contents of it whereever you like. 
- Step 2: There is no step 2; you're ready to go.

## Usage

ShowTime works out of the box, but you can customise it to turn it on or off (you could use this to have a demo environment),
change the colour and outline of the taps, and even choose whether to display the number of taps for multiple taps.
Here's a list of options:

- `ShowTime.itsShowTime`: Whether ShowTime is enabled (`true` by default)
- `ShowTime.fillColor`: The fill (background) colour of the touch circles
- `ShowTime.strokeColor`: The colour of the stroke (outline) of the touch circles
- `ShowTime.strokeWidth`: The width (thickness) of the stroke around the touch circles
- `ShowTime.size`: The size of the touch circles. The default is 44 x 44
- `ShowTime.showMultipleTapCount`: Whether the touch circles should indicate a multiple tap (i.e. show a number 2 for a double tap) (`false` by default)
- `ShowTime.multipleTapCountTextColor`: The colour of the text to use when showing multiple tap counts
