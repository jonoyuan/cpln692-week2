# Lab 2 - Functions as building blocks

We'll be looking further into functions in this lab. In particular, we're
interested in using functions to organize our thoughts and to render our
work more readable.


#### Part 1

Open [part1-functions-are-values.html](part1-functions-are-values.html)
and follow in-comment instructions.


#### Part 2

Open [part2-data-transformation.html](../part2-data-transformation.html)
and follow in-comment instructions. Try to organize your code (and your
understanding of the problem!) into these discrete tasks:
- Filtering values
- Cleaning data
- Creating and placing Leaflet objects on the map

If you get stuck, (as always) try to construct experiments in your console.


#### Part 3 (Stretch goal)

One reason we program things is to avoid human error. Unfortunately,
programs are, for the foreseeable future, mostly written by humans. The
reason programmers organize their code in functions and hide
implementation (which is a fancy way of referring to code which
satisfies - or implements - a desired behavior) behind a function
interface is to prevent humans (including future versions of ourselves)
from having to touch a tricky bit of code. One of the most common ways
for programmers to make mistakes is to write code that loops. Luckily,
functions can include loops. Try to implement a function which manages
logic related to iterating through a loop. See if you can use the
functions you wrote in part 1, above, without directly inserting those
functions into the body of your function's loop. In future classes, we'll
learn more tricks that depend on this pattern of passing functions as
arguments to avoid writing loops ourselves.
HINT: You will need to treat your functions as arguments to your looping
function.
