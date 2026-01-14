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


> We usually speak of in the singular, but subjects, especially people, have multiple identities. From an internal point of view, these seem like different faces of our singular identity, but other entities have a specific view that corresponds to only a subset of our internal view. 

The bank sees me as someone, my travel app see me as another, and the government see me as someone else.  All stored at different databases depending on the specific relationship that databases was meant to support. The multiple identities, or personas, as they are sometime called, are tied together by a few common data element (correlating attributes). These systems uses correlating attributes - my name, address, social security number, and birthday as keys for accessing them, however imperfectly.