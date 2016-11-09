_Vocabulary: [http://purl.com/net/phideas](index.md)_ 

---	
	




    


## Property ontology:philosurfical.owl#CONTAINS-CONCEPT


#### Tree

* rdfs:Property
    * ontology:philosurfical.owl#CONTAINS-CONCEPT





*NOTE* this is a leaf node.


#### URI
http://philosurfical.open.ac.uk/ontology/philosurfical.owl#CONTAINS-CONCEPT

#### Description
--


#### Inherits from:
owl:Thing



#### Usage


[ontology:philosurfical.owl#DISTINCTION](class-ontologyphilosurficalowldistinction.md) &amp;&amp;  

[ontology:philosurfical.owl#DICHOTOMY](class-ontologyphilosurficalowldichotomy.md) &amp;&amp;  

[ontology:philosurfical.owl#DEFINITORY-PROBLEM](class-ontologyphilosurficalowldefinitory-problem.md) &amp;&amp;  

[ontology:philosurfical.owl#FACTUAL-PROBLEM](class-ontologyphilosurficalowlfactual-problem.md) &amp;&amp;  

[ontology:philosurfical.owl#FUNCTIONAL-PROBLEM](class-ontologyphilosurficalowlfunctional-problem.md) &amp;&amp;  

[ontology:philosurfical.owl#RELATIONAL-PROBLEM](class-ontologyphilosurficalowlrelational-problem.md) &amp;&amp;  

[ontology:philosurfical.owl#PROBLEM](class-ontologyphilosurficalowlproblem.md) &amp;&amp;  

[ontology:philosurfical.owl#MODALITY-PROBLEM](class-ontologyphilosurficalowlmodality-problem.md) &amp;&amp;  

[ontology:philosurfical.owl#EXISTENCE-PROBLEM](class-ontologyphilosurficalowlexistence-problem.md) 
=&gt;&nbsp;_ontology:philosurfical.owl#CONTAINS-CONCEPT_&nbsp;=&gt;&nbsp;owl:Thing

#### Implementation
```
@prefix ontology: <http://philosurfical.open.ac.uk/ontology/> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix owl11: <http://www.w3.org/2006/12/owl11#> .
@prefix owl11xml: <http://www.w3.org/2006/12/owl11-xml#> .
@prefix phideas: <http://purl.com/net/phideas#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .
@prefix xml: <http://www.w3.org/XML/1998/namespace> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .

<http://philosurfical.open.ac.uk/ontology/philosurfical.owl#CONTAINS-CONCEPT> a owl:ObjectProperty ;
    rdfs:domain <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#DEFINITORY-PROBLEM>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#DICHOTOMY>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#DISTINCTION>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#EXISTENCE-PROBLEM>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#FACTUAL-PROBLEM>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#FUNCTIONAL-PROBLEM>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#MODALITY-PROBLEM>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#PROBLEM>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#RELATIONAL-PROBLEM> .


```










---

_Documentation automatically generated on 9th November 2016 with [OntoSpy](http://ontospy.readthedocs.org/ "Open") (v1.7.0-alpha)_