---
title: "Homework Lesson 1: Escaping Characters"
author: Elisabeth Maria Magin
date: February 2026
---

# Special characters

As you’ve discovered in the first lesson, several very common characters are used as part of the syntax Markdown uses to convey instructions to the computer. This also means that these characters may not show up in the way you expect them to in the output. The two asterixes around a word, for example, will disappear in the output; the computer doesn’t parse them as *characters,* it parses them as *instructions*. Similarly, a plus or dash at the start of a line is going to be interpreted as the start of an unordered list, not a + or a -.

# “Escaping” characters

In computing, to “escape” a character means that a character belonging to the syntax is in its own turn marked in such a way that the computer knows to display it as a literal character in this particular instance. In Markdown (as well as many other markup and programming languages), the “escape character” is the backslash.

At <https://www.markdownguide.org/basic-syntax/#escaping-characters> and below, you’ll find a list of all characters that you can/should escape when you want them printed as literal characters.

# Exercise

The list of characters that are part of the syntax in Markdown is inserted twice below, once in a single paragraph/line, and once with every character at the start of a new paragraph.

1. Use this document as a basis and export it to HTML.
2. Compare the output in the browser to your raw document. Which of the characters from the list can you see, which ones have changed, and have they changed both when appearing as part of a paragraph or as a paragraph on their own?
3. Experiment with backslashes. Put one of them in front of different characters (no whitespace!) and export the list again, if you like, several times.
4. Compare the new result with the previous result. What has changed?
5. Based on your observations, create a list of the characters you think you should escape every time you want the character printed literally, and a list of characters that don’t necessarily need to be escaped.

\ ` * _ {} [] < > () # + - . ! |

\ 

`

* 

_

{}

[]

<>

()

#

+

-

. [^period]

!

|

[^period]: Read through <https://www.markdownguide.org/basic-syntax/#lists-1>, specifically <https://www.markdownguide.org/basic-syntax/#starting-unordered-list-items-with-numbers> concerning the syntax meaning of a period.