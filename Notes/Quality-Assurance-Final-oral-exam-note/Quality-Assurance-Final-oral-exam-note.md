#Final oral exam notes

13.2 Fu Yuting + Zhang Yuan +14.2 Ravin

####What is Embedded Systems

Embedded systems control an (analogous) technical environment with digital components (HW and SW)

####Any challenges in quality assurance?

- Complexity
- Concurrency, realtime, liveness, reactivity, ...
- Non-functional requirements (time, memory, energy)
- Heterogeneity (HW/SW)
- Safety and Reliability must be ensured in all cases!

####What is model checking?

show that a model of the system (**specification**) satisfies given properties (**requirements**)

####Ask you to draw a timed automaton yourself. Then explain what are possible states of this automaton? 

####Paula writed some C code, and ask me to draw the Kripke Structures.


####Give example of LTL and CTL, then use LTL or CTL to describe the automaton you drew before.


####paula draw a model and asked the formula in LTL CTL(Ravin)


####What are LTL and CTL?

- LTL: linear (totally-ordered) sequence of time points
- CTL:Multiple successor states for one state possible.


####What is state explosion ploblem?

- concurrent or parallel processes
- Nested procedures

####Why use Zones? Show zones on your automaton.

reducing the number of equivalence classes

####Symbolic Model Checking question: show how to check EF q using SAT…

####Why OBDD? How to develop an obdd for a system? how to do model checking with it?

1. Remove redundant terminals 
2. Remove redundant non-terminals 
3. Remove redundant tests


do model checking with OBDD: using SAT algorithm

####What is POR? How to get ample set? What is independence? What is invisibility?

POR: partial-order Reduction, aggressively reduce the search space of model checking

####Paula gave a kripke structures and find the ample set (Ravin)

####Give an example of CSP



####She’ll add another process to your CSP example, and ask whether they are bisimulation or simulation? and ask if there is some refinement between them.

####Dining semantics or sth? No idea, but it turns out to be something related to Refinements. Are there any traces refinements or stable failure refinements in the two CSP before?

####ask if two process are trace and sf refinement or not(Ravin)

####Difference between operational semantics and traces(don’t remember clearly) semantics?

####Stuck at fault model checking. Give an example. How to find this kind of fault?


