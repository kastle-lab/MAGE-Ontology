# MAGE-Ontology: An Ontology for Malware Analysis in Ghidra for Executables

## About
The MAGE-Ontology provides a structured representation of the disassembly and decompilation of an executable file. It is built upon the reverse engineering tool Ghidra, utilizing Ghidra's API to materialize RDF triples to make a knowledge graph based on an executable file. The ontology is based on the symbol tree in Ghidra, providing structured sub-class and super-clas relations between different symbols and how they interact. SPARQL queries were generated based on the knowledge graphs with the purpose of categorizing malicious behaviors within the executables, with different forms of malicious behavior detected based on the type of malware.

## Resources:
* [Documentation](https://github.com/kastle-lab/MAGE-Ontology/tree/master/documentation): contains useful documentation of the project, such as key notions, schema digrams, the list of competency questions along with their associated queries, and more.
* [Ontology](https://github.com/kastle-lab/MAGE-Ontology/tree/master/ontology): contains the OWL file of the ontology.
* [Ghidra Scripting](https://github.com/kastle-lab/MAGE-Ontology/tree/master/ghidra-scripting): contains any scripts used to extract the data for the knowledge graph (writen in Pyghidra).
* [Queries](https://github.com/kastle-lab/MAGE-Ontology/tree/master/queries): contains a SPARQL file containing all the queries used in the project.
