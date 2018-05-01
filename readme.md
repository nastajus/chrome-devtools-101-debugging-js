https://www.youtube.com/watch?v=H0XScE08hy8

with devtools you can pause the code in the middle of it's execution, inspect the variables that are in scope at that moment of execution, and walk through the code one line at a time.

`CTRL+SHIFT+J` on windows / linux

##### `sources` panel is where you debug javascript
- 3 parts
    - 1: file navigator pane.
    - 2: code editor pane.
    - 3: javascript debugging pane.


the incorrect sum gets computed in click event listener that's associated to the button.

∴ you want to pause the code right when the event listener executes.

- event listener breakpoints permit this.

inside debugging pane > expand event listener breakpoints > expand mouse > check off click

- devtools now pauses on the first line of any event listener that executes.


[//]: # (status: stopped early since i realised this video wasn't showing me what i needed now, which is approximately ~~~how to debug jquery uumm <commands>? entered into the chrome devtools console~~~)