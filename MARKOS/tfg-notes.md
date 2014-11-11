# Technical Issues

- duplicate dublin dc annotation properties
- duplicate agent classes
	- is the friend of a friend ontology imported twice?
	- relationship between agent and LegalPerson?

# Licensing Issues

## Licenses of imported ontologies

### W3C Time Ontology

Presumably the W3C Software Notice and License, below, applies:

http://www.w3.org/Consortium/Legal/2002/copyright-software-20021231

This is an academic license.

### Friend of a Friend Ontology

http://www.w3.org/Consortium/Legal/2002/copyright-documents-20021231

License: CC BY 1.0

### W3C SKOS Ontology

URL:  http://www.w3.org/2004/02/skos/vocabs

License: Academic.  See below.

http://www.w3.org/Consortium/Legal/2002/copyright-software-20021231

### Protege Dublin Core Ontology

URL: http://protege.cim3.net/cgi-bin/wiki.pl?DublinCoreProtegeOntology

License:  MPL

See: http://protege.stanford.edu/doc/faq.html#08.01

The reciprocity clause of the MPL seems to only apply to textual modifications of the source code.

### Countries Ontology

URL: http://eulersharp.sourceforge.net/2003/03swap/countries.html
License: W3C Software License

# Possible other licenses to include in the ontology

Marcin gathered some statistics:

There are 1479 projects in the current data set. Only 197 of them
declare license type that is not represented in the ontology. So,
despite the fact that most of the user declared project license types
are not represented in the ontology - 25 vs 18, for huge majority of
the projects a declared license can be found in the ontology. This
means that the ontology covers all most important license types used
in practise.

The top hits license types that are not available in ontology are:

45 - ibmcpl,
34 - mpl11,
28 - other,
26 - artistic,
22 - publicdomain,
11 - osi,

The number at the beginning denotes number of projects using this license.

# To Do

- Define Class for Weak Copyleft Licenses (LGPL, MPLv2). 
- Defining which actions invoke the reciprocity conditions (e.g. textual modifications, linking, ...)
- Write rules to derive the license of a release from the license of
  its project.
- Write rules for different views on whether APIs are protected by copyright.




