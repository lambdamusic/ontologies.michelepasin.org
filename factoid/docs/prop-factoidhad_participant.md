Vocabulary: [http://purl.com/net/factoid](index.md) 



---	
	




    


## Property factoid:had_participant


### Tree

* rdfs:Property
    * factoid:had_participant





*NOTE* this is a leaf node.


### URI
http://purl.com/net/factoid#had_participant

### Description
--


### Inherits from:
owl:Thing



### Usage


[factoid:Temporal_Entity](class-factoidtemporal_entity.md) 
=&gt;&nbsp;_factoid:had_participant_&nbsp;=&gt;&nbsp;[factoid:Agent](class-factoidagent.md)

### Implementation
```
<p>@prefix : &lt;http://purl.com/net/factoid#&gt; .<br />@prefix cidoc_crm: &lt;http://www.cidoc-crm.org/rdfs/cidoc_crm_v5.0.4_english_label.rdfs#&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix sp: &lt;http://spinrdf.org/sp#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:had_participant a owl:ObjectProperty ;<br />    rdfs:label &quot;has participant&quot;^^xsd:string ;<br />    rdfs:domain :Temporal_Entity ;<br />    rdfs:range :Agent ;<br />    rdfs:subPropertyOf cidoc_crm:P11F.had_participant ;<br />    owl:inverseOf :took_part_in .</p>

<p></p>
```










---

Documentation automatically generated with [OntoSpy](http://ontospy.readthedocs.org/ "Open") on 30th October 2016 19:16