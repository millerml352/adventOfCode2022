# adventOfCode2022
Tracking my progress on Advent of Code 2022, working in Python, attempting to try new things as I'm sure will be needed to complete all challenges
Recording something below for each day that was at least relatively new to me
1. nested for loops written as one line comprehension
2. match case statement
3. dictionary to assign priority values to characters
4. list comprehension statement to determine range overlap
5. custom function for parsing text input to crate stacks. whew lord, challenging to parse and I was committed to not hardcoding the stacks. I knew how I wanted to tackle this, but I could not create the function myself so credit for parse_stack_text() code goes to reddit u/i_have_no_biscuits in r/adventofcode. I made sure to only take his code once I knew it was what I was flailing to do myself, and figure out the rest of the solution myself. Also spent a considerable amount of time examining the parts of that function to see how it did what I understood in concept but could not construct myself. Special bit of learning was extended slice notation i.e. \[start:stop:step\] in order to pull out each crate character
6. way simpler. felt like overacheiving so did part 2 two ways, one hardcoding variables, the other with one dynamic variable. new syntax for opening and closing a file used at top, and in the second method for part 2 used an 'if not boolean' to break the loop once the message marker was found, slightly less comfortable but it definitely seems like a streamlined way to write compared to what I used to