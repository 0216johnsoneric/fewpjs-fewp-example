# Demonstrate a Front-End Web Programming Example

## Learning Goals

- Define web programming
- Identify reference example
- Identify the "Three Pillars of Web Programming"

## Introduction

"Front-End Web Programming" is a phrase that gets used in a lot of places by a
lot of people. In this lesson we're going to create a common definition of "web
programming" and show one _tiny_ example that demonstrates all of "web
programming's" parts.

### Define Web Programming

Web programming, at its heart, is:

> Creating documents with HTML, styling / positioning the documents' content
> with CSS and updating that content and servers based on events using
> JavaScript.

When a document has a lot of JavaScript code so that the page feels closer to a
computer application, people call it a "**web application**."

<figure>
  <img src="https://curriculum-content.s3.amazonaws.com/fewpjs/fewpjs-fewp-example/legolas.png" alt="Twitter empty heart">
  <figcaption>Web programmers see their favorite sites...differently</figcaption>
</figure>

## Identify Reference Example

While this might be your first introduction to looking at some of your favorite
sites with "web programmer" eyes, you've probably experienced plenty of web
interactions that someone else programmed for you. For the rest of this
material, we're going to pick _one, tiny_ interaction as our shared example.

> **Web Programming Example**: "Favoriting" a social media post.

Regardless of the social media site (Instagram, Pinterest, Facebook, LinkedIn,
Twitter), the interaction went something like this:


1. The site renders some HTML content that is styled using CSS
2. You see the content and decide to show your approval of it
3. You _click_ some visual element meant to show approval (heart,
   thumbs-up, +1, etc.) picture e.g. <img src="https://curriculum-content.s3.amazonaws.com/fewpjs/fewpjs-fewp-example/empty.png" alt="Twitter empty heart">
4. The visual element _changes_ (animates, goes from empty to full, jiggles, etc) e.g.  <img src="https://curriculum-content.s3.amazonaws.com/fewpjs/fewpjs-fewp-example/full.png" alt="Twitter full heart">
5. Behind the scenes, the application _tells the provider_ that such and such
   post has gained one more approval (so that they can notify the creator or
   re-share your approved message to your network)

If all goes as it should, the entire process only takes a second or two. But
in this moment we did _all_ the work of front end web programming. As Blake
might have [said][Blake]:

> To see a World in a Grain of Sand  
> And a Web Programming in a single Like

### Identify the "Three Pillars of Web Programming"

We can break down web programming into three essential "pillars": In the
previous list, we _italicized_ steps 3-5. Each of those demonstrated one of the
"pillars" we must learn in order to be web programmers.

  - Step 3 showed "**Recognizing JS events**:" Your click action on the empty heart
    tells JavaScript to do work
  - Step 4 showed "**Manipulating the DOM**:" the work JavaScript was told to
    do was to update the screen to make the heart "look clicked"
  - Step 5 showed "**Communicate with the server**:" the work JavaScript was
    told to do was to tell the social media company that you approved of this
    content

Now you know what's going on when you click that heart! The next lessons will
focus on explaining each of the "pillars" to you. In the end your "web
programmer" eyes will have you looking at your favorite sites very differently!

## Conclusion

Web Programming is creating documents with HTML, styling / positioning the
documents' content with CSS and updating that content and servers based on
events using JavaScript. We can break down web programming into three pillars
that involve working with the DOM, JavaScript eventing and communication with
the server. Now that we've seen how these elements are connected in principle,
we can now move on to seeing how they work together in practice.

## Resources

- "Three Pillars of Web Programming" reference sheet


[Blake]: https://www.poetryfoundation.org/poems/43650/auguries-of-innocence
