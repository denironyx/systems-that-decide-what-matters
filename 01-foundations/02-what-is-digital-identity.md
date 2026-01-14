## Defining digital identity

A digital identity contains data that uniquely describes a person or thing but also contains information about the subject's relationships to other entities.

An example, consider the data record that represents your car, stored somewhere in your state or country's computers. This record, commonly called title, contains a vehicle identification number (VIN) that uniquely identifies the car. In addition, it contains other attributes of the car such as year, make, model, and color. The title also contains relationships; most notably, the title relates the vehicle to a person who owns it. In many places, the title is also historical document because it identifies every owner of the car from the time it was made, as well as whether it's been in flood or otherwise salvaged.

This is the functional definition of identity, as it's helps in building, managing, and using digital identity systems. More context on the [[01-the-nature-of-identity-and-digital-identity]]


---
Identity is how we recognize, remember and respond to specific people and things. **%% Identity systems %%** acquire, correlate, apply, reason over, and govern information assets of subjects, identifiers, attributes, raw data, and context.

This definition has proven to be useful over the years in thinking through thorny identity issues. 

The identity record for a car includes attributes that the systems needs to recognize it: in this case, the VIN. The title also includes attributes that are useful to people and organization who care about (that is, need to respond to) the car, including the owner, the state and potential buyers. The government runs a system for managing titles that is used to create, manage, transfer, and govern vehicles (remember, them). The system is designed to achieve it's primary (to record valuable property that the state has an interest in taxing and regulating) and secondary goals (protecting potential buyers and creating a way to prove ownership)

Digital identity management consists of processes for creating, managing, using and eventually destroying digital records.. These records might identify a person, a car, a computer, a piece of land, or almost anything else. 

### The Language of Digital identity


A subject/entity is a person, organization, software program, machine, place or other thing in some record. 

One of the key purposes of an identity system is to authenticate that the subject is who they claim to be and authorize requests to access a resource. A resource might be a web page, a piece of data in a database, or even credit card transaction. 

To gain access to the resource, the subject lays claim to an identity record. For people, this is usually called an account. 

> In this thinking, an identity record is a collection of data about a subject that represent attributes, preferences and traits.

- Attributes: describe information about a subject, specifically of characteristics that are acquired, eg drug allergy, purchase, bank balance etc.
- Preferences: Represent desires and defaults such as preferred seating on an airline, favourite brand, airline etc.
- Traits: Like attributes, traits are features of the subject, but they are inherent rather than acquired. Attributes changes at anytime, but traits change slowly, if at all. eg. eye colour, where a company was incorporate, place of birth.

Attributes are mostly used to mean the three subject representation in an identity record. 

> One of the main purpose of an identity system is to authorize specific actions.

---

**Identity in the Physical World**

To see how, consider a common transaction: buying beer at a US convenience store.

When a customer (the subject or entity) wants to buy beer (perform an action on a
resource), they are required to submit proof that they are of legal drinking age, usually
by presenting a driver’s license. A driver’s license is a credential containing claims
asserting that the subject has certain attributes and traits and permissions that
authorize the holder to drive a car (perform an action). The clerk (PEP) examines the
license to see if it looks real (determines the authenticity and validity of the credential)
and uses the picture (embedded biometric authentication factor) to see if the
person presenting the license is the same person who owns it (authenticates the
license). Once certain that the license is authentic and is being presented by the person
to whom it was issued, the clerk reads the birth date (an attribute) from the
license and determines whether the person is over 21 (consults a security policy
determined by the state and makes a policy decision about permissions associated
with the identity for a particular resource).

Now, suppose the person pays with a credit card (a separate identity credential). The
clerk has just seen the driver’s license and thus can establish the validity of this credential
by matching the name on it to the name on the driver’s license (attribute
matching). The clerk runs the card through the point-of-sale terminal, which transmits
to the bank the cardholder’s name, credit card number, and expiration date
(identity attributes) and requests credit (authorization request) in the amount necessary
to buy the beer (the resource to be accessed). The bank (PDP) determines
whether the customer is entitled to credit in the necessary amount and sends a credit
authorization (ADA). Upon receiving this, the clerk completes the transaction.


Digital Identity Perspectives.


> We usually speak of in the singular, but subjects, especially people, have multiple identities. From an internal point of view, these seem like different faces of our singular identity, but other entities have a specific view that corresponds to only a subset of our internal view. 

