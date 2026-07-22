# MAGE-Ontology: An Ontology for Malware Analysis in Ghidra for Executables

## About
The MAGE-Ontology is an ontology design pattern that provides a structured representation of the disassembly and decompilation of an executable file. It is built upon the reverse engineering tool Ghidra, utilizing Ghidra's API to materialize RDF triples to make a knowledge graph based on an executable file. The ontology is based on the symbol tree in Ghidra, providing structured sub-class and super-clas relations between different symbols and how they interact. SPARQL queries were generated based on the knowledge graphs with the purpose of categorizing malicious behaviors within the executables, with different forms of malicious behavior detected based on the type of malware.

## Repository Structure:
* [`Documentation/`](https://github.com/kastle-lab/MAGE-Ontology/tree/master/documentation): contains supporting documentation for the ontology design pattern.
  * [`Axiomization.md`](https://github.com/kastle-lab/MAGE-Ontology/blob/master/documentation/axiomization.md): lists all subclass axioms and their selection with axiom type.
  * [`Axioms.md`](https://github.com/kastle-lab/MAGE-Ontology/blob/master/documentation/axioms.md): contains descriptions for each module and the relating objects and axioms contained in them.
  * [`Competency-Question_Queries.md`](https://github.com/kastle-lab/MAGE-Ontology/blob/master/documentation/competency-questions-queries.md): lists all the competency questions and their corresponding SPARQL queries developed.
  * [`Key-Notions.md`](https://github.com/kastle-lab/MAGE-Ontology/blob/master/documentation/key-notions.md): includes key notions of the ontology, including any connected patterns and datasets associated with them.
  * [`Use-Case.md`](https://github.com/kastle-lab/MAGE-Ontology/blob/master/documentation/use-case.md): Outlines the narrative of the use case for the ontology design pattern.
* [`Ghidra Scripting/`](https://github.com/kastle-lab/MAGE-Ontology/tree/master/ghidra-scripting): Contains the Python scripts used to extract the data from the executable, parse the data, and materialize the knowledge graph.
* [`Ontology/`](https://github.com/kastle-lab/MAGE-Ontology/tree/master/ontology): contains the OWL file of the ontology. Serialized in the Turtle format.
* [`Queries/`](https://github.com/kastle-lab/MAGE-Ontology/tree/master/queries): contains the file that has all the SPARQL queries that were developed based on the competency questions.