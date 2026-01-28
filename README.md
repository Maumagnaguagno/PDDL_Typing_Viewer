# PDDL Typing Viewer
**Graph visualization of PDDL Typing**

Convert a PDDL Typing description into a [DOT](https://www.graphviz.org/doc/info/lang.html) graph to be client-rendered using [d3-graphviz](https://github.com/magjac/d3-graphviz).
Typing is similar to class inheritance to describe hierarchical relations between objects.
They are useful to obtain compact and readable descriptions, but may become complex to modify without a visual representation.
They follow the form ``child1 child2 - parent orphan``, where elements before the hyphen are childs of the ``parent`` after the hyphen.
Orphan elements may be considered childs of supertype ``object`` or explicitly require the description, implementation dependent.

Each generated typing description modifies the URL to simplify sharing.  
To load from a typing description encoded URL:

```
https://maumagnaguagno.github.io/PDDL_Typing_Viewer?types=red%20blue%20-%20color
```

For similar planning visualization projects, see [Classical Plan Viewer](../../../Classical_Plan_Viewer) and [HTN Plan Viewer](../../../HTN_Plan_Viewer).