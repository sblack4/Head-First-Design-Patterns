# Proxy Pattern 

**Definition**: 
Provides a surrogate or placeholder for another object to control access to it.  

There are a lot of variations of the proxy method, including; 
* Remote Proxy 
    * we used this in the Gumball Monitor
    * java provides access to remote JVM through `java.rmi.*`
* Virtual Proxy
    * represents object that may be expensive to create
    * we used this to handle image retrieval in the example 
* Dynamic Proxy
    * proxy class in created at runtime 
    * used in the HotOrNot example
* Protection Proxy 
    * an InvocationHandler handles access to subject 
* Web Proxy  
    * see serverlets and jsp 
* Firewall Proxy
    * Protects access to a set of network resources
    * can protect against "bad" clients 
* Smart Reference Proxy 
    * Provides additional actions to a subject 
    * i.e. counting number of calls
* Caching Proxy
    * provides temporary storage
    * allows multiple clients to share results
* Synchronization Proxy
    * provides safe access from multiple threads
* Complexity Hiding Proxy
    * the *Facade Proxy* 
    * controls access to subject 
* Copy-On-Write Proxy
    * defers copying until the client needs  it 
    * variant of *Virtual Proxy* 
    