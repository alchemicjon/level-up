# Level up!

Level up is a React-based web app that allows users to build branching "leveling trees" for personal use. Think Skyrim's leveling system, but for anything you want.

## To-dos

The first thing I want to do is to build the simplest version of this app, which will be leveling in a line - that is, without any branches. Achieving 'A' will unlock 'B', and so on.

```
A -> B -> C
```

So, I need to be able to:
* have a node represent an achievement
  * Nodes need to have a way to say that they're achieved
  * Nodes need to be descriptive
* have nodes link to each other
  * likely something like a branching linked list
  * achieving one node unlocks the next

After that, implement branching:

```
A -> B -> C
  \
   D -> E
```

* Nodes need to be able to point to more than one other node

