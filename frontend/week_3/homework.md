# Canvas app

Create a drawable canvas with the following requirements:

- A line that tracks the mouse is drawn while the mouse button is pressed down
- Pen colour can be changed using a palette of 8 colours of your choosing
- Pen size can be changed using a slider
- A button has been implemented which clears the entire canvas

Recommended steps:

1) Create a canvas and read about the Canvas API here: https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API
2) Draw some primitives - rectangles, lines, arcs etc using different colours
3) Use mouse events (https://developer.mozilla.org/en-US/docs/Web/API/Element#mouse_events) to draw lines
4) Implement controls

If in doubt, Google a tutorial on this and you should be able to find a reference implementation. Or you can contact me if you get stuck on a particular thing and you couldn't find an answer online.

# Facebook app

Create a simple Facebook-like timeline application with the following requirements:

- There are pre-populated posts shown on load
- There is a text input to create a new post
- New posts always appear at the top
- Posts can be edited and deleted
- Editing a post marks it as edited (Implement a label indicating this)

You can style this in any way you please.

Extra:

- Load enough posts that it overflows the page vertically
- Implement 'infinity' scrolling, where if you scroll enough it will keep loading more posts
- Persist the posts into the browser (see local storage: https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) What this means is that you can come back to the page and it will remember the posts you've added, deleted and edited

Recommended steps:

1) First design a data model. How are the posts going to be stored in JavaScript? Think about what attributes a post has. How are the collection of posts going to be stored? Consider whether or not a class is appropriate for this model.
2) Create functions to manipulate the data model. You can add, edit and delete from it.
3) Create a function which renders the HTML from the data model.
4) Hook up the text input for creating a post to a function from #2
5) Hook up each post's edit and delete functionality to a function from #2
