# **Chapter 1**

**The Problem**  
The internet was built without a layer to cater to the identification of individuals and organizations connecting through the internet. It was, instead, oriented toward identifying devices that connected through the internet.

**The Reasons**  
Reasons include the fact that the original internet was not meant to be used globally, rather for research and exchange of information among a specific group of individuals. The TCP/IP protocol to build a network of networks was very effective in creating an internet based on the exchange of data between machines. But it was underequipped to uniquely connect individuals, organizations and other non-machine entities.


**What role can blockchain play?**  
The biggest change in introducing Self Sovereign Identity (SSI) is the fact that it is truly decentralized. This is where blockchain comes in.

---
## **The three models of digital identity**  
Read [this](https://medium.com/evernym/the-three-models-of-digital-identity-relationships-ca0727cb5186) medium article for an elaborate discussion on these three types.

### **The Centralized Identity Model**
Under this model, a user has an identity with every single website, service, or application they receive a service from. For example, accounts in Facebook, Google, GitHub, Netflix etc. Each service provider grants an identity to a user in the form of an ***account***. The service provider is lending you credentials that represent you with limited controls and permissions. If you delete or take down all credentials you own with respect to all service providers, your virtual presence ceases to exist. But your siloed data is retained by these organizations or service providers.

Problems include:
- Burden of managing too many credentials
- Varying security policies across service providers (like minimum length, case or symbol requirements for passwords)
- Lack of portability and reusability of data
- Single point of failure for siloed storage of personal data

### **The Federated Identity Model**
The main idea behind this model is to have third party *identity providers* (**IDP**), to whom you and the website, service or application you are engaging with can federate the responsibilities of identification.  
The collection of all service providers who use the same IDP or group of IDPs is called a *federation*.  
Each organization or service provider within the federation, relying on this IDP or these IDPs, is known as a *relying party* (**RP**).

Problems include:
- Not ubiquitious - can't use one IDP across all services
- IDPs must have security and privacy policies that serve ALL relying parties
- IDPs become even bigger points of failure as centralized storage of private data for many services
- Lack of portability
- Can't accomodate the sharing of valuable personal data like passports, govt credentials, health data etc.


### **The Decentralized Identity Model**
This model is not account dependent. Rather it is the virtualization of the real world practice of keeping credentials and identifications in a wallet. Peer to peer connection, secured with public/private key cryptography makes this model equitable where the user and the organization are equal participants in the relationship or connection between them. Neither 'provides', 'controls' or 'owns' the relationship.  
Blockchain is used for a Decentralized Public Key Infrastructure (**DPKI**). Uses:
- Establishing secure connections between any two peers by exchanging public keys
- Storing some of these public keys on public blockchains to verify signatures on Verifiable Credentials (digital identity credentials)

---

## **What is Self Sovereign Identity?**
> A person’s identity that is neither dependent on nor subjected to any other power or state.

Two popular myths about SSI:  
1. **Self-sovereign identity is self-asserted identity**:  
The idea that only you can make identity assertions about yourself. This is false because most of your credentials and identities are dependent on information from trusted sources. Which is why everyone can rely on it.
2. **Self-sovereign identity is just for people**:  
The idea that only people can use SSIs. This is false because SSIs apply equally to organizations and things.

---

## **Why is SSI so important?**
SSI is so important because it represents a **shift in control or power**.  
Through this identity model, the control over identities is shifted from "centers of the network" (organizations that silo identities), to the "edges of the network" (where all of us exist and interact as peers).  
Over the next few years, SSI will progress rapidly with different SSI architectures popping up based on needs, wants and priorities of different communities implementing SSI. The most important thing to observe is how various SSI architectures become interoperable.

---

## **Market drivers for SSI**
Market drivers for SSI fall into three broad categories -  
1. **Business efficiency and customer experience**  
This is the biggest market driver for SSI and is enforced by desire of organizations to improve data security, increase compliance with privacy and data-protection regulations, reduce costs by improving workflows, and offer better user experience.
2. **Resistance to surveillance economy**  
Governments, privacy-conscious individuals, and a select number of corporations who want to combat *"surveillance capitalism"* - drive the adoption of SSI. The demand in this segment is fueled in parts by ideology, consumer sentiment, and strategic positioning.
3. **Sovereign individual movement**  
The demand from this segment comes from people who want to reassert control over their lives and data. Bitcoin, through permissionless cryptocurrency, creats truly decentralized economies that do not rely on any central parties for their operation. The same philosophy, when applied to digital identity, gives birth to this driver.

<br>

### **Example use cases of SSI**

**E-commerce**  
Adoption of SSI in e-commerce would allow users to:
- enjoy passwordless registraion and login at any SSI-supported e-commerce platform
- verify the reliability of the service provider
- streamline payments by using the digital wallet instead of third party gateways or serivces
- maintain a private log of purchases to feed to merchants or recommendation engines for better consumer experience

**Banking and finance**  
Adoption of SSI in banking and finance would allow users to:  
- access financial services from all SSI-supported providers instantly, smoothly
- pass Know Your Customer (KYC) and Anti Money Laundering (AML) checks easily
- digitally share credit information and acquire loans or mortages super fast
- get single-party or multi-party signatures to authorize important transactions (like million-dollar transactions)

**Healthcare**  
Current problems in healthcare include the existence of hundreds of vendors for cloud based EHRs which are rarely interoperable, the lack of portability of these EHRs across hospitals, doctors and healthcare professionals. Adoption of SSI would allow patients to:
- instantly obtain EHRs upon generation
- securely and privately share EHRs with healthcare professionals
- provide consent for medical procedures from personal devices
- have a persistence health profile spanning the entire lifespan of a patient

**Travel**  
Adoption of SSI in global travel industry would allow travelers to:
- provide proof of any digital credentials instantly with a single QR code on a phone
- receive credentials and maintain audit trail to present at subsequent checkpoints
- selective disclosure - present only what is needed
- all travel documents flow directly into the digital wallet, ready to be produced on demand






