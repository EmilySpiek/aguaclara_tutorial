# Interactive Tutorial 1: Markdown

## Working with Markdown

Press `Ctrl + Shift + M` to open a formatted preview on the right.

## Basic Text

Write two sentences about yourself, each in a different paragraph.

My name is Emily, and I am a sophomore chemical engineering student at Cornell University.

I love my dogs.

## Headers

Make a 3rd level header with your name:

### Emily Spiek

## Emphasis

Write 4 of your favorite words using each type of emphasis:

*joy,* **crescendo,** ***um,*** ~~what~~

## Lists

Make an ordered list of 3 things you hope to achieve this semester, and elaborate on them with sub items. Then, make an unordered list of 3 classes that you're taking this semester:

1. I want to get more sleep
    - I will finish my homework earlier
    - I won't drink coffee in the afternoon
2. I want to get a 4.0
    - I will study for prelims
    - I will finish all my work on time
3. I want to be healthier
    - I will exercise regularly
    - I will eat more fruits and vegetables

## Links

Write a sentence describing your major, and insert a link to your major's department website:

[Chemical engineering](https://www.cheme.cornell.edu/) combines chemistry with engineering to create large-scale chemical processes.

## Images

Insert the Cornell seal image with:
  1. A relative file path(`/Images/Cornell_University_seal.png`)


  2. A URL (https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)

1
![CornellSeal](/Images/Cornell_University_seal.svg.png)

2
![CornellSeal](https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/Cornell_University_seal.svg/2000px-Cornell_University_seal.svg.png)

## Code Formatting

Put the name of this file in an in-line (single backtick) code format.

`Interactive-Tutorial-1-Markdown`

Put the following text in a Python-formatted code block:

```
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

```python
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

## Tables

Create a table listing your 3 favorite animals, books, and places on campus. Use a different alignment for each column.


| Animals    | Foods    | Books     | Places at Cornell     |
| :------------- | :------------- | :------------- | :------------- |
| 1. Dogs| 1. Potatoes| 1. Harry Potter|1. Suspension Bridge|
| 2. Deer| 2. Blackberries| 2. The Book Thief|2. Entrance to West Campus|
| 3. Otters| 3. Raspberries|3. The Giver|3. Garden behind Cornell Store|


## Blockquotes

Write your favorite quote. It must be attributed to Albert Einstein.

> I have loved the stars too fondly to be fearful of the night -Albert Einstein

## Horizontal Rules

Add a horizontal rule:

---

## LaTeX Formatting

Copy the equation towards the end of the [Markdown tutorial](https://github.com/AguaClara/aguaclara_tutorial/wiki/Markdown#latex-formatting) and paste it here:

$$ a^2 + b^2 = c^2 $$
