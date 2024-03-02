# 🕸️ General

Considering the project from a broader view, which involves creating an ontology describing the behavior of all cognitive biases outlined in the wheel, we have chosen to develop a generic section of the ontology. This section is designed to gather all the structures of single bias ontologies by formally representing the structure of the wheel shown in[ Overview](../) .

<figure><img src="https://upload.wikimedia.org/wikipedia/commons/6/65/Cognitive_bias_codex_en.svg" alt=""><figcaption></figcaption></figure>

As shown in the picture above, the biases can be grouped around two level of concepts: a broader one in which we have the four concepts that we can see in the conrner of the picture, and a narrower layer where the biases are grouped around more specific concepts. 
Therefore, we have developed a model to represent this layering of concepts that can be expressed through the following diagram:

<figure><img src="../../uml/root.jpg" alt=""><figcaption></figcaption></figure>

This model conceptualizes both levels as concepts, using the class Concept of the ODP [Classification](http://ontologydesignpatterns.org/wiki/Submissions:Classification); additionaly, the broader level is defined as Collection of concepts using the ODP [Collection](http://ontologydesignpatterns.org/wiki/Submissions:Collection). 
Furthermore, we have created a property that links each bias to both the levels, through the property isCausedBy. Also the class BiasedAgent, that represents the agent who is affected by a specific bias, is connected to the class CognitiveBias through the property isAffectedBy; the class NonBiasedAgent, on the other hand, represents other individuals who interact with the BiasedAgent but are not affected by the bias itself.
Finally, we have modeled each bias as a class (and not as an individual of the class cognitive bias) since each bias can be described through [sub-categories](https://en.wikipedia.org/wiki/Confirmation_bias#Types).
