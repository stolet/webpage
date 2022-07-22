+++
description = "Home"
aliases = ["home"]
author = "Matheus Stolet"
+++

# Bio

I am a PhD student at MPI-SWS, where I am advised by [Antoine Kaufmann](https://people.mpi-sws.org/~antoinek/index.html) and investigate TCP kernel bypass and ways to free server CPUs from the burden of TCP packet processing. I also work with [Jonathan Mace](https://people.mpi-sws.org/~jcmace/) with whom I have explored reinforcement learning techniques to improve scheduling of requests for machine learning inference. 

Previously, I was a MSc student in the [Systopia Lab](https://systopia.cs.ubc.ca/) at the University of British Columbia, under the supervision of Ivan Beschastnikh[](https://www.cs.ubc.ca/~bestchai/) and [Aline Talhouk](http://alinetalhouk.com/). At UBC my interests revolved around building secure and privacy-preserving distributed systems, where I collaborated closely with [Mathias Lécuyer](http://mathias.lecuyer.me/) on exploring novel ways for DP systems to conserve their privacy budget.

---

# Education

:mortar_board: **PhD: Computer Science - 2021-Present**

*Max Planck Institute for Software Systems*

:mortar_board: **MSc: Computer Science - 2019-2021**

*University of British Columbia*

:mortar_board: **BA: Major, Computer Science | Minor, Philosophy - 2015-2019**

*University of British Columbia*

---

# Projects

### [LEAP](https://github.com/leap-project/leap) :frog:

LEAP is a large-scale federated and privacy preserving evaluation and analysis platform. LEAP allows users to analyze data distributed across multiple institutions in a private and secure manner, without leaking sensitive user information. This is achieved through an infrastructure that maintains privacy by design and brings the computation to the data, instead of bringing the data to the computation.

User queries are propagated to different sites, where each site gives back the result of running the computation on the local data, with carefully added noise to guarantee differential privacy. These results are then returned to the LEAP infrastructure in the cloud, where they are aggregated and sent to the end-user. The infrastructure also keeps track of the privacy loss from each query, safeguarding against information leakage from repeated queries.

### [TraVista](https://github.com/vaastav/TraViz) :milky_way:

Performance issues in cloud systems are hard to debug. Distributed tracing is a widely adopted approach that gives engineers visibility into cloud systems. Existing tracing tools support the analysis of a single request and are most useful for debugging correctness issues. However, diagnosing performance issues in the processing of a request requires comparing the performance statistics of the offending request with those of normal requests. This processing depends on trace aggregation, which is not supported by existing tracing tools.

TraVista is a tool designed for debugging latency issues in cloud systems. It helps developers identify the correct aggregate data for diagnosis and effectively visualizes the data, so that performance issues can be identified. Our tool aggregates four types of data: metrics, logs, temporal and structural data and uses an array of visualization techniques to reduce cognitive load and help developers more efficiently find issues with their systems.

### [Finesse](https://github.com/fsgeek/finesse) ::chart_with_downwards_trend:

Developing kernel file systems presents challenges due to the complexity of the environment. The inflexibility of this environment discourages exploration of alternatives; most file systems research is focused on improving the storage management aspects, rather than the application facing interfaces. While userspace file systems mitigate the development complexity, they do so with a significant performance penalty and little flexibility for exploring novel access models. Finesse addresses these two concerns by adding both a client side library and a FUSE file system library. Finesse implements a kernel bypass mechanism for key operations and enables making new interfaces available to applications, thus improving performance while balancing compatibility against flexibility.

### [Biscotti](https://github.com/DistributedML/Biscotti) :cookie:

Federated Learning is the current state of the art in supporting secure multi-party machine learning: data is maintained on the owner’s device and the updates to the model are aggregated through a secure protocol. However, this process assumes a trusted centralized infrastructure for coordination, and clients must trust that the central service does not use the byproducts of client data.  In addition to this, a group of malicious clients could also harm the performance of the model by carrying out a poisoning attack. Biscotti is a fully  decentralized peer to peer (P2P) approach to multi-party ML, which uses blockchain and cryptographic primitives to coordinate a privacy-preserving ML process between peering clients.

---

# Experience

#### Graduate Teaching Assistant - UBC
##### *January 2020 - May 2020*

* Helped students with topics such as distributed system design, replication, and failure recovery

* Responded student questions on an online discussion board

* Coordinated grading and assignment ideas with the course team

#### Research Assistant - UBC
##### *May 2019 - August 2019*

* Developed a data analytics platform to perform distributed queries in hospitals and research centres

* Used differentially private techniques to prevent information leakage from distributed queries

* Presented the work  on seminars at UBC and BC Cancer Research Centre

#### Undergraduate Teaching Assistant - UBC
##### *September 2018 - December 2018*

* Conducted tutorials on network infrastructure, packet routing, and communication protocols

* Held office hours to help students with assignments and lecture material

* Graded assignments and quizzes

#### Software Developer - Thrive Health
##### *May 2018 - August 2018*

* Worked on program to triage patients before surgery

* Used React and Redux to build webapp frontend

* Developed a media transcoder to convert videos into mp4 and to extract thumbnail from pictures

* Used AWS lambdas and SQS to scale deployment of media transcoder

---

# Posters and Publications

### [The Odd One Out: Energy is not like Other Metrics](https://hotcarbon.org/pdf/hotcarbon22-anand.pdf)
**HotCarbon 22**

***Vaastv Anand, Zhiqiang Xie, Matheus Stolet, Roberta De Viti, Thomas Davidson, Reyhaneh Karimipour, Jonathan Mace***

### [Finesse: Kernel Bypass for File Systems](https://www.eurosys2020.org/wp-content/uploads/2020/04/eurosys20posters-final100-abstract.pdf) (Poster)
**European Conference on Computer Systems (EuroSys' 20)**

***Matheus Stolet and Tony Mason***
