# Development

[Pre-Development](Development%202ff905652188470fbf0fd1552e90acd2/Pre-Development%20b4fe5378b2d741f2bdba196a15a709e6.md)

[Data structures](Development%202ff905652188470fbf0fd1552e90acd2/Data%20structures%2090a61d85013547abb4463e4ad11780ec.md)

[Customer Web Flow](Development%202ff905652188470fbf0fd1552e90acd2/Customer%20Web%20Flow%202671b05abeb74648a7b92ee8efca9a9b.md)

**Info:** The step that precedes the start of project development is the creation of the technical requirements document, found at: [Pre-Development](Development%202ff905652188470fbf0fd1552e90acd2/Pre-Development%20b4fe5378b2d741f2bdba196a15a709e6.md) . This technical requirements documentation has three main goals that must be achieved, Define the business requirements of the application; Raise technical dependencies; Find possible Rabbit Holes.

**Info:** The definition of the idea and surveys of this phase can be found in: [Data structures](Development%202ff905652188470fbf0fd1552e90acd2/Data%20structures%2090a61d85013547abb4463e4ad11780ec.md) . This documentation below is a summary of the discussion in the cited file.

**Info:** The definition of the idea and surveys of this phase can be found in: [Customer Web Flow](Development%202ff905652188470fbf0fd1552e90acd2/Customer%20Web%20Flow%202671b05abeb74648a7b92ee8efca9a9b.md) . This documentation below is a summary of the discussion in the cited file.

## Applied Development: Project Requirements

**Business Requirements**

The first objective of the document is, from the functionalities idealized in the R&D stage and materialized in Wireframes in the Shaping process, to define the business requirements that imply these functionalities.

Wireframes of streams:

> ***COLAR FIGMA***
> 

Open Business Requirements:

- How is the prediction model calculated?
- Can the user navigate between calls?

**Technical Dependencies**

For the app, it's clear from the Wireframes that we've chosen to target mobile platforms first – iOS & Android and Web for scheduling. Also, as a development choice, Flutter and Python were chosen as the framework for developing a hybrid application.

With the chosen platform, the technology to be used and the business requirements well defined, the next step aims to understand which technical dependencies (libraries, frameworks, custom behaviors, animations, etc.).

It is noteworthy that the process of analyzing the technical dependencies, as well as the step of finding Rabbit Holes, can affect the scope and even generate changes in the idealized Wireframes.

**Rabbit Holes**

A likely Rabbit Hole is the choice of model to be used. The type of content in the choice directly impacts the complexity with which they need to be structured and displayed. For example, if the sections have a name and at most images, it is possible to use a Markdown as a structure and this becomes much easier to translate into an interface. Now, if the cut decks have videos, or something more complex, animations using Flutter and or an option to draw over the image. In this scenario, we would need to deal with HTML content, and that involves using WebView to display that content, and so more and more questions arise:

- How do these Webviews behave on different platforms?
- How do these Webviews adapt to the most diverse screen sizes? Do we need to take this into account when developing the HTML of the content of choice or are Webviews able to resize this content in a simple way?
- What is the complexity (processing and difficulty) of using multiple Webviews (one for each question/answer) simultaneously during execution?

---

**Business Requirements**

The first objective of the document is, from the functionalities idealized in the R&D stage and materialized in Wireframes in the Shaping process, to define the business requirements that imply these functionalities.