# 👀 Methodology

The methodology adopted for this project is based on the ([Extreme Design Methodology (XD)](https://ceur-ws.org/Vol-516/pap21.pdf)) and an approach that can be summarized in the following five stages:&#x20;

1. Context and literature state of the art;&#x20;
2. Large Language Models;
3. Ontology Design Patterns;
4. Words as frame semantic triggers;
5. New modules integration and alignment.


This second approach summarizes the iterative tasks of the XD and rethinks it with the usage of the brand-new LLM with the goal of using them as a tool for Ontology Design.&#x20;

1. Context and Literature state of the art&#x20;

In this phase of the project, that can be aligned with Task 1 form XD, the designers get familiar with the topic, gathering an initial overview of the problem and then moving forward deepening their knowledge about the domain of interest.&#x20;

2. Large Language Models&#x20;

This stage of the workflow is focusing on using the LLM to develop have a first development of the XD. The questions asked are the following:&#x20;

1. Give a definition of the bias studied (task 1): this step helps to integrate the knowledge gathered in stage 1.&#x20;
2. Give 10 examples scenarios of the specified bias (task 2): here the role of the customer  in the XD is substituted by the LLM.&#x20;

This third stage of our workflows starts its reasoning from the results of the LLM modeling and the CQs provided to align them with already existing patterns (XD task 7). Ontology Design Patterns are used to find a solution to frequent ontology design problems and contribute to a Pattern-based Ontology Design (link paper nella documentazione).  The designer looks for existing ODPs in the repository of them (link sito web), aiming to find in them relationships and correlations that might allow to map classes and properties present in the developing ontology.&#x20;

4. Words as frame semantic triggers&#x20;

This stage does not appear as a part of the XD. It focuses on enriching the ontology with frame semantics. The designer extracts them from [Framester](https://framester.github.io/) using the [QUOKKA](https://protege.stanford.edu/) tool.&#x20;

5. New modules integration and alignment&#x20;

Finally, the newly created ontology modules are integrated i the overall structure, the alignment with existing modules is ensured (XD tasks 8-10). Each module is modelled into an OWL file using [Protégé](https://protege.stanford.edu/).&#x20;
