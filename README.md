# Awesome-Mainframe-Migration-Modernization

## Top Mainframe Migration & Modernization Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Mainframe Migration, Code Refactoring & Self-Hosted Modernization Tools*  

**Last updated: October 2026**



This repository tracks notable **commercial mainframe modernization platforms** and **open-source projects** that help organizations migrate, refactor, or rehost legacy mainframe applications (COBOL, PL/I, Assembler, JCL) to modern cloud and distributed platforms.



**Examples** include AWS Mainframe Modernization, Micro Focus (OpenText), Google Cloud Dual Run, Microsoft Azure Mainframe Modernization, TSRI, Astadia, LzLabs, Blu Age, Advanced (Modern Systems), and CloudFrame (the category leaders).



**Open-source emphasis**: Mainframe modernization is anchored by **GnuCOBOL** as the most complete open-source COBOL compiler , with **z390** and **Hercules** providing portable mainframe emulation for testing and development . **mainframe-migration-toolkit** brings specification-led COBOL and JCL migration to PySpark . **QWICS** demonstrates a hybrid approach to rehosting transactional COBOL in Java EE using entirely open-source components . **GnuCOBOL-based testing frameworks** and **REXX interpreters** round out the ecosystem. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Mainframe Modernization](https://aws.amazon.com/mainframe-modernization/)**  

  **AWS's mainframe modernization service** — provides tools for analyzing, developing, and deploying mainframe applications on AWS managed runtimes . **Supports automated refactoring (Blu Age) and replatforming (Micro Focus/Rocket Software)** . **Note**: The managed runtime experience is **no longer open to new customers** as of November 7, 2025; the self-managed experience remains available . **Best for AWS-native mainframe migrations** .



- **[Micro Focus (OpenText) Enterprise Suite](https://www.microfocus.com/)**  

  **The enterprise standard for COBOL and PL/I modernization** — comprehensive analysis, development, test, and deployment solutions for IBM mainframe applications . **Supports deployment across mainframe, Linux, virtual, Docker, and cloud platforms** — the same application workload can run on host or cloud without rewrite . **Banca Popolare di Sondrio boosted developer productivity by 20%** using the solution . **Best for enterprises wanting to preserve COBOL investments while modernizing infrastructure** .



- **[Google Cloud Dual Run](https://cloud.google.com/mainframe-dual-run)**  

  **Google's mainframe modernization testing platform** — runs workloads simultaneously on existing mainframes and Google Cloud to compare behavior . **Enables real-time testing and rapid collection of performance and stability data** . **Best for risk-managed incremental migration** .



- **[Microsoft Azure Mainframe Modernization](https://azure.microsoft.com/en-us/solutions/mainframe-modernization/)**  

  **Microsoft's mainframe migration solutions** — supports rehosting, refactoring, and replatforming to Azure . **Raincode IMSql** rehosts IMS DB/DC applications on Azure with SQL Server as the hierarchical data store . **Best for Azure-native mainframe migrations** .



- **[TSRI (JANUS Studio)](https://tsri.com/)**  

  **AI-driven application modernization platform** — pairs deterministic AI with GenAI for 99.9X% automated conversion . **Supports 35+ legacy and modern languages** including COBOL, PL/I, Assembler, and more . **Named 2026 ISG Leader in Mainframe Modernization** . **Delivers cloud-ready code with code warranty and no license fees** . **Best for high-fidelity automated refactoring** .



- **[Astadia (Amdocs)](https://www.astadia.com/)**  

  **Mainframe migration factory and methodology** — automates code and data transformation with functional equivalence testing . **Tooling includes CodeTurn, DataTurn, TestMatch, and DataMatch** . **Migrated a global flooring manufacturer's 10+ million lines of COBOL to Azure with full functional equivalency** . **Best for large-scale automated migrations** .



- **[LzLabs](https://www.lzlabs.com/)**  

  **Software Defined Mainframe (SDM) platform** — enables incremental application-by-application migration . **Applications run natively in the SDM without rewriting** — preserves existing code and data . **Achieves up to 60% OpEx savings** with concurrent operation during migration . **Best for gradual, low-risk mainframe exit** .



- **[CloudFrame Continuum](https://cloudframe.com/)**  

  **Runtime-truth based modernization platform** — runs code first to capture actual execution behavior, then transforms with verified accuracy . **Three outcomes: Optimize (reduce MIPS in place), Run (lift to cloud), Modernize (convert to Java)** . **Savings can reach 80% or higher** on the Run path . **Best for evidence-based, auditable code transformation** .



- **[Advanced (Modern Systems)](https://modernsystems.oneadvanced.com/)**  

  **Automated refactoring and migration services** — converted The New York Times' mainframe to AWS with full functional equivalence . **Migrated COBOL to Java, VSAM to Oracle, CICS to Jetty/Apache-CXF, and JCL to Spring Batch** . **Best for proof-of-concept and pilot migrations** .



## Open-Source GitHub Projects



### COBOL Compilers & Runtimes



- **[GnuCOBOL](https://github.com/GnuCOBOL/gnucobol)**  

  **The most complete and mature open-source COBOL compiler**, GPL-3.0 licensed with **1,500+ GitHub stars** . **COBOL frontend to the GNU C compiler** — translates COBOL to C, then compiles with gcc for high optimization . **Supports the same target architectures as gcc** — including mainframe Linux . **The foundation for open-source mainframe modernization** . **Best for compiling and testing COBOL applications** .



- **[z390](https://github.com/z390development/z390)**  

  **Portable mainframe assembler and emulator project**, open-source with **39 GitHub stars** . **Provides a complete mainframe development environment** for Assembler and COBOL . **Includes emulator, assembler, linker, and runtime libraries** . **Best for mainframe assembly development and testing** .



### Mainframe Emulation & Testing



- **[Hercules](https://github.com/hercules-390/hyperion)**  

  **The main repository for the Aethra version of the Hercules emulator for IBM mainframes**, open-source with **22 GitHub stars** . **Emulates IBM System/370, ESA/390, and z/Architecture** . **Runs mainframe operating systems including z/OS, z/VM, and z/VSE** . **Best for mainframe emulation and testing** .



- **[mainframe-migration-toolkit](https://pypi.org/project/mainframe-migration-toolkit/)**  

  **Python tools and runtime support for specification-led COBOL and JCL migrations to PySpark**, open-source . **Initializes isolated migration workspaces, parses JCL and copybooks, converts sequential datasets, scaffolds PySpark jobs, and validates output against golden datasets** . **Supports Claude Code and Devin agent orchestration** . **Best for modernizing batch COBOL to PySpark** .



- **[QWICS (Quick Web-Based Interactive COBOL Service)](https://github.com/pbrune1973/qwics)**  

  **Open-source architecture for rehosting transactional COBOL in Java EE**, open-source . **Uses only open-source components**: GnuCOBOL, PostgreSQL, JBoss WildFly, and custom glue components . **Integrates COBOL programs as part of JTA transactions** — no proprietary TPM middleware required . **Supports mainframe-to-mainframe rehosting (e.g., to Linux)** . **Best for open-source COBOL rehosting** .



### Mainframe Development & Testing Tools



- **[Cobol Check](https://github.com/openmainframeproject/cobol-check)**  

  **Testing framework for COBOL applications**, open-source with **80 GitHub stars** . **Unit testing framework specifically for COBOL** . **Best for COBOL unit testing** .



- **[JCL Parser](https://github.com/openmainframeproject)** — JCL parsing tools for migration and testing .



- **[Mainframe Disassembler in REXX](https://github.com/openmainframeproject)**  

  **Mainframe disassembler written in REXX**, open-source . **Useful for sites that have lost source code to important executables** . **Best for reverse-engineering legacy code** .



- **[ISPF Editor Emulator](https://github.com/openmainframeproject)**  

  **Powerful editor and file manager that emulates the IBM mainframe ISPF editor**, open-source with **28 GitHub stars** . **Best for mainframe development environment simulation** .



### Additional Strong Open-Source Options



- **KICKS** — CICS replacement for MVS 3.8 and z/OS, open-source with 43 GitHub stars .

- **RAKF** — Resource Access Control Facility for MVS 3.8j, open-source .

- **Jay Moseley MVS 3.8j sysgen automation** — MVS system generation automation, 71 GitHub stars .

- **Rexx/XML** — XML parser in REXX running on mainframes and distributed systems .

- **Awesome Mainframe** — Curated list of mainframe resources and projects, 79 GitHub stars .

- **Tn3270 to Z Python library** — Python TN3270 library, 57 GitHub stars .

- **c3270 Web frontend** — Web frontend for c3270 terminal emulator .



**Frameworks for building custom mainframe modernization solutions**: Combine **GnuCOBOL** for open-source COBOL compilation and testing . Use **z390** and **Hercules** for mainframe emulation during development and migration validation . Deploy **mainframe-migration-toolkit** for specification-led COBOL-to-PySpark migrations . Choose **QWICS** for rehosting transactional COBOL in Java EE with only open-source components . Integrate **Cobol Check** for unit testing. Note that true enterprise mainframe modernization with automated refactoring, functional equivalence guarantees, and large-scale migration factory capabilities (AWS Mainframe Modernization, TSRI, Astadia, LzLabs) remains primarily commercial territory; open-source stacks provide strong compilation, emulation, and rehosting foundations that require integration for complete mainframe modernization.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Mainframe modernization involves migrating mission-critical systems that handle core business operations. **Plan for incremental migration with coexistence** — running mainframe and modernized workloads in parallel reduces risk .

- **AWS Mainframe Modernization managed runtime is no longer available to new customers** as of November 7, 2025 . The self-managed experience remains available.

- **Functional equivalence testing is critical** — allocate 70-80% of project time to testing, as demonstrated in The New York Times migration . Automated testing tools (TestMatch, DataMatch) verify behavioral and data equivalence .

- **Talent continuity is a major risk** — mainframe skills are scarce and retiring. Modernization reduces key-person dependency through cross-training and documentation .

- **License considerations**: GnuCOBOL uses GPL-3.0, z390 is open-source, Hercules is open-source, and mainframe-migration-toolkit is open-source. Verify licensing against your use case before committing .

- The open-source ecosystem provides strong compilation, emulation, and rehosting foundations, but **automated refactoring, functional equivalence guarantees, and large-scale migration factory capabilities** remain primarily commercial offerings.



---



**Made for mainframe architects, modernization engineers, and organizations seeking mainframe migration sovereignty.**

Let's make mainframe migration and modernization more open, transparent, and risk-managed.
