# CS 230 Portfolio Artifact Submission

## Reflection

### Briefly summarize The Gaming Room client and their software requirements.

The Gaming Room is a client of Creative Technology Solutions (CTS), and they previously developed a successful multiplayer game called *Draw It or Lose It* for Android. Their goal was to expand the game to additional platforms, including web, iOS, and desktop, to increase reach and accessibility. The software needed to support cross-platform compatibility, multiplayer sessions, unique team and game names, and high performance under concurrent usage. My task was to design a scalable and maintainable architecture that would make this expansion possible.

### What did you do particularly well in developing this documentation?

I feel I did especially well in organizing the document clearly, breaking down technical elements in a way that made sense to both technical and non-technical stakeholders. I made use of software design patterns (such as the Singleton and Iterator) to solve real-world problems like entity management and data consistency. I also clearly articulated design constraints, platform evaluations, and future scalability options.

### What about the process of working through a design document did you find helpful when developing the code?

Creating a design document first helped me slow down and truly *think* before jumping into code. It let me map out how the different pieces of the system interact, which eliminated a lot of confusion during actual development. By pre-defining classes, relationships, and user flows, I was able to focus more on implementation rather than architecture when coding began.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revise the domain model to include more detail in the UML diagrams and possibly include sequence diagrams to better capture interaction flows. While the class structure was solid, I think visualizing the processes could help developers quickly understand how different components behave during a game session.

### How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I focused on the user’s need for a smooth, consistent multiplayer experience regardless of platform. That meant building for cross-platform performance, fast server responses, and simple, intuitive interfaces. Considering user needs is vital — software is only useful if it actually solves the user's problem in a way they enjoy interacting with. User-centered design helps ensure the product is not just functional, but actually engaging and accessible.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached this project by first identifying the problem space and constraints, then mapping out the system with OOP principles. I relied on known design patterns, modular architecture, and platform comparisons to shape my recommendations. In the future, I’d continue using these techniques but also introduce more stakeholder interviews, mockups, and maybe low-fidelity prototypes to visualize the design earlier on. I’d also like to incorporate security planning earlier in the design process.
