# Authentication Prototyping Workshop 10/8 - 10/11, Waterbury, VT

Between October 8-11th, 18F’s Vermont consulting team visited with the State of Vermont to participate in a 3-day war room session to work collaboratively on a prototype for authentication and authorization of Vermont’s IE&E services. Participants included a rotating slate of Vermonters (Cass, Thani, Mark, Seamus, Maureen, Susan, Emily, Josette), vendors who are currently working with Vermont as staff-aug (C2) and NAVA who is consulting on one module of the IE&E work called Customer Portal Phase 1. 

## Things 18F shared
### Authentication
- 18F proposed a possible path for focusing work on authentication and authorization, given it will become a prerequisite for all logins across all services, and an overarching need for IE&E. 
- 18F proposed a general technical strategy for sunsetting and introducing new technology called ‘encapsulation’ which could be applied to authentication
- Vermont shared their current module structure and how auth may fit into existing work

### Staffing
- We emphasized the agile way of working on one thing at a time vs. all the things at the same time.
- We emphasized the need for a dedicated Vermont team if this work moves forward. 

## Things We learned
### Authentication
- Program Sponsor flagged that spinning up a new module for authentication may require approval and would be a challenge to staff to introduce IAM as a new body of work. 
- Program Sponsor and Deputy Director of Operations (HAEEU) suggested that this work could possibly be a part of the ongoing customer portal work as authentication would be a key component of that work moving forward

### Staffing
- We heard concerns about staffing and availability. 
- Ongoing, we will use terminology widely used across Vermont’s product teams, which equates Product Owner = Product Lead, and Executive sponsor as the person who protects and enables the product team. 

### Workshop Dynamic
- The workshop took place over three days. The first day was focused on auth as a stragegy and how we would work together. The next day we created a journey map of a VHC user setting up an account, identified potential focus areas, and chose two areas to prototype in. The third day focused on creating prototypes and artifacts to communicate our ideas. 
- Vermont staff attended the workshop on and off. It would have benefitted the group to have a consistent presence / required a lot of recap and loss of momentum. This is symbolic of staff feeling like they are pulled in many directions. 
- Combining the Customer Portal Team (an existing module with a concrete product roadmap) and the newer concept on “authentication” caused some confusion.


## Prototypes and artifacts
Over the course of three days we had several discussions about what authentication means within the context of IE&E. As a starting place, we explored the user experience in Vermont Health Connect. This was a strategy to understand both the use case for authentication, and possible technical strategies we could take moving forward. We created a journey map of the current VHC account creation experience. This created a shared understanding and highlighted pain points we could prototype against. 

We took these observations and turned them into possible areas of focus for prototyping. The team prioritized these areas of focus and wrote design hypothesis. 

### On the technical side we produced:
- A prototype modeling some of the capabilities we would want an auth API to have [view gifs demonstrating the work here](https://github.com/VermontAHS/Authentication-Workshop/blob/master/auth_prototype_gifs.zip)
- [A systems model that would utilize the encapsulation strategy](https://github.com/VermontAHS/Authentication-Workshop/blob/master/AuthAPIDiagram.PNG)

### On the use case side we produced: 
- [A journey map of the current VHC account creation experience](https://app.mural.co/t/nava4113/m/nava4113/1539180761392/1d76b180583ab580b2ccd49acce205bc2fb48ee5)
- [A user flow diagram of what a future auth experience could be like](https://github.com/VermontAHS/Authentication-Workshop/blob/master/Create%20Account%20and%20Auth%20Steps.pdf)
- [Sketches and a pop prototype of what a future account creation experience could be like](https://invis.io/SXOIFAQBHNW) 
- [High fidelity screens to envision the above](https://github.com/VermontAHS/Authentication-Workshop/blob/master/VT_Auth_Mockups.zip)

### Other artifacts we generated: 
- [What would lead to success or failure](https://app.mural.co/t/gsa6/m/gsa6/1539872979181/ff3ebae672b613dfd21a767551412368b034cf6d) 
- [A parking lot of important ideas to return to if this work moved forward](https://app.mural.co/t/gsa6/m/gsa6/1539872979181/ff3ebae672b613dfd21a767551412368b034cf6d)

