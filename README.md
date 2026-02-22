# Learning Systems and Security

A curated collection of learning resources for systems programming, security, cryptography, mathematics, and related topics.

## Table of Contents
- [Assembly](#assembly)
- [Reverse Engineering](#reverse-engineering)
- [Fuzzing](#fuzzing)
- [Operating Systems](#operating-systems)
- [Software Engineering](#software-engineering)
- [Embedded Systems](#embedded-systems)
- [Game Programming](#game-programming)
- [Distributed Systems](#distributed-systems)
- [Compilers](#compilers)
- [Blockchain](#blockchain)
- [Cryptography](#cryptography)
- [Mathematics](#mathematics)
- [Entrepreneurship](#entrepreneurship)
- [Other Topics](#other-topics)

## Assembly

- [Programming in assembly language tutorial](https://github.com/mschwartz/assembly-tutorial) - Step-by-step tutorial for learning x86 assembly language programming from scratch
- [Learning Assembly](https://github.com/danbev/learning-assembly) - Personal notes and examples for learning assembly language on multiple architectures
- [Nand2Tetris: Build a Modern Computer from First Principles](https://www.nand2tetris.org/) - Build a complete computer system from NAND gates through an OS, covering hardware and software layers
- [x86 bare metal examples](https://github.com/cirosantilli/x86-bare-metal-examples) - Minimal runnable examples of x86 bare metal programming with no OS, bootloaders to VGA output
- [SkullSecurity Assembly Wiki](https://wiki.skullsecurity.org/Assembly) - Reference wiki covering x86 assembly fundamentals with a security-oriented perspective
- [RPISEC MBE: Modern Binary Exploitation](https://github.com/RPISEC/MBE) - RPI course materials covering reverse engineering, exploit development, and binary analysis
- [OpenSecurityTraining: The Life of Binaries](http://opensecuritytraining.info/LifeOfBinaries.html) - Covers how binaries are compiled, linked, loaded, and executed at the OS level
- [OpenSecurityTraining: Introductory Intel x86](http://opensecuritytraining.info/IntroX86.html) - Free course teaching Intel x86 architecture, registers, instructions, and calling conventions
- [x86 Assembly: Hello World! - John Hammond](https://youtu.be/HgEGAaYdABA) - Beginner walkthrough of writing and compiling a hello world program in x86 assembly
- [Quick Tips For Learning Assembly and Reverse Engineering at The Same Time - OALabs](https://youtu.be/hN9G8MsbgZc) - Practical tips for combining assembly learning with hands-on reverse engineering practice
- [From 0x90 to 0x4c454554, a Journey into Reverse Engineering - myne-us](http://www.myne-us.com/2010/08/from-0x90-to-0x4c454554-journey-into.html) - Personal narrative of learning reverse engineering from NOP sleds to reading raw hex

### Books
- [Compiling to Assembly from Scratch - Vladimir Keleshev](https://keleshev.com/compiling-to-assembly-from-scratch/) - Teaches how to build a compiler that emits ARM assembly, covering parsing, code generation, and optimization

## Reverse Engineering

- [Nightmare, intro to reverse engineering course based around ctf challenges](https://guyinatuxedo.github.io/index.html) - Structured RE course using real CTF challenges to teach binary analysis and exploitation
- [Reverse Engineering](https://beginners.re/) - Free comprehensive book on reverse engineering for x86/x64 and ARM with real-world examples
- [Reverse Engineering for Beginners](https://yurichev.com/club/) - Community and resources by Dennis Yurichev for learning RE fundamentals and techniques
- [Exploit development - Sam Bowne](https://samsclass.info/127/127_S18.shtml) - College course covering buffer overflows, format strings, ROP chains, and modern exploit mitigations
- [Binary Exploitation and Memory Corruption - LiveOverflow](https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN) - Video series explaining stack overflows, heap exploitation, and memory corruption bugs
- [Insecure Programming](https://github.com/gerasdf/InsecureProgramming) - Collection of intentionally vulnerable C programs for practicing exploit development
- [Corelan: Exploit Development Tutorials](https://www.corelan.be/) - In-depth tutorials on Windows exploit development covering SEH, ROP, and heap spraying
- [OpenSecurityTraining: Free courses with lots of content](http://opensecuritytraining.info/) - Collection of free security courses covering x86, malware analysis, and exploit development
- [SecurityTube Megaprimers](http://www.securitytube.net/) - Video courses on penetration testing, exploit research, and security tool development
- [Violent Python archive](https://web.archive.org/web/20121110045053/http://www.violentpython.org/wordpress/?) - Resources for using Python to build security tools, fuzzers, and exploit scripts
- [A binary analysis: count me if you can - shell-storm](http://shell-storm.org/blog/A-binary-analysis-count-me-if-you-can/) - Walkthrough of analyzing a binary challenge using disassembly and static analysis techniques
- [SkullSecurity Blog](https://blog.skullsecurity.org/) - Security research blog covering reverse engineering, CTF writeups, and vulnerability analysis
- [Awesome Reversing - tylerha97](https://github.com/tylerha97/awesome-reversing) - Curated list of reverse engineering resources including tools, tutorials, and practice targets
- [Best books, tutorials, and courses for exploit development - pentest.guru](http://www.pentest.guru/index.php/2016/01/28/best-books-tutorials-and-courses-to-learn-about-exploit-development/) - Curated guide to the best learning paths for becoming an exploit developer
- [Path to exploit developer - Reddit AskNetsec](https://www.reddit.com/r/AskNetsec/comments/5i73db/path_to_exploit_developer/db61ken/) - Community-sourced roadmap for progressing from beginner to professional exploit developer
- [SANS Advanced Exploit Development for Penetration Testers](https://www.sans.org/event/sans-europe-pen-test-special-2020/course/advanced-exploit-development-penetration-testers) - Professional training on advanced heap exploitation, kernel bugs, and modern mitigations
- [Smashing the Browser - demi6od](https://github.com/demi6od/Smashing_The_Browser) - Browser exploitation research covering JavaScript engine bugs and renderer vulnerabilities
- [HackerSploit](https://www.youtube.com/channel/UC0ZTPkdxlAKf-V33tqXwi3Q) - YouTube channel with tutorials on penetration testing, ethical hacking, and security tools
- [BinExp - r0hi7](https://github.com/r0hi7/BinExp) - Linux binary exploitation learning path with progressive challenges from basic to advanced
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) - Free interactive labs teaching web vulnerabilities like SQL injection, XSS, and SSRF

### Exercises
- [microcorruption tutorial](https://microcorruption.com/debugger/Tutorial) - Embedded security CTF where you exploit lock firmware using an in-browser debugger and MSP430 assembly
- [Reverse-Engineering-C-challenges](https://github.com/rustymagnet3000/Reverse-Engineering-C-challenges) - Practice challenges for reverse engineering compiled C programs using disassemblers and debuggers

### Tools
- [pwntools - CTF toolkit](https://github.com/Gallopsled/pwntools) - Python library for writing exploits, handling binary I/O, shellcode generation, and ROP chain building
- [Tutorials for getting started with Pwntools](https://github.com/Gallopsled/pwntools-tutorial) - Step-by-step guide to using pwntools for CTF challenges and exploit development

### Binary exploitation
- [Smashing the stack for fun and profit](https://insecure.org/stf/smashstack.html) - The classic 1996 paper by Aleph One that introduced stack buffer overflow exploitation techniques
- [CNIT 127: Exploit Development](https://samsclass.info/127/127_F15.shtml) - College course covering stack and heap overflows, shellcode writing, and format string attacks
- [exploit.education](https://exploit.education/) - Vulnerable VMs and challenges for learning memory corruption, format strings, and kernel exploitation
- [Buffer Overflow in Belkin N750 (CVE-2014-1635) - Integrity Labs](https://labs.integrity.pt/articles/from-0-day-to-exploit-buffer-overflow-in-belkin-n750-cve-2014-1635/) - Real-world case study of discovering and exploiting a buffer overflow in a consumer router
- [dostackbufferoverflowgood - justinsteven](https://github.com/justinsteven/dostackbufferoverflowgood) - Beginner-friendly tutorial on Windows stack buffer overflows for OSCP-level preparation
- [Binary Exploitation (binexp-spring2015) - RPI Security](http://security.cs.rpi.edu/courses/binexp-spring2015/) - University course on Linux binary exploitation covering shellcode, ROP, and heap attacks
- [CNIT 127: Exploit Development (Fall 2019)](https://samsclass.info/127/127_F19.shtml) - Updated exploit development course with modern techniques and mitigations

#### Books
- Practical Reverse Engineering: x86, x64, ARM, Windows Kernel, Reversing Tools, and Obfuscation by Bruce Dang, Alexandre Gazet, Elias Bachaalany - Covers processor internals, Windows kernel reversing, and code obfuscation analysis techniques

### Wargames
- [Over The Wire](https://overthewire.org/wargames/) - Progressive wargames teaching Linux command line, networking, and binary exploitation skills
- [Smash the stack](http://smashthestack.org/) - Network-based wargame focused on memory corruption and binary exploitation challenges
- [Exploit exercises](https://exploit-exercises.lains.space/) - VMs with escalating privilege escalation and exploit development challenges
- [PwnAdventure](http://pwnadventure.com/) - Intentionally vulnerable 3D MMO game designed for practicing game hacking and reverse engineering
- [PwnAdventure Sourcery](https://sourcery.pwnadventure.com/) - Source-code-level hacking challenges set in the PwnAdventure game universe
- [ROP Emporium](https://ropemporium.com/) - Progressive challenges specifically designed to teach return-oriented programming techniques
- [0x0539](https://0x0539.net/) - Hacking challenge site with levels covering web, crypto, and binary exploitation
- [Pwnable.xyz](https://pwnable.xyz/) - Binary exploitation wargame with challenges ranging from basic stack overflows to advanced heap attacks
- [HackTheBox](https://www.hackthebox.eu/individuals) - Online platform with vulnerable machines for practicing penetration testing and exploitation
- [SkullSecurity CTFs](https://blog.skullsecurity.org/category/ctfs) - CTF writeups and challenge archives for learning offensive security techniques

#### Books
- Hacking, the Art of Exploitation - Jon Erikson - Teaches C programming, networking, and exploitation from first principles with hands-on examples
- The Shellcoders Handbook - Anley, Heasman, Lindner and Richarte - Comprehensive guide to finding and exploiting security holes across platforms and architectures
- Gray Hat Hacking The Ethical Hacker's Handbook - Covers vulnerability discovery, reverse engineering, and exploit development for ethical hackers
- The Art of Software Security Assessment: Identifying and Preventing Software Vulnerabilities - Exhaustive guide to auditing source code for security flaws in C/C++ and web applications
- The IDA Pro Book: The Unofficial Guide to the World's Most Popular Disassembler by Chris Eagle - Complete guide to using IDA Pro for disassembly, scripting, and reverse engineering workflows
- A Bug Hunter's Diary: A Guided Tour Through the Wilds of Software Security by Tobias Klein - Real stories of finding bugs in VLC, Solaris kernel, iOS, and other major software

## Fuzzing

- [FuzzySecurity](http://www.fuzzysecurity.com) - Tutorials on exploit development, fuzzing techniques, and Windows privilege escalation
- [LibFuzzer Workshop](https://github.com/Dor1s/libfuzzer-workshop) - Hands-on workshop for learning coverage-guided fuzzing with LLVM's LibFuzzer

## Operating Systems

- [The little book about OS development](https://littleosbook.github.io/) - Guide to writing a small x86 operating system kernel from scratch, covering boot, paging, and interrupts

## Software Engineering

- [Foundations of Software Engineering](https://cmu-313.github.io/) - CMU course covering software design, testing, architecture, and development process at scale

## Embedded Systems

- [Introductory Microcontroller Programming - Peter Alley](https://web.wpi.edu/Pubs/ETD/Available/etd-042811-095908/unrestricted/alley.pdf) - Thesis-based tutorial on microcontroller programming covering I/O, timers, interrupts, and ADC

## Game Programming

- [COMP4300 - Dave Churchill](https://www.youtube.com/watch?v=LpEdZbUdDe4&list=PL_xRyXins848jkwC9Coy7B4N5XTOnQZzz) - University course building a 2D game engine from scratch using C++ and SFML
- [GamesWithGabe](https://www.youtube.com/c/GamesWithGabe/playlists) - Video series on building game engines and games in Java and C++ from the ground up

## Distributed Systems

- [Distributed Systems - Martin Kleppmann](https://www.youtube.com/playlist?list=PLeKd45zvjcDFUEv_ohr_HdUFe97RItdiB) - Cambridge lecture series covering clocks, replication, consensus, and Byzantine fault tolerance
- [PingCAP Talent Plan](https://github.com/pingcap/talent-plan) - Open-source training courses for building distributed databases and systems in Rust and Go
- [MIT 6.824: Distributed Systems](https://www.youtube.com/channel/UC_7WrbZTCODu1o_kfUMq88g/videos) - Classic graduate course covering MapReduce, Raft, Spanner, and distributed transactions

### Basics
- [Distributed systems for fun and profit](http://book.mixu.net/distsys/) - Concise free ebook covering fundamentals of distribution, time, replication, and consistency
- [History of the Impossibles - CAP and FLP](https://dinhtta.github.io/flpcap/) - Explains the two foundational impossibility results in distributed computing and their implications
- [FLP and CAP aren't the same thing](https://www.the-paper-trail.org/post/2012-03-25-flp-and-cap-arent-the-same-thing/) - Clarifies the distinction between FLP impossibility and the CAP theorem
- [Readings in Database Systems - Peter Bailis, Joseph M. Hellerstein, Michael Stonebraker](http://www.redbook.io/all-chapters.html) - Curated collection of the most important database research papers with modern commentary
- [The Log: What every software engineer should know about real-time data's unifying abstraction - Jay Kreps](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying) - Foundational essay on how append-only logs unify stream processing, replication, and data integration

### Courses
- [CS6213 Special Topics in Distributed Computing](https://ilyasergey.net/CS6213/index.html) - Graduate course on distributed algorithms with formal verification using separation logic
- [CS 425 Distributed Systems](https://courses.engr.illinois.edu/cs425/fa2013/lectures.html) - UIUC course covering gossip protocols, consensus, distributed file systems, and key-value stores
- [Aphyr's class](https://github.com/aphyr/distsys-class) - Outline and exercises from Kyle Kingsbury's distributed systems class covering linearizability and Jepsen
- [MIT 6.824](https://pdos.csail.mit.edu/6.824/schedule.html) - Reading list and lab assignments for MIT's distributed systems course including Raft and sharded KV stores
- [The System Design Primer](https://github.com/donnemartin/system-design-primer) - Study guide for large-scale system design interviews covering caching, load balancing, and databases

### Papers
- [Readings in Distributed Systems - Christopher Meiklejohn](https://christophermeiklejohn.com/distributed/systems/2013/07/12/readings-in-distributed-systems.html) - Annotated bibliography of essential distributed systems papers organized by topic
- [A Note on Distributed Computing - Jim Waldo et al.](https://scholar.harvard.edu/files/waldo/files/waldo-94.pdf) - Classic paper arguing that local and remote computing are fundamentally different and cannot be unified
- [MapReduce: Simplified Data Processing on Large Clusters](https://ai.google/research/pubs/pub62) - Google's seminal paper on the MapReduce programming model for parallel data processing
- [Dynamo](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf) - Amazon's paper on a highly available key-value store using consistent hashing, vector clocks, and quorums
- [An overview of clock synchronization](https://groups.csail.mit.edu/tds/papers/Lynch/lncs90-asilomar.pdf) - Survey of clock synchronization algorithms and their correctness guarantees in distributed systems
- [Impossibility of Distributed Consensus with One Faulty Process](http://macs.citadel.edu/rudolphg/csci604/ImpossibilityofConsensus.pdf) - The FLP impossibility result proving consensus is unsolvable in asynchronous systems with one crash failure
- [Harvest, Yield and Scalable Tolerant Systems](http://radlab.cs.berkeley.edu/people/fox/static/pubs/pdf/c18.pdf) - Introduces harvest/yield tradeoffs as a practical alternative to the strict CAP theorem
- [Unreliable Failure Detectors for Reliable Distributed Systems](http://courses.csail.mit.edu/6.852/08/papers/CT96-JACM.pdf) - Foundational paper defining failure detector abstractions that make consensus solvable in asynchronous systems
- [Survey on Scalable Failure Detectors](http://www.scs.stanford.edu/14au-cs244b/labs/projects/song.pdf) - Overview of failure detection approaches that scale to large distributed systems
- [Life beyond distributed transactions](https://www.ics.uci.edu/~cs223/papers/cidr07p15.pdf) - Pat Helland's influential paper on building scalable systems without distributed transactions
- [Two phase commit](https://www.the-paper-trail.org/post/2008-11-27-consensus-protocols-two-phase-commit/) - Clear explanation of the 2PC atomic commit protocol, its guarantees, and its blocking failure mode
- [Three phase commit](https://www.the-paper-trail.org/post/2008-11-29-consensus-protocols-three-phase-commit/) - Explains how 3PC avoids 2PC's blocking problem by adding a pre-commit phase
- [Paxos](https://www.the-paper-trail.org/post/2009-02-03-consensus-protocols-paxos/) - Accessible explanation of the Paxos consensus algorithm and its correctness properties
- [Chubby](https://ai.google/research/pubs/pub27897) - Google's distributed lock service built on Paxos, used for leader election and metadata storage
- Zookeeper - Apache's coordination service for distributed applications providing configuration, naming, and locks
- [A Quorum-based Commit Protocol](https://ecommons.library.cornell.edu/bitstream/1813/6323/1/82-483.pdf) - Proposes using quorum-based voting instead of unanimous agreement for distributed commit
- [Bully algorithm](https://en.wikipedia.org/wiki/Bully_algorithm) - Simple leader election algorithm where the process with the highest ID becomes coordinator
- [How to Build a Highly Available System Using Consensus](https://www.microsoft.com/en-us/research/publication/how-to-build-a-highly-available-system-using-consensus/) - Practical guide to using consensus protocols for building fault-tolerant replicated state machines
- [Distributed Snapshots: Determining Global States of a Distributed System](https://www.microsoft.com/en-us/research/publication/distributed-snapshots-determining-global-states-distributed-system/) - Chandy-Lamport algorithm for recording consistent global snapshots without stopping the system
- [Atomic broadcast](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.3.4709&rep=rep1&type=pdf) - Defines total order broadcast and proves its equivalence to consensus
- [Gossip](http://bitsavers.informatik.uni-stuttgart.de/pdf/xerox/parc/techReports/CSL-89-1_Epidemic_Algorithms_for_Replicated_Database_Maintenance.pdf) - Xerox PARC paper on epidemic algorithms for efficient replicated database maintenance
- [Chain Replication for Supporting High Throughput and Availability](http://www.cs.cornell.edu/home/rvr/papers/OSDI04.pdf) - Replication protocol that achieves high throughput by chaining updates through an ordered sequence of servers
- The Part-Time Parliament - Lamport's original Paxos paper describing consensus through the metaphor of a Greek parliament
- Viewstamped Replication: A New Primary Copy Method to Support Highly-Available Distributed Systems - Introduces view-change-based replication as an alternative to Paxos for state machine replication
- Fast Paxos - Extends classic Paxos to reduce message delays by allowing clients to send directly to acceptors
- Paxos Made Moderately Complex - Step-by-step description of a complete, implementable Paxos-based replicated state machine
- Distributed Snapshots: Determining Global States of Distributed Systems - The Chandy-Lamport snapshot algorithm for capturing consistent global state in a distributed system
- Forward and Backward Simulations Part I: Untimed Systems - Formal framework for proving correctness of concurrent systems using simulation relations
- An Axiomatic Proof Technique for Parallel Programs I - Foundational work on Owicki-Gries method for verifying shared-variable parallel programs
- Proving Liveness Properties of Concurrent Programs - Techniques for proving that concurrent programs eventually make progress using well-founded orderings

### Exercises
- [Toydb](https://github.com/erikgrinaker/toydb) - Distributed SQL database built from scratch in Rust with Raft consensus and MVCC transactions
- [pea2pea](https://github.com/ljedrz/pea2pea) - Lightweight Rust library for creating peer-to-peer networking nodes with minimal boilerplate
- [geohot/minikeyvalue](https://github.com/geohot/minikeyvalue) - Minimal distributed key-value store in under 1000 lines demonstrating core distributed storage concepts

### TLA+
- [Leslie Lamport's The TLA+ Video Course](https://www.youtube.com/playlist?list=PLWAv2Etpa7AOAwkreYImYt0gIpOdWQevD) - Official video course by TLA+ creator Leslie Lamport on specifying and verifying concurrent systems
- [Dr. TLA+ Series - Raft](https://youtu.be/6Kwx8zfGW0Y) - Walkthrough of formally specifying the Raft consensus algorithm in TLA+
- [Dr. TLA+ series - learn an algorithm and protocol, study a specification](https://github.com/tlaplus/DrTLAPlus) - Collection of TLA+ specifications for well-known distributed algorithms with video explanations

### Raft
- [An Erlang implementation of RAFT from WhatsApp](https://github.com/WhatsApp/waraft/blob/main/src/wa_raft_server.erl) - Production Raft implementation in Erlang used at WhatsApp scale

### Data Structures
- [Distributed Hash Tables](https://www.linuxjournal.com/article/6797) - Introduction to DHT concepts including consistent hashing and peer-to-peer lookup protocols

### Real Systems
- [GFS](http://static.googleusercontent.com/media/research.google.com/en/us/archive/gfs-sosp2003.pdf) - Google File System paper on a scalable distributed file system for large-scale data-intensive applications
- [Spanner](http://static.googleusercontent.com/media/research.google.com/en/us/archive/spanner-osdi2012.pdf) - Google's globally-distributed database using TrueTime for external consistency across datacenters
- [F1](http://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/41344.pdf) - Google's distributed relational database built on Spanner for the AdWords system
- [Chubby](http://static.googleusercontent.com/media/research.google.com/en/us/archive/chubby-osdi06.pdf) - Google's distributed lock service providing coarse-grained locking and reliable small-file storage
- [BigTable](http://static.googleusercontent.com/media/research.google.com/en/us/archive/bigtable-osdi06.pdf) - Google's distributed storage system for managing structured data at petabyte scale
- [MillWheel](http://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/41378.pdf) - Google's fault-tolerant stream processing framework with exactly-once delivery guarantees
- [Omega](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/41684.pdf) - Google's shared-state cluster scheduler using optimistic concurrency control for flexible scheduling
- [Dapper](http://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/36356.pdf) - Google's large-scale distributed systems tracing infrastructure for diagnosing performance issues
- [Paxos Made Live](http://www.cs.utexas.edu/users/lorenzo/corsi/cs380d/papers/paper2-1.pdf) - Engineering lessons from implementing Paxos in Google's Chubby lock service
- [The Tail At Scale](http://cseweb.ucsd.edu/~gmporter/classes/fa17/cse124/post/schedule/p74-dean.pdf) - Jeff Dean's paper on techniques for reducing latency variability in large-scale distributed systems
- [Dryad](http://research.microsoft.com/en-us/projects/dryad/eurosys07.pdf) - Microsoft's general-purpose distributed execution engine for coarse-grained data-parallel applications
- [Cassandra](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf) - Facebook's distributed NoSQL database combining Dynamo's partitioning with BigTable's data model
- [Ceph](http://ceph.com/papers/weil-ceph-osdi06.pdf) - Distributed object store and file system designed for performance, reliability, and scalability
- [RAMCloud](https://ramcloud.stanford.edu/wiki/display/ramcloud/RAMCloud+Papers) - Stanford's low-latency storage system keeping all data in DRAM across a datacenter cluster
- [HyperDex](http://hyperdex.org/papers/) - Distributed key-value store using hyperspace hashing for efficient multi-attribute search
- [PNUTS](http://www.mpi-sws.org/~druschel/courses/ds/papers/cooper-pnuts.pdf) - Yahoo's globally distributed data serving system with per-record timeline consistency
- [Azure Data Lake Store](https://dl.acm.org/citation.cfm?id=3056100) - Microsoft's hyperscale distributed file store optimized for big data analytics workloads

### Blog Posts & Talks
- [Everything Will Flow - Zach Tellman](https://www.youtube.com/watch?v=1bNOO3xxMc0) - Talk on backpressure, queuing theory, and flow control in distributed systems

### Other
- [CAP Twelve Years Later: How the "Rules" Have Changed](https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed/) - Eric Brewer revisits the CAP theorem with nuance on partition handling and recovery
- [Fallacies of distributed computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing) - The eight false assumptions programmers make about networks that cause distributed system failures
- [You Can't Sacrifice Partition Tolerance: In which there are limits to the CAP conjecture](https://codahale.com/you-cant-sacrifice-partition-tolerance/) - Argues that network partitions are inevitable, so systems must choose between consistency and availability
- [Two Generals' Problem](https://en.wikipedia.org/wiki/Two_Generals%27_Problem) - Classic thought experiment proving that consensus over unreliable communication is impossible
- [Byzantine fault](https://en.wikipedia.org/wiki/Byzantine_fault) - Explanation of failures where components may behave arbitrarily, including sending conflicting information
- [Vector clock](https://en.wikipedia.org/wiki/Vector_clock) - Logical clock mechanism for determining causal ordering of events in distributed systems
- [Quorum](https://en.wikipedia.org/wiki/Quorum_(distributed_computing)) - Minimum number of votes needed for a distributed operation to proceed, ensuring consistency
- [baseds: Exploring the basics of distributed systems](https://medium.com/baseds) - Beginner-friendly blog series explaining distributed systems concepts with illustrations

### Books
- [Distributed systems for fun and profit](http://book.mixu.net/distsys/) - Free concise ebook covering time, replication, consistency models, and fault tolerance fundamentals
- Designing Data Intensive Applications - Martin Kleppmann - Covers storage engines, replication, partitioning, transactions, and stream processing for modern data systems
- Replication: Theory and Practice - Comprehensive academic treatment of data replication techniques, consistency models, and fault tolerance
- Introduction to Reliable and Secure Distributed Programming - Textbook on building reliable distributed abstractions from broadcast to consensus with formal specifications

## Compilers

- [CS143 Compilers - Stanford](https://web.stanford.edu/class/archive/cs/cs143/cs143.1128/) - Stanford's compiler course covering lexing, parsing, semantic analysis, and code generation
- [Tiger: Toy compiler implementation in OCaml](https://github.com/thizanne/tiger) - Implementation of the Tiger language compiler from Appel's textbook in OCaml
- [Types and Programming Languages - Benjamin C. Pierce](https://www.cis.upenn.edu/~bcpierce/tapl/) - Foundational textbook on type theory covering lambda calculus, subtyping, and polymorphism
- [lambda_calculus: Untyped lambda calculus in Rust](https://github.com/ljedrz/lambda_calculus) - Rust implementation of untyped lambda calculus with multiple reduction strategies
- [How I wrote my own "proper" programming language - Mukul Rathi](https://mukulrathi.com/create-your-own-programming-language/intro-to-compiler/) - Blog series walking through building a concurrent language with type inference and LLVM backend
- [coollang-2020-fs: Compiler for a small Scala subset in F#](https://mykolav.github.io/coollang-2020-fs/) - F# implementation of a compiler for a Scala-like language with classes and type checking
- [Toy Compiler Using Ocamllex, Menhir, and LLVM - Daniel Volya](https://volya.xyz/blog/toy-compiler/) - Tutorial on building a compiler with OCaml's lexer/parser generators targeting LLVM IR
- [OCaml Programming: Type Checking chapter - Cornell CS 3110](https://cs3110.github.io/textbook/chapters/interp/typecheck.html) - Explains how to implement type checking for a simple language in OCaml
- [Introduction to Compilers and Language Design - Douglas Thain](http://compilerbook.org) - Free textbook covering scanner, parser, AST, type checking, and code generation for a C-like language
- [Beautiful Racket - Matthew Flatt](https://beautifulracket.com) - Teaches language-oriented programming by building domain-specific languages in Racket
- [Crafting interpreters - Robert Nystrom](https://craftinginterpreters.com) - Build two complete interpreters (tree-walk in Java, bytecode VM in C) for the Lox language
- [Engineering a Compiler - Keith D. Cooper, Linda Torczon](https://www.goodreads.com/en/book/show/1997607.Engineering_a_Compiler) - Textbook covering intermediate representations, optimization, instruction selection, and register allocation
- [The Programming Languages Zoo - Andrej Bauer](https://plzoo.andrej.com) - Collection of small language implementations demonstrating different PL concepts and type systems

### Project Ideas
- Lambda calculus
- Compiler targeting QBE / LLVM
- Hindley-Milner type system / W Algorithm
- BitTorrent client
- DHT
- Trees: Merkle tree, LSM
- Consensus algorithms: Raft
- CRDTs
- SNARKs / STARKs
- American Fuzzy Lop
- Symbolic execution
- TLA+

## Blockchain

### Introduction
- [Foundations of Blockchains](https://timroughgarden.github.io/fob21/) - Tim Roughgarden's course covering consensus protocols, mechanism design, and blockchain theory
- [DeFi MOOC](https://www.youtube.com/channel/UCB67PxhB5LAWEbI4etQS7aw/playlists) - University-level course covering decentralized finance protocols, AMMs, lending, and oracles

### Pre-requisites
- [Public & Private Keys](https://www.youtube.com/watch?v=GSIDS_lvRv4) - Visual explanation of asymmetric cryptography and how public/private key pairs work
- [Digital Signatures - How they work?](https://www.youtube.com/watch?v=s22eJ1eVLTU) - Explains how digital signatures provide authentication, integrity, and non-repudiation
- [What is Hashing on the Blockchain?](https://www.youtube.com/watch?v=IGSB9zoSx70) - Explains cryptographic hash functions and their role in blockchain data integrity

### Cultural
- [Nic Carter: Bitcoin Core Values, Layered Scaling, and Blocksize Debates](https://youtu.be/mDyBbGCiBUU) - Discussion of Bitcoin's philosophical foundations and the scaling war history
- [Balaji Srinivasan - Bitcoin and Ethereum, Crypto Oracles, and More](https://youtu.be/eim8REOYLzA) - Wide-ranging conversation on crypto's role in technology, governance, and the network state
- [Raoul Pal Discusses with Punk6529: NFTs, IP Rights & The Metaverse](https://youtu.be/2Un_S1Z8yQo) - Discussion on digital ownership, NFT intellectual property, and metaverse economies
- [Michael Saylor: Bitcoin, Inflation, and the Future of Money](https://youtu.be/mC43pZkpTec) - Deep dive into Bitcoin as a store of value and its monetary policy implications
- [The Networked State - Balaji Srinivasan](https://youtu.be/NlY8HICFiRs) - Vision for building new digital-first communities and nations using blockchain technology
- [Cancelled Nickel Trades on the LME - Patrick Boyle](https://youtu.be/tHXF5LyLI4M) - Analysis of the 2022 LME nickel short squeeze and how centralized exchanges can reverse trades

### Basics
- [But how does bitcoin actually work?](https://www.youtube.com/watch?v=bBC-nXj3Ng4) - 3Blue1Brown's visual explanation of Bitcoin's proof-of-work, hashing, and blockchain mechanics
- [Bitcoin paper](https://bitcoin.org/bitcoin.pdf) - Satoshi Nakamoto's original whitepaper describing a peer-to-peer electronic cash system
- [Ethereum paper](https://ethereum.org/en/whitepaper/) - Vitalik Buterin's whitepaper proposing a blockchain with a Turing-complete programming language
- [Understanding the Ethereum Blockchain Protocol - Vitalik Buterin](https://youtu.be/gjwr-7PgpN8) - Vitalik explains Ethereum's technical architecture including state tries, the EVM, and gas
- [Cryptoeconomics In 30 Minutes - Vitalik Buterin](https://youtu.be/GQR1xjQn5Pg) - Concise overview of how economic incentives secure blockchain protocols
- [Trie, Merkle, Patricia: A Blockchain Story](http://kronosapiens.github.io/blog/2018/07/04/patricia-trees.html) - Explains the data structures behind Ethereum's state storage: tries, Merkle trees, and Patricia tries

### Courses
- [Stanford CS 251: Cryptocurrencies and Blockchain Technologies](https://cs251.stanford.edu/syllabus.html) - Stanford course covering consensus, smart contracts, DeFi, and privacy in blockchain systems
- [MIT 15.S12 Blockchain and Money - Gary Gensler](https://www.youtube.com/playlist?list=PLUl4u3cNGP63UUkfL0onkxF6MYgVa04Fn) - MIT course examining blockchain technology through the lens of finance and regulation

### Solidity
- [Learn Solidity in Y minutes](https://learnxinyminutes.com/docs/solidity/) - Quick syntax reference for Solidity covering types, functions, modifiers, and events
- [Solidity by Example](https://solidity-by-example.org/) - Concise, runnable Solidity examples covering common patterns from basic to advanced
- [Crypto Zombies](https://cryptozombies.io/) - Interactive tutorial that teaches Solidity by building a zombie-themed game step by step
- [Peter's Solidity Recruitment Test](https://youtu.be/80fA7foSi7c) - Video walkthrough of a Solidity coding challenge used for smart contract developer hiring
- [BuidlGuidl is a curated group of Ethereum builders](https://buidlguidl.com/) - Community of Ethereum developers building open-source projects with Scaffold-ETH

#### Contracts
- [Programming DeFi: Uniswap V2](https://jeiwan.net/posts/programming-defi-uniswapv2-1/) - Step-by-step guide to implementing the Uniswap V2 automated market maker from scratch

### Ethereum Internals
- [EVM Deep Dives: The Path to Shadowy Super Coder](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy?s=r) - Deep technical exploration of EVM internals including opcodes, memory layout, and gas costs
- [EVM: From Solidity to byte code, memory and storage](https://youtu.be/RxL_1AfV7N4) - Video explaining how Solidity compiles to bytecode and how the EVM manages memory and storage
- [Ethereum Virtual Machine](https://youtu.be/BsDq2mzC5tk) - Overview of EVM architecture, stack-based execution, and smart contract deployment
- [Ethereum VM and Consensus by Fredrik Haga](https://youtu.be/Wq8kryb2Ats) - Explains how the EVM executes transactions and how Ethereum reaches consensus

### Ethereum Security
- [Ethernaut](https://ethernaut.openzeppelin.com/) - Wargame where you exploit vulnerable smart contracts to learn Solidity security patterns
- [Honeypot](https://github.com/scaffold-eth/scaffold-eth/tree/honeypot-example) - Example of a smart contract honeypot trap built with Scaffold-ETH for educational purposes
- [Honeypots in Ethereum And How To Avoid Them](https://youtu.be/DDn5mksOUCc) - Video explaining how deceptive smart contracts lure victims and how to identify them
- [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/) - Wargame with DeFi-specific challenges covering flash loans, oracles, and governance attacks
- [Solidity Security: Comprehensive list of known attack vectors and common anti-patterns](https://blog.sigmaprime.io/solidity-security.html) - Reference guide to Solidity vulnerabilities including reentrancy, overflow, and access control flaws
- [Capture the Ether](https://capturetheether.com/challenges/) - CTF-style challenges teaching Ethereum security by exploiting vulnerable smart contracts

### Vulnerabilities
- [Smart Contract Vulnerabilities (SCV) List](https://github.com/sirhashalot/SCV-List) - Categorized registry of smart contract vulnerability types with real exploit examples

### MEV
- [Understanding MEV - with Georgios Konstantopoulos, Dan Robinson, and Hasu](https://youtu.be/vCCYFSAdCFo) - Panel discussion explaining miner/maximal extractable value and its impact on Ethereum
- [Interview with a Searcher - with MEV Senpai and Hasu](https://youtu.be/6jfSlDvH77k) - First-hand account of running MEV extraction bots and the competitive searcher landscape
- [Flash Boys 2.0: Frontrunning, Transaction Reordering, and Consensus Instability in Decentralized Exchanges](https://arxiv.org/abs/1904.05234) - Seminal paper quantifying frontrunning and MEV extraction on decentralized exchanges
- [MEV 101](https://github.com/0xmebius/mev/blob/main/MEV101.pdf) - Introduction to MEV concepts including sandwiching, liquidations, and arbitrage strategies

### Zero Knowledge Proofs

#### Basics
- [Intro to zero knowledge proofs](https://www.youtube.com/watch?v=HUs1bH85X9I) - Beginner-friendly explanation of what zero-knowledge proofs are and why they matter
- [Security and Privacy for Crypto with Zero-Knowledge Proofs](https://www.youtube.com/watch?v=3NL0ThdvWMU) - Overview of how ZKPs enable privacy-preserving transactions and identity verification

#### ZK SNARKs
- [What are zk-SNARKs?](https://z.cash/technology/zksnarks/) - Zcash's explanation of succinct non-interactive arguments of knowledge and their use in private transactions
- [Intro to zk-SNARKs - Howard Wu](https://zeroknowledge.fm/38-2/) - Podcast episode providing an accessible introduction to zk-SNARK construction and applications
- [Zcash Ceremony](https://www.youtube.com/watch?v=D6dY-3x3teM) - Documentary on Zcash's trusted setup ceremony and why it was necessary for the SNARK parameters

#### ZK STARKs
- [Hasu gets STARK-pilled - with Eli Ben-Sasson](https://youtu.be/-6BtBUbiUIU) - StarkWare founder explains STARK advantages: no trusted setup, post-quantum security, and scalability
- [Cairo - a Turing-complete STARK-friendly CPU architecture](https://eprint.iacr.org/2021/1063.pdf) - Paper describing Cairo's CPU architecture designed for efficient STARK proof generation

#### Advanced topics
- [Vitalik's introduction to how zk-SNARKs are possible](https://vitalik.ca/general/2021/01/26/snarks.html) - Accessible walkthrough of the math behind SNARKs: polynomials, elliptic curves, and pairings
- [Vitalik's post on quadratic arithmetic programs](https://medium.com/@VitalikButerin/quadratic-arithmetic-programs-from-zero-to-hero-f6d558cea649) - Explains how computation is converted to QAPs, the core representation used in SNARKs
- [Comparing General Purpose zk-SNARKs](https://medium.com/coinmonks/comparing-general-purpose-zk-snarks-51ce124c60bd) - Comparison of Groth16, PLONK, Marlin, and other SNARK schemes by performance and tradeoffs

#### Examples with code
- [Dark forest's intro + circuits Part 1](https://blog.zkga.me/intro-to-zksnarks) - Practical introduction to zk-SNARKs through building circuits for the Dark Forest game
- [Dark forest's intro + circuits Part 2](https://blog.zkga.me/df-init-circuit) - Continues building zk-SNARK circuits for Dark Forest's initialization proof

### R1CS/Circuits
- [Circom tutorial](https://github.com/therealyingtong/roll_up_circom_tutorial) - Tutorial on writing arithmetic circuits in Circom for building a simple rollup
- [R1CS programing workshop](https://github.com/mir-protocol/r1cs-workshop/blob/master/workshop.pdf) - Hands-on workshop on writing rank-1 constraint systems for zero-knowledge proof circuits

### Papers
- [A Note on Cryptocurrency Stabilisation: Seigniorage Shares - Robert Sams](https://github.com/rmsams/stablecoins/blob/master/paper.pdf) - Early algorithmic stablecoin design using seigniorage shares to maintain a price peg

## Cryptography

- [Introduction to Cryptography - Christof Paar](https://www.youtube.com/playlist?list=PL6N5qY2nvvJE8X75VkXglSrVhLv1tVcfy) - University lecture series covering symmetric ciphers, public key crypto, hashing, and digital signatures
- [Cryptography I - Dan Boneh](https://www.coursera.org/learn/crypto) - Stanford's foundational crypto course covering encryption, authentication, key exchange, and public-key systems

### Exercises
- [amrayn/mine](https://github.com/amrayn/mine) - Minimal C++ encryption library for learning AES, RSA, and Base64 implementations
- [mimoo/disco-c](https://github.com/mimoo/disco-c) - C implementation of the Disco protocol combining Noise framework with Strobe for secure handshakes
- [LoupVaillant/Monocypher](https://github.com/LoupVaillant/Monocypher) - Small, portable C cryptography library for studying implementations of Curve25519, ChaCha20, and Blake2b

### Blogs
- [Trail of Bits](https://blog.trailofbits.com/) - Security research blog covering cryptography audits, vulnerability research, and tool development

### Books
- [Real World Cryptography](https://www.manning.com/books/real-world-cryptography?a_aid=Realworldcrypto&a_bid=ad500e09) - Practical guide to modern cryptography covering TLS, end-to-end encryption, and post-quantum crypto
- [Programming Bitcoin - Jimmy Song](https://www.oreilly.com/library/view/programming-bitcoin/9781492031482/) - Teaches elliptic curve cryptography, transactions, and the Bitcoin protocol by coding them in Python

### Elliptic Curves
- [Elliptic Curve cryptography explained](https://fangpenlin.com/posts/2019/10/07/elliptic-curve-cryptography-explained/) - Visual and intuitive explanation of elliptic curve math and its application to cryptography
- [Elliptic curves - Trustica](https://trustica.cz/en/category/ecc/page/3/) - Blog series exploring elliptic curve theory from basic group law to pairing-based cryptography
- [Elliptic curves in simple Weierstrass form - Trustica](https://www.youtube.com/playlist?list=PLN9KZDpNfsHMd7d7PX87JGesGY_Qzyb3V) - Video series on elliptic curves in Weierstrass form with concrete computations
- [18.783 Elliptic Curves - MIT](https://math.mit.edu/classes/18.783/2022/lectures.html) - Graduate-level MIT course covering elliptic curve arithmetic, isogenies, and cryptographic applications

#### Discrete Logarithm problem
- [18.783 Elliptic Curves Lecture #9 - The discrete logarithm problem](https://math.mit.edu/classes/18.783/2022/LectureNotes9.pdf) - Covers algorithms for the elliptic curve discrete log problem including Pollard rho and baby-step giant-step
- [Zero Knowledge from the Discrete Logarithm Problem](https://youtu.be/hO6feBcKQ98) - Explains how the hardness of discrete logarithm enables zero-knowledge proof constructions

### Pairings
- [Pairings for beginners - Craig Costello](https://static1.squarespace.com/static/5fdbb09f31d71c1227082339/t/5ff394720493bd28278889c6/1609798774687/PairingsForBeginners.pdf) - Gentle introduction to bilinear pairings on elliptic curves and their use in cryptographic protocols
- [The Basics of Pairings - Dan Boneh](https://www.youtube.com/watch?v=F4x2kQTKYFY) - Lecture explaining bilinear maps and how pairings enable BLS signatures, IBE, and SNARKs

### CTF
- [CTF Cryptography for Beginners](https://charcharbinks.com/post/ctf_crypto_for_beginners/) - Guide to common crypto CTF challenge types including RSA, XOR, and classical ciphers
- [Cryptohack](https://cryptohack.org/courses/) - Interactive platform for learning cryptography through progressive challenges from basics to advanced
- [Cryptopals](https://cryptopals.com) - Famous set of 48 practical cryptography exercises covering attacks on real-world crypto systems
- [Krypton](https://overthewire.org/wargames/krypton/) - OverTheWire wargame teaching classical cipher breaking from Caesar to Vigenere and beyond
- [Cryptanalysis](https://www.root-me.org/en/Challenges/Cryptanalysis/) - Cryptanalysis challenges ranging from basic encoding to breaking modern crypto implementations

#### Tools
- [CyberChef](https://gchq.github.io/CyberChef/) - Web-based tool for encoding, decoding, encryption, compression, and data analysis operations

### zk-SNARK
- [The missing explanation of ZK-SNARKs: Part 1 - David Wong](https://www.cryptologie.net/article/507/the-missing-explanation-of-zk-snarks/) - Builds up zk-SNARK intuition from polynomials to the verification equation
- [The missing explanation of zk-SNARKs: Part 2 - David Wong](https://cryptologie.net/article/508/the-missing-explanation-of-zk-snarks-part-2/) - Continues the construction with elliptic curve pairings and the trusted setup
- [Why and How zk-SNARK works - Maksym Petkus](https://arxiv.org/pdf/1906.07221.pdf) - Detailed mathematical walkthrough of zk-SNARK construction from basic algebra to Groth16
- [zkSNARKs in a nutshell - Christian Reitwiessner](https://blog.ethereum.org/2016/12/05/zksnarks-in-a-nutshell/) - Compact overview of zk-SNARK components: encoding, homomorphic encryption, and verification
- [An approximate introduction to how zk-SNARKs are possible - Vitalik Buterin](https://vitalik.ca/general/2021/01/26/snarks.html) - Vitalik's accessible explanation of the polynomial commitments and pairings behind SNARKs
- [Quadratic Arithmetic Programs: from Zero to Hero - Vitalik Buterin](https://medium.com/@VitalikButerin/quadratic-arithmetic-programs-from-zero-to-hero-f6d558cea649) - Step-by-step guide to converting programs into the QAP form needed by SNARK provers
- [Exploring Elliptic Curve Pairings - Vitalik Buterin](https://medium.com/@VitalikButerin/exploring-elliptic-curve-pairings-c73c1864e627) - Explains bilinear pairings on elliptic curves and why they are essential for zk-SNARKs
- [zk-SNARKs: Under the Hood - Vitalik Buterin](https://medium.com/@VitalikButerin/zk-snarks-under-the-hood-b33151a013f6) - Final part of Vitalik's series connecting QAPs, pairings, and the full SNARK protocol
- [The Mathematics behind zkSNARKS - Mirco Richter](https://youtu.be/iRQw2RpQAVc) - Video lecture covering the algebraic foundations needed to understand SNARK constructions

#### Languages
- [Lurk: A Turing-complete programming language for zk-SNARKs](https://github.com/lurk-lab/lurk) - Lisp-like language where program execution can be proven in zero knowledge
- [Noir](https://github.com/noir-lang/noir) - Domain-specific language for writing zero-knowledge proofs with a Rust-like syntax

#### Proof systems
- [Nova](https://github.com/microsoft/Nova) - Microsoft's recursive SNARK scheme using incrementally verifiable computation with minimal overhead

### STARKs
- [STARKs, Part I: Proofs with Polynomials - Vitalik Buterin](https://vitalik.ca/general/2017/11/09/starks_part_1.html) - Explains how polynomial evaluation and Merkle trees enable transparent, trustless proofs
- [STARKs, Part II: Thank Goodness It's FRI-day - Vitalik Buterin](https://vitalik.ca/general/2017/11/22/starks_part_2.html) - Covers the FRI protocol for proving that a committed value is close to a low-degree polynomial
- [STARKs, Part 3: Into the Weeds - Vitalik Buterin](https://vitalik.ca/general/2018/07/21/starks_part_3.html) - Complete walkthrough of building a STARK prover and verifier with concrete Python code

#### Provers and verifiers
- [Winterfell](https://github.com/novifinancial/winterfell) - Rust library for generating and verifying STARK proofs with a focus on performance and usability

### Other
- [Crypto Screencasts - David Wong](https://www.youtube.com/playlist?list=PLBJMt6zV1c7FN3IjBDr9lydgqGzh_SqHV) - Short video explanations of cryptographic concepts including hash functions, MACs, and key exchange
- [ZK docs](https://www.zkdocs.com/) - Community-maintained documentation hub for zero-knowledge proof systems and implementations

## Mathematics

- [The two cultures of mathematics](https://www.dpmms.cam.ac.uk/~wtg10/2cultures.pdf) - Timothy Gowers' essay contrasting problem-solving and theory-building approaches in mathematics
- [Introduction to Computational Thinking - Alan Edelman, David P. Sanders and Charles E. Leiserson](https://computationalthinking.mit.edu/Spring21/) - MIT course teaching computational thinking through Julia with applications in data science and modeling
- [Matrix Methods in Data Analysis, Signal Processing, and Machine Learning](https://ocw.mit.edu/courses/mathematics/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/) - Gilbert Strang's MIT course on matrix decompositions, deep learning, and optimization

### Linear Algebra
- [Essence of linear algebra - 3blue1brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - Visual series building geometric intuition for vectors, linear transformations, eigenvalues, and determinants
- [Linear Algebra - Steve Brunton](https://www.youtube.com/playlist?list=PLMrJAkhIeNNRjxJ_sMtJ02geqw_-vuB7O) - Engineering-focused linear algebra covering SVD, PCA, and applications to data-driven methods
- [Introduction to Applied Linear Algebra - Stephen Boyd](https://www.youtube.com/watch?v=oR6G1MUMveE&list=PLoROMvodv4rMz-WbFQtNUsUElIh2cPmN9) - Stanford course covering vectors, matrices, least squares, and applications in data fitting and control
- [Linear Algebra Done Right - Sheldon Axler](https://www.youtube.com/playlist?list=PLGAnmvB9m7zOBVCZBUUmSinFV0wEir2Vw) - Proof-based linear algebra emphasizing vector spaces and linear maps over determinant-heavy approaches

### Analysis
- [The Essence of Calculus - 3blue1brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) - Visual series building intuition for derivatives, integrals, and the fundamental theorem of calculus
- [Measure theory - The Bright Side Of Mathematics](https://www.youtube.com/playlist?list=PLBh2i93oe2qvMVqAzsX1Kuv6-4fjazZ8j) - Step-by-step introduction to sigma-algebras, measures, Lebesgue integration, and convergence theorems
- [Functional Analysis - The Bright Side Of Mathematics](https://www.youtube.com/watch?v=yDdxFBcvSGw&list=PLBh2i93oe2qsGKDOsuVVw-OCAfprrnGfr) - Covers Banach spaces, Hilbert spaces, bounded operators, and the spectral theorem
- [Distributions theory - The Bright Side Of Mathematics](https://www.youtube.com/watch?v=gwVEEUg8PBY&list=PLBh2i93oe2qsbptdcvFlowCl51EX_a3nB) - Introduction to distributions (generalized functions), test functions, and the Dirac delta

### Complex Analysis and Fourier
- [Complex analysis - Richard E. Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj51F9XZ_Ka4bLnQoxTdMx0AL) - Fields medalist's lecture series covering analytic functions, contour integrals, and residue theory
- [Fourier Analysis - Steve Brunton](https://www.youtube.com/playlist?list=PLMrJAkhIeNNT_Xh3Oy0Y4LTj0Oxo8GqsC) - Covers Fourier series, Fourier transform, FFT, and applications to signal processing and PDEs
- [Visual Complex Functions: an Introduction with Phase Portraits - Elias Wegert](https://www.goodreads.com/book/show/12353218-visual-complex-functions?from_search=true&from_srp=true&qid=04GqQgkIBM&rank=1) - Introduces complex analysis through colorful phase portraits that visualize analytic functions
- [Complex Analysis - Serge Lang](https://cloudflare-ipfs.com/ipfs/bafykbzacebds7eaero37rx6fztl2wg36h4yklf7ilwjsrjl654etvz4omqzfm?filename=%28Graduate%20Texts%20in%20Mathematics%20103%29%20Serge%20Lang%20-%20Complex%20Analysis-Springer%20%282003%29.pdf) - Graduate-level textbook covering Cauchy's theorem, conformal mappings, and Riemann surfaces

### Probability and Statistics
- [Probability The Science of Uncertainty and Data - John Tsitsiklis](https://www.edx.org/course/probability-the-science-of-uncertainty-and-data) - MIT course covering probability axioms, random variables, Bayesian inference, and limit theorems
- [Fundamentals of Statistics - Philippe Rigollet](https://www.edx.org/course/fundamentals-of-statistics) - MIT course on statistical estimation, hypothesis testing, and confidence intervals
- [Random Walks - Santa Fe Institute](https://www.complexityexplorer.org/courses/46-random-walks) - Course on random walk theory and its applications in physics, biology, and finance
- [The Logic of Science by E.T. Jaynes](https://www.youtube.com/watch?v=rfKS69cIwHc&list=PL9v9IXDsJkktefQzX39wC2YG07vw7DsQ_) - Video series on Bayesian probability as extended logic, based on Jaynes' foundational textbook

### Machine Learning and Deep Learning
- [Introduction to Statistical Learning Series - Robert Tibshirani and Trevor Hastie](https://www.youtube.com/watch?v=5N9V07EIfIg&list=PLOg0ngHtcqbPTlZzRHA2ocQZqB1D_qZ5V) - Stanford course covering regression, classification, resampling, tree methods, and unsupervised learning
- [Practical Deep Learning for Coders](https://course.fast.ai/) - Fast.ai's top-down course teaching deep learning with PyTorch through practical applications first
- [Part 2: Deep Learning from the Foundations](https://course19.fast.ai/part2) - Fast.ai's advanced course rebuilding deep learning frameworks from scratch, covering backprop and optimizers
- [Geometric Deep Learning - Michael Bronstein](https://youtu.be/PtA0lg_e5nA?list=PLn2-dEmQeTfQ8YVuHBOvAhUlnIPYxkeu3) - Unifying framework for deep learning on graphs, meshes, groups, and manifolds

### Complexity and Dynamical Systems
- [Nonlinear Dynamics: Mathematical and Computational Approaches - Santa Fe Institute](https://www.complexityexplorer.org/courses/115-nonlinear-dynamics-mathematical-and-computational-approaches) - Course on bifurcations, chaos, fractals, and numerical methods for nonlinear systems
- [Introduction to Dynamical Systems and Chaos - Santa Fe Institute](https://www.complexityexplorer.org/courses/105-introduction-to-dynamical-systems-and-chaos) - Introductory course covering iterated maps, strange attractors, and the onset of chaos
- [Data-Driven Dynamical Systems Overview - Steve Brunton](https://www.youtube.com/playlist?list=PLMrJAkhIeNNR6DzT17-MM1GHLkuYVjhyt) - Using machine learning and data analysis to discover dynamical systems models from measurements
- [Parallel Computing and Scientific Machine Learning - MIT 18.337J](https://github.com/mitmath/18337) - MIT course combining parallel computing, differential equations, and neural network approaches

### Abstract Algebra
- [Abstract Algebra - Socratica](https://www.youtube.com/playlist?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6) - Short, clear videos introducing groups, rings, and fields with motivating examples
- [Abstract (Modern) Algebra - Bill Kinney](https://www.youtube.com/playlist?list=PLmU0FIlJY-Mn3Pt-r5zQ_-Ar8mAnBZTf2) - Full lecture course covering groups, rings, fields, and Galois theory at the undergraduate level
- [Rings and modules - Richard E. Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj52XDLrmvrFDgwcf6XOm2TEE) - Graduate-level lectures on ring theory, modules, and their applications in algebra
- [Abstract Algebra - Michael Artin](https://www.youtube.com/playlist?list=PLelIK3uylPMGzHBuR3hLMHrYfMqWWsmx5) - MIT lectures based on Artin's textbook covering groups, symmetry, linear algebra, and rings
- [Visual Group Theory - Matthew Macauley](https://www.youtube.com/playlist?list=PLwV-9DG53NDxU337smpTwm6sef4x-SCLv) - Group theory taught visually using Cayley diagrams, symmetry, and geometric intuition

#### Books
- [Algebra - Serge Lang](https://www.wiley.com/en-au/Abstract+Algebra,+3rd+Edition-p-9780471433347) - Comprehensive graduate algebra textbook covering groups, rings, modules, fields, and Galois theory
- Topics in Algebra - Herstein - Classic undergraduate algebra text known for rigorous treatment of groups, rings, and field extensions

### Number Theory
- [Elementary Number Theory: Primes, Congruences, and Secrets - William Stein](https://wstein.org/ent/ent.pdf) - Free textbook covering primes, modular arithmetic, and cryptographic applications using Sage
- [Algebraic Number Theory](https://www.jmilne.org/math/CourseNotes/ANT.pdf) - Milne's graduate notes on number fields, rings of integers, Dedekind domains, and class field theory
- [Introduction to number theory - Richard E. Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj53L8sMbzIhhXSAOpuZ1Fov8) - Lecture series covering divisibility, primes, congruences, and quadratic reciprocity
- [Theory of numbers - Richard E. Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj52Qf7lc3HHvHRdIysxEcj1H) - Advanced number theory lectures covering algebraic integers, p-adic numbers, and zeta functions

### Real Analysis
- [Real Analysis: Lectures by Professor Francis Su](https://www.youtube.com/playlist?list=PL0E754696F72137EC) - Full course on sequences, continuity, compactness, and metric spaces with elegant proofs

### Category Theory
- [Categories for the idle mathematician - Richard E. Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj51F9XZ_Ka4bLnQoxTdMx0AL) - Accessible introduction to categories, functors, natural transformations, and adjunctions

### Topology
- [Algebraic Topology: a beginner's course - N J Wildberger](https://www.youtube.com/playlist?list=PL41FDABC6AA085E78) - Introductory course covering simplicial complexes, homology groups, and the fundamental group

#### Point Set Topology
- [Point Set Topology Online Notes with Problems: MAT327 Course Notes](http://www.math.toronto.edu/ivan/mat327/?resources) - Course notes covering topological spaces, continuity, compactness, connectedness, and metric spaces

### Geometry
- [Visual Differential Geometry and Forms: A Mathematical Drama in Five Acts - Tristan Needham](https://www.vdgf.space/) - Geometric and visual approach to differential geometry, curvature, and differential forms

### Dynamical Systems Theory and Chaos
- [More is different - Anderson](https://t.co/g0vE10UvyA?amp=1) - Classic paper arguing that complexity at each scale requires fundamentally new laws, not just more particles
- [What is complexity? Remarks on simplicity and complexity - Gell-Man](https://onlinelibrary.wiley.com/doi/abs/10.1002/cplx.6130010105) - Nobel laureate's essay defining different notions of complexity and their relationships
- [Numerical Evidence That the Motion of Pluto Is Chaotic - Gerald Jay Sussman, Jack Wisdom](https://web.mit.edu/wisdom/www/pluto-chaos.pdf) - Demonstrates through numerical integration that Pluto's orbit exhibits chaotic behavior over millions of years
- [Deterministic nonperiodic Flow - Edward Lorenz](https://journals.ametsoc.org/doi/pdf/10.1175/1520-0469%281963%29020%3C0130%3ADNF%3E2.0.CO%3B2) - The foundational 1963 paper discovering deterministic chaos in a simple atmospheric convection model
- [Intermittent transition to turbulence in dissipative dynamical systems - Yves Pomeau, Paul Manneville](https://link.springer.com/article/10.1007%2FBF01197757) - Describes the Type I intermittency route to chaos through tangent bifurcations near periodic orbits
- [Roads to turbulence in dissipative dynamical systems - Eckmann](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.53.643) - Review of the main scenarios by which laminar flow transitions to turbulent chaos

## Entrepreneurship

- [Peter Thiel: Going from Zero to One](https://www.youtube.com/watch?v=rFZrL1RiuVI) - Thiel's talk on building monopoly businesses by creating new value rather than competing in existing markets

## Other Topics

### Finance
- [Bridgewater Associates](https://www.youtube.com/c/Bridgewater/videos) - Videos from the world's largest hedge fund on macro investing, economic cycles, and risk parity
- [DX Analytics](https://github.com/yhilpisch/dx) - Python library for derivatives and risk analytics using Monte Carlo simulation
- [Risk Management - Pasquale Cirillo](https://www.youtube.com/playlist?list=PLgCR5H4IzggGihtfhTtA0fxGiBU8DMWHq) - Lecture series covering VaR, expected shortfall, extreme value theory, and operational risk
- [Economics of Money and Banking - Perry Mehrling](https://www.coursera.org/learn/money-banking) - Course explaining the money view of the financial system, central banking, and the hierarchy of money
- [Quantitative Risk Management - Pasquale Cirillo](https://www.youtube.com/watch?v=-E4QMeCNvIE&list=PLgCR5H4IzggHyHw8dalrVHqHAqZfmTeWa) - Advanced course on modeling financial risk with copulas, heavy tails, and dependence structures
- [Financial Mathematics - Pasquale Cirillo](https://www.youtube.com/watch?v=JyoeWaNtWLM&list=PLgCR5H4IzggF_w7l1WSYMaoDSZNNkk9gE) - Course covering interest rates, bond pricing, portfolio theory, and the Black-Scholes model
- [Python for Computational Finance - Yves Hilpisch](https://home.tpq.io/certificates/compfin/) - Training program on using Python for financial modeling, algorithmic trading, and risk analytics

#### Papers
- [Demystifying Rebalancing Premium and Extending Portfolio Theory in the Process - Vladislav Dubikovsky, Gabriele Susinno](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2927791) - Formalizes how periodic portfolio rebalancing generates excess returns from volatility
- [Rough Volatility Literature](https://sites.google.com/site/roughvol/home/risks-1) - Collection of papers on rough volatility models that better capture observed market dynamics
- [Radical Complexity - Jean-Philippe Bouchaud](https://arxiv.org/abs/2103.09692) - Argues that standard economic models fail due to ignoring complexity, reflexivity, and fat tails
- [Buy Rough, Sell Smooth - Paul Glasserman, Pu He](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3301669) - Develops trading strategies exploiting the difference between rough and smooth volatility models

#### Volatility
- [Rough volatility - Jim Gatheral](https://youtu.be/gW073Tnx7CE) - Lecture on how fractional Brownian motion with low Hurst parameter models realized volatility
- [Fragile Markets - Understanding the dynamic of a Flash Crash - Harel Jacobson](https://volquant.medium.com/fragile-markets-understanding-the-dynamic-of-a-flash-crash-e86fbc8b4e6c) - Analysis of market microstructure breakdown and liquidity evaporation during flash crashes
- [Liquidity, Volatility, and Information Asymmetry - Harel Jacobson](https://volquant.medium.com/liquidity-volatility-and-information-asymmetry-c7eb52dd3a4c) - Explores the relationship between market maker behavior, information flow, and implied volatility
- [So You Want to Trade Options - Volatility Trading 101 - Harel Jacobson](https://volquant.medium.com/so-you-want-to-trade-options-volatility-trading-101-b96bccbd467b) - Introduction to options trading fundamentals including Greeks, vol surface, and basic strategies
- [Delta Hedging made simple (sort of...) - Harel Jacobson](https://volquant.medium.com/delta-hedging-made-simple-sort-of-34441d1d1db8) - Practical explanation of delta hedging mechanics and P&L from gamma and theta
- [Volatility Smile and Delta Hedging (Part 1) - Getting intimate with the vol surface - Harel Jacobson](https://volquant.medium.com/volatility-smile-and-delta-hedging-part-1-getting-intimate-with-the-vol-surface-7bdcafaf8bdf) - Explains why the volatility smile exists and how it affects delta hedging strategies
- [Turbocharging Derivatives - Variance, Convexity, and Everything in Between - Harel Jacobson](https://volquant.medium.com/turbocharging-derivatives-variance-convexity-and-everything-between-3988741664d4) - Deep dive into variance swaps, convexity adjustments, and higher-order Greeks
- [Trading Volatility Roughness - Rethinking Statistical Arbitrage - Harel Jacobson](https://volquant.medium.com/trading-volatility-roughness-rethinking-statistical-arbitrage-41a204c93b6d) - Applies rough volatility theory to design statistical arbitrage strategies on the vol surface
- [A Brief History of Volatility Models - Harel Jacobson](https://volquant.medium.com/a-brief-history-of-volatility-models-cc0bbefe8b90) - Survey from Black-Scholes through local vol, stochastic vol, to rough volatility models
- [A Story of Liquidity, Volatility, and Returns - Nope, it's Lily](https://nope-its-lily.medium.com/a-story-of-liquidity-volatility-and-returns-754e0019c2d0) - Explains how options market maker hedging flows amplify or dampen equity market moves

### Money and Monetarism
- [Money - Perry Mehrling](https://youtu.be/f49T53oKIw8) - Lecture on money as a hierarchical system of promises and the role of central banks in settlement
- [What is Money, Anyway? - Lyn Alden](https://www.lynalden.com/what-is-money/) - Comprehensive essay tracing the history and properties of money from commodity to digital forms
- [Bagehot was a Shadow Banker: Shadow Banking, Central Banking, and the Future of Global Finance - Perry Mehrling](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2232016) - Reinterprets Bagehot's Lombard Street through the lens of modern shadow banking and dealer markets

### Geopolitics
- [Ray Dalio: Money, Power, and the Collapse of Empires](https://youtu.be/TISMidxdZoc) - Dalio's framework for understanding the rise and fall of empires through debt cycles and reserve currencies

# Not yet reviewed

> These resources were recently found and have not been reviewed yet. They will be organized into the appropriate sections after review.

### Reverse Engineering & Security
- [OpenSecurityTraining2](https://p.ost2.fyi/courses) - Free, university-quality curriculum on x86/x64 architecture, Windows/Linux kernel internals, and exploitation
- [pwn.college](https://pwn.college/) - 1000+ structured challenges covering shellcode, sandboxing, memory corruption, and kernel pwn
- [LibAFL: A Framework to Build Modular and Reusable Fuzzers (CCS 2022)](https://www.s3.eurecom.fr/docs/ccs22_fioraldi.pdf) - Rust-based composable fuzzing library replacing AFL++
- [xairy/linux-kernel-exploitation](https://github.com/xairy/linux-kernel-exploitation) - Continuously maintained reference index of Linux kernel exploitation techniques and CVEs

### Assembly & Low-Level
- [RISC-V Assembly Programming](https://riscv-programming.org/) - Free textbook teaching assembly through the modern RISC-V ISA
- [Rust Atomics and Locks - Mara Bos (O'Reilly, free online)](https://maras.nl/atomics/) - Definitive treatment of low-level concurrency: atomics, memory ordering, building OS primitives in Rust
- [Learning eBPF - Liz Rice (O'Reilly)](https://cilium.isovalent.com/hubfs/Learning-eBPF%20-%20Full%20book.pdf) - Practical introduction to eBPF for tracing, networking, and security

### Distributed Systems
- [Gossip Glomers - Fly.io Distributed Systems Challenges](https://fly.io/dist-sys/) - Hands-on challenges built on Maelstrom (Jepsen) covering broadcast, CRDTs, Kafka logs, and transactional KV
- [FoundationDB: A Distributed Unbundled Transactional Key Value Store (SIGMOD 2021)](https://dl.acm.org/doi/10.1145/3592838) - Architecture paper on simulation testing, deterministic replay, and the record layer
- [Log-structured Protocols in Delos (OSDI 2021)](https://ceres.cs.umd.edu/818/papers/delos.pdf) - How Meta built a layered, reconfigurable consensus system
- [Zanzibar: Google's Consistent, Global Authorization System](https://research.google/pubs/zanzibar-googles-consistent-global-authorization-system/) - Spawned SpiceDB, OpenFGA, and the entire Zanzibar-like authorization category

### Compilers
- [CS 6120: Advanced Compilers (Cornell) - Adrian Sampson](https://www.cs.cornell.edu/courses/cs6120/2020fa/self-guided/) - PhD-level compiler course covering SSA, dataflow, LLVM passes
- [MLIR Getting Started - Jeremy Kun](https://www.jeremykun.com/2023/08/10/mlir-getting-started/) - Clearest introduction to MLIR concepts and dialect system
- [SSA-based Compiler Design (free PDF)](https://pfalcon.github.io/ssabook/latest/book.pdf) - Comprehensive academic treatment of SSA form in optimizing compilers

### Cryptography
- [Proofs, Arguments, and Zero-Knowledge - Justin Thaler (free PDF)](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.html) - Most rigorous textbook on interactive proofs, SNARKs, and ZK arguments
- [ZK-Learning MOOC (Berkeley CS294)](https://rdi.berkeley.edu/zk-learning/) - Full university course on ZKP foundations through practical SNARKs and STARKs
- [MIT IAP: Modern Zero Knowledge Cryptography](https://zkiap.com/) - MIT intensive on elliptic curves, polynomial commitments, Groth16, PLONK, Halo2

### Mathematics
- [Neural Networks: Zero to Hero - Andrej Karpathy](https://karpathy.ai/zero-to-hero.html) - Builds backprop, micrograd, GPT from scratch in pure Python
- [Freya Holmer: Math for Game Devs](https://www.youtube.com/@acegikmo) - Outstanding visual course on vectors, matrices, splines, quaternions
- [The Nature of Code (2nd ed., 2024) - Daniel Shiffman](https://natureofcode.com/) - Physics simulations, autonomous agents, genetic algorithms through creative coding

### Game Programming
- [Inigo Quilez: Articles on SDFs, Raymarching & Shaders](https://iquilezles.org/articles/) - Best online reference for distance field rendering and procedural graphics by Shadertoy co-creator
- [Graphics Programming community resources](https://graphicsprogramming.github.io/resources/) - Community-curated index of rendering papers, API guides, and GPU architecture references

### Distributed Systems (New)
- [The Art of the Fugue: Minimizing Interleaving in Collaborative Text Editing - Weidner & Kleppmann (IEEE TPDS, 2025)](https://arxiv.org/abs/2305.00583) - Fugue/FugueMax CRDT algorithms with maximal non-interleaving correctness for replicated lists
- [Loro: High-Performance CRDTs in Rust](https://github.com/loro-dev/loro) - Rust CRDT library integrating Fugue, Eg-walker, and rich text CRDTs; alternative to Yjs/Automerge
- [PowerInfer: Fast LLM Serving with Consumer-grade GPU (SOSP 2024)](https://dl.acm.org/doi/10.1145/3694715.3695964) - Exploits power-law neuron activation for GPU-CPU hybrid inference; up to 11.69x speedup on RTX 4090
- [TigerBeetle: Deterministic Simulation Testing](https://github.com/tigerbeetle/tigerbeetle) - Financial transactions database in Zig with VOPR simulation testing; 3.3s simulation covers 39min real-world. See also [Phil Eaton's overview](https://notes.eatonphil.com/2024-08-20-deterministic-simulation-testing.html)

### Compilers & Languages (New)
- [The MLIR Transform Dialect (CGO 2025)](https://2025.cgo.org/details/cgo-2025-papers/7/) - Controllable IR-based transformation system within MLIR for fine-grained compiler control
- [First-Class Verification Dialects for MLIR (PLDI 2025)](https://users.cs.utah.edu/~regehr/papers/pldi25.pdf) - Integrates formal verification methods directly into MLIR's dialect framework
- [Mojo Programming Language](https://docs.modular.com/mojo/) - Chris Lattner's MLIR-native systems language for AI workloads; compiles to GPUs, TPUs, ASICs
- [Zig Self-Hosted x86_64 Backend (2025)](https://ziglang.org/devlog/2025/) - Native x86 backend passes more tests than LLVM backend; incremental compilation approaching default-on

### Operating Systems & Formal Verification (New)
- [Asterinas: Linux ABI-Compatible Rust-Based Framekernel OS (USENIX ATC 2025)](https://github.com/asterinas/asterinas) - Confines unsafe Rust to ~14% of codebase; supports 210+ Linux syscalls with performance on par with Linux
- [Verus: Practical Foundation for Systems Verification (SOSP 2024)](https://github.com/verus-lang/verus) - Verification for Rust code 3-61x faster than prior art; case studies in distributed systems, OS, storage
- [Atmosphere: Practical Verified Kernels with Rust and Verus (SOSP 2025)](https://dl.acm.org/doi/10.1145/3731569.3764821) - L4-style microkernel verified in Rust/Verus with 7.5:1 proof-to-code ratio in ~2 person-years
- [Mathematics in Lean (Lean 4 / Mathlib)](https://leanprover-community.github.io/mathematics_in_lean/) - Interactive textbook for formalizing mathematics in Lean 4 using Mathlib (210,000+ theorems)

### Security, Fuzzing & Reverse Engineering (New)
- [Rust-for-Linux: Success, Dissatisfaction, and Compromise (USENIX ATC 2024)](https://www.usenix.org/system/files/atc24-li-hongyu.pdf) - Examines 240 driver vulnerabilities and evaluates Rust's actual safety impact in the Linux kernel
- [MOCK: Optimizing Kernel Fuzzing Mutation with Context-aware Dependency (NDSS 2024)](https://www.ndss-symposium.org/wp-content/uploads/2024-131-paper.pdf) - Context-aware syscall mutation achieving 32% branch coverage growth over state-of-the-art
- [LLM4Decompile: Decompiling Binary Code with LLMs (2024)](https://github.com/albertan017/LLM4Decompile) - Open-source LLM (1.3B-33B) for binary decompilation outperforming GPT-4o and Ghidra by 100%+ on re-executability

### AI/ML Systems (New)
- [FlashAttention-3: Fast Attention with Asynchrony and Low-precision (NeurIPS 2024 Spotlight)](https://arxiv.org/abs/2407.08608) - Exploits Hopper GPU asynchrony and FP8; 1.5-2.0x faster than FlashAttention-2 on H100
- [SGLang: Efficient Execution of Structured LM Programs (2024)](https://arxiv.org/abs/2312.07104) - RadixAttention for KV cache reuse and compressed FSMs for constrained decoding; up to 5x throughput vs vLLM
- [DSPy: Compiling Declarative LM Calls into Self-Improving Pipelines (ICLR 2024)](https://github.com/stanfordnlp/dspy) - Stanford framework for programming LLMs with automatic prompt/weight optimization
- [Towards Efficient Generative LLM Serving: A Survey (ACM Computing Surveys, 2025)](https://dl.acm.org/doi/10.1145/3754448) - Comprehensive survey covering decoding, quantization, parallelism, memory, and scheduling

### WebAssembly (New)
- [WASI 0.2 and the WebAssembly Component Model (2024)](https://component-model.bytecodealliance.org/) - Stable release with Component Model for CLI, sockets, clocks; WASI 0.3 adds native async

### Mathematics (New)
- [Math for Programming - Ronald T. Kneusel (No Starch Press, 2025)](https://nostarch.com/math-programming) - Vectors/matrices, calculus for optimization, graph theory, probability with algorithm applications
- [Formalising Mathematics 2024 - Kevin Buzzard (Imperial College, Lean 4)](https://github.com/ImperialCollegeLondon/formalising-mathematics-2024) - Full course on formalizing math in Lean 4 with Mathlib exercises and projects
