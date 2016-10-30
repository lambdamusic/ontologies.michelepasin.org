Vocabulary: [http://purl.com/net/factoid](index.md) 



---	
	




    


## Property factoid:took_part_in


### Tree

* rdfs:Property
    * factoid:took_part_in





*NOTE* this is a leaf node.


### URI
http://purl.com/net/factoid#took_part_in

### Description
--


### Inherits from:
owl:Thing



### Usage


[factoid:Agent](class-factoidagent.md) 
=&gt;&nbsp;_factoid:took_part_in_&nbsp;=&gt;&nbsp;[factoid:Temporal_Entity](class-factoidtemporal_entity.md)

### Implementation
```
<p>@prefix : &lt;http://purl.com/net/factoid#&gt; .<br />@prefix cidoc_crm: &lt;http://www.cidoc-crm.org/rdfs/cidoc_crm_v5.0.4_english_label.rdfs#&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix sp: &lt;http://spinrdf.org/sp#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:took_part_in a owl:ObjectProperty ;<br />    rdfs:label &quot;took part in&quot;^^xsd:string ;<br />    rdfs:domain :Agent ;<br />    rdfs:range :Temporal_Entity ;<br />    rdfs:subPropertyOf cidoc_crm:P11B.participated_in ;<br />    owl:inverseOf :had_participant .</p>

<p></p>
```










---

Documentation automatically generated with [OntoSpy](http://ontospy.readthedocs.org/ "Open") on 30th October 2016 19:16