## What is Entity Resolution? 

Entity resolution is the process of determining whether two references to real-world objects are referring to the same object or to different objects. The term ***entity*** describes the real world object, a person, place, or thing, and term resolution is used because ER is fundamentally a decision process to answer (resolve) the question, are the references to the same or to different entities. 

**Entities** are described in terms of their characteristics, called attributes. The values of these attributes provide information about a specific entity. Identity attributes are those that when taken together distinguish one entity from another.

**Identity attributes** for people are things such as name, address, date of birth, and fingerprint, the kind of things often asked for to identify the person requesting a driver’s license or hospital admission. For a product identity, attributes might be model number, size, manufacturer, or universal product code (UPC).

A *reference* is a collection of attributes values for a specific entity. When two references are to the same entity, they are sometimes said to co-refer or to be matching references. 

*Unique reference assumptions* state that references are always created to refer to one, and only one, entity. The reason for this assumption is that in real-world situations a reference may appear to be ambiguous – that is, it could refer to more than one entity or possibly no entity.

### Entity vs Entity References:

Entities exist in the real world, they can be customers of a business, a person. This customer may be referenced by many different records in the company’s information systems or in some cases, multiple systems. And those references are entity references.

In an ER context, entities do not exist in the information system – they exist in the real world

        ***ER Principle #1: Information systems store and manipulate references to entities, not the entities.*** 

**Reasons why a company might create multiple references to same customer:**

- Data silos: Customer purchasing items through different branches, departments, or point of sales channels of the company. Each channel often has its own database, and that database may not be properly integrated with other databases in the company. 

- Customer characteristics, especially contact information, change over time. That is if information like name, mailing address, telephone, or email address are not captured and managed properly, the system may assume that transactions using the unrecorded contact information represent a new customer rather than one the system already recognizes. Recognizing that these records are actually references to the same customers is the essence of ER

- In other cases the problem may simply be the lack of proper information quality controls. 
