# lessons_learned_teaching_scratch

A compilation of lessons learned from teaching MIT's Scratch programming tool to students.

# Who This is For

This document is for instructors (including non-technical instructors) who are teaching or want to teach programming to young adults using Scratch.

The authors of this document are volunteers of the MADE, the Museum of Art and Digital Entertainment in Oakland, CA. We've compiled this document based on our experiences teaching Scratch for a Saturday morning code class since 2012.

# Online vs Offline Editor

The online editor refers to the Scratch editor at [[https://scratch.mit.edu]] that runs in the web browser, while the offline editor is the downloadable software that runs directly on your computer. Note that Scratch requires Flash and can only run on laptops and chromebooks, not tablets or smartphones.

- Pros of the online editor: It's easy to save work to an account and instantly share it on the internet, it has the "backpack" feature, and is similar to what students will use on home or library computers, multiple Scratch editors can be open at the same time (one per browser tab).
- Cons of the online editor: It requires internet access to use, and unreliable wifi can cause it to stop working.
- Pros of the offline editor: It doesn't require the internet to work.
- Cons of the offline editor: Only one editor can be open at a time, sharing projects online is a separate step, it requires setup installation.

# Setting Up the Computers

These are steps that you might want to follow before the class begins.

- A mouse is much easier to use than the trackpad, especially for dragging. You may have to encourage students to use them over the trackpad.
- If your project includes images from the internet, download them first and save them to the desktop so they're easy to find. Never let students find their own images on Google image search, even with the adult filter turned on. The filter isn't 100%.
- At the end of class, if you need to get the students to stop and move on, tell them to save their program and shut the lid of the laptop. With the laptop closed, their attention won't be taken by the computer.
- Make sure students can see the projector screen. Things at the bottom of the editor can be hard to see from the back of the room.
- A good intro we use at the MADE is for the kids to say their names and their favorite video game is. This is a good way to take roll.
- Set a large mouse pointer on the computer connected to the projector so it is easier to see. On Mac this is found under System Preferences, Universal Access, Mouse, Cursor Size and on Windows this is found under Control Panel, Mouse, Pointers (set it to the Windows Aero (extra large) scheme).
- Maximize the browser window on the laptops. Students will use a smaller browser window and not realize they can maximize it themselves.
- Mute all of the computers before class. Scratch has sound effects, but they can be distracting.

# General Scratch Teaching Tips

- KEEP YOUR HANDS OFF THEIR KEYBOARD AND MOUSE. This is probably the most important tip. Although it may be tempting to type on the student's computer yourself, they won't develop the "muscle memory" of putting together the code themselves.
- Keep students from grabbing other students' mouse and keyboard. Tell them that they should ask first.
- Each block's color matches the color of the bock categories where they can be found. Be sure to point this out to the students.
- Remind students to save the program throughout the class. It might make sense to have some partially-complete projects that they can start from in case they lose all their work.
- Always rename sprites and costumes. Unless it's part of the lesson, don't let them choose their own names.
- Always make them use the names you choose for variables, broadcast messages, and sprites. This may seem a bit controlling, but the names they come up with will often cause confusion down the road and also make it harder to debug their programs.
- When putting a boolean operator ("and", "or") in a "if/then" block, don't place additional boolean blocks inside other boolean blocks. Instead of using multiple "and" blocks, nest multiple "if/then" blocks instead each other.
- Use multiple, separate "when green flag clicked, forever" scripts rather than putting too much code in one script.
- Point out the Undo button early on when doing anything that involves the Paint Editor. Students will make several mistakes, but the Undo (and Redo) buttons can help them fix it.
- If you're projecting on a screen, click the Zoom buttons in the lower right of the Scratch editor to increase the size of the blocks.
- You can copy blocks to other sprites by dragging them to the other sprite's icon in the Sprite Area. This is a useful shortcut to duplicate blocks across sprites.

# Common Scratch Pitfalls

There are several common mistakes that students make while putting together Scratch programs.

- It's possible to type spaces at the front and end of the text fields, causing subtle bugs when "x = 10" is actually set to "x =       10".
- Students will commonly set variables to "For all sprites" instead of "For this sprite only" or vice versa. Remember that "For this sprite only" variables will have the sprite name prepended to the variable display on the stage.
- Students will commonly add code to the wrong sprite, or to the backdrop. Check which sprite's code they're looking at by seeing which sprite icon in the Sprites Area has the blue outline around.
- Many blocks don't apply to the Stage. If students complain they can't find the blocks they need (especially in the Motion, Looks, and Pen category), make sure they do not have the Stage currently selected in the Sprites Area.
- If students complain that they can't find a variable block that they previously created, they may have created it as a "For this sprite only" variable for a different sprite. Click on the other sprites in the Sprite Area to see if their Data category contains the variable they're looking for.
- Variable blocks are orange, while List blocks are red. Students sometimes click "Make a Variable" instead of "Make a List" or vice versa.
- If the instructions include duplicating costumes, students sometimes duplicate the sprite instead (or vice versa). Make sure they understand the costume list is on the Costumes Tab and runs down the center of the editor, while the Sprites Area is in the lower left.
- The buttons for painting a new sprite, costume, and backdrop look identical. Make sure students are clicking on the correct one.

# Blocks That Are Commonly Confused With Each Other

Some blocks are commonly confused with each other. Whenever instructing students to use one of the following blocks, point out that they do not want to select the other blocks.

- The "if/then" and "if/then/else" blocks. The "if/then" blocks are C-shaped, the "if/then/else" blocks are shaped like an E.
- The "change x by", "set x to", "change y by" and "set y to" blocks.
- The "set variable to" and "change variable by" orange Data blocks.
- The "<" and ">" green Operator blocks.
- The "repeat 10" and "repeat until" blocks.
- The "wait 1 secs" and "wait until" blocks.
- The "x position" and "y position" blocks.
- The "broadcast" and "broadcast and wait" blocks.
- The "go to" and "go to x y" blocks.

# Paint Editor Pitfalls

The paint editor on the Costumes tab has its own set of commonly encountered problems. In general, avoiding the paint editor by using Scratch's built-in images from the sprites library or backdrop library will save you on class time and headache.

- Avoid anything that requires changing the costume center. If the sprites seems to behave oddly when using the "turn" blocks, it may be due to the costume center being set incorrectly.
- Students using the fill tool will have often left a "gap" in the shape they are filling, resulting in much of the canvas being filled in with this color. Use the undo button to fix this.
- Note that while you can always change the color of something using the fill tool as long as you are filling with a solid color, if you click on the horizontal, vertical, or circular gradient tools, you will lose the ability to change the color of the gradient with the fill tool. Use the undo button to remove the gradient and try a different color.
- You can always tell whether a sprite is in bitmap or vector mode because the drawing tool buttons in vector mode are along the right side, while bitmap mode has them along the left side.
- Students tend to draw sprites far too large for a program. Use the grow/shrink tool or the "set size" block to correct this.

# Selecting Projects

If students are going to follow along and recreate a project that you've made, here are some tips for the kinds of projects that work well for a class.

- The simpler the program, the better. Games don't have to be complicated to be fun, and there's usually only a few minutes left at the end of class by the time students complete the programs anyway.
- Casual games (such as mobile games or Flash games) are good ideas. Don't do game projects that have multiple levels.
- Minimize the amount of time students spend in the paint editor. Drawing can easily eat up a lot of class time.
- Try to use only the images in the sprite or backdrop library. Uploading images to Scratch, or drawing images in the paint editor tends to be complicated and time consuming.
- Minimize the number of variables in your games. Try to keep it to two or three at most. Try to stick to "For all sprites" variables only.
- Instead of setting the rotation style for a sprite in the Info Panel, use the "set rotation style" block. Students are less likely to miss this step if it is done through a code block that they can see.
- Use the "set size" block instead of using the grow/shrink tools. The "set size block" lets you set a specific size, rather than eyeball it with the grow/shrink tool.
- Don't do games that use a "camera" or scrolling. This tends to be a very complex mechanic to implement in Scratch.
- Have several "test points" where students check that their program does what it's supposed to before moving on. Bugs can accumulate pretty quickly, and it's best to find them early on. Followa "Code a little, test a little" approach.
- If the game involves shooting, don’t use literal guns. As an alternative, use a bow & arrow, lightning bolts, cannons & cannonballs, or dodge balls.
- If the game involves shooting, don't have targets be living things. As an alternative, use targets, stars, asteroids, or sprites from the Things category.

# Note for Professional Software Developers

If you are a professional software developer, it can be easy to have overly high expectations about the capabilities of Scratch or students. Remember that some things that make sense in computer science algorithms or well-maintained professional source code don't necessarily apply to a programming education tool like Scratch.

- Don't write "generalized" code, as it's often more abstract and harder to understand. It's okay to have duplicate code.
- Global variables (which, in Scratch, are "For all sprites" variables) are fine to use.
- Broadcast messages are like functions, except there is no call stack. This means recursion isn't possible to do with just broadcast or custom "More Blocks" blocks.
- You can simulate using recursion using Lists, but this is probably too sophisticated of a concept for students. Use an iterative approach instead.
- When choosing variable names, be a part of the "vowel generation": Use variable names like "string compare", not "strcmp".
- Code that uses indirection/abstract concepts (indexes to lists, magic numbers, etc) will be hard to understand.
- Scratch has no error messages, but instead uses sensible defaults. (Zero divide just results to a string "infinity".)
- There are no data types in Scratch, though round text fields are restricted to numbers only while square text fields can have any text.

# Special Scratch Tricks

Here are some tricks in Scratch that took us a while to discover.

- The Backpack (only available in the online editor) lets you share code blocks between Scratch projects. Click the drawer along the bottom of the Scratch editor to open it, then drag code blocks inside of it.
- You can right-click the "<", "=", and ">" green Operator blocks and switch their symbols, rather than pull out a new block.
- You can right-click the "+", "-", "*", and "/" green Operator blocks and switch their symbols, rather than pull out a new block.
- TODO finish this section