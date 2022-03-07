# Report on Refactor the codebase
## 1.Introduction
 You joined a new project. The project codebase is difficult to manage. Your team lead has asked to study a few concepts and refactor the codebase.  Create a report on SOLID with code samples.
## 2.Body
### 2.1: **_What is Code Refactoring?_**
   Code refactoring is a concept well known in software development and it is the process of restructuring code without changing its external behavior and implementing changes in line with the most recent standards and testing for their impact on the remaining parts of the product.
### 2.2: **_Why we go with the code refactoring_**
 If making changes or adding features to the codebase consumes more time than one would expect compared to e.g. `building a codebase from scratch` with each commit made due to bugs, unpredictable code behaviour, and crashes
### 2.3: **_Some steps/measures to follow before refactoring the codebase_**
- **Review Document**
    -Reviewing documentation of the original requirements will help you understand where the code came from.
-  **Only Rewrite Code When It’s Necessary**
    -Rewriting an inherited codebase can be tempting. But it’s usually a mistake .It takes too much time and too many programmers to rewrite everything. And even if you do it, rewriting code can introduce new bugs. Or it can remove hidden functionality.
-  **Make Changes in Different Review Cycles**
    -Don’t make too many changes at once. It’s a bad idea to refactor in the same review cycle as functional changes.Plus, this makes it easier for code reviews. Isolated changes are much more obvious to the reviewer than a sea of changes.
-  **Collaborate With Other Developers**
    -You may not know the codebase very well. But some of your fellow developers probably do.So, if it’s possible, collaborate with someone who knows it better than you do.
-  **Keep New Code Clean**
    -You can’t control the quality of the inherited code. But you can make sure that the code you add is clean.
 ### 2.4: Introduction to Solid Principle
  Writing clean code is one of the core precepts of software development. There are various software design approaches to ensure an understandable, flexible, and maintainable code base. 
 - **What is Solid Principle?**
   - The SOLID principle is a design principle and pattern intended to make software designs more understandable, flexible, and maintainable. When creating an object, the object’s design is essential in the software development process, notably in deciding the accessibility scope.
   - SOLID principles have been tested and trusted by software developers, and the underlying technique of this principle, when applied correctly, can aid in developing standard object-oriented software applications.
- **The SOLID principle and its implementation**
   - _S----Single responsibility principle_
   - _O----Open and close principle_
   - _L----LISKOV substitution principle_
   - _I----Interface Segregation Principle_
   - _D----Dependency inversion principle_
 - **A.Single responsibility principle:**
   - It States that a class should have one and only one reason to change, meaning that a class should have only one job. 
 - **B.Open and close principle:**
   - This principle states that objects should be open for extension but closed for modification. The open and close principle ensures our code is easily extensible without editing or rewriting the existing codebase.
 - **C.LISKOV substitution principle:**
   - This principle illustrates that if a section of your code is extending a superclass, then all subclasses of the superclass should be able to replace the superclass in your code. A section of your code does not have to know which class it is as far as it is a superclass subclass.
 - **D.Interface Segregation Principle:**
   - It States that a client should never be forced to implement an interface that it doesn’t use, or clients shouldn’t be forced to depend on methods they do not use.
 - **E.Dependency inversion principle:**
   - The dependency inversion principle ensures that classes should not depend on solid classes but should only depend on abstraction  
## 3.Conclusion
 Generally refactoring is considered a long running task which can take months. Typically, it is done via one huge change and release. Developers have to inform businesses that feature-request in that module can’t be implemented due to ongoing refactoring. This makes it difficult for the team to allocate enough time for doing needed refactoring. Even if the team gets to do those refactoring, due to big changes made in refactoring, there is high risk associated with side effects. These kind of side effects which are produced as a result of weeks of work are hard to fix
## 4.References
 1.<https://www.brightwork.com/blog/7-steps-effective-report-writing>
 2.<https://www.gcu.ac.uk/library/smile/writingandnumeracy/planningyourwork/reportstructure>  
 3.[MarkDown Syntax Guide](markdownguide.org/basic-syntax/)   
 4.<https://www.section.io/engineering-education/introduction-to-solid-principle>  
 5.<https://youtu.be/eJojC3lSkwg>  
 6.<https://www.digitalocean.com/community/conceptual_articles/s-o-l-i-d-the-first-five-principles-of-object-oriented-design>
