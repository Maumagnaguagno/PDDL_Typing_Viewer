# PDDL_Typing
**Graph visualization of PDDL Typing**

Convert a PDDL Typing description into a [DOT](https://www.graphviz.org/doc/info/lang.html) graph to be client-rendered using [d3-graphviz](https://github.com/magjac/d3-graphviz).
Typing is similar to class inheritance to describe hierarchical relations between objects.
They are useful to obtain compact and readable descriptions, but may become complex to modify without a visual representation.
They follow the form ``child1 child2 - parent orphan``, where elements before the hyphen are childs of the element after the hyphen, while other elements are considered orphans or childs of ``object``.