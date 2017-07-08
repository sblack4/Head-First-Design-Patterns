# Singleton Pattern 

**Definition**: 
Ensures a class has only one instance, and provides global access to it. This is done with a private constructor.  

Threading can complicate a lazily-instantiated singleton.  You can use "double-checked locking" (the keywords `volatile` and `synchronized`) to fix this without too much overhead.  