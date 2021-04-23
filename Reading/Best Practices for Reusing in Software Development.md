# Best Practices for Reusing in Software Development

## What is Reuse-based software engineering?
Reuse-based software engineering is a software strategy where the development process is geared to reusing existing software.

## Application system
The whole of an application system may be reused either by incorporating it without change into their system or by developing application families.

## Subsystem, Component, and Module
Components of an application from sub-systems to modules may be reused.

## Object, Function, or Procedure
Software components that implement a single well-defined object or function may be reused.

## How to apply them
-   The reuse of patterns.
-   Create generic programs or configurable frameworks that support similar solutions for a variety of use cases and environments.
-   Use a model-driven approach with model patterns.

## Design patterns
-   **Creational**: Abstracts the instantiation process so that there is a logical separation between how objects are composed and finally represented.
-   **Structural**: Focuses more on how classes and objects are composed using the different structural techniques, and to form structures with more or altered flexibility.
-   **Behavioral**: Are concerned with the inner algorithms, process flow, the assignment of responsibilities, and the intercommunication between objects.

## Component-based development
Systems are developed by integrating components that conform to component-model standards.

It emerged from the failure of object-oriented development to support effective reuse. Single object classes are too detailed and specific. Components are more abstract than object classes and can be considered to be stand-alone service providers. They can exist as stand-alone entities.

## Application frameworks
They are moderately large entities that can be used. Application frameworks are somewhere between system and component reuse.

We collect abstract and concrete classes that are adapted and extended to create application systems.

## Legacy system wrapping
Legacy systems are ‘wrapped’ by defining a set of interfaces and providing access to these legacy systems through these interfaces.

## Service-oriented systems
Systems are developed by linking shared services, which may be externally provided.

## Software product lines
A software product line is a set of applications with a common architecture and shared components so that they can be adapted for different customers. We can implement a number of adaptations as follows.

-   Component and system configuration
-   Adding new components to the system
-   Selecting from a library of existing components
-   Modifying components to meet new requirements

## Commercial-Off-The-Shelf (COTS) product reuse
Systems are developed by configuring and integrating existing application systems without changing the source code of the system.

They are adapted by using built-in configuration mechanisms that allow the functionality of the system to be tailored to specific customer needs.

## ERP systems
Large-scale systems that encapsulate generic business functionality and rules are configured for an organization.

Common business processes such as ordering and invoicing, manufacturing, etc.

## Configurable vertical applications
Generic systems are designed so that they can be configured to the needs of specific system customers.

## Program libraries
Class and function libraries that implement commonly used abstractions are available for reuse.

## Model-driven engineering
Software is represented as domain models and implementation independent models and code is generated from these models.

## Program generators
A generator system embeds knowledge of a type of application and is used to generate systems in that domain from a user-supplied system model.

## Aspect-oriented software development
Shared components are woven into an application at different places when the program is compiled.