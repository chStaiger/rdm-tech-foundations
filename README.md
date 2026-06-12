[![Read the book](https://img.shields.io/badge/read-the%20book-blue.svg)](https://chstaiger.github.io/rdm-tech-foundations/)
[![i want to contribute!](https://img.shields.io/badge/i%20want%20to-contribute!-brightgreen)](CONTRIBUTING.md)
# RDM Tech Foundations — The Book

![https://doi.org/10.5281/zenodo.3460552](book/img/DatStewVenn_highres.png)
*https://doi.org/10.5281/zenodo.3460552*

This repository contains the source files for RDM Tech Foundations, a book that explains the technical foundations of modern Research Data Management (RDM) from the perspective of data stewards.

While data stewards work across three domains: policies, research practice, and IT/infrastructure, this book focuses on the infrastructure layer: the systems, standards, workflows, and architectural patterns that enable data stewards to support FAIR‑aligned research throughout the data lifecycle.

## The Three Working Areas of Data Stewards

Data stewards operate at the intersection of three stakeholder groups:

- Policy makers — funders, universities, EU bodies, deans; they define how data should be handled.
- Researchers and data scientists — they produce and analyse data and must remain empowered to do research while staying policy‑compliant.
- Infrastructure and IT providers — ICT staff, technicians, application managers; they provide the tools that implement data policies.

Each group has its own terminology, priorities, and constraints.
Data stewards translate between them but translation only works when the infrastructure itself is coherent, predictable, and FAIR‑aligned.

This book focuses on that infrastructure: the systems and architectural patterns that make the steward’s bridging role technically possible.

## Structure of the Book

The book is organised into several major parts:

- **Conceptual Foundations** — repositories, policy engines, metadata services, PID systems, storage, and how they relate.
- **From Components to a Platform** — how specialised services become a coherent RDM platform through orchestration, shared schemas, and lifecycle transitions.
- **FAIR as Infrastructure Requirements** — what Findable, Accessible, Interoperable, and Reusable mean for system design.
- **Transitions in the RDM Lifecycle** — where identity, metadata continuity, and provenance are preserved or lost.
- **Examples and Boundary-Spanning Tools** — including FAIRDOM‑SEEK and FAIR Data Station, which combine linked data, DOIs, and file storage and therefore span multiple categories of RDM services.
- **Designing a FAIR-Aligned RDM Platform** — architectural patterns, integration strategies, and orchestration layers.

Each chapter is self‑contained but designed to build toward a coherent understanding of RDM infrastructure.

## Why This Book Exists

Modern RDM ecosystems are composed of specialised services — repositories, PID systems, metadata catalogues, workflow engines, storage layers — but **FAIR only emerges when these services work together**.

This book explains:

- the **roles** of each component  
- the **boundaries** between them  
- the **transitions** where digital objects change state  
- the **orchestration layer** required to maintain identity, metadata, and provenance across services  

Without this orchestration layer, even well‑designed APIs cannot prevent the loss of trace, provenance, and metadata continuity between components.

## Audience

The book is intended for:

- research software engineers  
- data stewards and data managers  
- infrastructure architects  
- policy developers  
- domain specialists building community‑specific RDM tools  
- anyone designing or maintaining FAIR‑aligned RDM services  

It assumes basic familiarity with research workflows but does not require prior knowledge of RDM standards.

## How to Build or View the Book

If you are using **Quarto**, **Sphinx**, or another documentation engine, include instructions here.  
For example:

```
quarto render
```

or

```
make html
```

(Adjust this section to match your actual build system.)

## Contributing

Contributions are welcome.  
You can propose improvements via:

- pull requests  
- issues  
- suggestions for examples, diagrams, or clarifications  

Please follow the repository’s coding and documentation style guidelines.