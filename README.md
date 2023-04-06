# RDF modelling for Maltese verbs with OntoLex-Morph
An example of using OntoLex-Morph for Semitic languages

This is a companion repository for a paper _Beyond Concatenative Morphology: Applying OntoLex-Morph to Maltese_, submitted to LDK 2023.

An overview of the repository:
* lexical-entries-small.ttl — a toy example with 3 verbs mentioned in the paper, all the headers and rules; does not specify character classes, relies on hardcoded classes C and V.
* rules.ttl — header, character classes and rules for strong verbs like the ones mentioned in the paper.
* entries.ttl — lexical entries for all the strong verbs extracted from [Ġabra](https://mlrs.research.um.edu.mt/resources/gabra/).
* construct-forms.rq — an example of a SPARQL query that generates forms for all the lexical entries with paradigms that have rules linked to them. Uses hardcoded character classes C and V.
