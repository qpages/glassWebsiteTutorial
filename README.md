# STEPS
0. Create the propotype in Figma (see another video?)
1. Code the glass thing
2. Code the content: Dashboard & Games

## In more details
1. Code the background
    1.1 Set the background linear color
    1.2 Set the dimension and the position of the glass.
    1.3 Add circle and put them behind the glass (z-index)
    1.4 Add the blur effect (backdrop-filter)

2. Code the dashboard in glass
    2.1 Segment left glass part in 3 parts:
        + a User div
        + a Links div
        + a "Become a pro" div
    2.2 Segment right glass part in 3 parts:
        + Title
        + Search bar
        + Cards which contains each an image, a text, a progress bar and a percentage (class card-info)
    2.3 Make all design things in CSS
    2.4 Change font to Poppins Regular 600

# Questions ?
* What is a vh?

* What is a rem?
> A certain amount of pixels

* Why circle wasn't on the screen?
> Need to give it an absolute position

* Why when I applyed 50% of border radius, my shape is not circle?
> Be careful, to do so, heigth and width must be equal

* How to set Dashboard and Games an equal width?
> `flex: 1` in .games and .dashboard

* How to leave the Game 2 times more space than Dasboard?
> `flex 2` in .games and `flex 1`in .dashboard

* How to center all the textin dashboard class?
> `text-align: center` in .dashboard

* How to make .pro img relative to div pro?
> `positon: relative` in .pro and position: absolute in .pro img

* What is the difference between font-size and font-weight?
> Weight is if font is more or less bold and Size is height of font.

* How to clip the background to the text ?
> `-webkit-background-clip: text;` and `-webkit-text-fill-color: transparent;`

# Tips
* Set opacity to title for a better "glass" effect.
* `overflow: hidden` to hide something going outside its div as progress::after does.