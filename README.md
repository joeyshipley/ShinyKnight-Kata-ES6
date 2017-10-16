# ShinyKnight Kata in ES6

Converted from the ruby roboticon talk: https://github.com/joeyshipley/Roboticon_2016_ImprovingCodeThroughReadability

This kata was designed to give you a playground to explore readability in programming. The first time you look at this consider how long it takes you to understand what it is doing. Afterwards ask yourself what parts you liked and what parts confused you. As you go through the exercise, try to notice the times you found something that surprised you.

### Reading Materials

Here are some great resources on the subject of code structure that directly relates to readability

- Read: Clean Code - Uncle Bob
- Watch: Cleancoders.com: videos 1 to 5 - Uncle Bob (Full Disclosure: his videos are light hearted and a bit odd at times, but worth their weight in gold.)
- Read: Good naming is a process, not a single step - Arlo Belshee
- Read: Refactoring: Improving the Design of Existing Code - Martin Fowler

---

### Getting Started

- start your terminal, clone the repo, navigate to the folder
- run > npm install
- run > npm test

### Failing Tests (Code fix will be needed)

```
#dmg => When our Young Squire is concerned about how much damage they take
  and they received an overpowering attack,
    1) it resets the hit points to 20
    2) it does not allow the characters level to go below 1

#dmg => When our Wise Defender is concerned about armor
  and they are wearing full plate,
    3) it applies reduced damage
    4) it does not protect when surprised
    5) it's effectiveness is reduced from armor penetration
```

### Code Organization

```
/src
- shinyknight.js

/src/util
- math.utils.js

/tests
- shinyknight.tests.js
```

### Additional Katas

- https://github.com/emilybache/GildedRose-Refactoring-Kata
- https://github.com/emilybache/Tennis-Refactoring-Kata
