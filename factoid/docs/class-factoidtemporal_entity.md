Vocabulary: [http://purl.com/net/factoid](index.md) 



---	
	




    


## Class factoid:Temporal_Entity


### Tree

* OWL:Thing
    * factoid:Temporal_Entity


        * [factoid:Event](class-factoidevent.md) 

        * [factoid:Situation](class-factoidsituation.md) 
        






### URI
http://purl.com/net/factoid#Temporal_Entity

### Description
--



### Inherits from:
owl:Thing




### Implementation
```
<p>@prefix : &lt;http://purl.com/net/factoid#&gt; .<br />@prefix cidoc_crm: &lt;http://www.cidoc-crm.org/rdfs/cidoc_crm_v5.0.4_english_label.rdfs#&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix sp: &lt;http://spinrdf.org/sp#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Temporal_Entity a owl:Class ;<br />    rdfs:label &quot;Temporal Entity&quot;^^xsd:string ;<br />    rdfs:subClassOf cidoc_crm:E2.Temporal_Entity,<br />        owl:Thing .</p>

<p></p>
```




### Instances of factoid:Temporal_Entity can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="factoid:Temporal_Entity" href="class-factoidtemporal_entity.md" class="rdfclass">factoid:Temporal_Entity</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="factoid:had_participant" href="prop-factoidhad_participant.md">factoid:had_participant</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="factoid:Agent" href="class-factoidagent.md" class="rdfclass">factoid:Agent</a>

                    
                    
                </td>
            </tr>

            

        

    

</table>













---

Documentation automatically generated with [OntoSpy](http://ontospy.readthedocs.org/ "Open") on 30th October 2016 19:16