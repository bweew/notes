---
title: Vim
Date: “2023-03-04"
---
## vim

- control d control u = pg up down
- shift ZQ quit
- change xrate to move faster on keys 350 is a good setting
- shift curlybracket move around
-   A moves to end of line and enter insert
- I enter insert mode
- :X is also save and quit
- :W save
- :sort sorts everything
- d to delete dw delete word x delete char
- d$ delete to end of line
- 0 and caret take you to start
- D also deletes to end of line
- w and e are movement commands e end to nex word
- b move back a word
- d{ delete paragraph
- 2w move 2 words forward
- dd delete line
- - u undo control r redo
- daw delete word AND white space around it
- diw delte word not the white space around it
- dap delete paragraph
- di( delete in paranthesis da( delete everything including
- :earlier 5m go back in time!! 
- :later 15m
- di” da”
- d
- p is put or paste dd p is copy paste
- c deletes and puts you in insert better than r replace
- ci{ cw caw
- ctrl G file status 25% jumps to 
- gg top G to bottom
- / search n N forwards backward
- o start new paragraph enter a line
- O does above
- matching parenthesis jump %

## sed like substitution
- :s/thee/the/g replace all in line no go only does one
- :%s/thee/the/gc gc gives a prompt
- :#,#s/old/new/g within a range substitute

- ? is search backwards
- :! run a command
- v is visual selection
- vap select a whole paragraph
- yap copy whole paragraph
- V selects whole line
- CONTROL block selection!!
-  period does last command!
- yy yank whole line
- :Norm does normal mode
- capital R goes into replace mode OVER WRITES only good if its same length
- cw is better tho 99% of the time
- theres settings for spellcheck and jump to mispelled word
- :set_ic turns search to case insensitive

## Grep

## sed

## Awk

## regular expressions

## regex yt script

[Opening shot of a computer screen displaying a code editor]

Narrator: "Welcome to this video about regular expressions! Regular expressions, or regex for short, are a powerful tool for searching and manipulating text. They allow you to find patterns in text that you wouldn't be able to find with a simple 'find and replace' method. Let's see some examples of situations where regex can be more useful."

[Cut to a split-screen of two code editors, one with a sample text document and the other with a 'find and replace' dialog box]

Narrator: "Let's say we have a document with a list of phone numbers. We want to format them all in a consistent way, with parentheses around the area code and a hyphen between the next three digits. We could use a 'find and replace' function to replace each instance of the phone number with the formatted version, but that could be time-consuming if we have a lot of phone numbers to format."

[Switch to a new window with a regex editor open]

Narrator: "With regex, we can use a pattern to find all instances of phone numbers in the document and then format them all at once. Let's look at an example pattern."

[The regex editor displays the pattern "\d{3}\d3\s\d{3}-\d{4}" and highlights the matching phone numbers in the sample text document]

Narrator: "This pattern matches phone numbers in the format of (123) 456-7890. We can use this pattern to find all instances of phone numbers in the document, and then format them all at once."

[Switch back to the split-screen of the two code editors]

Narrator: "As you can see, regex can be much more efficient than a 'find and replace' method in this situation. But that's just one example. Let's look at another one."

[Cut to a new window with a sample HTML code]

Narrator: "Let's say we have a web page with a lot of links to external websites. We want to change the target attribute of each link to '_blank' so that the links open in a new window. Again, we could use a 'find and replace' method to change each instance of the target attribute, but that could be time-consuming and error-prone."

[Switch to a new window with a regex editor open]

Narrator: "With regex, we can use a pattern to find all instances of the target attribute and then change them all at once. Let's look at an example pattern."

[The regex editor displays the pattern "target="_blank"" and highlights the matching target attributes in the sample HTML code]

Narrator: "This pattern matches the target attribute with the value of '_blank'. We can use this pattern to find all instances of the target attribute and then change them all at once."

[Switch back to the split-screen of the two code editors]

Narrator: "As you can see, regex can be much more efficient than a 'find and replace' method in this situation as well."

[Closing shot of the computer screen displaying the final result of the regex search and replace]

Narrator: "So, those are just a couple of examples of how regex can be more useful than a 'find and replace' method. If you're working with text and you want to find patterns or manipulate text in a more efficient way, consider using regex."

## regex sonnet

[![regex sonnet](https://i.imgur.com/kLdEwoy.jpg)
](https://youtu.be/hb2qw-HeFpM)

Oh, Regex! Your power doth surpass compare,
A tool for seeking patterns in the text,
With symbols, metacharacters all so rare,
Your mastery doth leave mere mortals perplexed.

Your strength lies in the patterns that you find,
With syntax that unlocks the hidden code,
You sift through strings with keen and nimble mind,
And bring to light what once lay in abode.

No more the need for find and replace old,
Your power to manipulate doth astound,
From URLs to phone numbers, all so bold,
Your use in text-processing knows no bound.

Regex, the language of the text's domain,
Forevermore shall thou in glory reign.
