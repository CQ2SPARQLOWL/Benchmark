A benchmark of schema-level Competency Questions and corresponding SPARQL-OWL patterns. 
The details are described in the paper: 
Dawid Wisniewski, Jedrzej Potoniec, Agnieszka Lawrynowicz, C. Maria Keet  
_Competency Questions and SPARQL-OWL Queries Dataset and Analysis_, available on [https://arxiv.org/abs/1811.09529](https://arxiv.org/abs/1811.09529).

Description of files:
* [signature_to_patterns.json](signature_to_patterns.json), 
[signature_to_patterns_high_level.json](signature_to_patterns_high_level.json), 
[patterns_to_signatures.json](patterns_to_signatures.json), 
[patterns_to_signatures_high_level.json](patterns_to_signatures_high_level.json): 
JSON files representing mapping between CQ patterns and SPARQL-OWL signatures.
In case of pattern to SPARQL-OWL signature mapping, there are empty mappings, because some patterns don’t have SPARQL-OWL translations defined.
In case of SPARQL-OWL signature to pattern mapping, there are empty mappings, because some SPARQL-OWL signatures map to CQs that don’t form a pattern (don’t utilize placeholders and are unique in their surface form).
* [linguistic_patterns.txt](linguistic_patterns.txt), 
[linguistic_higher_level_patterns.txt](linguistic_higher_level_patterns.txt): 
linguistic pattern lists
* [signatures.json](signatures.json): a list of signatures calculated.
* [OWLkeywords.json](owlkeywords.json): a list of OWL keywords with listed ontologies against which CQ translation contain given keyword.
* [SPARQLkeywords.json](sparqlkeywords.json): a list of SPARQL keywords with listed ontologies against which CQ translation contain given keyword.
* [EC.rules](EC.rules): rules defining Entity Chunk extraction procedure.
* [PC.rules](PC.rules): rules defining Predicate Chunk extraction procedure.


The competency questions were obtained from the following sources:
 * SWO [https://softwareontology.wordpress.com/2011/04/01/user-sourced-competency-questions-for-software/](https://softwareontology.wordpress.com/2011/04/01/user-sourced-competency-questions-for-software/)
 * OntoDT [https://doi.org/10.1016/j.ins.2015.08.006](https://doi.org/10.1016/j.ins.2015.08.006)
 * Dem@Care [http://www.demcare.eu/results/deliverables/61-semantic-knowledge-structures-and-representation](http://www.demcare.eu/results/deliverables/61-semantic-knowledge-structures-and-representation)
 * AWO [https://people.cs.uct.ac.za/~mkeet/OEbook/](https://people.cs.uct.ac.za/~mkeet/OEbook/)

The SPARQL-OWL queries, signatures and patterns are licensed under a [Creative Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0/).

