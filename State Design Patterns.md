# State Design Patterns

### Defination :
In State pattern a class behavior changes based on its state. This type of design pattern comes under behavior pattern.

### Discussion :

The State pattern is a solution to the problem of how to make behavior depend on state.

* Define a "context" class to present a single interface to the outside world.
* Define a State abstract base class.
* Represent the different "states" of the state machine as derived classes of the State base class.
* Define state-specific behavior in the appropriate State derived classes.
* Maintain a pointer to the current "state" in the "context" class.
* To change the state of the state machine, change the current "state" pointer.



