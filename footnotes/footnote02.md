- If you have found the book *To Mock a Mockingbird* interesting, then you might like the following resources as well
  - **[Alligator Eggs](http://worrydream.com/AlligatorEggs/)**
  - **[To Dissect a Mockingbird](http://dkeenan.com/Lambda/)**
- Currying is something fundamental to the philosophy of Haskell itself and is seen in many other contexts.
  - In the context of some other languages like Javascript, Lisp, this is referred to as [Closure](https://en.wikipedia.org/wiki/Closure_(computer_programming)).
  - This construct is refered to as a [Cartesian Closed Category](https://en.wikipedia.org/wiki/Cartesian_closed_category) in Category Theory
    - A lot of concepts in Haskell have a category theory analogue. There are several blog posts along these lines on the internet. I personally enjoyed these: 
      - [Categories and Haskell](https://www.reddit.com/r/haskell/comments/6oagzk/lecture_notes_on_category_theory_concepts_and/)
      - [Haskell Wikibook](https://en.wikibooks.org/wiki/Haskell/Category_theory)
- You have defined `factorial` in class today. Kishlaya sent you [really convoluted definitions](https://www.willamette.edu/~fruehr/haskell/evolution.html) for the same.
  - In the same spirit, define `fib :: Int -> Integer` such that `fib i` gives the `i`th [fibonacci number](http://oeis.org/A000045)
    - Does your program work for large integers? Why does it take a lot of time?
      - **Warning:** A very large integer might actually take a lot of memory and freeze your system.
      - Use `:set +s` in your GHCi interpreter to figure out the time taken to evaluate a function.
    - Use [Double Fibonacci Identities](https://brilliant.org/wiki/fast-fibonacci-transform/#double-fibonacci-identities) to implement the same function.
      - Does it work for large integers now? Use `:set +s` in your interpreter to check how much the improvement has been.
      - Why is this faster? By how much is this faster?