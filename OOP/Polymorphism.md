# Polymorphism

To explain Polymorphism I'll compare it to what people do all the time: Generalizing.

If you have a kitten, some people would call it a cat and some would say it's an animal.
Both of them are right, an animal is just much more generalized than the cat.
A kitten would be even more specific than the cat.

A kitten IS A cat and a cat IS An animal. To be Polymorphic an object needs to have more than one IS-A relationships.

```
public class Animal {
  public int Age;
  public String MakeSound() {
    return "I don't know what Animal I am, so I don't know what sound I make";
  }
}
public class Cat : Animal {
  public override String MakeSound() {
    return "Meow";
  }
}
public class Kitten : Cat {
  public override String MakeSound() {
    return "KittenSound";
  }
}
```

~~If you see a book, you won't say something like this:
Hey, can you give me the Physics book with ISBN 978-1-78434-202-9 that has 527 pages, ... ?
No, you'll just say
Hey, can you give me that book?
Maybe you'll say it's a physics book or that it's a black book, but the general name for it is a book.
Polymorphism allows you to do this in your program as well.~~
