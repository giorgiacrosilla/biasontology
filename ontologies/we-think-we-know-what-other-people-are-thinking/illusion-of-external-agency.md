# Illusion of external agency

{% embed url="https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/giorgiacrosilla/biasontology/main/owl/CurseOfKnowledge.owl" %}

[Illusion Of External Agency OWL](https://raw.githubusercontent.com/giorgiacrosilla/biasontology/main/owl/IllusionOfExternalAgency.owl)

<figure><img src="../../uml/ExternalAgency-formalization.jpg" alt=""><figcaption></figcaption></figure>

The Illusion of External Agency is a cognitive bias where individuals mistakenly attribute their self-generated satisfaction to an external, influential, insightful and benevolent agent.
This bias consists of illusions of influence, insight, and benevolence.For instance, when people underestimate their capacity to generate satisfaction with future outcomes and experience such self-generated satisfaction, they may conclude that it was caused by an external agent1. This bias can also lead to the false belief that positive outcomes occur due to external influences rather than personal effort.This cognitive bias suggests that belief in omniscient, omnipotent, and benevolent external agents, such as God, may derive in part from people’s failure to recognize that they have generated their own satisfaction.


***

References:

{% embed url="https://psycnet.apa.org/record/2000-00920-002" %}

{% embed url="https://handwiki.org/wiki/Philosophy:Illusion_of_external_agency" %}

***

### <mark style="color:red;">L</mark>LM

#### Can you give me a definition of "Illusion of external agency" bias?

The illusion of external agency, as a cognitive bias, refers to the tendency of individuals to perceive external forces, beings, or entities as having intentional and purposeful actions, even when none exist. This bias involves attributing human-like qualities, motivations, or consciousness to external stimuli, inanimate objects, or abstract concepts. People experiencing this illusion may believe that events or occurrences are guided by some form of intentional agency, often overlooking more plausible explanations rooted in natural or non-conscious processes. This cognitive bias can lead to the ascription of meaning, purpose, or deliberate action to phenomena that are, in reality, devoid of intentional agency.  

#### Ok now give me 10 example scenarios of illusion of external agency bias 

Certainly! Here are ten example scenarios illustrating the illusion of external agency bias: 

    Finding a Lucky Charm: Believing that carrying a specific item, like a lucky charm or a particular piece of clothing, directly influences positive outcomes in various life situations. 

    Sports Superstitions: Athletes who think that certain rituals or habits, unrelated to their performance, contribute to their success, such as wearing specific socks or following a particular routine before a game. 

    Traffic Light Persuasion: Feeling that one's thoughts or wishes can influence traffic lights to turn green more quickly if a person concentrates hard enough. 

    Electronic Device Preferences: Thinking that a computer or smartphone works better when treated with care, gratitude, or even scolding it when it malfunctions, ascribing intentional behavior to the device. 

    Weather Rituals: Engaging in rituals or behaviors, like wearing a specific outfit or performing a particular dance, to influence weather conditions or bring about a desired climate change. 

    Gambling Superstitions: Believing that certain actions, like blowing on dice, can affect the outcome of a game of chance, attributing intentionality to random events. 

    Finding Patterns in Random Events: Seeing intentional patterns or messages in random occurrences, such as interpreting coincidences as signs from a higher power or external force. 

    Relationship Rituals: Thinking that performing specific actions, like following a set routine or adhering to certain relationship rules, can influence the success or stability of a romantic partnership. 

    Animistic Beliefs: Attributing consciousness or intentional agency to natural elements, such as believing that trees or rocks have feelings, thoughts, or motivations. 

    Technological Animism: Believing that electronic devices, like a malfunctioning computer or a glitchy software program, have a personal vendetta or intention to cause inconvenience, rather than recognizing technical issues. 


#### Now consider the scenario "7. Finding Patterns in Random events" and give me a small user story from it 

\*\*Scenario:\*\*

Samantha, a superstitious individual, often finds herself searching for patterns in seemingly random events. One day, she notices that every time she wears her favorite blue sweater, she receives positive news or experiences good events. Convinced that her sweater holds a special charm, Samantha starts wearing it during important meetings, exams, and social events, believing that the positive outcomes are directly linked to the garment. Despite the events being unrelated to the color of her sweater, Samantha maintains a strong conviction in the illusion of external agency, attributing her successes to the mystical powers she associates with the clothing item. 

#### We can now derive example-based-CQs from the user story.&#x20;

1. Who is the agent affected by the bias of Illusion of External Agency?&#x20;

```sparql
SELECT ?biasedAgent
WHERE {
  ?biasedAgent rdf:type bias:BiasedAgent .
  ?biasedAgent bias:isAffectedBy externalagency:IllusionOfExternalAgencyBias .
} 
```

2. In which event Samantha is participating in, and what is the biased outcome she perceives?&#x20;

```sparql
SELECT ?event ?outcome
WHERE {
  externalagency:Samantha participation:isParticipantIn ?event .
  ?event rdf:type participation:Event .
  ?event externalagency:hasOutcome ?outcome .
  ?outcome rdf:type externalagency:BiasedOutcome .
}
```

3. What does Samatha perceive because of the bias and what is it attributed to?&#x20;

```sparql
SELECT ?perception ?attribution
WHERE {
	externalagency:Samantha externalagency:perceive ?cause .
	?perception rdf:type externalagency:Cause .
	?perception externalagency:isAttributedTo ?attribution .
	?attribution rdf:type participation:Event .
}
```

#### If you should make an ontology of illusion of external agency bias what classes and properties would you create?
Creating an ontology for the illusion of external agency bias involves defining classes (categories) and properties (relationships) to represent the various aspects and relationships within this cognitive bias. Here's a simplified example: 

Classes: 

    Phenomenon: 

    Definition: Represents events or occurrences that individuals might attribute external agency to. 

    Examples: Traffic lights, weather conditions, luck in games, electronic devices. 

    Agent: 

    Definition: Represents perceived external entities or forces that individuals believe influence events. 

    Examples: Luck, charms, supernatural beings, random chance. 

    BiasObserver: 

    Definition: Represents individuals who exhibit the illusion of external agency bias. 

    Examples: People who engage in superstitions, rituals, or anthropomorphize objects. 

Properties: 

    hasBias: 

    Definition: Indicates the presence of the illusion of external agency bias in an individual. 

    Domain: BiasObserver 

    Range: Phenomenon 

    attributesTo: 

    Definition: Describes the attribution of intentional agency by an individual to a specific agent. 

    Domain: BiasObserver 

    Range: Agent 

    influences: 

    Definition: Represents the perceived impact of an agent on a phenomenon. 

    Domain: Agent 

    Range: Phenomenon 

    engagesInRituals: 

    Definition: Denotes the specific actions or behaviors an individual performs due to the illusion of external agency bias. 

    Domain: BiasObserver 

    Range: Rituals or behaviors associated with the bias. 

    basedOnPerception: 

    Definition: Indicates that the illusion of external agency bias is rooted in the subjective perception of the individual. 

    Domain: BiasObserver 

    Range: Phenomenon 


### ODP used:

- [Participation](http://ontologydesignpatterns.org/wiki/Submissions:Participation)
