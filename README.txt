! WORK IN PROGRESS PROJECT ! FEEL FREE TO DOWNLOAD !

Better-CSS is a css framework I've designed to make css and html faster and more organised. While using Better-CSS your projects css file will not be clogged with super
advanced css for every class, instead there are many default setting classes which you can quickly and easily add to your html objects classlist. Using convenient assisted
code editors will make this even easier as they will show you possible parameters for any settings. The CSS file is very large so it is not ideal for public release, when
using a bundling manager this issue will be resolved as it will only keep used lines from the css file in the final bundle. This is made to be a plug and play file so it
comes with a couple default parameters which will be listed in the content body of this text below. You can edit these defaults as they're all at the top of the file. There
is a gap for you to place your custom css to make it so you don't have to scroll all the way to the bottom of the file to write any changes you need.

{x} means a parameter value

Defaults:
Text colour = black;
Background colour = white;
Body = 100vh & 100vw;

Classes:
    Size and positioning:
        .w-{x}vw = width: {x}vh;                   x options: 100, 75, 50, 25, 20, 10
        .w-{x}perc = width: {x}%;                  x options: 100, 75, 50, 25, 20, 10
        .h-{x}vh = height: {x}vh;                  x options: 100, 75, 50, 25, 20, 10
        .h-{x}perc = height: {x}%;                 x options: 100, 75, 50, 25, 20, 10
        .relative = position: relative;
        .relative-r{x} = right: {x}px;             x range = 1 - 40
        .relative-l{x} = left: {x}px;              x range = 1 - 40
        .relative-t{x} = top: {x}px;               x range = 1 - 40

    Borders:
        .radius-{x} = border-radius: {x}px;        x range = 1 - 50
        .b-width-{x} = border-width: {x}px;        x range = 1 - 30
        .b-style-{x} = border-style: {x};          x = any border style

    Margin:

    Shadow:

    Text:

    Grid:
