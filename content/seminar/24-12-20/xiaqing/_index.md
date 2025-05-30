---
title: Using Dynamically Layered Definite Releases for Verifying the RefFS File System
date: 2024-12-20
---

**Presenter**: {{% mention "Xiaqing Zhou" %}}

**Authors**: Mo Zou, Dong Du, and Mingkai Dong, Institute of Parallel and Distributed Systems, SEIEE, Shanghai Jiao Tong University; Engineering Research Center for Domain-specific Operating Systems, Ministry of Education, China; Haibo Chen, Institute of Parallel and Distributed Systems, SEIEE, Shanghai Jiao Tong University; Engineering Research Center for Domain-specific Operating Systems, Ministry of Education, China; Huawei Technologies Co. Ltd

**Abstract**: RefFS is the first concurrent file system that guarantees both liveness and safety, backed by a machine-checkable proof. Unlike earlier concurrent file systems, RefFS provably avoids termination bugs such as livelocks and deadlocks, through the dynamically layered definite releases specification. This specification enables handling of general blocking scenarios (including ad-hoc synchronization), facilitates modular reasoning for nested blocking, and eliminates the possibility of circular blocking.

The methodology underlying the aforementioned specification is integrated into a framework called MoLi (Modular Liveness Verification). This framework helps developers verify concurrent file systems. We further validate the correctness of the locking scheme for the Linux Virtual File System (VFS). Remarkably, even without conducting code proofs, we uncovered a critical flaw in a recent version of the locking scheme, which may lead to deadlocks of the entire OS (confirmed by Linux maintainers). RefFS achieves better overall performance than AtomFS, a state-of-the-art, verified concurrent file system without the liveness guarantee.

**URL**: https://www.usenix.org/conference/osdi24/presentation/zou
