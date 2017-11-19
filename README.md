# IntoTheMachine
An interactive programming guide for ages -3/4 up to 999.
## Things To Teach
- [ ] means we know where to implement it (more or less)
- [x] means it's implemented
---------------------------------------------------------
- [ ] Primitive Datatypes
- [ ] If - else Statements

See OtherTopics.md for other things
## Story
There is no story
## Zones
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
### Loops
#### For Loops
* Calculate the nth number of a sequence (Fibonacci, Exponential growth, ...)
* Get the minimum and maximum value in an array
* Kernel Filter
#### While Loops
* Read a file one line at a time
* Find at which index a sequence passes a certain treshold
