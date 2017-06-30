# Observer 

> defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically 

This helps ensure loose coupling between objects, and 
only requires that each observer implement a common interface
so that can be called by the observer when it's state updates

There is a default implementation `java.util.Observable` and `java.util.Observer`