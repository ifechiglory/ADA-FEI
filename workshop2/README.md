##We finally got to CSS *yay!*

It's exciting but we're just in the beginning. In this session, I am trying out CSS selectors, pseudo selectors, animation using the @keyframes rule and some other stuff.

In my little research, pseudo selectors are plenty *(who knew)*. These selectors also perform different functions.

I found out that the ::marker pseudo selector is definetly not the same thing as the ::before pseudo selector. They look the same on the screen but do not let that deceive you

The ::before pseudo selector basically creates a child element and appends it to the element you are working on.

The ::marker pseudo selector selects the marker box of a list item. This [resource (https://developer.mozilla.org/en-US/docs/Web/CSS/::marker)] helped a lot in my research on the marker psuedo selector. 

Ideally, the marker box is what I should use to change the color of my list style type but it was not marking well *(:sob:)*

Edit: I changed the ::before pseudo selector to the ::marker pseudo selector. I found what I was doing wrong. I had set list-style-type to none and I expected my marker to work :smiling_face_with_tear:. Anyways, we learn everyday.