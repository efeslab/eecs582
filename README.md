# EECS 582: Advanced Operating Systems

## Announcements

|Date| Note|
| :- | :- |
|**01/06**|<p>- Fill in [the EECS 582 Student Information form](https://docs.google.com/forms/d/e/1FAIpQLSeNnGuJ6VbzVFS5LENLEjo_bG5O10PNMVigqCFtkF1HxyQAxQ/viewform?usp=sf_link)</p><p>- You will receive an invitation to join the 582 slack channel after creating an account on the paper-review website (see the “Paper reviews” below)</p><p>- Final paper templates: <https://www.usenix.org/conferences/author-resources/paper-templates></p>|
|**01/11**|- You can use [this document](https://docs.google.com/document/d/1sRoTSKAlXwpV6KzaxUQbJbTxPwrHfn9-RCUw_Pp31r4/edit?usp=sharing) to discuss your background and interests (with the ultimate goal of finding some team members!)|


## Administrivia

### Course Info

|**Course**|EECS 582, Winter 2022, 4 credits |
| :- | :- |
|**Meetings**|<p>1010 DOW T/Th: 12:00–1:30 PM (Lectures/Discussion, for the first 3 lectures, rest will be presentations)</p><p>(When we do meet on Fridays, it will be at 3150 DOW, 1:30–2:30PM)</p>|
|**Instructors**|Tanvir Ahmed Khan, Ian Neal |
|**GSI**|Gefei Zuo|
|**Contact**|<eecs582-staff@umich.edu>|
|**Office hours**|Zoom, by appointment only|
|**Paper reviews**|<p><https://eecs582.eecs.umich.edu/papers/> **(Create an account ASAP!)**</p><p>To submit a review after logging in, click “start new paper” and enter the title of the paper. Attach your review as a PDF file according to the [format](https://gist.github.com/kasikci/49e7107dfdee281d6f6450b132555550) (there are a variety of tools to convert markdown to PDF). Put your name and your umich email as the author. Affiliation and abstract don’t matter.</p>|
|**Recordings**|Course lectures may be audio/video recorded and made available to other students in this course. As part of your participation in this course, you may be recorded.|

### Grading

| Paper Reviews                                         | 20% |
| :- | :- |
|**Presentations (paper presentations + midterm + final)**|**15%**|
|**Class Participation**|**10%**|
|**Project (prototype)**|**45%**|
|**Project (final paper)**|**10%**|


- Paper Reviews: You can miss 4 reviews with no penalty. Afterwards, each miss beyond that will result in 25% decrease (i.e., 5% out of the 20% alloted for the Paper Reviews component) in grade for this portion of the course. Missing eight or more paper reviews will result in getting 0% out of the 20% possible for the Paper Reviews component.
- See the first set of lecture slides (link coming soon) for more details


### Project Milestones

|     Date             |     Milestone                             |     Details                                                                                         |
|----------------------|-------------------------------------------|-----------------------------------------------------------------------------------------------------|
|     Jan   11/ASAP    |     Find   project partners               |     Find   2-3 like-minded students                                                                 |
|     Jan   13         |     Contact   project supervisor/staff    |     Email   the supervising PhD students OR   email EECS 582 staff with your group’s proposal       |
|     Jan   21         |     Finalize   deliverables               |     After   regular back-and-forth   discussions with the project supervisors                       |
|     Feb   22–25      |     Mid-semester   presentations          |     Define and motivate the problem, survey   related work, and form initial hypothesis and idea    |
|     Apr   19         |     Video   presentations                 |     Record   a presentation of your findings                                                        |
|     Apr   28         |     Research   paper                      |     Submit a project paper like the ones   we’ve read                                               |

## Schedule

The papers due for a review are marked with an **(R**)**.** Here is the review [template](https://gist.github.com/kasikci/49e7107dfdee281d6f6450b132555550) we will use. 



|**Date**|**Topic**|**Required Material**|**Optional Material**|
| :- | :- | :- | :- |
|<p>Jan 6 [Th]</p><p>(slides)</p>|<p>**Welcome to EECS 582 - Introductions**</p><p></p>|<p>[You and Your Research](https://www.youtube.com/watch?v=a1zDuOPkMSw)</p><p>[Strong Inference](http://pages.cs.wisc.edu/~markhill/science64_strong_inference.pdf)</p><p>[The Many Faces of System Research](https://www.usenix.org/legacy/event/hotos05/final_papers_backup/red_team/red_html/paper.html)</p>|<p>[The Night Watch](https://www.usenix.org/system/files/1311_05-08_mickens.pdf)</p><p>[Doing a Systems PhD](https://docs.google.com/presentation/d/1em55Tcl1XZAO0dSOe7FnsqlPPss16mXoU0CFUo3CtUQ/edit?usp=sharing)</p><p>[The Scientific Method](https://www.youtube.com/watch?v=0KmimDq4cSU)</p>|
|Jan 7 [F]|No class|<p>***Select papers to present***</p><p>[How to Read a Paper?](https://www.albany.edu/spatial/WebsiteFiles/ResearchAdvices/how-to-read-a-paper.pdf)</p><p>[Writing Systems Conference Reviews](https://people.inf.ethz.ch/troscoe/pubs/review-writing.pdf)</p>|<p>[Reading & Evaluating Papers](http://www.cs.kent.edu/~jmaletic/howtoread.html)</p><p>[Task of the referee](https://www.cs.utexas.edu/users/mckinley/notes/reviewing-smith.pdf)</p><p></p>|
|<p>Jan 11 [T]</p><p>(slides)</p>|<p>System Design</p><p></p>|<p>***Find project partners***</p><p>[Hints for Computer System Design](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/acrobat-17.pdf)</p><p>[Updated Hints for Computer System Design](https://www.youtube.com/watch?v=TRLJ6XdmgnA)</p>|[Updated Hints Paper](https://arxiv.org/abs/2011.02455)|
|<p>Jan 13 [Th]</p><p>(slides)</p>|<p>Tackling</p><p>Complexity</p><p></p>|<p>***Pick projects and get in touch with your contact students and us (through email)***</p><p>[Design Philosophy of DARPA Internet Protocols](http://ccr.sigcomm.org/archive/1995/jan95/ccr-9501-clark.pdf)</p><p>[End to End Arguments in System Design](http://web.mit.edu/Saltzer/www/publications/endtoend/endtoend.pdf) **(R)**</p>|[The Architecture of Complexity](https://www.cc.gatech.edu/classes/AY2013/cs7601_spring/papers/Simon-Complexity.pdf)|
|<p>Jan 14 [F] </p><p></p>|No class|<p>[How to Give a Bad Talk?](https://people.eecs.berkeley.edu/~pattrsn/talks/BadTalk.pdf)</p><p>[How to Give a Great Talk?](https://www.youtube.com/watch?v=sT_-owjKIbA)</p><p>[A good conference talk](https://www.youtube.com/watch?v=jE0V-p1odPg)</p>|[How to Give a Technical Talk?](https://homes.cs.washington.edu/~mernst/advice/giving-talk.html)|
|Jan 18 [T]|<p>Kernels</p><p></p>|<p>***Presentations begin***</p><p>[The Unix Timesharing System](https://people.eecs.berkeley.edu/~brewer/cs262/unix.pdf) </p><p>[Exokernel](https://pdos.csail.mit.edu/6.828/2016/readings/engler95exokernel.pdf) **(R)**</p>|<p>[THE](https://klevas.mif.vu.lt/~liutauras/books/Dijkstra%20-%20The%20structure%20of%20the%20THE%20multiprogramming%20system.pdf)</p><p>[The Unix Operating System](https://www.youtube.com/watch?v=tc4ROCJYbm0&t=1s)</p><p>[Pilot Operating System](https://pdfs.semanticscholar.org/adc0/5b35955558934a1d200d6ed71ac378574ff3.pdf)</p><p>[Tannenbaum-Torvalds Debate](https://en.wikipedia.org/wiki/Tanenbaum%E2%80%93Torvalds_debate)</p><p>[Threads and Input/Output in the Synthesis Kernel](https://www.researchgate.net/profile/Calton-Pu-2/publication/2687881_Threads_and_InputOutput_in_the_Synthesis_Kernel/links/54d249980cf2b0c614692038/Threads-and-Input-Output-in-the-Synthesis-Kernel.pdf)</p>|
|<p>Jan 20 [Th]</p><p></p>|<p>Naming</p><p></p>|<p>[Development of the DNS](https://courses.cs.washington.edu/courses/cse551/09sp/papers/dns.pdf)</p><p>[Designing a Global Name System](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/acrobat-15.pdf) **(R)** </p>|[Practical Naming Examples](https://www.youtube.com/watch?v=zm2VP0kHl1M&ab_channel=MITOpenCourseWare)|
|Jan 21 [F]|<p>No class</p><p></p>|<p>***Submit deliverables for the project (forms the basis of your grade)***</p><p>[How to Write a Great Research paper?](https://www.youtube.com/watch?v=VK51E3gHENc)</p><p>[How to Write a Good Systems Paper?](https://www.usenix.org/legacy/publications/library/proceedings/dsl97/good_paper.html)</p>|[The Elements of Style](https://www.amazon.com/Elements-Style-William-Strunk-Jr/dp/194564401X)|
|Jan 25 [T]|<p>Locality</p><p></p>|<p>[The Locality Principle](http://denninginstitute.com/pjd/PUBS/CACMcols/cacmJul05.pdf)  **(R)**</p><p>[Optimizations for Improving Data Locality](http://www.cs.utexas.edu/users/mckinley/papers/asplos-1994.pdf)</p>|[Numbers you should know ](https://people.eecs.berkeley.edu/~rcs/research/interactive_latency.html)|
|Jan 27 [Th]|<p>Performance</p><p></p>|<p>[AutoFDO](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45290.pdf) **(R)**</p><p>[NVBit](https://github.com/NVlabs/NVBit/releases/download/v1.0/MICRO_19_NVBit.pdf)</p>|[Google-Wide Profiling](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/36575.pdf)|
|Jan 28 [F]|No class||[DTrace](http://www.brendangregg.com/dtrace.html)|
|Feb 1 [T]|<p>Virtualization</p><p></p>|<p>[Formal Requirements for Virtualization](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.141.4815&rep=rep1&type=pdf)</p><p>[Xen and the Art of Virtualization](https://www.cl.cam.ac.uk/research/srg/netos/papers/2003-xensosp.pdf) **(R)** </p>|[Disco](http://pages.cs.wisc.edu/~remzi/Classes/838/Spring2013/Papers/bugnion97disco.pdf)|
|Feb 3 [Th]|<p>Lightweight</p><p>Virtualization</p>|<p>[Resource Containers](http://www.scs.stanford.edu/nyu/03sp/sched/resource.pdf)</p><p>[IX](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-belay.pdf) **(R)**</p>|[Arrakis](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-peter_simon.pdf)|
|Feb 4 [F]|No class|||
|Feb 8 [T]|<p>Security-1</p><p></p>|<p>[How Diffie Hellman Fails In Practice](https://weakdh.org/imperfect-forward-secrecy-ccs15.pdf) **(R)**</p><p>[Control Flow Integrity](https://users.soe.ucsc.edu/~abadi/Papers/cfi-tissec-revised.pdf) </p>|[17 Mistakes Microsoft Made in the Xbox Security System](https://kapravelos.com/teaching/csc405-s17/readings/xbox-security.pdf)|
|Feb 10 [Th]|Security-2|<p>[Spectre](https://spectreattack.com/spectre.pdf) **(R)**</p><p>[Systematic Evaluation of Transient Execution Attacks and Defenses](https://www.usenix.org/system/files/sec19-canella.pdf)</p>|<p>[Foreshadow](https://foreshadowattack.eu/foreshadow.pdf)</p><p>[A Note on the Confinement Problem](https://www.cs.utexas.edu/~shmat/courses/cs380s_fall09/lampson73.pdf)</p>|
|Feb 11 [F]|No class|***Work on projects***||
|Feb 15 [T]|<p>Debugging</p><p></p>|<p>[Delta Debugging](https://www.st.cs.uni-saarland.de/publications/files/zeller-esec-1999.pdf)</p><p>[Magpie](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/magpie-osdi.pdf) **(R)**</p>|<p>[Paxos](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf)</p><p>[Paxos for Human Beings](http://web.eecs.umich.edu/~barisk/teaching/eecs582/paxos-for-humans.pdf)</p>|
|Feb 17 [Th]|<p>Fault</p><p>Tolerance</p>|<p>[Microreboot](https://www.usenix.org/legacy/event/osdi04/tech/full_papers/candea/candea.pdf) **(R)**</p><p>[Byzantine Fault Tolerance](https://people.csail.mit.edu/alinush/6.824-spring-2015/papers/pbft.pdf)</p>|[Error-free Multi-Valued Consensus](http://disc.ece.illinois.edu/publications/guanfeng-PODC2011.pdf)|
|Feb 18 [F]|No class|***Work on Projects***||
|Feb 22 [T]|<p>Projects</p><p></p>|***Mid-term Presentations***||
|Feb 24 [Th]|Projects|***Mid-term Presentations***||
|Feb 25 [F]|Projects|***Mid-term Presentations (3150 DOW)***||
|Mar 1 [T]|No class|***Break***||
|Mar 3 [Th]|No class|***Break***||
|Mar 4 [F]|No class|***Break***||
|Mar 8 [T]|Failures|<p>[REPT](https://www.usenix.org/conference/osdi18/presentation/weidong) **(R)**</p><p>[Bugs as Deviant Behavior](https://web.stanford.edu/~engler/deviant-sosp-01.pdf)</p>||
|Mar 10 [Th]|<p>Datacenter</p><p>Systems - 1</p>|<p>[MapReduce](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf) **(R)**</p><p>[Google File System](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)</p>|<p>[Log-Structured File System](http://pages.cs.wisc.edu/~remzi/OSTEP/file-lfs.pdf)</p><p>[Redbook](http://www.redbook.io/)</p>|
|Mar 11 [F]|No class|***Work on projects***||
|Mar 15 [T]|<p>Datacenter</p><p>Systems - 2</p>|<p>[Hive](http://infolab.stanford.edu/~ragho/hive-icde2010.pdf)</p><p>[Spanner](https://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf) **(R)**</p>|<p>[The Google File System](https://www.cs.ucdavis.edu/~wu/ecs251/ecs251_GFS_sosp2003.pdf)</p><p>[GFS: An Evolution on Fast-Forward](http://queue.acm.org/detail.cfm?id=1594206)</p>|
|Mar 17 [Th]|<p>Datacenter</p><p>Systems - 3</p>|<p>[Big Table](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf) **(R)**</p><p>[Canopy: An End-to-End Performance Tracing And Analysis System](http://static.cs.brown.edu/people/jcmace/papers/kaldor2017canopy.pdf)</p>|<p>[TAO: Facebook’s Distributed Data Store for the Social Graph](https://www.usenix.org/system/files/conference/atc13/atc13-bronson.pdf)</p><p>[Segcache: a memory-efficient and scalable in-memory key-value cache for small objects](https://www.pdl.cmu.edu/PDL-FTP/Storage/NSDI21_segcache.pdf)</p>|
|Mar 18 [F]|No class|***Work on projects***||
|Mar 22 [T]|<p>Testing and</p><p>Verification - 1</p>|<p>[Klee](https://llvm.org/pubs/2008-12-OSDI-KLEE.pdf) **(R)**</p><p>[Sel4: Formal verification of an OS Kernel](https://www.sigops.org/sosp/sosp09/papers/klein-sosp09.pdf) </p><p></p>|<p>[Therac 25: An engineering Disaster](http://www.bowdoin.edu/~allen/courses/cs260/readings/therac.pdf)</p><p>[Northeastern Blackout](https://en.wikipedia.org/wiki/Northeast_blackout_of_2003)</p><p>[A Few Billion LOC Later](https://web.stanford.edu/~engler/BLOC-coverity.pdf)</p>|
|Mar 24 [Th]|<p>Testing and</p><p>Verification - 2</p>|<p>[Jaaru: Efficiently Model Checking Persistent Memory Programs](http://web.cs.ucla.edu/~harryxu/papers/jaaru-asplos21.pdf)</p><p>[Agamotto: How Persistent is your Persistent Memory Application?](https://www.usenix.org/conference/osdi20/presentation/neal) **(R)**</p>|<p>[Cross-Failure Bug Detection in Persistent Memory Programs](https://www.cs.virginia.edu/~smk9u/liu_xfd_asplos2020.pdf)</p><p>[Witcher: Systematic Crash Consistency Testing for Non-Volatile Memory Key-Value Stores](https://cosmoss-vt.github.io/pages/pubs/witcher-fu-sosp21.pdf)</p>|
|Mar 25 [F]|No class|***Work on projects***||
|Mar 29 [T]|<p>Machine</p><p>Learning</p><p>Systems</p>|<p>[T](https://ai.google/research/pubs/pub45381)[ensorFlow](https://ai.google/research/pubs/pub45381) **(R)**</p><p></p><p>[Ray: A Distributed Framework for Emerging AI Applications](https://www.usenix.org/system/files/osdi18-moritz.pdf)</p>|<p>[Machines That Think?](https://www.edge.org/response-detail/26200)</p><p>[The Great AI Awakening](https://www.nytimes.com/2016/12/14/magazine/the-great-ai-awakening.html)</p><p>[On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](https://dl-acm-org.proxy.lib.umich.edu/doi/pdf/10.1145/3442188.3445922)</p>|
|Mar 31 [Th]|Rethinking the OS Design|<p>[Barrelfish](https://people.inf.ethz.ch/troscoe/pubs/sosp09-barrelfish.pdf) **(R)**</p><p>[Linux Scalability](https://pdos.csail.mit.edu/papers/linux:osdi10.pdf) </p>|[Scalable Commutativity Rule](https://people.csail.mit.edu/nickolai/papers/clements-sc.pdf)|
|Apr 1 [F]|No class|***Work on projects and final paper***||
|Apr 5 [T]|<p>Heterogeneous</p><p>Systems</p>|<p>[Cascade](https://cs.stanford.edu/people/eschkufz/docs/asplos_19.pdf) **(R)**</p><p>[FIRRTL](https://aspire.eecs.berkeley.edu/wp/wp-content/uploads/2017/11/Reusability-is-FIRRTL-Ground-Izraelevitz.pdf)</p>|[Popcorn](http://www.ssrg.ece.vt.edu/papers/eurosys15.pdf)|
|Apr 7 [Th]|Concurrency|<p>[Lamport Clocks](https://amturing.acm.org/p558-lamport.pdf)</p><p>[Learning From Mistakes](https://www.cs.columbia.edu/~junfeng/09fa-e6998/papers/concurrency-bugs.pdf) **(R)**</p>|[The Problem with Threads](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2006/EECS-2006-1.pdf)|
|Apr 8 [F]|No class|***Work on projects and final paper***||
|Apr 12 [T]|<p>Atomicity &</p><p>Consistency</p>|<p>***Last (scheduled) day of class***</p><p>[Dynamo](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf) **(R)**</p><p>[Optimistic Concurrency Control](https://www.eecs.harvard.edu/~htk/publication/1981-tods-kung-robinson.pdf)</p>|<p>[CAP Theorem](https://pdfs.semanticscholar.org/5015/8bc1a8a67295ab7bce0550886a9859000dc2.pdf)</p><p>[CAP Theorem Twelve Years Later](https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed)</p>|
|Apr 14 [Th]|Flex Day|Catch-up if needed||
|Apr 15 [F]|No class|***Work on projects and final paper***||
|Apr 19 [T]|Flex Day|<p></p><p>Catch-up if needed</p>||
|Apr 28 [Th]|**Final Paper Due**|
