# Room_Probability_Distribution
Given a object that is part of the English Language the algorithm returns a probability distribution over a set of room for where the item is usually located.

by Alexandros Vassiliades, Nick Bassiliades

We have created an algorithm that based on a probability distribution it returns the probability of: "In which room is most likely located the object X". For the probability distribution we use information from ConceptNet, DBpedia, Our own IKEA dataset, VirtualHome Dataset, and AI2THOR. 

Anyone who wants to use it needs first to make a small change in the path existing in the Java Code file, by going to the source code and define the new path for the Onto.ttl. Then, he need to create a new jar and give the name of the new jar in the main python program. As this is the mechanism of the program that sends SPARQL queries to the VirtualHome.
