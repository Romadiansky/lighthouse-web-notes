# Diana's Notes

## Summary

This repository contains all of the notes taken by [Diana](https://github.com/Romadiansky) for the [Lighthouse Labs](https://www.lighthouselabs.ca/) Web Development Bootcamp.

### Table of Contents

* [Week 1](https://github.com/Romadiansky/lighthouse-web-notes/tree/master/Week_1)
  * [Day 1](https://github.com/Romadiansky/lighthouse-web-notes/tree/master/Week_1/Day_1)


### Below are some of the tools and rules I've learned

1. This
2. Is
3. How
4. I make an ordered list

- and
- this
- is
- how
- I make and unordered list


```javascript

var anyString = process.argv;

  var pigString = "";
  for (var ws = 2; ws < anyString.length; ws++) {
    var word = anyString[ws];
    for (var l = 1; l < word.length; l++) {
      pigString+= word[l];
    }
    pigString+= word[0];
    pigString+= "ay" + " ";
  }

  console.log(pigString);

  ```