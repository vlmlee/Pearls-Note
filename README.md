# Programming Pearls

1. Work on the right problem.
2. Explore the design space of solutions.
3. Look at the data.
4. Use the back of the envelope.
5. Design with components.
6. Build prototypes.
7. Make tradeoffs when you have to.
8. Keep it simple.

## Important Notes

__Program into a language, not in it.__

### The contribution of computer science to software is often through simple ideas. 

1. Don’t write a big program when a little one will do. 
2. The more general problem may be easier to solve. 
3. Data structures reduces big programs into small programs.
4. Representation is the essence of programming.

### Few principles to ponder:

1. Rework repeated code into arrays. A long stretch of similar code is often best expressed by the array.
2. Be familiar with advanced data structures. 
3. Let the data structure the program. You can structure a program by replacing complicated code by a data structure.

### The majority of the programming task focus on three things:

1. Problem definition
2. Algorithm design
3. Data structure selection

### Speed up factors:

1. Algorithms and Data Structures
2. Algorithm Tuning
3. Data Structure Reorganization
4. System-Independent Code Tuning
5. System-Dependent Code Tuning
6. Hardware

__The battle for a fast system can be won or lost in specifying the problem it is to solve.__

## System Structure

The decomposition of a large system into modules is probably the single most important factor in determining its performance.

__The keys to fast modules are usually the structures that represent its data and the algorithms that operate on the data.__

## Observations

The cheapest, fastest, and most reliable components of a computer system are those that aren’t there. The importance of a simple design can’t be overemphasized.

__Use the principle of common sense: if something doesn’t sound right, it most likely isn’t. And even so, double check always!__

__Employ safety factors to compensate for your ignorance.__

__Crabbing: aim to overperform/overcompensate or you may miss your target.__

## Algorithm Design

1. An algorithmic view of a problem gives insight that can make a program simpler to understand and to write.
2. Use divide and conquer.
3. Save state to avoid recomputation. This is dynamic programming.
4. Preprocess information into data structures. 
5. Use scanning algorithms. Extend solutions. 

### Code Tuning

1. Caching: data that is accessed most often should be the cheapest to access. 
2. Profiling identifies the hot spots of the program.
3. Perhaps, rather than approach the problem with a complicated data structure, tune the code to reduce the cost of computation.
4. Code tuning should actually be done rarely. Premature optimization is the root of programming evil. 

### Squeezing Space

1. Reducing space sometimes has desirable side effects on run time.  
2. By studying the context in which the problem arose, you may be able to replace the original problem with a simpler problem.
3. Don’t store, recompute.
4. Replacing a data structure can drastically reduce the space required to store given information. 

### Principles In Program Design

1. Understand the perceived problem. What is the context in which the problem arises? 
2. Specify an abstract problem. A clean, crisp problem statement helps us solve this problem and then to see who this solution can be applied to other problems.
3. Explore the design space. 
4. Implement one solution. One solution is usually superior to the rest. We usually have to prototype a few to choose the best. 
5. Retrospect. Looking back to solutions, we can become better problem solvers.

### Consider:

1. Before you build a fancy program, experiment with a simple prototype on many inputs. 
2. Separate the concerns. A well built program is divided into independent components, each of which does one thing well. 
3. Use the tools available to you: prototyping, simplicity, separating concerns, careful problem definition, and back of the envelope calculations.

__Good engineers distinguish between what a component does and how it does it.__
