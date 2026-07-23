# The Controller Was Already in My Design World

Around the fall of 2014, I began asking a question that has stayed with me: What
happens when a designer's work is consumed directly by the system that creates
the experience?

In engineering, a controller is the part of a system that keeps its behavior
moving toward a goal. It reads the current state, compares it with the desired
state, takes an action, and uses the result to decide what to do next.

At the time, I was designing software for engineers. Two parts of the same role
were beginning to meet.

Inside the product team, I found one of my most fulfilling ways to design. I
would sit next to a JavaScript developer and make interface changes with them.
We might start with a heuristic, gather whatever user or product evidence we
could get quickly, discuss it, change the interface, and see what happened.

The work moved fast because the distance between evidence, design,
implementation, and observation was small. Ideas became behavior. Behavior
produced new evidence. The evidence shaped the next change.

The same role put me in direct contact with customers using our tools to build
autonomous vehicles, drones, and other controlled systems. The controller was
already part of my design world. I was designing tools for people who used this
loop to shape how physical systems behaved.

UX designers were handing their intent to front-end engineers through
wireframes, specifications, and prototypes. I began to wonder what the
relationship would look like when a controller could interpret more of that
design intent directly.

Could a designer show the system what good behavior looked like and give it
evidence from people using the product? Could the system propose or implement a
change? Could the designer observe the result, correct it, and keep teaching
the system what a good experience means?

I began to see the controller itself as another design collaborator.

## A design practice built around the loop

I was imagining a continuous relationship among five things:

1. The experience people are having.
2. The evidence available to the team.
3. The designer's interpretation and judgment.
4. The system's ability to change its behavior.
5. The observed effect of that change.

Screens and flows would remain useful. The deeper work would involve shaping
the conditions under which a system acts:

- What human outcome should it pursue?
- Which parts of the experience must remain stable and predictable?
- Which components, movements, messages, and service behaviors may it use?
- What evidence should cause it to change?
- How should it behave when it is uncertain or wrong?
- Which changes require a person's approval?

This is experience design expressed in a form the system can use.

## The idea already had a history

The language available to me in 2014 was incomplete. Related fields already
held important parts of the idea.

A [NASA-hosted review of supervisory
control](https://ntrs.nasa.gov/api/citations/19890010519/downloads/19890010519.pdf?attachment=true)
described a person setting goals, instructing a computer, monitoring execution,
intervening, and learning from the result. The paper also distinguished forms
of delegated and shared control. That work came from automation and robotics,
and its structure resembles the relationship I was beginning to imagine for
design.

[Interactive machine learning](https://doi.org/10.1145/604045.604056) gave
people a way to train, inspect, correct, and retrain a system through use. In
one early example, an interface designer coaches a classifier until its
behavior becomes useful. A December 2014 paper on [human participation in
interactive learning systems](https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/2513/0)
argued that people should remain involved from early exploration through later
refinement.

I connected that history to the daily work of a UX designer. The rapid loop I
had experienced beside a developer could become a direct relationship between
design intent and a system capable of acting on it. That question has continued
to organize how I see the role: design can reach into the mechanism that
produces the experience.

## A working name

I have been calling this **closed-loop experience design**.

UX practice already includes research, iteration, and post-release learning. In
this model, the experience-producing system itself participates in the loop.
I use the phrase to describe that operating relationship.

Closed-loop experience design turns human evidence and design judgment into
guidance a system can use. A designer supervises the change, observes the
outcome, and uses that evidence to guide the next iteration.

Here, the controller connects a model and its tools to the team's rules and
approval gates. It changes system behavior. People need a way to see the change
and correct it. They also need a way to contest a consequential outcome or
leave.

The question that began in a physical-systems context has become practical in
digital design. Coding agents can now read implementation context, build an
interface, operate the result, and revise it. That digital loop is the first
place where I can practice the relationship directly.

It may also be the training ground for something larger.
