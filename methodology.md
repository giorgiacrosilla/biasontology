# 👀 Methodology

The methodology adopted for this project is based on the [Extreme Design Methodology (XD)](https://ceur-ws.org/Vol-516/pap21.pdf), which is an approach that can be summarized in the following five stages:

1. Context and literature state of the art;
2. Large Language Models;
3. Ontology Design Patterns;
4. Words as frame semantic triggers;
5. New modules integration and alignment.

This second approach summarizes the iterative tasks of the XD and rethinks it with the usage of the brand-new LLM with the goal of using them as a tool for Ontology Design.

### 1. Context and Literature state of the art

In this phase of the project, that can be aligned with Task 1 from XD, the designers get familiar with the topic, gathering an initial overview of the problem and then moving forward deepening their knowledge about the domain of interest.

### 2. Large Language Models

This stage of the workflow is focused on using the LLM to have a first development of the XD. The questions asked are the following:

* Give a definition of the bias studied (task 1): this step helps to integrate the knowledge gathered in stage 1.
* Give 10 examples scenarios of the specified bias (task 2): here the role of the customer in the XD is substituted by the LLM.
* Give a user story based on one of the previously obtained scenarios (task 2).&#x20;
* Production of a possible ontology by the LLM: here the Language Model is requested to impersonate the designer producing itself a possible model of the object of study.&#x20;

From the user scenario proposed by Chat GPT, we derived competency questions (XD task 4) to understand what the ontology should represent and how it should do so. Subsequently, we formalized the competency questions into SPARQL queries, which were then tested in our final ontologies using Protégé.

### 3. ODP&#x20;

This third stage of our workflows starts its reasoning from the results of the LLM modeling and the CQs provided to align them with already existing patterns (XD task 7). Ontology Design Patterns are used to find a solution to frequent ontology design problems and contribute to a Pattern-based Ontology Design. The designer looks for existing ODPs in the [repository](http://ontologydesignpatterns.org/wiki/Submissions:ContentOPs), aiming to find in them relationships and correlations that might allow to map classes and properties present in the developing ontology.

### 4. Words as semantic triggers.

This stage does not appear as a part of the XD. It focuses on enriching the ontology with frame semantics. The designer extracts them from [Framester](https://framester.github.io/) using the [QUOKKA](https://protege.stanford.edu/) tool.

### 5. New modules integration and alignment.

Finally, the newly created ontology modules are integrated in the overall structure: the alignment with existing modules is ensured (XD tasks 8-10). Each module is modeled into an OWL file using [Protégé](https://protege.stanford.edu/).
