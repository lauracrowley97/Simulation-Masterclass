# [L1 Introduction: History, Terminology, Time & State ](https://simulation.tudelft.nl/SEN9110/lecture1.php)




#### What is a simulation?
Shannon, 1975 defines it as:
(Shannon, R.E., 1975. Systems Simulation – The Art and
Science, Prentice-Hall.) --> can't find this anywhere without payment wahh
  >"The process of designing a model of a real system and conducting experiments with this model **for the purpose** either of understanding the behavior of the system or of evaluating various strategies (within the limits imposed y a criterion or set of criteria) for the operation of the system."

Purpose of simulation (from slide 10) can be further specified as as quantative analysis, what-if analysis, having a **safe testing environment**.


- Animation is **not** essential to simulation, but can give additional insight... slide 21

#### DESS/DTSS/DEVS defined slides 28/29/30

- **"Formalism"** -  System Dynamics or Agent Based Modeling or Discrete Event Modeling
- Don't misuse formalism and paradigm
- "Simulation model" is a type of **"model family"**

### Nance, 1981: *The time and state relationships in simulation modeling*

- page 1 @ myNotebook
- slide 38 @ Alexander

#### The Definitional Disorder
Some key definitions (just copy from the paper if asked):
- **state**
- **instant**
- **interval**
- **event**
- **span**
- **activity**
- **process**

#### The 3 Worldviews
- defined page 1 Nance, p1 myNotebook
 - Developed as *f(Geographical communication gap, language success, randomness)*
 - **Problem** is that variation in interpretation of formalism is mistaken for variation in the formalisms themselves.
 - This adds to image of M&S as **unscientific**, lacking convergence of core concepts, uncertain, expensive.

#### The significance of the disorder
 - **Isolation** of researchers in M&S
 - Relegation of concepts to a minor role in programming/training.
 - Lack of importability of Models

#### State-sequenced simulation

*see paper and page 2 of myNotebook*


# [L2 System Theory: Klir, Rosen, Ackoff, Ashby](https://simulation.tudelft.nl/SEN9110/lecture2.php)

*Cybernatics:* science of communications and automatic control systems in both machines and living things. Provides good formal concepts of (dynamic) system theory in an independent, abstract way that M&S does not provide. (see Ashby)

*Set Theory* see slide 28 if need in exam and cheat sheet

![](images/SetTheory.jpg)

### Klir's definition does is non-temperal!
  - S = (T,R)
  - T = {things}
  - R = {relations between things in T}
  - abstract, generic

### Ackoff's definition is purpose-centric

- Definition (slide 7) introduces concept of **essential parts** ... behavior, state, subsystem
- Focus is on the **interaction effects** between parts etc
- Dangers of decomposition or the "Engineering approach"
- **4 Types** of systems are hierarchical ... purposeful
- The **mismatch** between systems and their models...

### Rosen's definition is probably biased but pragmatic

Have seen this in every class since Q2... encoding, implicitation, decoding, commutative etc etc
> Modeling is the essence of science and the habitat of epistemology.

### Ashby is focused on transformations

- **Transformation:** *what* happens is more imporant than *why* it happens. A set of tranistions (changes).
- Terminology: operands, operator ... etc.
- Relations are sets of pairs e.g. time advance function.
- A transformation is **closed** *iff* Range is a subset of Domain.
- Function is a **single-valued** relation which can have **one-to-one** mapping.
- Transitions/transformations/relations/mappings ... do not mix-up! (Deceptively confusing...)

# [L3 System Specification: Klir's Levels, DEVS](https://simulation.tudelft.nl/SEN9110/lecture3.php)

### Klir's system Specification
>From his paper *"Facets of Systems Science",* 2001

- S = (T,R) with R - *relation* - as defined by Common Sense (see L2).
- Slide 8 has example of expressing a system with set notation in case the exam also asks for a similar example!
- Deductive vs Inductive system frameworks (paper).
- Levels (for definitions use Zeigler paper/ Klir slides 11-13).

Key points:
- Difference between the two is the **temporal element** of Zeigler's levels.
- Simulation is a process of **data generation** froma **time-invariant representation** of an object of interest (**a generative system**).
- **Structure Systems:** couple systems and outputs, whereas **meta systems** can switch behavior e.g. schedules for workers etc.

### How does discrete event simulation work?
>From **Schriber & Brunner's** paper *"Inside Discrete-Event Simulation Software: how it works and why it matters.",* 2015
... which is based on their paper published in 1998 *"Ch.24 How Discrete-Event Simulation works."*)

