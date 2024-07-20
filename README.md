# significant-reads

The following articles and books are the ones I found most impactful throughout my software engineering career.
"Impactful" here means sources that:

- I agree with
- are not included in every single beginner tutorial on the web (and indeed mostly contradict them!)
- helped me build _maintainable_ software

The sources below are ordered by the time I found and read them.

## Book "Dependency Injection" by Mark Seemann
<!-- Found and read mid 2022 -->
DI and IoC are mentioned in almost every tutorial about how to grow an application from beginner level to useful enterprise code.
This book, however, is the only source I ever found that states _when_ to use DI and even more importantly _when not_ to.

## Book "Growing Object-Oriented Software, Guided by Tests" by Steve Freeman and Nat Pryce
There is an abundance of TDD blogs.
Many of them make TDD look like requiring hard work simply to be proud of the code coverage later.
This book showcases how TDD actually saves time and money.

Downside: Even though I adored the elegance of the test-driven workflow proposed in this book, I wasn't really able to copy the elegance to my NodeJS systems.

## Blog Post "Dependency Composition" by Daniel Somerfield
https://martinfowler.com/articles/dependency-composition.html

This blog post showcases Daniel's adoption of dependency injection into the NodeJS world.
I love that he does not blindly use javascript classes and their constructors to inject dependency but factory functions instead (factory function is a big word for `export const createModule = (dependencies) => async function realFunctionUsingTheDependencies(...) {...}`
