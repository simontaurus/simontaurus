# Dr. Simon Stier

**Head of Digital Transformation** at Fraunhofer ISC and **freelance software engineer**
Würzburg, Germany

[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0410--3616-green.svg)](https://orcid.org/0000-0003-0410-3616)
[![Website](https://img.shields.io/badge/Website-data--info--knowledge.de-blue.svg)](https://data-info-knowledge.de)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-simon--stier-blue.svg)](https://www.linkedin.com/in/simon-stier-9649a71b8/)

---

## About

I work where natural science meets software engineering: turning scientific and
industrial data into machine-interpretable form, and building the platforms,
ontologies and agents that run on it. Dual background in Computer Science and
Functional Materials, doctorate in natural science, and fifteen years of writing
production code from embedded firmware up to distributed web platforms.

### Focus

- Ontologies, knowledge graphs and schema design for scientific and industrial data
- Semantic lab platforms: ELN and LIMS, research data management, FAIR principles
- Laboratory and plant automation: instrument integration, OPC-UA, time series
- LLM agents grounded in knowledge graphs rather than in free text alone
- Interoperability and dataspaces, standards and specification work

### Selected achievements

- **Principal Investigator** in multi-million Euro research projects (50M+ EUR total
  funding since 2019, 5M+ EUR personal share)
- **15+ peer-reviewed publications** (*Advanced Materials*, *Advanced Energy Materials*
  and others)
- **3 patents** in sensor systems and flexible electronics
- **50+ contributions, invited talks and workshops** at international conferences
- Editor of an open specification with a persistent `w3id.org` namespace and
  reference implementations in three languages

---

## Open source

### [OpenSemanticLab (OSL)](https://github.com/OpenSemanticLab)

Semantic laboratory platform combining ELN and LIMS functionality with a knowledge graph.

- Full-stack solution for FAIR scientific data management, in production since 2022
- Triple store integration with automated workflow execution
- Typed Python API generated from wiki-hosted schemas ([`osw-python`](https://github.com/OpenSemanticLab/osw-python), PyPI)
- Eleven MediaWiki extensions: schema-driven form engine, SVG, spreadsheet and
  molecule editors, HDF5 media handling, RDF export, in-browser notebooks
- Adoption in 15+ research projects and industry cooperations

### [Object-Oriented Linked Data (OO-LD)](https://github.com/OO-LD)

A document that is simultaneously a valid JSON Schema and a JSON-LD context.

- [Specification](https://github.com/OO-LD/oold-schema) in W3C style with a normative
  rule catalogue, published under `w3id.org/oo-ld`
- Reference implementations in [Python](https://github.com/OO-LD/oold-python),
  JavaScript and PHP, held in conformance parity by CI
- Bidirectional mapping between code objects, JSON documents and knowledge graphs
- Funded by the German PrototypeFund

### Ontologies

- [**General Process Ontology (GPO)**](https://github.com/General-Process-Ontology/ontology):
  cross-domain vocabulary for scientific and manufacturing processes, `w3id.org/gpo`
- [**Battery Value Chain Ontology (BVCO)**](https://github.com/Battery-Value-Chain-Ontology/ontology):
  battery process terminology, built on EMMO
- Co-author of [PMDco](https://github.com/materialdigital/core-ontology), contributor
  to [EMMO](https://github.com/emmo-repo/EMMO) and [BattINFO](https://github.com/BIG-MAP/BattINFO)

### [Abstract Workflow Language (AWL)](https://github.com/OO-LD/awl-schema)

Executable workflow descriptions with built-in provenance.

- Round-trips Python code to JSON-LD and back, so workflows become queryable RDF
- [Python implementation](https://github.com/OO-LD/awl-python) with a human-in-the-loop module

### [Semos Agentura](https://github.com/semos-org/semos-agentura)

Modular multi-agent system on the Model Context Protocol (MCP) and Agent-to-Agent (A2A).

- Provider-agnostic agentic loop, tool-call validation, document and file agents
- Open reference implementation, Apache 2.0

### Upstream contributions

Merged pull requests to [pyld](https://github.com/digitalbazaar/pyld),
[datamodel-code-generator](https://github.com/koxudaxi/datamodel-code-generator),
[w3id.org](https://github.com/perma-id/w3id.org) (including its redirect test suite),
[SemanticMediaWiki](https://github.com/SemanticMediaWiki/SemanticMediaWiki),
MediaWiki core, [The ELN File Format](https://github.com/TheELNConsortium/TheELNFileFormat),
EMMO, BattINFO and others.

---

## Research impact

### Recent publications

| Year | Journal | Title | DOI |
|------|---------|-------|-----|
| 2024 | *Advanced Materials* | Materials Acceleration Platforms (MAPs): Accelerating materials R&D to meet urgent societal challenges | [10.1002/adma.202407791](https://doi.org/10.1002/adma.202407791) |
| 2025 | *Advanced Engineering Materials* | Advancing digital transformation in material science: The role of workflows within MaterialDigital | [10.1002/adem.202402149](https://doi.org/10.1002/adem.202402149) |
| 2025 | *ChemSusChem* | Semantic resources for managing knowledge in battery research | [10.1002/cssc.202500458](https://doi.org/10.1002/cssc.202500458) |
| 2024 | *Energy Technology* | Ontology-based battery production dataspace and AI-empowered analytics | [10.1002/ente.202301305](https://doi.org/10.1002/ente.202301305) |

### Leadership roles

- **Fraunhofer ISC**: Head of research group "Digital Transformation"
- **NFDI**: Principal Investigator in FairMat II and MatWerk II (21M+ EUR projects)
- **EMMC**: Co-Chair, Task Area Digitalisation and Interoperability

---

## Technical stack

- **Programming:** Python • C/C++ • C# • Java • JavaScript/TypeScript • PHP
- **Semantic web:** RDF • OWL • SPARQL • JSON-LD • SHACL • triple stores • ontology engineering
- **AI:** LLM integration • agents • MCP • A2A • RAG • tool calling • local and hosted inference
- **Backend:** FastAPI • REST • PostgREST • OAuth/OIDC • Keycloak
- **Data:** PostgreSQL • TimescaleDB • graph databases • time series • pandas/NumPy/SciPy
- **Cloud and DevOps:** Docker • Kubernetes • Terraform • Ansible • Azure • CI/CD • release automation
- **Hardware and lab:** OPC-UA • IoT • embedded systems • PCB design • instrument integration • lab automation

Client work covers industrial data pipelines, plant and laboratory automation,
measurement data analysis and cloud infrastructure. Those repositories are private.

---

## Collaboration and speaking

I care about open science and interdisciplinary collaboration, and speak regularly
at international conferences on materials digitalisation, semantic technologies and
AI in scientific research.

**Recent keynotes and invited talks:**

- **MRS Fall Meeting 2024** (Boston): Materials Acceleration Platforms
- **E-MRS 2025** (Strasbourg): Object-Oriented Linked Data for Materials Science
- **openLCA Conference 2025** (Berlin): Integrating Sustainability from the Start

---

## Contact

Open for research collaborations in materials informatics, freelance engineering
engagements, consulting on semantic technologies and dataspaces, guest lectures and
workshops on scientific digitalisation, and open source contributions.
