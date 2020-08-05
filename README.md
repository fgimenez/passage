# passage

passage is a substrate-based decentralized system that allows to coordinate several parties to perform concrete tasks. 
These parties form a collective and decide on the initiation, results and outcomes of the task by performing on-chain
actions, like creating motions, casting votes and closing motions. 

The initiation of the process, the votes themselves and the actions performed as a consequence of the decission taken are 
usually the result of off-chain events. For example, a new motion to release a concrete binary of a software project can 
be created after an actor detects a new release candidate version of that binary has been created, other actors can start 
running some tests on this new software version and cast votes depending on the result, once the motion has passed an 
additional actor can close it and perform the required actions to release the software.

In some cases the process might require votes from human actors to be approved, this can be controlled by the number of required
votes to pass.
