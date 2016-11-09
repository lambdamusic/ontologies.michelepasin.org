_Vocabulary: [http://purl.com/net/phideas](index.md)_ 

---	
	




    


## Property ontology:philosurfical.owl#STUDIES


#### Tree

* rdfs:Property
    * ontology:philosurfical.owl#STUDIES





*NOTE* this is a leaf node.


#### URI
http://philosurfical.open.ac.uk/ontology/philosurfical.owl#STUDIES

#### Description
--


#### Inherits from:
owl:Thing



#### Usage


[ontology:philosurfical.owl#STUDY-AN-IDEA](class-ontologyphilosurficalowlstudy-an-idea.md) &amp;&amp;  

[ontology:philosurfical.owl#STUDY-A-DOCUMENT](class-ontologyphilosurficalowlstudy-a-document.md) &amp;&amp;  

[ontology:philosurfical.owl#STUDY](class-ontologyphilosurficalowlstudy.md) 
=&gt;&nbsp;_ontology:philosurfical.owl#STUDIES_&nbsp;=&gt;&nbsp;owl:Thing

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

<http://philosurfical.open.ac.uk/ontology/philosurfical.owl#STUDIES> a owl:ObjectProperty ;
    rdfs:domain <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#STUDY>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#STUDY-A-DOCUMENT>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#STUDY-AN-IDEA> .


```










---

_Documentation automatically generated on 9th November 2016 with [OntoSpy](http://ontospy.readthedocs.org/ "Open") (v1.7.0-alpha)_