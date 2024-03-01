# Survivorship bias

### <mark style="color:red;">C</mark>ontext literature and state of the art

**Survivorship bias** or survival bias is the logical error of concentrating on entities that passed a selection process while overlooking those that did not. This can lead to incorrect conclusions because of incomplete data. 

<figure><img src="Danielebias-Survivorship-Bias.drawio.png" alt=""><figcaption></figcaption></figure>

References:

{% embed url="https://en.wikipedia.org/wiki/Survivorship_bias" %}

{% embed url="(https://www.scribbr.com/research-bias/survivorship-bias/)https://www.scribbr.com/research-bias/survivorship-bias/" %}

***
### <mark style="color:red;">L</mark>LM

#### Can you give me a definition of "Survivorship bias"?

**Survivorship bias** is a cognitive bias that occurs when we focus only on the individuals or things that have "survived" a selection process or a certain period, overlooking those that did not. This bias can lead to distorted conclusions because the data or observations are skewed towards the successes or survivors, neglecting the failures or non-survivors. In other words, survivorship bias arises when we draw conclusions based only on the experiences of those who made it through a particular process or time frame, ignoring the ones that didn't, which can lead to false assumptions about the factors contributing to success or failure. 

#### Can you create 10 scenarios compelling with the bias?

Sure, here are ten example scenarios of survivorship bias: 

1. **Investment Success Stories**: Individuals who share their investment success stories online or in the media may only represent a fraction of all investors, overlooking those who have lost money or failed to achieve similar gains. 

2. **Historical Aircraft Survivors**: Documentaries or books that focus on historical aircraft may highlight successful missions or famous pilots, neglecting the numerous aircraft and crew members lost in combat or accidents. 

3. **Celebrity Entrepreneurship**: Media coverage often highlights successful entrepreneurs and celebrities who have launched thriving businesses, overshadowing the many failed ventures and struggling startups that never make it to the spotlight. 

4. **Survivors of Natural Disasters**: News reports may feature stories of people who survived natural disasters, such as hurricanes or earthquakes, while overlooking the individuals who perished or suffered significant losses.  

5. **Longevity Studies**: Studies on longevity may focus on centenarians and their lifestyles, ignoring individuals who may have followed similar habits but did not live to an advanced age.  

6. **Product Endorsements**: Endorsements or testimonials for skincare products, weight loss programs, or supplements typically feature satisfied customers who achieved positive results, disregarding those who experienced no improvement or negative outcomes.  

7. **Career Success Stories**: Career advice books or seminars often showcase individuals who have achieved remarkable success in their professions, disregarding the countless others who may have faced setbacks or struggled to progress. 

8. **Survivors of Medical Treatments**: Medical case studies or testimonials may highlight patients who have successfully recovered from a particular treatment or procedure, while overlooking those who did not respond well or experienced adverse effects. 

9. **Survivors of War**: War documentaries or memoirs may focus on the experiences of soldiers who survived battles or captivity, neglecting the stories of those who were injured, killed, or suffered from psychological trauma. 

10. **Education Success Stories**: Success stories in education, such as high school valedictorians or college graduates who achieved remarkable career success, may overlook the challenges faced by students who dropped out or struggled academically. 

#### Now consider the scenario "Surviovrs of Wars" and give me a short user story from it.

User Story: As a documentary filmmaker, I want to create a compelling narrative about the experiences of veterans who survived combat, so that their stories can be shared with a wider audience and their sacrifices honored. 

Acceptance Criteria: 

1. Research and identify veterans who have compelling stories of survival during wartime. 

2. Conduct interviews with selected veterans to capture their experiences, emotions, and reflections on surviving combat situations. 

3. Gather archival footage, photographs, and other visual materials to complement the interviews and provide context for the stories. 

4. Edit the footage and interviews into a cohesive and engaging documentary that highlights the challenges, resilience, and courage of the veterans. 

5. Ensure that the documentary pays tribute to the fallen comrades and acknowledges the impact of war on both survivors and their families. 

6. Seek feedback from veterans and relevant stakeholders to ensure that their stories are portrayed accurately and respectfully. 

7. Distribute the documentary through film festivals, streaming platforms, and community screenings to reach a broad audience and raise awareness about the experiences of war survivors. 

***The LLM in this case mistaken the task. We can still use the information provided to proceed with our workflow***

#### We can now derive example-based-CQs from the user story.&#x20;

1. Who are the survivor of the selection war?
  * veterans.
2. Who did go through war and what role did it had at the end  of it?
  * soldiers, as veteran, prisoner or death.
3. Which member of war army passed  which selection?
  * veteran, war.

#### If you should make an ontology based of the "survivorship bias" which classes and properties would you create?

To create an ontology of survivorship bias, we would define classes to represent various aspects and entities related to the concept, along with properties to describe their relationships and characteristics. Here's an outline of possible classes and properties for the ontology: 

Classes: 
1. **Survivorship Bias**: The overarching class representing the phenomenon of survivorship bias itself. 
2. **Population**: Represents the entire group or population from which a subset is selected. 
3. **Selection Process**: Describes the method used to select or filter individuals from the population. 
4. **Survivors**: Represents the subset of individuals or entities that have "survived" the selection process. 
5. **Non-Survivors**: Represents the individuals or entities that did not "survive" the selection process. 
6. **Outcome**: Describes the result or observation that is biased due to survivorship bias. 
7. **Factors**: Represents the variables or characteristics that influence survivorship bias. 
8. **Domain-specific Context**: Represents the specific domain or field in which survivorship bias occurs (e.g., finance, medicine, history).  

Properties: 
1. **hasSelectionProcess**: Relates a population to the method used for selection. 
2. **hasOutcome**: Relates survivorship bias to the biased result or observation. 
3. **includesSurvivors**: Relates a population to the subset of survivors. 
4. **includesNonSurvivors**: Relates a population to the subset of non-survivors. 
5. **isInfluencedBy**: Relates survivorship bias to factors that influence it. 
6. **occursInContext**: Relates survivorship bias to the specific domain or context in which it occurs. 
7. **hasMagnitude**: Describes the extent or magnitude of survivorship bias present in a particular scenario. 
8. **hasBiasType**: Describes the type or nature of survivorship bias (e.g., positive results bias, publication bias). 
9. **isMitigatedBy**: Relates survivorship bias to methods or strategies used to mitigate its effects. 
10. **isCausedBy**: Relates the outcome to the survivorship bias that causes it. 

These classes and properties provide a framework for representing and understanding survivorship bias within various contexts and domains, allowing for more systematic analysis and management of its effects. 

### Framester used
* Entity

### ODP used
* Participation
* collection
* observation
