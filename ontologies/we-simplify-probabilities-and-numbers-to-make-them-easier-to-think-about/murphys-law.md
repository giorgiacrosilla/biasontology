# 😞 Murphy's law

{% embed url="https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/giorgiacrosilla/biasontology/main/owl/MurphysLaw.ttl" %}

<figure><img src="giorgiabias-appealtoprobability2.drawio.png" alt=""><figcaption></figcaption></figure>

Generally synthesized as "Anything that can go wrong will go wrong." the Murphy’s Law is one of the most famous biases, created by the aerospace engineer Edward A. Murphy Jr. around the end of 1940s. In 1977 Arthur Bloch published the humoristic book Murphy's Law, and Other Reasons Why Things Go WRONG in which the bias is defined as follows:&#x20;



> MURPHY'S LAW:&#x20;
>
> If anything can go wrong, it will. &#x20;
>
> &#x20;
>
> Corollaries:&#x20;
>
> _1. Nothing is as easy as it looks._&#x20;
>
> _2. Everything takes longer than you think._&#x20;
>
> _3. If there is a possibility of several things going wrong, the one that will cause the most damage will be the one to go wrong._&#x20;
>
> _4. If you perceive that there are four possible ways in which a procedure can go wrong, and circumvent these, then a fifth way will promptly develop._&#x20;
>
> _5. Left to themselves, things tend to go from bad to worse._&#x20;
>
> _6. Whenever you set out to do something, something else must be done first._&#x20;
>
> _7. Every solution breeds new problems._&#x20;
>
> _8. It is impossible to make anything foolproof because fools are so ingenious._&#x20;
>
> _9. Nature always-sides with the hidden flaw._ &#x20;
>
> _10. Mother nature is a bitch._&#x20;

&#x20;

There is no scientific evidence for Murphy's Law, it is more of a common saying that reflects on human experience and observations. It is not a physical or natural law, but rather a principle that reflects the human tendency to notice and remember negative events, while positive events may be overlooked.&#x20;

***

References:

Bloch A., _Murphy's Law, and Other Reasons Why Things Go WRONG,_ Price/Stern/Sloan, Los Angeles, 1977.

{% embed url="https://en.wikipedia.org/wiki/Murphy%27s_law" %}

***

### <mark style="color:red;">L</mark>LM

#### Can you give me a definition of "Murphy's Law"?

Murphy's Law is a popular adage that states, "Anything that can go wrong, will go wrong." It suggests that if something has the potential to go awry or fail, it is likely to do so at the most inconvenient or inopportune moment. The expression is often used humorously to acknowledge the unpredictability and challenges of life, particularly in situations where things seem to be going smoothly.

#### Can you create 10 scenarios compelling with the bias ? (only one shown here)

Flat Tire on a Road Trip:&#x20;

* Your car tire will go flat in the middle of nowhere when you are on a road trip, and you don't have a spare or the necessary tools.&#x20;

#### Now consider the scenario "Flat Tire" and give me a short user story from it.

User Story: The Unexpected Adventure&#x20;

As a road-trip enthusiast, I want to explore new places with ease, So that I can create memorable experiences.&#x20;

Scenario: Flat Tire on a Road Trip&#x20;

Acceptance Criteria:&#x20;

* Given that I am on a road trip, when I least expect it, then a flat tire occurs on my vehicle.&#x20;
* Given the flat tire situation, when I assess the damage and realize I don't have a spare tire, then I feel a sense of frustration and uncertainty.&#x20;
* Given the unexpected adventure of a flat tire, when I try to call for roadside assistance, then my phone battery dies, adding a new layer of challenge.&#x20;
* Given the need for help, when a kind stranger passing by stops to offer assistance, then I appreciate the kindness of strangers and experience a sense of relief.&#x20;
* Given the delay caused by the flat tire, when I finally get back on the road, then I realize that the detour led me to a hidden gem or a breathtaking scenic route, turning the setback into an unexpected adventure.&#x20;
* Given the entire experience, when I share the story later with friends, then we laugh about the twists and turns of the journey, creating a lasting memory from what initially seemed like a road trip mishap.&#x20;



#### We can now derive example-based-CQs from the user story.&#x20;

1. What did go wrong at first?&#x20;

Flat tire&#x20;

2. Is this the only thing that went wrong, or afterwards something happened and made things even worse?&#x20;

When trying to call for assistance, phone battery died. &#x20;

3. In the end the outcome for the main character is positive or negative?&#x20;

Even though negative events happened subsequentially, the main character find some positive aspects in the overall experience and remembers this event not as a negative one. &#x20;



#### If you should make an ontology based of the "Murphy's Law" which classes and properties would you create?

Classes:&#x20;

* Situation: Represents a set of circumstances or events in which Murphy's Law may come into play.&#x20;
* Outcome: Represents the result or consequence of a situation influenced by Murphy's Law.&#x20;
* Entity: Represents any object, person, or system affected by Murphy's Law within a given situation.&#x20;
* Intention: Represents the original purpose or plan before Murphy's Law disrupts it.&#x20;

Properties:&#x20;

* hasSituation: Relates an entity to a situation, indicating the circumstances in which it is involved.&#x20;
* hasOutcome: Relates a situation to its outcome, representing the result influenced by Murphy's Law.&#x20;
* isAffectedBy: Relates an entity to Murphy's Law, indicating that the entity is influenced or affected by the law within a given situation.&#x20;
* disruptsIntention: Relates a situation to its original intention, indicating that Murphy's Law has disrupted the initial plan or purpose.&#x20;

Example Instances:&#x20;

Situation 1: &#x20;

* Class: Situation&#x20;
* Property: hasOutcome&#x20;

Value: Outcome 1&#x20;

Outcome 1:&#x20;

* Class: Outcome&#x20;
* Property: isAffectedBy&#x20;

Value: Entity 1&#x20;

Entity 1:&#x20;

* Class: Entity&#x20;
* Property: disruptsIntention&#x20;

Value: Intention 1&#x20;

Intention 1:&#x20;

* Class: Intention&#x20;

### ODP used:

* [Reaction](http://ontologydesignpatterns.org/wiki/Submissions:Reaction)