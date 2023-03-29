# PetriNets
In this folder you can find materials about Petry Nets and Uppaal Timed Automata.

# What is a Petri Net?
Petri Nets (PT) are the evolution of Automata. Automata as instrument to model Concurrent System fails.
They are a useful instrument to model concurrent system , but not only , as i like to say,
PT can be used to model discrete events based system.

A very important concept on PT are the P-invariants. What i want to show in the slides is to extend the basic concept of PT by adding some notions about "control". 
In the slides you can find how P-invariants can be used to verify the boundeness of the network , in particular i've showed how (by definition) they form a linear space, and so closed for a linear combination its elements.
Starting from this , I've introduced the concept of "Controlled Invariants" , and I've formulated an example to show how them can be used in defining a control on the PT.
The presention ends with the concept of Control Positions.

# UPPAAL TIMED AUTOMATA
Timed Automata are a natural extension of a basic Automata. They was born with the intent of modeling time-dependent systems.
UPPAAL (Uppsala , Aalborg) Timed  Automata , are a natural extension of the basic definition (include for example the concept of synchronized channels).

In the slides I've presented an example (working example) based on the CSMA-CD protocol.
