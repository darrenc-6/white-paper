The guiding principles for governance are:

1. Alignment of incentives between the governing body and the governed
   
2. Practical efficiency
   
3. Competency
   
4. Self-Improvability

The governing structure proposed in this white paper is a **D**ecentralized **O**rganization (DO) or **D**ecentralized **C**orporation (DC[^1]) which lies between a **DAO (DAC)** and a **boring old organization (corporation)** as described by Vitalik Buterin[^2]. The subtle difference between a DAO and DO is in the word 'autonomous'. A DAO makes decisions for itself while in a DO the humans are the ones making the decisions.[^2] It is worth pointing out that the DO proposed here is a little different that it is the humans and the automation combined that makes the decisions.

The proposed governing structure, referred to as the **regime** in the following text draws inspiration from political systems. The regime consists of 3 bodies:


1. The **tenets**, which are automated regulations and fundamental principles of the organization. It might happen in practice that some regulations or principles can not be programmed as automation or the incurred cost is unreasonable, in which case, there can be an additional set of regulations or principles written in human language. The guiding principles are as follows
   
   1.  The tenets are designed to change and evolve through *proposal approval process*
   
   2.  Tenets are designed to be automated as much as possible with also practicability in consideration.

    *Implementation draft:* The automated tenets are smart contracts on a blockchain and the rest of the tenets in human language can be stored as a reference on the blockchain to a file on IPFS.

2. **Stakeholders** are people and financial institutions or entities that hold financial stakes in the organization. e.g. individual or institutional investors, restaurant owners who invest in the organization, etc. Stakeholders participate in the following organization events:
3. 
    1. **Election**. The stakeholders elect the president of the organization at a predetermined interval with voting power / weight proportionate to their stakes.
   
    2. **Proposal approval process**. Both stakeholders and governing body can sponsor a proposal which goes through a consensus based decision making process where it will be debated openly, amended accordingly until a consensus is reached to either approve or reject the proposal. There is no limit to the scope of the proposal being it a budget bill to the executive, amendment to the organization tenets or even an organization reform.

    The participants of the organization are encouraged to become stakeholders. Indeed, a rational participant would want a stake proportionate to the value gained from the organization as this aligns the incentive of the organization with that of the participant's. In theory, individual participants can invest in the equities of a public traded company and take part in the company's decision making. In practice, however, retail investors can barely make their voice heard due to the inefficient voting process and the lack of transparency in the company's operation even when the retail investors collectively hold the majority of the company's stakes.
    
    **Implementation draft:** The DO issues governance tokens as its native currency and stakeholders are reserved governance tokens proportional to their investments. A stake delegation mechanism will be in place to facilitate scalable and resilient voting and consensus based decision making, where stakeholders can delegate their stakes to other stakeholders or groups representing collective interests, through which to participate in the election and proposal approval process. Cryptographic voting system can be built on a blockchain to provide transparency and public verifiability while ensuring optional anonymity. Holographic consensus voting mechanism is another promising voting mechanism which offers both scalability and resilience.[^4]


4. The **governing body**, which consists of the executive and the court.
   
   1. The **executive** manages the operation of the organization, which in the food delivery business include marketing, customer service, coordination of food ordering and delivery, etc, The president of the organization is the head of the executive and has the ultimate power over the executive's decision making including hiring, daily operation, planning, etc.
   
   2. The **court** interprets the organization tenets when confusion arises, guards the executive and stakeholders against violating the regulations or principles set in the tenets, resolve disputes within the organization using tools like .

    The governing body should be incentivized to automate their tasks and ensure the maximum transparency for the benefit of its participants. This objective is guarded by the separation of power and their balancing incentives. There should be no secrets in the governing body unless they are justified by the stakeholders.

    **Implementation draft:** A decentralized food delivery application (a Dapp) built on smart contracts can bring transparency to its participants. Smart contracts can also be used to automate tasks performed by the exectutive and the court, e.g. [Aragon Court](https://aragon.org/aragon-court), 


5. The **founding team** is a temporary constituent of the organization which lays the foundation of the organization structure and bootstraps the business. The founding team has the absolute power over the decision making in the organization and operates close to the *executive* in the governing body while superseding the organization tenets and the court. The founding team will be disbanded when the organization becomes self-sufficient and stable as is set for now at *phase 3* in the *Roadmap* section.


Another perspective: [TO-DO]

    When the DO is compared to a traditional company structure, the stakeholders are like shareholders of a company. 
    When the DO is compared to a political system, the stakeholders are like the citizens of a state

internal chain

[^1]: Note some literature refers to Decentralized Community as DC, which is not the case here.
[^2]: [DAOs, DACs, DAs and More: An Incomplete Terminology Guide](https://blog.ethereum.org/2014/05/06/daos-dacs-das-and-more-an-incomplete-terminology-guide/)
[^3]: Restaurants provide values by making food and consumers also contribute to the 'value' of the food delivery organization from their expenses, which is why the total number of tokens are divided by 2.
[^4]: [Holographic Consensus](https://medium.com/daostack/holographic-consensus-part-1-116a73ba1e1c)
