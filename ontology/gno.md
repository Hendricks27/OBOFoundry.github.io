---
layout: ontology_detail
id: gno
contact:
  email: nje5@georgetown.edu
  label: Nathan Edwards
  github: edwardsnj
description: GlyTouCan provides stable accessions for glycans described at varyious degrees of characterization, including compositions (no linkage) and topologies (no carbon bond positions or anomeric configurations). GNOme organizes these stable accessions for interative browsing, for text-based searching, and for automated reasoning with well-defined characterization levels.
domain: glycan structure
homepage: https://gnome.glyomics.org/
products:
  - id: gno.owl
    description: Glycan Naming and Subsumption Ontology, OWL format (primary)
  - id: gno.obo
    description: Glycan Naming and Subsumption Ontology, OBO format (automated conversion from OWL)
  - id: gno.json
    description: Glycan Naming and Subsumption Ontology, JSON format (automated conversion from OWL)
title: Glycan Naming and Subsumption Ontology (GNOme)
build:
  checkout: git clone https://github.com/glygen-glycan-data/GNOme.git
  system: git
  path: "."
tracker: https://github.com/glygen-glycan-data/GNOme/issues
license:
  url: https://creativecommons.org/licenses/by/4.0/
  label: CC-BY 4.0
browsers:
  - label: Structure Browser
    title: GNOme Glycan Structure Browser
    url: https://gnome.glyomics.org/StructureBrowser.html?HexNAc=4&Hex=5&dHex=1&NeuAc=2
  - label: Composition Browser
    title: GNOme Glycan Composition Browser
    url: https://gnome.glyomics.org/CompositionBrowser.html?HexNAc=4&Hex=5&dHex=1&NeuAc=2
usages:
  - user: https://www.glygen.org/
    description: Computational and Informatics Resources for Glycoscience
    examples:
      - url: https://www.glygen.org/glycan/G00028MO
        description: GlyGen uses GNOme for display glycan subsumption relationship
  - user: https://proconsortium.org/
    description: Protein Ontology
    examples:
      - url: http://purl.obolibrary.org/obo/PR_000059585
        description: an example of PRO imports GNOme terms.
  - user: https://www.ebi.ac.uk/chebi/init.do
    description: Chemical Entities of Biological Interest
    examples:
      - url: https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:167503
        description: an example of ChEBI imports GNOme term.
activity_status: active
---
