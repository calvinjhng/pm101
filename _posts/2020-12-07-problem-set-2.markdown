---
layout: post
title:  "Problem Set 2"
date:   2020-12-07 11:50:00 +0800
categories: python problem-set
---

# Problem 1 #

Given
* (i) a single word
* (ii) a phrase - collection of words - where the number of words is exactly equal to the number of alphabets used in (i)

Write a function to replace each alphabet of the word in (i) with the nth letter of the nth word in the phrase where n is the position of the alphabet in (i)
However, if the length of the word is shorter than the position number, then keep the original alphabet.

Example:

Word: apple
Phrase: mary had a little lamb

The first alphabet in apple "a" shall be replaced with the first alphabet of the first word in the phrase "m" in mary.
The second alphabet in apple "p" shall be replaced with the second alphabet of the second word in the phrase "a" in had.
The third alphabet in apple "p" shall remain because the corresponding third word in the phrase "a" is only 1 alphabet long.
The forth alphabet in apple "l" shall be replaced with the fourth alphabet of the fourth word in the phrase "t" in little.
Lastly, the fifth alphabet in apple "e" shall also remain because the corresponding fifth word in the phrase "lamb" is only 4 alphabets long.

```
Sample word input: "apple"
Sample phrase input: "mary had a little lamb"
Result: "mapte"
```

### Skeleton ###
```python
def replace_string(word, phrase):
    # Write rest of code here


# Test cases
print(replace_string("apple", ["mary", "had", "a", "little", "lamb"]) == "mapte")
```