### Worldviews
- Definitions in Nance (p1) or myNotebook (p1)
- Each WV can be described using the concept of *locality* (Overstreet, 1986) --> describes how behavioral logic is grouped e.g. time, state, object.
- See slide 19/20 for good example of proccess interaction and activity scanning.

### Inside DES software - TRICKY section
- Slides 21-30
- Future event list Delay list - is the only true distinction the point at which each of the items on these become deterministic within the simulation run ...?
- Describe how DEVS can be described as Activity scanning e.g. time advance function and event list is scanning...?

- Exam question 1b Jan 2019
  - ABM is activity scanning but in terms of Brunner & Schriber it operates with entities in time delay states.
  - Queues can be seen as entities in condition delayed states. DEVS can be expressed as Queues. Therefore...
  - Process Interaction combines both time-delay states (an object is waiting in between its different states) and condition-delayed states (an object is waiting for other objects to be in a certain state).



# [L4 The DEVS Formalism: Zeigler's Levels, DEVS](https://simulation.tudelft.nl/SEN9110/lecture4.php)




# [L5 DEVS Extensions](https://simulation.tudelft.nl/SEN9110/lecture5.php)

# [L6 Object Oriented Simulation](https://simulation.tudelft.nl/SEN9110/lecture6.php)

# [L11 notes](https://simulation.tudelft.nl/SEN9110/lecture11.php) - Monday 14th October
-see word doc

# [L12 notes](https://simulation.tudelft.nl/SEN9110/lecture12.php)

# [L13 notes](https://simulation.tudelft.nl/SEN9110/lecture13.php) - Monday 14th October

## Review last lecture: [Multi-Resolution modeling](https://simulation.tudelft.nl/SEN9110/slides/SEN9110_12_MultiResolutionSimulation.pdf)

### Aggregation
- use meta-model of [Kleijnen](W. J. H. Van Groenendaal and J. P. C. Kleijnen. 1996. “Regression metamodels and design of experiments”) for the aggregation part of multi-resolution Modeling
 - note: this kind of deterministic regression ignores **STOCHASTICS**
 - can add a constant error term to account for the distribution that you see in your equations (a single one instead of one for every variable etc to save time)

### Disaggregation
- Difficult: no longer know what these constant parameters relate to in the 'real world'/original model.

### Is this valid?
- the **connection** between the aggregate to the disaggregate model has to show realistic behavior
- *[Davis Report WR-224, 2005](https://simulation.tudelft.nl/SEN9110/background/12%20Davis%20RAND-WR-224%20Multirsolution%20Multiperspective%20Modeling.pdf)* from RAND has a method for checking the validity of these implementations.

![](images/L13.png)

Only works if the states in the disaggregate and aggregate model are actually *comparable* !! e.g. car model/density function are not comparable (directly)
  - Weak commonality: comparing the states on the **dis-** aggregate level
  - Strong commonality/consistency: on the aggregate level

### Data Assimilation into Simulation Models

Consider being able to observe **partial states** at high accuracy -- how do we assimilate the data from the past into the model? e.g. Weather forecasting / control a system for best response / ML to understand a system better.


- **digital twin**
- For **understanding/controlling/prediction**


1) *Kalman filter (LQE)* used for continuous models to account for the errors and fitting parameters onto observations assuming linearity, normal distribution etc...
Can't use in DEVS due to discreteness/jumps/piecewise constant etc duh

2) DEVS uses *Monte Carlo*: particles, importance sample, has history, drift. Also being used in continuous systems more and more e.g. weather forecasting --> try to 'find' the anomalies in weather (continuous systems)



## EXAM TIPS ##
Answer 3 out of 4, bring anything you want (non electronic)
- Questions that come up each time (Q2 - DEVS) is a variation on a theme each year.
- Other questions are combinations of topics from classes - not the exact same as we did in class.
- "How" questions - high level of reasoning.
- Could be a question about the language we studied and relate to a paper etc.
- Point to slide X in class or figure of papers (page and paper etc).

## L13 - Simulation Languages (1/2)

A simulation language is based on a worldview:
- **[Locality](Weinberg 1971) of object** - process interaction, fully contained within each object etc e.g. Salabim describes a Lifecycle of an object. That is why it is susceptible to dead locks. Then for interactions each object needs to be able to 'see' other objects - need a global list so what was the point of hiding them in the first place?
- Tough **trade off** between scope at large scale models e.g. memory/deadlock/starvation.
- Common misconception - defining the process of an entire model (and not just an object) is NOT process interaction but event scheduling.
- **ABM** - pure activity scanning (locality of state). Each activity routine descries all actions that occur because a particular state is reached.
- **DEVS** - *is pure event scheduling in the way that behavior is defined. But internally, activity scanning (not continuously scanning but piecewise) is used to determine the next state (think about this one?)...*
