# Fork's purpose
This is _almost_ one-to-one copy of isarn/isarn-collections used in "scala for beginners" course during demonstration of different languages features and Intellij hotkeys.

In a single line of code there was made an error which leads to 2 failing tests. Task for students is to find where bug is, using all available navigation & debugging tools and common sense (pay attention for method names!). Fix is not necessary, as it requires small understanding of data structures, one can try to fix as a bonus assignment.


# isarn-collections
Collections and related data structures

### API documentation
https://isarn.github.io/isarn-collections/latest/api/

### How to use in your project

``` scala
libraryDependencies += "org.isarnproject" %% "isarn-collections" % "0.0.4"
```

This package compiles against `% Provided` dependencies:

```scala
libraryDependencies += "org.isarnproject" %% "isarn-algebra-api" % "0.0.3"
```

To use with Algebird, the following deps may be included:

```scala
libraryDependencies += "org.isarnproject" %% "isarn-algebird-algebra-api" % "0.0.4"
libraryDependencies += "com.twitter" %% "algebird-core" % "0.13.4"
```
