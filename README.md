# PhD Level Course on Research Directions in Post-Quantum Cryptography (DiPoQ)

Welcome to the webpage of **Research Directions in Post-Quantum Cryptography** (**ReDiPoQ**). This is a **PhD-level seminar course** designed to give participants a structured overview of the state of the art research and history of the main directions in post-quantum cryptography.

The course focuses on the mathematical foundations, implementation challenges, standardization process, and open research problems that shape modern post-quantum cryptography. 
The goal is to learn, and to teach, the core assumptions of existing post-quantum constructions, what is feasible to build from these problems, as well as iconic attack techniques, and open challenges.

The course is arranged as a series of interactive seminars. Participants work in **small groups** (2-3 people). Each group selects **two topics** from the list below, prepares educational handouts aimed at **master students in cryptography**, and leads a **2-hour interactive seminar** on the selected topics.

A good seminar explains the basic problem, the main constructions or techniques, the relevant security assumptions, known attacks or limitations, and concrete open research directions.

## Course Calendar

All seminars are *onlive* (i.e., live + online) at this
[zoom link](TODO).

## Schedule and Topics

Participants should select **two topics**. Suggestions for additional topics are welcome.

The column **Who** identifies the group in charge of the topic. Pair up with a different person for your second topic. 
A = Adrian, E = Emil, H = Lucia, L = Lucia, T = Tejas.
Due to the large body of work on LBC, I suggest 3 people there, and to compensate Shai helps with Isogenies

Date | Who | Topic (the current order is only a suggestion) | Handout
---|---|---|---
**TBD** | TBD | Lattice-based cryptography: ML-KEM / Kyber, ML-DSA / Dilithium, Falcon / FN-DSA | TBD
**TBD** | TBD | Hash-based post-quantum cryptography: SLH-DSA / SPHINCS+, XMSS, LMS | TBD
**TBD** | TBD | Code-based cryptography: Classic McEliece, BIKE, HQC | TBD
**TBD** | + S | Isogeny-based cryptography after SIDH/SIKE | TBD
**TBD** | TBD | Multivariate cryptography | TBD
**TBD** | TBD | Quantum algorithms for attacking cryptography | TBD
**TBD** | TBD | Other: e.g., post-quantum signatures from MPC-in-the-head, information-theoretic constructions | TBD
**TBD** | TBD | Crypto-agility, hybrid solutions, and migration to post-quantum cryptography | TBD


## Handout Requirements

Each handout should be self-contained and pedagogical. It should aim to explain the topic clearly rather than merely summarize papers. Think your audience to be very motivated masters students. 
A good handout should contain:

1. **Title and authors**
2. **Table of Contents**
3. **Gentle introduction and context**
4. **Math background**
5. **Assumptions/Problems definitions** (not just statements, but also intuitions)
6. **Core construction, theorem, attack, or technique**
7. **What (else) can we build from these?**
8. **Known limitations** 
9. **Open Problems**
10. **Your main take aways**
11. **List of References / Further Reading**

The handout should be written clearly, in English, in latex, typst or markdown language. Submit both source files and compiled pdf. Keep in mind that your fellow attendees (and maybe future master students) should be able to use it as study material before the seminar.


## Seminar Structure

Each seminar is led by one pair. The pair is responsible for selecting the two topics, finding suitable resources, preparing the handouts, and leading the 2-hour seminar.

The seminar should not be a conference-style talk. It should be an educational session designed to make a technically difficult area accessible to master students while still identifying the research frontier for PhD students. Some visual aids (slides / notes / displayed handouts) are recommended but not mandatory.

A suggested structure is:

1. **Motivation**: Why does this topic matter for post-quantum cryptography? Where does it excel compared to other approaches?
2. **Background**: What mathematical structures / problem does it exploit?
3. **Core ideas**: What are the main constructions, assumptions, or techniques?
4. **Security viewpoint**: What is proven, conjectured, or empirically assessed?
5. **Research frontier**: What are the main open problems?
6. **Take away points**: What are the 5 things one should remember about this topic/seminar?

## Instructions for Attendees

1. Read the handouts before the seminar.
2. Skim at least one of the suggested resources.
3. Prepare questions about unclear definitions, assumptions, proofs...
4. Participate actively in the discussion.
5. Connect the seminar topic to your own research whenever possible.

## ChatGPT Suggested General Resources

- NIST Post-Quantum Cryptography Project:
  https://csrc.nist.gov/projects/post-quantum-cryptography

- NIST Selected Algorithms:
  https://csrc.nist.gov/projects/post-quantum-cryptography/post-quantum-cryptography-standardization/selected-algorithms

- NIST Additional Digital Signature Schemes:
  https://csrc.nist.gov/projects/pqc-dig-sig

- PQCrypto Conference:
  https://pqcrypto.org/

- IACR Cryptology ePrint Archive:
  https://eprint.iacr.org/

- Daniele Micciancio and Oded Regev,
  "Lattice-based Cryptography":
  https://cims.nyu.edu/~regev/papers/pqc.pdf

- Chris Peikert,
  "A Decade of Lattice Cryptography":
  https://eprint.iacr.org/2015/939

## Learning Objectives

At the end of the course, participants should be able to:

- Explain and compare the main families of post-quantum cryptographic assumptions.
- Describe the design principles behind major post-quantum KEMs and signatures.
- Understand the role of quantum algorithms in the post-quantum threat model.
- Identify open problems in post-quantum design, cryptanalysis, proofs.
- Prepare pedagogical technical material for a masters audience.
- Lead a research-level discussion on a developing area of cryptography.

## Credit Calculation

**3hp credit** for delivering one paired seminar.  
**0.5** for studying and attending other's seminars

### Delivering seminar

- 40hrs for studying (this is 1 week of full work),
- 10hrs for finding and organizing resources,
- 20hrs for preparing the handouts,
- 8hrs for preparing the seminar,
- 2hrs for delivering the seminar.

### Attending seminar
- 8hrs for reading the handouts (this is 1 full day of work)
- 2hrs for thinking of good questions to ask during the seminar
- 1hr for giving feedback (either on the presentation or on the handouts) 
- 2hrs for attending the seminar.

#### Back-of-the-envelope credit count

Let `p` be the number of presenting pairs.

- Presenting one paired seminar: **3hp**
- Attending the other seminars: **0.5hp × (p - 1)**

For example, if there are 5 seminars and you present twice:

- Presenter credit: **6hp** (2x3)
- Attendance credit: **0.5hp × 3 = 1.5hp**
- Total estimate: **7.5hp**
