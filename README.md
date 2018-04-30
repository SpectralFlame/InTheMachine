# IntoTheMachine
An interactive programming guide for ages -3/4 up to 999.

## Things To Teach
- [ ] means we know where to implement it (more or less)
- [x] means it's implemented
---------------------------------------------------------
- [ ] Primitive Datatypes
- [ ] If - else Statements
---------------------------------------------------------
See OtherTopics.md for other things we can implement

## Story
### Plot 1
You're an evil mastermind. You find a city of machines. You try to figure out how everything works to then modify it to make an evil robot that will always do what you say.

### Plot 2
Your dad is the boss (or mayor) of Mech City. Ever since he got in control more and more things went wrong. The city is totally abandoned now and barely anything works. Today is the day that you've been waiting for, your dad retires and you get to have the whole city for yourself. Your plan is to make Mech City great again, step by step.

## Zones
The zones are in no particular order

### The Core
Introduction ? or perhaps the opposite

### Garbage Dump
Datatypes

A dump in the background with a shaky machine. There are buttons that makes the machine spit out boxes. These boxes have a value and color depending on the datatype.

type | color
---- | -----
? `void` | black
`boolean` | yellow
`byte` | pink
? `short` | orange
`int` | red
? `long` | dark red
? `float` | light green
`double` | green
? `decimal` | dark green
`char` | light blue
`string` | blue
? `object` | white

Boxes would just fall on the floor and get pushed into a tube to the next section.

### Get Sorted
If / else statements

A piston system needs to sort the boxes but is broken. By dragging code to a piston the piston will adjust it's behavior (based on color of the box on it).

```javascript
function(piston, color) {
  // Place for code to be dragged here
}
```

```javascript
if (color == "green") {
  // Place for code to be dragged here
}
```

```javascript
piston.activate = true;
```

### Recycling Facility
All about code reuse

### Assembly Line
idk yet

### Packing Zone
Classes ?

### Gear Train
inheritance ?

### Robotics
Interfaces ?

Artificial Intelligence

### Steam Engine
Cloud stuff ?

### Wind Farm
Cloud stuff ?

### Oil Refinery
Refine your skills

### Printing Press
printing to the output etc

### The Shredder
idk, randomizing data maybe, or finding patterns in "shredded" data

## Artwork
There is no art yet

### Static Images
- [ ] Garbage dump

### Animation
- [ ] Shaky Machine
- [ ] Assembly Line (Like the Packages of https://atom.io/)
- [ ] Oil Refinery
- [ ] Steam Engine
- [ ] Wind Farm

## Ideas
### Game Additions
* Achievements
* Levels with an extra harder task to earn extra points/achievements
### Loops
#### For Loops
* Calculate the nth number of a sequence (Fibonacci, Exponential growth, ...)
* Get the minimum and maximum value in an array
* Kernel Filter
#### Foreach Loops
* Make invisible objects visible
#### While Loops
* Read a file one line at a time
* Find at which index a sequence passes a certain treshold
