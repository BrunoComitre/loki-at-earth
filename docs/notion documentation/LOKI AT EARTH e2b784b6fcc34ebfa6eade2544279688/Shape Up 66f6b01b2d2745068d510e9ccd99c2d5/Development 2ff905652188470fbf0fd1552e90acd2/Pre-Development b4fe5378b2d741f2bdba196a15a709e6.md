# Pre-Development

Finally, the last step is to find the project's Rabbit Holes. A Rabbit Hole is an application feature that we consider to be an unknown point, and that can potentially take a long time to execute due to lack of implementation knowledge. It is so named because it follows the analogy of a rabbit hole, which from the surface looks like a small hole, but is much larger from inside the hole.

---

## Document Structure

The technical requirements document has three main objectives that must be achieved:

- Define the application's business requirements;
- Raise technical dependencies;
- Find possible Rabbit Holes.

---

**Business Requirements**

The first objective of the document is, from the functionalities idealized in the R&D stage and materialized in Wireframes in the Shaping process, to define the business requirements that imply these functionalities.

*Wireframes of streams*

Open Business Requirements:

- How is the prediction model calculated?
- Can the user navigate between calls?
- ....

**Technical Dependencies**

For the app, it's clear from the Wireframes that we've chosen to target mobile platforms first – iOS & Android and Web for scheduling. Also, as a development choice, Flutter and Python were chosen as the framework for developing a hybrid application.

With the chosen platform, the technology to be used and the business requirements well defined, the next step aims to understand which technical dependencies (libraries, frameworks, custom behaviors, animations, etc.).

It is noteworthy that the process of analyzing the technical dependencies, as well as the step of finding Rabbit Holes, can affect the scope and even generate changes in the idealized Wireframes.

**Rabbit Holes**

Finally, the last step is to find the project's Rabbit Holes. A Rabbit Hole is an application feature that we consider to be an unknown point, and that can potentially take a long time to execute due to lack of implementation knowledge. It is so named because it follows the analogy of a rabbit hole, which from the surface looks like a small hole, but is much larger from inside the hole.

- How do these Webviews behave on different platforms?
- How do these Webviews adapt to the most diverse screen sizes? Do we need to take this into account when developing the HTML of the content of choice or are Webviews able to resize this content in a simple way?
- What is the complexity (processing and difficulty) of using multiple Webviews (one for each question/answer) simultaneously during execution?

For each Rabbit Hole surveyed, we do an investigation raising hypotheses and possibilities about possible solutions for that problem. Depending on the context, at this stage POC (Proof of Concept) can be developed about possible solutions to the problem, that is, we try to create the smallest possible solution before the development stage. In case the investigations do not bring more clarity, nor the POCs, we left the functionality marked as open scope, both in terms of time and in terms of deadline, as it was not possible to identify its complexity.

---

## References

[Pré-Desenvolvimento: Como definir os requisitos técnicos para projetos de software](https://olympus.pingback.com/p/pre-desenvolvimento-como-definir-os-requisitos-tecnicos-para-projetos-de-software)

---