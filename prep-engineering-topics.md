# Engineering Topics to discuss #
The article "quantity over quality hammers the idea that working to produce more will indeed get you producing better work. Th repeated act of creating will end up honing your craft, and teachng oyu more that way.

In "Clean Code: chapter 1", we are reflecting on the needs of clean code. Phrases like 'efficient' and 'elegant' are used to desribe the kinds of code we are looking to aim for. 
This may seem at odds with the article we read earlier, and I for one am presently feeling the tug between these two different considerations.
The memorable note that sticks in my head is "code is easier to read is code that is easier to write". Another extension fo the "WTFs per minute" notion.

_The Red Green Refactor Approach_

Red = Think about what you want to accomplish
Green = think about how to make your tests pass
Refactor = think about how to improve your existing implementation.

Questions to consider when planning to refactor:
Below is a list of questions you should ask yourself when you’re considering a refactor:

- Can I make my test suite more expressive?
- Does my test suite provide reliable feedback?
- Are my tests isolated?
- Can I reduce duplication in my test suite or implementation code?
- Can I make my implementation code more descriptive?
- Can I implement something more efficiently?


_The Cycles of TDD_

The _granularity_ of TDD is what we are diving into in this article.
THESE ARE THE THREE LAWS OF TDD
1) You must write a failing test before you write any production code.
1) You must not write more of a test than is sufficient to fail, or fail to compile.
1) You must not write more production code than is sufficient to make the currently failing test pass.

A straightforward way of putting it is: _Make it work. Make it right. Make it fast._

The milli-cylce is a place where we see the tests get more specific while the code gets more generic. Exploring creative ways to stretch the code's capabilities while making the code more robust.

The Primary cycle, the hour by hour cycle, is the "step back and look where we have been heading, is this where we want to be going?" cycle
