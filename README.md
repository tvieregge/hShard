# hRaft
### An implementation of Raft in Haskell

This implementaion is based off the original description of the algorithm in the paper
"In Search of an Understandable Consensus Algorithm" by
Diego Ongaro and John Ousterhout of Stanford University

It is desinged as a state machine that follows through the Raft server states shown in
Fig. 4.   
_Currently the state machine is implicit and mixes pure and impure code, this is a priority
to fix_

- [x] Heatbeats
- [x] Leader Election
- [ ] Follower Failure
- [ ] Leader Failure
- [ ] Writes
- [ ] Reads
