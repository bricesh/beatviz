Generated from the following Copilot prompts:
1. "write a web page using purely html, javascript, and css. the user should be presented with a text box. The number entered in the text box is a beats per minute value. an array containing a tuple should be looped through. the tuple contains a colour value and a number of beats value. the user should be shown a filled circle of radius 20 pixels based on the colour value for a specific number of seconds. the number of seconds is calculated from the number of beats value times 60 divided by the number of beats per minute value"
1. "regenerate without using setTimeout"
1. "when the start button is pressed, a modal should show the coloured circle"
1. "the modal should close when the escape key is pressed and the array should be looped through indefinitely"


Maladie d'Amour:
```js

        const beatsArray = [
            ['blue', 2, 'D'],
            ['red', 2, 'A'],
			['blue', 2, 'Bm'],
            ['red', 2, 'F#m'],
			['blue', 2, 'G'],
            ['red', 2, 'D'],
            ['black', 2, 'E7'],
			['red', 2, 'A'],
			
			['blue', 2, 'D'],
            ['red', 2, 'A'],
			['blue', 2, 'Bm'],
            ['red', 2, 'F#m'],
			['blue', 2, 'G'],
            ['red', 2, 'D'],
            ['black', 2, 'A'],
			['red', 2, 'G'],
			['blue', 2, 'D'],
			
			['blue', 2, 'D'],
            ['red', 2, 'A'],
			['blue', 2, 'Bm'],
            ['red', 2, 'F#m'],
			['blue', 2, 'G'],
            ['red', 2, 'D'],
            ['black', 2, 'E7'],
			['red', 2, 'A'],
			
			['blue', 2, 'D'],
            ['red', 2, 'A'],
			['blue', 2, 'Bm'],
            ['red', 2, 'F#m'],
			['blue', 2, 'G'],
            ['red', 2, 'D'],
            ['black', 2, 'E7'],
			['red', 2, 'A'],
        ];
```
