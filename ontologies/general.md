# 🕸️ General

Considering the project from a broader view, which involves creating an ontology describing the behavior of all cognitive biases outlined in the wheel, we have chosen to develop a generic section of the ontology. This section is designed to gather all the structures of single bias ontologies by formally representing the structure of the wheel shown in[ Overview](../) .

<inserire ruota>

As shown in the picture above, the biases can be grouped around two level of concepts, a broader one in which we have the four concepts that we can  see in the conrner of the picture, and a narrower layer where the biases are grouped around more specific concepts. 
Therefore we have developed a model to represent these layering of concepts that can be expresses through the following diagram:

<inserire uml>

These model conceptualizes the two levels as concepts reuising the odp concept and the brader level of the collection as a collection of concepts using the odp collection. Furthermore we have created a property that links each bias to an Agent, who is affected by this specific bias, and a Non Biased Agent which represent other individuals who relates with the Biased Agent but are not affected by the bias itself.
This ontology is connected to the ontologies describing each bias through these relation connection the biased agent and the congitive bias. Finally, we have modeled each bias as a class and not as an individual of the class cognitive bias since each bias can be described through sub-categories.
()
