A quick programming note about `tuple` and `list`: You'll see both of these in this class, but far more of the latter. It's easier to standardize using `list` for everything, so that's what I'll be presenting in this class. However, if you already know about `tuple`, I'm not trying to pull a fast one on you.

This is a `list` of strings: `my_words = ["This", "is", "a", "list"]`

This is a `tuple` of strings: `my_words = ("This", "is", "a", "list")`

For many (but not quite all!) purposes the above `my_words` variable can be used interchangably. For the vast majority of this class, we will use the first list-of-items as a `list`. There are reasons to use tuples, a best-practice, and a where-and-when. If you see an applicable case, please feel free to try it out and I'll coach where I can.

A spirited debate on the subject of when to use either is here: https://stackoverflow.com/questions/1708510/list-vs-tuple-when-to-use-each.  Often we use tuples when we want to communicate immutability -- the idea that an object cannot be changed once created. Note, I said "communicate," not "enforce". 

Python lets us get away with all kinds of hijinks -- it's part of the language's charm I'll argue -- so relying on the interpreter to enforce immutability is asking for problems. There's another argument that tuples are faster than lists, for which I'll offer up better tools for speed with something called `numpy`. Don't get suckered into the "my language is faster than yours" debate... it's just a sinkhole. There are proper tools for proper jobs. We're using Python for general-fit business and analytics programming. It's really good at that, and that's enough.

**tl;dr**: We'll be working with `list` in this class. I know about tuples; I just won't be presenting them, except within the content of function returns. Use a tuple and your code works? I might offer suggestions, but I won't grade against it.