# fit-my-text

Fits the typed text into an output div that can be resized. Also some Jasmine unit tests.

Improvement suggestions:

1) It would be good to also save the font size and width of the output div between sessions. At the moment the text always loads with the maximum font size, even if it's too long to be contained by the default width output div.
2) Improve cross-browser compatibility. Currently, the solution does not work in Safari due to a security error related to localStorage. This could probably be fixed with a work-around.
3) The fitText() function could be tweaked to be smoother and more accurate. Perhaps it would be possible to find a relationship between the output div width and the font size instead of increasing or decreasing font size by a set number. This would probably also solve improvement #1.
