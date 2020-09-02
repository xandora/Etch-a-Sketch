== Instructions for Etch-A-Sketch Project ==

    1. Follow the instructions atop Odin’s Google Homepage project to setup a git repository for this project.
    2. Create a webpage with a 16x16 grid of square divs
        a. Create the divs using JavaScript… don’t try making them by hand with copy and pasting in your html file!
        b. Best to put your grid squares inside another “container” div (that one can go directly in your html)
        c. There are several different ways to make the divs appear as a grid (versus just one on each line) feel free to use any or play with each of them:
            i.   float/clear
            ii.  inline-block
            iii. flexbox
            iv.  CSS Grid
        d. Be careful with borders and margins, they can adjust the size of the squares!
        e. “OMG, Why isn’t my grid being created???”
            i.   Open your browser’s developer tools
            ii.  Check if there are any errors in the JavaScript console
            iii. Check your “elements” pane to see if the elements have actually shown up but are somehow hidden.
            iv.  Go willy-nilly and add console.log statements in your JavaScript to see if it’s actually being loaded.
    3. Set up a “hover” effect so that the grid divs change color when your mouse passes over them, leaving a (pixelated) trail through your grid like a pen would.
        a. Hint: “hovering” is what happens when your mouse enters a div and ends when your mouse leaves it.. you can set up event listeners for either of those events as a starting point.
        b. There are multiple ways to change the color of the divs, including:
            i.  adding a new class to the div
            ii. changing the div’s background color using JavaScript.
    4. Add a button to the top of the screen which will clear the current grid and send the user a popup asking for how many squares per side to make the new grid. Once entered the new grid should be generated in the same total space as before (e.g. 960px wide) and now you’ve got a new sketch pad.
        a. Research button tags in HTML and how you can make a JavaScript function run when one is clicked.
        b. Also check out prompts
        c. You should be able to enter 64 and have a brand new 64x64 grid pop up without changing the total amount of pixels used
    5. (Optional): Instead of just changing the color of your grid from black to white (for example) have each pass through it with the mouse change to a completely random RGB value. Then try having each pass just add another 10% of black to it so that only after 10 passes is the square completely black.
    6. Push your project to GitHub!

