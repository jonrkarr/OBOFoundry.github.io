---
layout: ontology_detail
id: mro
title: MHC Restriction Ontology
description: An ontology for Major Histocompatibility Complex (MHC) restriction in experiments
tracker: https://github.com/IEDB/MRO/issues
homepage: https://github.com/IEDB/MRO
domain: biochemistry
tags:
  - Major Histocompatibility Complex
contact:
  label: Bjoern Peters
  email: bpeters@lji.org
  github: bpeters42
  orcid: 0000-0002-8457-6693
license:
  url: https://creativecommons.org/licenses/by/3.0/
  label: CC BY 3.0
products:
  - id: mro.owl
usages:
  - user: https://www.iedb.org/
    type: annotation
    description: MRO is used by the The Immune Epitope Database (IEDB) annotations
    examples:
      - url: https://www.iedb.org/assay/1357035
        description: "Epitope ID: 59611 based on reference 1003499"
    publications:
      - id: https://www.ncbi.nlm.nih.gov/pubmed/26759709
        title: "An ontology for major histocompatibility restriction"
activity_status: active
repository: https://github.com/IEDB/MRO
preferredPrefix: MRO
---

The MHC Restriction Ontology (MRO) is an application ontology capturing how Major Histocompatibility Complex (MHC) restriction is defined in experiments, spanning exact protein complexes, individual protein chains, serotypes, haplotypes and mutant molecules, as well as evidence for MHC restrictions.
