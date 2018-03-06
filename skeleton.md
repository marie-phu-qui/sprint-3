<h1>What happens to the layout when you resize the screen to less than 550 px.</h1>

The Iphone image is different (the 2 Iphones disappear to display only one). As well the whole look of the website becomes different - it is now displaying in a columns look. Everything is on top of each other to get a scrolling downward look. The design of the padding and alignement of the text changes as well. The text is now aligned to the centered instead of left aligned - which makes sense as the bigger screen needs to reflect the 'F shape' reading preferences of major information, and smaller screens need the stregnth impact of a centered title to pop.

<h1>How do you think that works?</h1>

I think this is made via @media (min-width: 550px). Skeleton obeys to the mobile first design.
The whole code is firstly defined to fit a mobile design - but if the screen can fit more than 550px wide, then the properties under '@media (min-width: 550px)' are taking over. This respond to the cascading style of the CSS. 
So every last property is the one that is displayed for the user.
That is why the @media are arranged in a smaller to bigger screen descending fashion.