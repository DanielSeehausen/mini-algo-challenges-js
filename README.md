# Complete the challenges!
Do not look up the solutions to these problems while working on them! Neither on the interwebs nor in ./test/solutions.js!

As a general workflow, you may benefit from following this structure when completing algorithm challenges:

#### 1. Read the problem/prompt. Read it again! Know the inputs/outputs to a T!

#### 2. Can this problem be broken down into a series of smaller sub-problems? Identify and isolate them. See: [Optimal Substructure](https://en.wikipedia.org/wiki/Optimal_substructure#Problems_with_optimal_substructure)

#### 3. Describe your intended solution. Write it out in pseudo-code/comments/whiteboard, whatever speaks to *you* best. Don't keep the solution in your head! We want to externalize all of the thinking that we can.

#### 4. [KISS. KISS as hard as you can.](https://en.wikipedia.org/wiki/KISS_principle) (<-- link)
  * Implement the solution as simply as possible for you. This often entails being more verbose, having more functions than you think you need, and writing more explicitly than is required. In this step, it is crucial to delay optimization. Your concern should be a working solution, not the ideal solution.
  * Do both [unit testing](https://en.wikipedia.org/wiki/Unit_testing) as well as solution testing. Copy and pasting into a running node session in console is an inexpensive (effort wise) way to start! If you plan on running the file many times to test, make relevant testing calls at the end of the file and implement meaningful print statements ('\t' is an excellent way to start organizing terminal output)
  * Make sure that your variables and functions **accurately represent what they do/what they are. (even if they are painfully verbose!)**. This is to continue externalizing our brain power.
  * The above two bullets go together like a horse and carriage. In order to solve complex algorithm challenges, we *must* be able to trust that our sub-functions perform accurately and as expected. [(unit testing is invaluable here!)](https://en.wikipedia.org/wiki/Unit_testing) This enables us to incapsulate our logic into variable/function names without needing to constantly re-check what a function does or what a value is. Externalize!

#### 5. Refactor
  * Assert that all arguments entering your function are valid. (See: [Data Validation](https://en.wikipedia.org/wiki/Data_validation)). Simultaneously, address any and all [corner cases](https://en.wikipedia.org/wiki/Corner_case)
  * Eliminate violations of the DRY principle.
  * Consider the time and space complexity of your solution. Some common questions you should be asking are:
    * "Am I iterating more than I need to?"
    * "Am I creating new variables than I need?"
    * "If my solution is [brute force](https://en.wikipedia.org/wiki/Brute-force_search), does there exist a solution that is not?"
  * See step 5


  # In Conclusion / TL:DR
  If the method described above does not resonate with you, or you already have a method that you prefer, no problem. The important part is that you define and refine whatever solving process works for you so that you can focus on the problem and not the method. Contrary to popular belief, 'intelligence' has little to do with how good you are at coding/algorithm challenges. You get good at them the same way [you git to Carnegie Hall.](https://www.youtube.com/watch?v=XNAF5pAQENI)

  - Understand the problem and the I/Os
  - Identify the sub-problems
  - Externalize the solution (Pseudo code/comments/whiteboard)
  - KISS out a solution
  - Refactor (multiple times)
  - Relax and play some [code golf](https://en.wikipedia.org/wiki/Code_golf)
