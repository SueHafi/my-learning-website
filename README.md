This is just a practise project after developing my HTML and Bootstrap skills a bit more, I wanted to implement my learning in the form of a project.

# Notes on some choices I had to make

I had to style the Navbar link that was imported from bootstrap. I chose to use important method because the particular css selector had 4+ classes that I needed to override. It didn't seem reasonable to over ride the specificity any other way (there are a few other ways I could of done this but this was my prefered way, happy to discuss in the interview).

For the current page underline I used text-underline-offset and text-decoration-thickness, it is supported by most browsers currently. For full browser support I would of used the border-bottom method. I made this decision because I believe simpler is better and I believe that this was the simplest way to implement this.
