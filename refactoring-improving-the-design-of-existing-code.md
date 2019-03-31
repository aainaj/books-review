## Refactoring: Improving the Design of Existing Code
by Martin Fowler

![Refactoring: Improving the Design of Existing Code](refactoring.jpg)

This book focuses on ways of refactoring and things to keep in mind while doing refactoring:
* First chapter starts with why you need Refactoring: 
	* When you have to add a feature to a program but the code is not structured in a convenient way, first refactor the program to make it easy to add the feature, then add the feature.
	* The first step in refactoring is to ensure you have a solid set of tests for that section of code. These tests must be self-checking. You should think tests as a bug detector to protect you against your own mistakes. 
	* Refactoring changes the programs in small steps. So if you make a mistake, it is easy to find where the bug is.
	* It shows various examples to refactor code and focuses on rule: Always leave the code base healthier than when you found it.
	* A healthy code base maximizes our productivity, allowing us to build more features for our users both faster and more cheaply.
  * The key to effective refactoring is recognizing that you go faster when you take tiny steps, the code is never broken, and you can compose those small steps into substantial changes.

* Chapter 2 focuses on principles in refactoring:
  * Refactoring is a change made to the internal structure of software to make it easier to understand and cheaper to modify without changing its observable behavior. 
  If someone says their code was broken for a couple of days while they are refactoring, you can be pretty sure they were not refactoring. 
  Refactoring is always done to make the code “easier to understand and cheaper to modify.”
  * When you add functionality, you shouldn’t be changing existing code; you are just adding new capabilities. You measure your progress by adding tests and getting the tests to work.
  When you refactor, you make a point of not adding functionality; you only restructure the code.
  * Why should we refactor?
    * Refactoring Improves the Design of Software
    * Refactoring Makes Software Easier to Understand
    * Refactoring helps in finding bugs
    * Refactoring helps you in program faster
  * When should you refactor?
    * Preparatory Refactoring—Making It Easier to Add a Feature 
    * Comprehension Refactoring: Making Code Easier to Understand
    * Litter-Pickup Refactoring.
    * Planned and Opportunistic Refactoring
    * Long-Term Refactoring
    * Refactoring in a Code Review
    
      The rules of three - 
  > The first time you do something, you just do it. The second time you do something similar, you wince at the duplication, but you do the duplicate thing anyway. The third time you do something similar, you refactor. Or for those who like baseball: Three strikes, then you refactor.
  
  By Don Roberts
    
      You have to refactor when you run into ugly code—but excellent code needs plenty of refactoring too. 
      It’s also a common error to see refactoring as something people do to fix past mistakes or clean up ugly code. 
      Certainly you have to refactor when you run into ugly code, but excellent code needs plenty of refactoring too. 
      Whenever you write code, you are making tradeoffs—how much do you need to parameterize, where to draw the lines between functions?
      “for each desired change, make the change easy (warning: this may be hard), then make the easy change”

* Chapter 3 throws light over bad smells in Code
Deciding when to start refactoring—and when to stop—is just as important to refactoring as knowing how to operate the mechanics of it.
Bad smells are:
  * Mysterious name
  * Duplicated code
  * Long function
  * Long parameter list
  * Global data
  
  When you feel the need to write a comment, first try to refactor the code so that any comment becomes superfluous.

* Chapter 4 focues on building tests. Refactoring requires tests. If you want to refactor, you have to write tests.

* Author introduce catalogue of refactoring from Chapter 5 and Chapter 6. 

### Conclusion: 
This book gives a lot of ideas to refactor code.
