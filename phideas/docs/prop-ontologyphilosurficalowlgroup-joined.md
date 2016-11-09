_Vocabulary: [http://purl.com/net/phideas](index.md)_ 

---	
	




    


## Property ontology:philosurfical.owl#GROUP-JOINED


#### Tree

* rdfs:Property
    * ontology:philosurfical.owl#GROUP-JOINED





*NOTE* this is a leaf node.


#### URI
http://philosurfical.open.ac.uk/ontology/philosurfical.owl#GROUP-JOINED

#### Description
--


#### Inherits from:
owl:Thing



#### Usage


[ontology:philosurfical.owl#LEARNING-AT-INSTITUTION](class-ontologyphilosurficalowllearning-at-institution.md) &amp;&amp;  

[ontology:philosurfical.owl#JOINING-A-GROUP](class-ontologyphilosurficalowljoining-a-group.md) &amp;&amp;  

[ontology:philosurfical.owl#TEACHING-AT-INSTITUTION](class-ontologyphilosurficalowlteaching-at-institution.md) &amp;&amp;  

[ontology:philosurfical.owl#WORKING-FOR-ORGANIZATION](class-ontologyphilosurficalowlworking-for-organization.md) 
=&gt;&nbsp;_ontology:philosurfical.owl#GROUP-JOINED_&nbsp;=&gt;&nbsp;owl:Thing

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

<http://philosurfical.open.ac.uk/ontology/philosurfical.owl#GROUP-JOINED> a owl:ObjectProperty ;
    rdfs:domain <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#JOINING-A-GROUP>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#LEARNING-AT-INSTITUTION>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEACHING-AT-INSTITUTION>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#WORKING-FOR-ORGANIZATION> .


```










---

_Documentation automatically generated on 9th November 2016 with [OntoSpy](http://ontospy.readthedocs.org/ "Open") (v1.7.0-alpha)_