The bank sees me as someone, my travel app see me as another, and the government see me as someone else.  All stored at different databases depending on the specific relationship that databases was meant to support. The multiple identities, or personas, as they are sometime called, are tied together by a few common data element (correlating attributes). These systems uses correlating attributes - my name, address, social security number, and birthday as keys for accessing them, however imperfectly.


---

Tiers of Identity

Andre Durand, the founder and CEO Ping Identity introduced the concept of tiers of identity back in 2002..  At the bottom is Tier 1

Tier (my identity) 1 consists of traits associated with the subject that are both timeless and unconditional; my name is Dennis irorere, I have blue eyes and so on. 

Tier (shared identity) 2 consists of attributes assigned to us by others. These are attributes are shared because they are used to identify the individual but are issued temporarily based on some kind of relationship. This could be driver license, employee badge, credit card, passport, issurance card, library card. your wallet is full of those.. And examples of identity information that is assigned to you. Once the relationship that defines the identity is terminated the attributes associated with it are no longer useful.  This ususally happen with you consent from registering on traveling site, or ecommerce site 

The topmost layer Tier 3 Abstracted Identity: establishes group identity. for example I could be identified as Birmingham black male late 20s, companies may classify us as frequent flier, or first-time customer, cookies fall under this, your likes, clicks etc. All these grouping identify me in some way, but only abstractly. Tier 3 is largely about marketing.. And it's very crucial now, more than ever as this is what help the business understand some of the things you do. 

Tier 2 identity relationships may happen with your consent or not, but most are welcome
because they are based on a relationship that probably has value to you. Tier 3
relationships, on the other hand, are usually forced on us. For example, email spam is
a Tier 3 identity issue, as are telephone solicitations and even TV advertisements.
Online surveillance is one of the defining realities
of the modern Web 2.0 experience. Tier 3 identities are inaccurate, imprecise, and
nonspecific, so they rarely meet a real need for their subjects, for whom the benefit is
so small as to be inconsequential. Most people perceive Tier 3-based relationships as bothersome and resent them. However, companies realize significant benefit from
such relationships and invest large amounts of money collecting, understanding and managing them (some goes as far as bridging tier2 to tier3). This is where bunch of analytics and data science model is trained upon, and using social theory, as based the goal is to understand a lot of this arbitrary identities or behaviours of millions of users inorder to be able to predict or model other peoples behaviour. and finding ways to connect tier 3 to tier 2 and finally tier 1.

---

Control


Another way to view digital identity is in terms of its locus of control—who or what
controls the relationship. Control has several factors, including:
• Who initiates the relationship?
• Who owns the identifier (in other words, who can take it away)?
• Who sets the rules governing interactions?
• Who determines how attributes are shared?


At the bottom of the diagram, with the lowest level of autonomy, is a category I call
administrative. The vast majority of identity systems in use today are administrative,
built and operated for the purpose of an organization. The organization determines
its system’s rules of operation, what attributes are allowed, how they are used, and
whether and where they can be shared. Often the sharing is opaque, with the person
who is the subject having little insight into how the identity system is being used or
by whom.
In 2004, with the rise of Web 2.0 and its seemingly insatiable appetite for accounts,
identity professionals began talking about identity systems, called user-centered, that
would give people a higher degree of autonomy (the middle category of Figure 2-4).
From those discussions, protocols such as OpenID and OAuth were born. These gave
rise to social login, the ability to federate an account from one service, often a social
media account, to another.

Using your Twitter account to login to Medium is an
example of this. Social logins are user-centric because the person chooses what
account to use (from a small list) and is redirected from the relying party (such as
Medium) to the identity provider (in this case Twitter) to approve the account sharing. Autonomy is limited in this model because the acceptable identity providers
are chosen by the relying party, and the account being used as the foundation (Twitter)
is still administrative, with all the limits that implies


Since 2015, many people have been building a new model called self-sovereign identity
(SSI). In contrast to administrative and user-centered identity systems—with the
basis for the relationship being identifiers and interactions dictated by one side—parties
in an SSI-based relationship exchange identifiers that can be mutually authenticated
using cryptographic means. This relationship provides a trustworthy channel for
exchanging protocol-mediated messages that can be tailored to the needs of the
interaction.
The word sovereign