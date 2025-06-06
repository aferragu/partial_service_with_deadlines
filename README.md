# Last but not least: matching Earliest-Deadline-First performance through deadline-oblivious policies.

## [Andres Ferragut - Universidad ORT Uruguay.](https://aferragu.github.io) 
### Joint work with Diego Goldsztajn and Fernando Paganini.

### Abstract:
In several queueing systems, arriving tasks or customers have service and timing requirements. These systems with customer abandonment have a long and rich history in queueing theory, and have several applications in task scheduling in computer systems, operations research problems, etc. A common point in all of these works is that they deal with customers reneging from the system only while in the queue, and not during service. However, in several applications, customers may also leave during service, and the partial work performed by the system during their stay is still useful.

We will therefore model this new type of partial service queues with abandonment through a point process state representation. Building upon the machinery of measure-valued processes that has been the backbone of this line of research, we will show a common framework in which to include several policies.

Finally, we will show that the deadline-oblivious policy (preemptive) LCFS achieves exactly the same performance as Earliest-Deadline-First in the fluid scale. This is a striking property, that makes this scenario interesting, and overcomes the difficulty of estimating deadlines entirely.

