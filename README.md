# CS230-Portfolio
# CS 230 The Gaming Room Project Reflection

## Client and Software Requirements

The client was The Gaming Room, which wanted to expand its Android game, Draw It or Lose It, into a web-based application accessible across different platforms. The game needed to support multiple teams and players, unique identifiers, and checks for duplicate names. My documentation described the Java domain prototype and recommended an approach for future browser access, timed gameplay, persistent storage, and security.

## What I Did Well

I did particularly well at connecting the client’s requirements to specific design decisions. I explained the relationships between games, teams, and players and how inheritance and the singleton pattern supported the prototype. I also compared operating platforms and explained my recommendations for a Linux-based server, storage, memory management, and security. The document clearly distinguished existing prototype features from proposed production features.

## How the Design Document Helped With Development

Working through the design document helped me organize the application’s classes and responsibilities. Defining how games contain teams and teams contain players provided a clear structure for the Java code. Documenting name checks and identifiers also helped clarify how objects should be created and managed. Having these decisions written down made it easier to connect the code to the client’s requirements.

## What I Would Revise

I would expand the system architecture section with a deployment diagram showing the browser clients, application servers, database, and image storage. Although the recommendations explain these components, a diagram would make their connections easier to understand. I would also include a sample request flow showing how a player’s guess reaches the server and how the updated game state returns to players.

## Interpreting and Addressing User Needs

I translated the client’s needs into requirements for organizing games, teams, and players while planning for access from different devices. The prototype addressed the domain structure and duplicate-name checks, while the proposed design addressed responsive browser access and server-controlled timing. Considering user needs is important because the system must support how people actually play. A technically functional application would still fall short if players experienced confusing controls, inconsistent scores, or unfair timing.

## My Design Approach and Future Strategies

I approached the design by identifying requirements and constraints, examining the domain model, and comparing platforms before making recommendations. I considered compatibility, cost, performance, and security alongside the application’s functionality. For future projects, I would use UML diagrams, small prototypes, and a requirements checklist to connect each design decision to a client need. I would also plan measurable tests for concurrent users, recovery, and browser compatibility so recommendations could be evaluated before a full deployment.

## AI Acknowledgment

I used OpenAI ChatGPT to assist with drafting and organizing this README reflection based on my completed software design document. AI assistance used during the projects is acknowledged separately in the design document.
