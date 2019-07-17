# y2s19-css-meetx

Before we begin, make sure to fork and clone this repository as we did yesterday:

  - Click the *Fork* button at the top right of the screen to make your own copy of the repository
  - Clone it as we did before:
  ```
  cd ~/Desktop
  git clone https://github.com/meet-projects/y2s19-css-meetx.git
  cd y2s19-css-meetx
  ```
  
  
# Lab 1 - Basic CSS
 
1. Open hello.html and create a page with a header, two paragraphs, and at least one link.

2. Open style.css and create a style file such that the background color is blue and all text is white.

3. In your HTML file, add this somewhere inside the `<head>`:

```
<link rel="stylesheet" type="text/css" href="style.css">
```

4. Use a CSS tag selector to change the color of all links.

5. Add a list of six favorite foods to your website. Use the `<ul>` tag to accomplish this. 

6. Use CSS class selectors to make vegetarian foods one color and non-vegetarian foods a different color.

7. Use a CSS id selector to give one element on your page a different background color.

8. Using Google and/or w3schools, find out what the following properties do.
- font-family
- font-size

# Lab 2 - CSS Continued

1. Organize your page:

- In `hello.html`, make the header a div and give it a class name of "title".
- Put the rest of your content (paragraphs and links) in a `<div>` with a class of "content".
- You should by now have divs with"title" and "content" classes, let's now create a new `<div>` with a class of "sidebar" between the title and content class divs. Put some text or links in it!
- Lastly, put the "content" and "sidebar" classes in another `<div>` with a class of "container".

If you're confused, look at the lecture slide with the title "Lab 3: Hints".

2. Open `style.css`. Give the sidebar a light background color of your choosing.

3. Make the title banner have a height of 60px, and a width of 100%.

4. Give the `container` class the `position: relative` property.

5. Give the sidebar and main content classes `position: absolute;` and `top: 0px;` Have the sidebar be positioned on the left margin of the page, and the main content be positioned 200px from the left.

6. Make it so the sidebar is exactly wide enough to touch the main content, using the `width` property.

7. Give the container a height of 1000px. 
- This is because the container has only absolutely positioned \<div\>s inside it, which means it has zero size by default.

8. Now, give the sidebar a height of 100%, to have it go all the way down the page.

9. Lastly, use the inspector on your browser (right-click on the page, then click "Inspect Element") to remove the `position: relative;` property from the `container` class. Notice how the position of the sidebar and main content changes, and show this demo to the TA to get checked off.


# Lab 3 - Centering and Advanced Selectors
## 1. Center Yourself
- Open `lab2-centering` in your browser, we've added some extra content - and all of the content is color-coded. Check out the linked style sheet to see what element is what color. 

- Your task in this lab is to make the webpage look like this: 
![Alt text](centered_page.png?raw=true "Title")
- But the catch is that you can only edit the style sheet!

- Hint - to tell if something is block vs inline, look at the background color! Is the background just big enough to fit? Also, remember inline elements don't make newlines (so they would need a `<br>` element for newlines).

- Hint - the text "Survey Time" is a `p`, so it gets centered when you center all `p` elements. But unlike the other `p`'s, this one is inside a `div`. How can you use advanced selectors to un-center this element? Remember, what is the left-margin of something not centered?

## 2. Super Selectors
- Go have some fun with selectors [here](https://flukeout.github.io/)

# Lab 4 - Bootstrap
## Part 1: Bootstrap Grid
__Edit exercise.html for this portion of the lab__
1. Create a table layout **using bootrstrap grid** that includes 3 types of animals of your choice. The table layout should look similar to this **for all types of screens**: 

| Name       | Image  |
| ------------- | -----|
| Cat     | <img src="https://i.ytimg.com/vi/YCaGYUIfdy4/maxresdefault.jpg" width="350"> |
| Red Panda     | <img src="https://i.redd.it/0vbx9fw2hpd01.jpg" width="350"> |
| Dolphin     | <img src="https://i0.wp.com/funkidsjokes.com/wp-content/uploads/2016/08/dolphin-203875_960_720.jpg?resize=300%2C200&ssl=1" width="350"> |
2. Show your work to an instructor or TA!

**Bonus**
Open the website you made then right click and inspect element. As you notice, the image isn't compatible with the screen size and can sometimes get out of the borders of the column that includes it. Google how to fix that. (hint: you need to make the image's width compatible with its parent)


## Part 2: Bootstrap Components
__Edit exercise.html for this portion of the lab__
1. Make a carousel that displays the images of the animals you listed previously.
2. Add a "Primary" Button with the text Next, and a "Secondary"Button with the text "Previous"
3. Show your work to an instructor or TA
