# lessons_learned_teaching_scratch
A compilation of lessons learned from teaching MIT's Scratch programming tool to students.

# Who This is For

- TODO for teachers (including non CS teachers) who want to lead classes through Scratch.
- TODO we are the MADE and have been teaching Scratch on Saturday mornings since 2012.

# Online vs Offline Editor

- TODO pros of online: easier to save and share, has backpack, more like what the kids will use at home or in a library
- TODO pros of offline: doesn't require wifi
- TODO cons of online: needs internet access while using
- TODO cons of offline: only one editor at a time, sharing is more difficult but still possible, requires set up
- TODO note: scratch doesn't run on tablets or smartphones since they don't support the Flash browser plugin, only laptops and desktops and chromebooks.

# Setting Up the Computers

- TODO mice are easier to use but take up more space
- TODO download images first, and to the desktop. never let kids find their own images on Google image search, even with the adult filter turned on.
- TODO at the end of class, if you need to get the kids to stop, tell them to save, them close scratch, then close the lid of the laptop
- TODO make sure kids can see the projector screen. buttons at the bottom of the editor can be hard to see from a distance.
- TODO a good intro is for the kids to say their names and their favorite video games (this also gives you an idea of what kids are playing)
- TODO give yor computer connected to the projector a large mouse cursor.
- TODO maximize the browser window, kids will use a small window and not maximize it themselves.
- TODO mute all computers

# General Scratch Tips

- TODO the block colors match the categories, be sure to point this out to the kids
- TODO save the program every 15 minutes. It might make sense to have some partially-complete projects that they can start from in case they lose all their work
- TODO rename sprites and costumes always. Unless it's part of the lesson, don't let them choose their own names.
- TODO always make them use the names you choose for variables and broadcast messages.
- TODO don't use more than one boolean operator in a if/then block. Go ahead and nest if/then blocks instead of using multiple "and" blocks.
- TODO use separate "when green flag clicked, forever" scripts rather than putting too much into one.
- TODO undo button in paint editor
- TODO remember to praise
- TODO keep your hands off their keyboard
- TODO tell them to ask before they touch other kid's keyboards
- TODO zoom in the blocks if projecting
- TODO don't block the projector
- TODO you can copy code blocks by dragging them over to other sprites in the Sprite Area.

# Common Scratch Pitfalls

- TODO adding whitespace to the end of text fields
- TODO mistaking For all sprites, For this sprite only
- TODO adding code to the wrong sprite (or to the backdrop)
- TODO not seeing blocks because the stage is selected, or the variable is For all sprites only
- TODO making a variable instead of a list, and vice versa
- TODO duplicating sprites instead of costumes
- TODO clicking on a new backdrop instead of sprite or costume.

# Blocks That Are Commonly Confused With Each Other

- TODO if/then, if/then/else (one is shaped like C, the other like E)
- TODO set/change x/y
- TODO < and >
- TODO set/change variable
- TODO repeat 10, repeat until
- TODO wait 1 secs, wait until
- TODO x position, y position
- TODO broadcast, broadcast and wait
- TODO go to, go to x y

# Selecting Projects

- TODO the simpler the better, games don't have to be complicated to be fun, they'll only play them for ten minutes anyway
- TODO small phone app games or flash games are good ideas. Don't do things that have multiple levels.
- TODO try to avoid using the paint editor
- TODO minimize the number of variables
- TODO use "set rotation style" instead of telling them to set it in the info panel
- TODO use "set size" instead of the grow/shrink tool
- TODO don't do games that use a "camera" or scrolling
- TODO avoid uploading images, stick to the ones in the backdrop and sprite library. You can do color changes or use them as a base.
- TODO have several "test points" where kids check that their program does what it's supposed to before moving on. Have a written list. Bugs can accumulate pretty quickly. "Code a little, test a little"
- TODO Don’t use literal guns in the game. Alternatives: bow & arrow, “energy balls”, lightning bolts, cannons & cannonballs.
- TODO If there is shooting, don't have targets be living things. Alternatives: targets, stars, asteroids, or sprites from the Things category.

# Note for Professional Software Developers

- TODO elegant and generalized code means nothing, it's too hard. Go ahead and use global variables (for all sprites), and even copy & paste code
- TODO don't do recursion, there's no callstack anyway bc there's no functions (though this can be simulated with lists and )
- When choosing variable names, be a part of the "vowel generation": Use variable names like "string compare", not "strcmp".
- Code that uses indirection/abstract concepts (indexes to lists, magic numbers, etc) is hard to understand.
- TODO scratch has no error messages, but uses sensible defaults. zero divide just sets it to "infinity" string.
- TODO there are no data types. There is only a list.

# Paint Editor Pitfalls

- TODO avoid changing the costume center
- TODO fill tool mishaps
- TODO vector vs bitmap mode (use bitmap mode, drawing tools are on the left side)
- TODO kids tend to draw things too large

# Special Scratch Tricks

- TODO right-click to change <. =, >
- TODO backpack
-