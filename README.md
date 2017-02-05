## Important Links
* [Course Materials, Slides, etc](https://www.dropbox.com/sh/x9iayt9af5e6zk8/AADDNf0GNyzHkyFfSu65UL9va?dl=0)
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [Ubuntu Server](http://www.ubuntu.com/download/server)

# Syllabus
## Official Course Description
<p align="justify">
<a href="http://www.cofc.edu"><img src="http://freyja.cs.cofc.edu/cofc.sepng" height="50" align="right" hspace="10px"> </a>
This course covers basic techniques for the design and construction of distributed systems. Its aim is to give the skills needed to build simple systems and to identify key issues for the analysis of distribution problems.
</p>

## Required Text
Distributed Systems: Principles and Paradigms by Tanenbaum and van Steen - http://www.distributed-systems.net/index.php?id=distributed-systems-principles-and-paradigms

The copyright has been returned to the author, and now the book is free! You can download it using the link provided above.

AND

Distributed Algorithms: An Intuitive Approach (MIT Press) by Wan Fokkink

## Course Details

### Contact Information
* Professor: Dr. Paul Anderson
* Office: 313 HWEA
* Office Hours: My preferred method of e-contact is the Facebook group as I can respond to questions there quickly and for everyone to benefit. If you would like to use e-mail I will endeavor to respond within 24 hours.
* E-mail: andersonpe2@cofc.edu
* Office Phone: 843-953-8151
* Facebook: andersonpe2@cofc.edu

### Course (learning) outcomes
1. Learn and apply the theory of distributed systems, including architectures, processes, communication, synchronization, consistency and replication, distributed file systems, big data processing systems, distributed object-based systems, web-based systems, and coordination-based systems.

2. Implement 2 - 4 large scale distributed systems that provide solutions for problems for the following applications: big data-oriented, CPU intensive, web-based, and cloud-based.

3. Research modern distributed system problems and proposed solutions

4. Learn how to install and manage software and technology related to distributed systems.

### Grading Policy
* Exams - 40%
* Programming Assignments - 40%
* Discussions - 20%

Grading Scale: A: 90-100; B: 80-89; C: 70-79; F: <70. Plusses will be used at the discretion of the instructor.

Grading Guidelines: Submitted work requires Analysis, Evaluation, and Creation of ideas, concepts, and materials into various deliverables (e.g., see revised Bloom's Taxonomy and reference below).

* The grade of A is for work that involves high-quality achievement in all three Bloom areas.
* The grade of B is for work that involves high-quality achievement in at least two Bloom areas, and medium-level achievement in the other.
* The grade of C is for work that involves high-quality achievement in at least one Bloom area, and medium-level achievement in the others.
* The grade of F is for work that does not meet above criteria.

Reference: Errol Thompson, Andrew Luxton-Reilly, Jacqueline L. Whalley, Minjie Hu, and Phil Robbins. 2008. Bloom's taxonomy for CS assessment. In Proceedings of the tenth conference on Australasian computing education - Volume 78 (ACE '08), Simon Hamilton and Margaret Hamilton (Eds.), Vol. 78. Australian Computer Society, Inc., Darlinghurst, Australia, Australia, 155-161.

Feedback will be given as quickly as possible with a goal of within a week of the assignment due date.

### Course Structure and Philosophy

This course will be taught in roughly two modules. The first is a discussion of the principles, background, and theory of distributed systems. This will be supported by the required textbook. The second module of the course will focus on implementation. In module 1, each day will go as follows: 1. Exam over previous week's material; 2. Overview lecture on the chapter; 3. 15 - 30 minute team individual study (details below); 4. Discussion presentations to the class.

### Exams 

During the first module, exams will be given every weekly via OAKS. There is no final exam for this course. Each exam will have an OAKS portion and a take home portion. The take home portion is due a week after when it was assigned.

### Programming Assignments

Programming assignments will be assigned in module 2. They will consist of both short skill building exercises and longer more in-depth projects.

### Lectures

An overview of the content and learning outcomes will be given each week.

### Discussions

Discussions will be conducted in teams and then a summary will be presented to the entire class. Topics will be assigned at random. Team lead must rotate.

### Honor Code

You must do your work alone (or with your teammates, for group assignments).
You must identify your sources of material and inspiration. It is a violation of the honor code to present someone else's work or ideas as your own.
In any course deliverable, you must always identify the person(s) that helped you (directly or indirectly), if any, and explain their contribution to your work.
Also see the College of Charleston Student Handbook, especially sections on The Honor Code (p. 11), and Student Code of Conduct (p. 12). There is other useful information there.
Classroom Policies

No late days will be allowed without an excuse. Falling behind on assignments will make it difficult to achieve the learning outcomes of this course.

### Late Policy

No late days will be allowed without a documented excuse.

## Take Home Exam Policy
For each take home exam, you must upload your solutions to an OAKS dropbox by the due date. For each numbered portion of the assignment, you must complete the following.

https://www.dropbox.com/s/d2h2evvs3sf0nt4/exam-1.1.1.docx?dl=0

Failure to do so will result in an automatic 10% deduction from your score. Make sure you have a file for each portion of the exam. Make sure you don't deviate from the numbering scheme. All will be well :)

## Sample Schedule
(All details are subject to change)

### Week 1 (8/23)
Chapter 1 and 2

#### Group topics
1. Centralized Architectures
2. Application Layering
3. Structured Peer-to-Peer Applications
4. Unstructured Peer-to-Peer Applications
5. Hybrid Systems
6. Architectures versus Middleware
7. Self-management in distributed systems
8. Compare and contrast layered architectures, object-based architectures, data-centered architectures, and event-based architectures

[Take Home Exam 1](https://anderson-lab.github.io/take-home-exam-1-csis-604)

### Week 2 (8/30)
Chapter 3

#### Group topics
1. Traditional Threads
2. User space vs kernel vs hybrid
3. Multithreaded clients
4. Architecture of Virtual Systems
5. Servers focusing on state, stateless, etc
6. Server clusters
7. Distributed Servers: PlanetLab
8. Migration

[Take Home Exam 2](https://anderson-lab.github.io/take-home-exam-2-csis-604)

### Week 3 (9/6)
Out of town

### Week 4 (9/13)
1. Layered Protocols and OSI
2. RPC: Parameter passing
3. Asynchronous RPC
4. DCE RPC
5. MPI
6. MOM: message queuing model
7. IBM: WebSphere MQ

Chapter 4

[Take Home Exam 3](http://anderson-lab.github.io/take-home-exam-3-csis-604/)

### Week 5 (9/20)
Chapter 5

1. Flat Naming
2. Structured Naming
3. Attribute-based Naming

[Take Home Exam 4](http://anderson-lab.github.io/take-home-exam-4-csis-604/)

### Week 6 (9/27)
Chapter 6

1. Physical clocks and global positioning systems
2. NTP and Berkeley Algorithms
3. Clock synchronization in wireless networks
4. Lamport's logical clocks
5. Mututal exclusion: centralized, decentralized, and distributed
6. Election algorithms: bully and a ring algorithm

https://anderson-lab.github.io/take-home-exam-5-csis-604

### Week 7 (10/4)
Class starts at 7 PM because of JIAB

### Week 8 (10/11)
No class

### Week 9 (10/18)
Chapter 7

1. Data-centric: Continuous consistency
2. Data-centric: Sequential consistency
3. Data-centric: Causal Consistency
4. Client-centric: Eventual Consistency

Break

1. Consistency protocols: continuous consistency
2. Consistency protocols: primary based consistency
3. Consistency protocols: read-write protocols
4. Consistency protocols: Cache coherence protocols
5. Implementing client-centric consistency

### Week 10 (10/25)
Implementation 1 (http://anderson-lab.github.io/implementation-1/) - Due 11/16

Group spreadsheet: https://docs.google.com/spreadsheets/d/1QuYe_8gHuYMIhPPz_HeMeIWgFMcfU5WDWhO6bWppDMI/edit?usp=sharing

### Week 11 (11/1)
Implementation

### Week 12 (11/8)
No class. Fall break.

### Week 13 (11/15)
Implementation 2 (http://anderson-lab.github.io/csis-604-fall-2016-implementation-2/) - Due 11/23

### Week 14 (11/22)
Implementation

### Week 15 (11/29)
Implementation 3 (http://anderson-lab.github.io/csis-604-fall-2016-implementation-3/) - Due 12/7

### Week 16 (12/06)
Implementation

Extra credit: https://anderson-lab.github.io/csis-604-fall-2016-extra-credit/

### End of Semester Summary

Topics Discussed

1. Centralized Architectures
2. Application Layering
3. Structured Peer-to-Peer Applications
4. Unstructured Peer-to-Peer Applications
5. Hybrid Systems
6. Architectures versus Middleware
7. Self-management in distributed systems
8. Compare and contrast layered architectures, object-based architectures, data-centered architectures, and event-based architectures
1. Traditional Threads
2. User space vs kernel vs hybrid
3. Multithreaded clients
4. Architecture of Virtual Systems
5. Servers focusing on state, stateless, etc
6. Server clusters
7. Distributed Servers: PlanetLab
8. Migration
1. Layered Protocols and OSI
2. RPC: Parameter passing
3. Asynchronous RPC
4. DCE RPC
5. MPI
6. MOM: message queuing model
7. IBM: WebSphere MQ
1. Flat Naming
2. Structured Naming
3. Attribute-based Naming
1. Physical clocks and global positioning systems
2. NTP and Berkeley Algorithms
3. Clock synchronization in wireless networks
4. Lamport's logical clocks
5. Mututal exclusion: centralized, decentralized, and distributed
6. Election algorithms: bully and a ring algorithm
1. Data-centric: Continuous consistency
2. Data-centric: Sequential consistency
3. Data-centric: Causal Consistency
4. Client-centric: Eventual Consistency
1. Consistency protocols: continuous consistency
2. Consistency protocols: primary based consistency
3. Consistency protocols: read-write protocols
4. Consistency protocols: Cache coherence protocols
5. Implementing client-centric consistency

Implementation Experience

1. Virtual Machines
2. DHCP
3. DNS
4. Linux Command Line
5. Threads
6. Distributed Sorting
7. Queues
8. RPI
9. Hadoop
10. Distributed file systems
11. HDFS
12. Clock synchronization
13. Distributed resources/mutual exclusion
14. Distributed graph processing

# <a href="http://anderson-lab.github.io/">Anderson Data Science Research Lab</a>

<p align="justify">
<a href="http://anderson-lab.github.io/"><img src="http://freyja.cs.cofc.edu/Paul-labs-logo.png" alt="Data Science Research Lab" height="100" align="right"  hspace="10px"/></a>
The Anderson Data Science Research Lab specializes in applying data mining, machine learning, and artificial intelligence to the fields of bioinformatics, genomics, and metabolomics. We develop algorithms and software to tackle some of the most challenging and interesting data intensive problems in the life sciences. Our research interests include data science, big data, pattern analysis in high-dimensionality data sets, evolutionary computation and optimization, machine learning, computational genomics, cloud computing, computational metabolomics, and eScience. We currently have multidisciplinary projects underway in metabolomics, human cognition, toxicology, marine biology, medical genomics, biomedical informatics, and marine genomics.
</p>
