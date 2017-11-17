# IntoTheMachine
An interactive programming guide for ages -3/4 up to 999.
## Things To Teach
### Computer Stuff
- [ ] How Programs Work
  - [ ] Instruction Order Importance
  - [ ] Code Execution
  - [ ] Compiler
- [ ] How Memory Works
  - [ ] What Is A Bit
### Basic Programming Stuff
- [x] Primitive Datatypes
- [ ] Type Conversion
- [x] If - else Statements
- [ ] Switch Statements
- [ ] While Loops
- [ ] For Loops
- [ ] Do While Loops
- [ ] Functions / Methods
### Object Oriented Programming
- [ ] Interfaces
- [ ] Classes
  - [ ] Properties
  - [ ] Constructor
  - [ ] Methods
- [ ] Polymorphism
  - [ ] Inheritance
  - [ ] Composition
- [ ] Unified Modelling Language (UML)
### Design Patterns
- [ ] Creational Patterns
  - [ ] Singleton
  - [ ] Builder
  - [ ] Factory
  - [ ] Prototype
  - [ ] Object Pool
  - [ ] ...
- [ ] Structural Patterns
  - [ ] Flyweight
  - [ ] Adapter
  - [ ] Decorator
  - [ ] Facade
  - [ ] ...
- [ ] Behavioral Patterns
  - [ ] Command
  - [ ] Strategy
  - [ ] Template
  - [ ] Observer
  - [ ] ...
- [ ] Concurrency Patterns
  - [ ] Blockchain
  - [ ] Thread Pool
  - [ ] ...
### Data Structures
https://en.wikipedia.org/wiki/List_of_data_structures
#### Arrays
- [ ] Array
- [ ] Circular Buffer
- [ ] ...
#### Lists
- [ ] Linked List
- [ ] Doubly Linked List
- [ ] Array List
- [ ] Self Organizing List
- [ ] ...
#### Trees
##### Binary Trees
- [ ] Binary Tree
- [ ] Binary Search Tree
- [ ] AVL Tree
- [ ] ...
##### B-Trees
- [ ] B-Tree
- [ ] ...
##### Heaps
- [ ] Heap
- [ ] Binary Heap
- [ ] D-ary Heap
- [ ] ...
##### Trees
- [ ] Trie
- [ ] Merkle Tree
- [ ] ...
##### Multiway Trees
- [ ] Ternary Tree
- [ ] ...
##### Space-Partitioning Trees
- [ ] Segment Tree
- [ ] Interval Tree
- [ ] Range Tree
- [ ] ...
##### Application-Specific Trees
- [ ] Decision Tree
- [ ] MinMax Tree
- [ ] ...
### Algorithms
- [ ] Big O notation
#### Sort Algorithms
- [ ] Bubble Sort
- [ ] Selection Sort
- [ ] Insertion Sort
- [ ] Merge Sort
- [ ] In-Place Merge Sort
- [ ] Quick Sort
- [ ] Heap Sort
#### Search Algorithms
http://www.geeksforgeeks.org/searching-algorithms/
- [ ] Linear Search
- [ ] Binary Search
- [ ] Jump Search
- [ ] Interpolation Search
- [ ] Exponential Search
- [ ] Sublist Search
- [ ] Fibonacci Search
- [ ] Obiquitous Binary Search
- [ ] ...
#### Pathfinding Algorithms
- [ ] Dijkstra
- [ ] A*
- [ ] Depth First Search
- [ ] Breadth First Search
- [ ] Hill Climbing 
- [ ] Backtracking
- [ ] ...
### Maths in Programming
- [ ] Coordinate System (Graphics)
- [ ] Angles (Graphics)
- [ ] Trigonometry (Graphics)
- [ ] Complex Numbers (Graphics)
- [ ] Matrices (Transformations)
- [ ] Pythagoras (For all sorts of things)
- [ ] Group Theory (Security)
- [ ] ... (Depends a lot on what you're doing)

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
