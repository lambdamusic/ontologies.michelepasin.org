_Vocabulary: [http://purl.com/net/phideas](index.md)_ 

---	
	




    


## Property ontology:philosurfical.owl#CARRIED-OUT-BY


#### Tree

* rdfs:Property
    * ontology:philosurfical.owl#CARRIED-OUT-BY





*NOTE* this is a leaf node.


#### URI
http://philosurfical.open.ac.uk/ontology/philosurfical.owl#CARRIED-OUT-BY

#### Description
--


#### Inherits from:
owl:Thing



#### Usage


[ontology:philosurfical.owl#MEETING](class-ontologyphilosurficalowlmeeting.md) &amp;&amp;  

[ontology:philosurfical.owl#2-PERSONS-MEETING](class-ontologyphilosurficalowl2-persons-meeting.md) &amp;&amp;  

[ontology:philosurfical.owl#TELEPHONE-CONVERSATION](class-ontologyphilosurficalowltelephone-conversation.md) &amp;&amp;  

[ontology:philosurfical.owl#ACTIVITY](class-ontologyphilosurficalowlactivity.md) &amp;&amp;  

[ontology:philosurfical.owl#JOURNEY](class-ontologyphilosurficalowljourney.md) &amp;&amp;  

[ontology:philosurfical.owl#MAIL-EXCHANGE](class-ontologyphilosurficalowlmail-exchange.md) 
=&gt;&nbsp;_ontology:philosurfical.owl#CARRIED-OUT-BY_&nbsp;=&gt;&nbsp;owl:Thing

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

<http://philosurfical.open.ac.uk/ontology/philosurfical.owl#CARRIED-OUT-BY> a owl:ObjectProperty ;
    rdfs:domain <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#2-PERSONS-MEETING>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#ACTIVITY>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#JOURNEY>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#MAIL-EXCHANGE>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#MEETING>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TELEPHONE-CONVERSATION> .


```










---

_Documentation automatically generated on 9th November 2016 with [OntoSpy](http://ontospy.readthedocs.org/ "Open") (v1.7.0-alpha)_