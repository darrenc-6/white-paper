The guiding principles for governance are:

1. Alignment of incentives between the governing body and the governed
2. Practical efficiency
3. Competency
4. Self-Improvability

The governing structure proposed in this white paper is a **D**ecentralized **O**rganization (DO) or **D**ecentralized **C**orporation (DC[^1]) which lies between a **DAO (DAC)** and a **boring old organization (corporation)** as described by Vitalik Buterin[^2]. The subtle difference between a DAO and DO is in the word 'autonomous'. A DAO makes decisions for itself while in a DO the humans are the ones making the decisions.[^2] It is worth pointing out that the DO proposed here is a little different that it is the humans and the automation combined that makes the decisions.

The proposed governing structure, referred to as the **regime** in the following text draws inspiration from political systems. The regime consists of 3 bodies:

1. The stakeholders, which consists of share holders and value makers not exclusively. 
   - Value makers are those who contributes to the business value of the organization, be it monetary value or reputation. Examples are restaurant owners that contribute to making food, drivers that handle delivery, consumers that buy food, customer support representatives that resolve issues, etc. 
   - Share holders are people and financial institutions or entities that hold financial stakes in the organization. e.g. individual / institutional investors, restaurant owners who invest in the organization, etc.
  
    In principle, the value makers are encouraged to also become share holders from rational thinking. A bad example is the current food delivery industry where very few participants (value makers) of the buisness are investors (share holders) and even fewer among the individual investors who happen to be the participants (e.g. individuals who buys the stocks of public traded food delivey companies) can make a combined and coordinated impact on the decision makeing of the companies or the industry.

    The stakeholders elect the government within a predetermined interval with voting weight proportionate to the combined stakes of the share of the organization as for share sholders and temporal value made after the last election as for value makers. This election mechanism is an attempt to fix the misalignment of incentives between the governing body and the governed as is often seen in a public traded corporation with ROI their sole objective instead of the value the corporation can contribute to its participants.

    Implementation draft: 

    The DO issuess governance tokens as its native currency and stakeholders are reserved governence tokens proportional to their investments. Value makers are issued value 'tokens' (vt) which are proportionate to the equivalent amount of monetery value they contributed. As an example for restaurant owners:[^3]

    <p align="center">
    <img src="https://latex.codecogs.com/svg.image?value\_token&space;=&space;total\_governance\_token&space;\cdot&space;\frac{annulized\_revenue}{2&space;\cdot&space;market\_capitalization}" title="value\_token = total\_governance\_token \cdot \frac{annulized\_revenue}{2 \cdot market\_capitalization}" />
    </p>

2. The constitution, which is a set of fundamental principles built as automation. It might happen in practice that some principles can not be programmed as automation or the incurred cost is unreasonable, in which case, there can be an additional set of fundamental principles written in human language. The principle here is to have as many constitutional rules as possible automated with also practicability in consideration.

    Implementation draft:

    Automated rules are smart contracts on a blockchain and the rule set in human language can be stored as a reference on the blockchain pointing to a file on IPFS.

1. The government, which consists of an executive team, a judicial team and optionally a legislative team as in the federal government of the United States.
   1. The executive team corresponds to the body of a traditional corporation, which in the food delivery business include marketing, customer service, coordination of food ordering and delivery, etc, 
   2. The judicial team interprets the constitution when confusion arises, guards against violating the rules set in the constitution, resolve disputes within the organization ([Aragon ourt](https://aragon.org/aragon-court) can be useful).
   3. A legislative team can be omitted if the stakeholders can efficiently draft, modify and approve new proposals to the constitution. If not, the team will be in charge of coordinating making changes to the constitution. ([DAOstack](https://daostack.io/)'s holographic consensus can be interesting)

    The government should try to automate as much of their task as possible and ensure the maximum transparency for the benefit of its participants. This objective is done by the separation of power and their balancing incentives.

[^1]: Note some literature refers to Decentralized Community as DC, which is not the case here.

[^2]: [DAOs, DACs, DAs and More: An Incomplete Terminology Guide](https://blog.ethereum.org/2014/05/06/daos-dacs-das-and-more-an-incomplete-terminology-guide/)

[^3]: Restaurants provide values by making food and consumers also contribute to the 'value' of the food delivery organization from their expenses, which is why the total number of tokens are divided by 2.