# Awesome Consensus

A curated selection of artisanal consensus algorithms and hand-crafted distributed lock services.

- [A brief history of Consensus, 2PC and Transaction Commit](http://betathoughts.blogspot.com/2007/06/brief-history-of-consensus-2pc-and.html)

## Paxos - Algorithm

* [Part-time Parliament](https://research.microsoft.com/en-us/um/people/lamport/pubs/lamport-paxos.pdf)
* [Paxos made Simple](http://research.microsoft.com/en-us/um/people/lamport/pubs/paxos-simple.pdf)
* [Paxos made Practical](http://read.seas.harvard.edu/~kohler/class/08w-dsi/mazieres07paxos.pdf)
* [Wikipedia: Paxos](https://en.wikipedia.org/wiki/Paxos_(computer_science))
* [Paxos lecture (Raft user study)](https://www.youtube.com/watch?v=JEpsBg0AO6o)
* [The Paxos Algorithm (Google Tech Talk by Luis Quesada Torres)](https://www.youtube.com/watch?v=d7nAGI_NZPk)
* [[Dr. TLA+ Series] Paxos - Andrew Helwer](https://www.youtube.com/watch?v=zCaJSrTmUFA)
* [Paxos Agreement - Computerphile](https://www.youtube.com/watch?v=s8JqcZtvnsM)
* [Paxos Simplified by Chris Colohan](https://www.youtube.com/watch?v=SRsK-ZXTeZ0)
* [Neat Algorithms: Paxos Visualized](http://harry.me/blog/2014/12/27/neat-algorithms-paxos/)
* [Model Checking Paxos in Spin](https://arxiv.org/abs/1408.5962)
* [Paxos Consensus, Deconstructed and Abstracted (Extended Version)](https://arxiv.org/abs/1802.05969)

## Paxos - Engineering

* [Lessons Learned from Implementing Paxos](http://blog.willportnoy.com/2012/06/lessons-learned-from-paxos.html)
* [Tencent/phxpaxos](https://github.com/Tencent/phxpaxos)
* [Practical Experience Report: The Performance of Paxos in the Cloud](https://arxiv.org/abs/1404.6719)
* [Paxos for System Builders](http://www.cnds.jhu.edu/pub/papers/cnds-2008-2.pdf)
* [Using Paxos to Build a Scalable, Consistent, and Highly Available Datastore](https://arxiv.org/abs/1103.2408)
* [Paxos made Moderately Complex](http://www.cs.cornell.edu/courses/cs7412/2011sp/paxos.pdf), [website](http://paxos.systems/)
* [Paxos made Live](http://research.google.com/pubs/pub33002.html)
* [Paxos made code: Implementing a high throughput Atomic Broadcast](http://www.inf.usi.ch/faculty/pedone/MScThesis/marco.pdf), [libpaxos](https://bitbucket.org/sciascid/libpaxos)
* [500 lines or less: Clustering by Consensus](http://www.aosabook.org/en/500L/clustering-by-consensus.html)
* [Practical Experience Report: The Performance of Paxos in the Cloud](https://arxiv.org/abs/1404.6719)
* [ScalienDB: Designing and Implementing a Distributed Database using Paxos](https://arxiv.org/abs/1302.3860)
* [Seamless Paxos Coordinators](https://arxiv.org/abs/1710.07845)
* [IronFleet: Proving Practical Distributed Systems Correct](https://www.microsoft.com/en-us/research/publication/ironfleet-proving-practical-distributed-systems-correct/)

## Zookeeper

* [Zab: A Simple Totally Ordered Broadcast Protocol](http://research.yahoo.com/files/ladis08.pdf)
* [ZooKeeper: Wait-free coordination for Internet-scale systems](http://static.usenix.org/event/usenix10/tech/full_papers/Hunt.pdf)

## Raft

* [The Raft Consensus Algorithm](https://raft.github.io/)
* [Raft: In Search of an Understandable Consensus Algorithm](https://ramcloud.stanford.edu/wiki/download/attachments/11370504/raft.pdf)
* [Raft lecture (Raft user study)](https://www.youtube.com/watch?v=JEpsBg0AO6o)
* [Raft Understandable Distributed Consensus Visualization](http://thesecretlivesofdata.com/raft/)
* [Ark: A Real-World Consensus Implementation](https://arxiv.org/abs/1407.4765)
* [Understanding performance aspects of etcd and Raft - Hitoshi Mitake, NTT Laboratories](https://www.youtube.com/watch?v=snG3kSdGTrA)

## Chubby

* [The Chubby Lock Service for Loosely-Coupled Distributed Systems](https://research.google.com/archive/chubby.html)
* [Papers We Love](https://www.youtube.com/watch?v=kX9Z0F-eTt4) 

## CASPaxos

* [CASPaxos: Replicated State Machines without logs](https://arxiv.org/abs/1802.07000)
* [Paxos on Steroids and a Crash Course in TLA+](https://tschottdorf.github.io/single-decree-paxos-tla-compare-and-swap)
* [A TLA+ specification for Gryadka](https://medium.com/@grogepodge/tla-specification-for-gryadka-c80cd625944e)

## Fast Paxos

* [Fast Paxos](https://www.microsoft.com/en-us/research/publication/fast-paxos/)
* [Dr. TLA+ Series - Fast Paxos](https://www.youtube.com/watch?v=eW6Zv0X53T4)
* [The Performance of Paxos and Fast Paxos](https://arxiv.org/abs/1308.1358)
* [On the Coordinator's Rule for Fast Paxos](https://arxiv.org/abs/1710.08047)

## AllConcur

* [AllConcur: Leaderless Concurrent Atomic Broadcast (Extended Version)](https://arxiv.org/abs/1608.05866)
* [Formal Specification and Safety Proof of a Leaderless Concurrent Atomic Broadcast Algorithm](https://arxiv.org/abs/1708.04863)

## Multi-Paxos

* [Formal Verification of Multi-Paxos for Distributed Consensus](https://arxiv.org/abs/1606.01387)
* [Multi-Paxos: An Implementation and Evaluation](https://www.cs.washington.edu/tr/2009/09/UW-CSE-09-09-02.PDF)
* [Moderately Complex Paxos Made Simple: High-Level Specification of Distributed Algorithm](https://arxiv.org/abs/1704.00082)

## Other Paxos Variants

* [There is more consensus in egalitarian parliaments (paper)](https://www.cs.cmu.edu/~dga/papers/epaxos-sosp2013.pdf), [video](https://www.youtube.com/watch?v=KxoWlUZNKn8), [efficient/epaxos](https://github.com/efficient/epaxos)
* [Flexible Paxos: Quorum intersection revisited](https://fpaxos.github.io/), [Dr TLA+ talk](https://www.youtube.com/watch?v=LX-WK8EmoFE)
* [Designing Distributed Systems Using Approximate Synchrony in Data Center Networks](https://syslab.cs.washington.edu/papers/specpaxos-nsdi15.pdf), [UWSysLab/specpaxos](https://github.com/UWSysLab/specpaxos)
* [WPaxos: Ruling the Archipelago with Fast Consensus](https://www.cse.buffalo.edu//tech-reports/2017-03.pdf)
* [Paxos Quorum Leases: Fast Reads Without Sacrificing Writes](http://www.pdl.cmu.edu/PDL-FTP/associated/moraru-socc14.pdf)
* [Self-Stabilizing Paxos](https://arxiv.org/abs/1305.4263)
* [Generalized Paxos Made Byzantine (and Less Complex)](https://arxiv.org/abs/1708.07575)
* [PaxosLease: Diskless Paxos for Leases](https://arxiv.org/abs/1209.4187)

## Distributed Consensus

* [Heidi Howard - Distributed Consensus: Making Impossible Possible](https://www.youtube.com/watch?v=gYkueS5sKqo)
* [Can’t we all just agree?](https://blog.acolyer.org/2015/03/01/cant-we-all-just-agree/) -- 10 part blog series on distributed consensus algorithms
* [Consensus in the Cloud: Paxos Systems Demystified](https://www.cse.buffalo.edu/tech-reports/2016-02.pdf)

## Other

* [Paxos Protocol Framework](https://github.com/ailidani/paxi)
* [Byzantine Generals](https://research.microsoft.com/en-us/um/people/lamport/pubs/byz.pdf)
* [Just say NO to Paxos Overhead: Replacing Consensus with Network Ordering](https://www.usenix.org/system/files/conference/osdi16/osdi16-li.pdf)
* [Impossibility of Distributed Consensus with One Faulty Process - FLP](https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf)
* [Practical Byzantine Fault Tolerance and Proactive Recovery](http://www.pmg.csail.mit.edu/papers/bft-tocs.pdf)
