
# Portfolio 

## Week 1 challenge - HTML & CSS

### GitHub Pages link:

https://jimmylee88.github.io/week1-challenge/

### Intro

I'm currently enrolled on a Web Development bootcamp, and we've been learning some foundational HTML and CSS during the first week. Our first challenge is to create our own portfolio page, and implement some of the things we've been learning in classes.

### Approach

I actually started by scribbling on pen & paper, a rough idea of what I wanted to include content-wise and a basic strucutre. I then went into the HTML and made sure I structured it using semantic tags, with an idea of where things would sit on a page.

Then I gradually added in the content, bit by bit unstyled at first before moving onto the CSS styling. For the visual design, and styling I started by picking the geometric sans-serif font, "Poppins" as I like how friendly it is. I think in turn, this influenced why I made so much use of rounding the border-radius of many elements like the images, nav bar, and article cards. The choice of colours were based on the photo I chose of myself, and helped narrow it down to warm tones that complement each other. 

With consideration for accessibility, I wanted to make sure that images have relevant alt text descriptions, and colours pass contrast ratio checks—the orange just about does, but only for large sizes so may need tweaking in future. In addition to this, I wanted to explore subtle CSS transitions, pseudo classes with my decision to ensure that elements that have focus and active states have distinct differences that don't rely solely on colour changes. This will help users who may have visual impairments. e.g. Underline on hovering over text links in the nav, article cards that shrink when hovered, and the box-shadow on the form submit button.

### Challenges

I wanted to make the nav bar sticky, so that interacting with the anchor links can be easily accessed at any point when viewing the page. I made it essentially a one-column layout as there aren't many sections and is laid out linearly. Unfortunately I couldn't get this to work, so will have to revisit in future.

I also struggled with spacing out the nav bar links evenly, and had to add space with padding and adjust the width in a bit of a hacky way. 

Another problem I was having, was with the Poppins font. I wasn't sure if it was rendering properly on devices that didn't have it installed. I already had the font on my machine, so couldn't easily tell. I did a bunch of commits and back-and-forth tweaking even after I submitted this work to try and work it out.

I also couldn't work out why putting the text in a paragraph tag for the footer would automatically make it align to the left, when everything else was centred. In the end I used a h4 tag in a bit of a hacky way.
 
### Reflection & Next Steps

This was a really fun assignment for me, and I valued being able to apply the little bits I learned in class exercises.

Knowing that spacing things out with flexbox is much easier, is a relief and I would like to use it for this in future. It would help with the nav bar, and also laying out the article cards.

I would like to figure out where I'm going wrong with making the nav bar sticky too. Other things to improve, are making it properly responsive and adapt to different breakpoints. I've kind of got away with it in a lazy way by essentially laying everything out in one big column.
