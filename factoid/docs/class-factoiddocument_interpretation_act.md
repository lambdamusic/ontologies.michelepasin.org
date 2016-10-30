Vocabulary: [http://purl.com/net/factoid](index.md) 



---	
	




    


## Class factoid:Document_Interpretation_Act


### Tree


* [factoid:Event](class-factoidevent.md)

    * factoid:Document_Interpretation_Act





*NOTE* this is a leaf node.


### URI
http://purl.com/net/factoid#Document_Interpretation_Act

### Description
&quot;Class that represents the act of interpreting an historical document, to the purpose of extracting a &#39;factoid&#39; from it (that is, an assertion circa the existence of a state of things of some sort)&quot;



### Inherits from (2)

- [factoid:Event](class-factoidevent.md)

- [factoid:Temporal_Entity](class-factoidtemporal_entity.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/factoid#&gt; .<br />@prefix cidoc_crm: &lt;http://www.cidoc-crm.org/rdfs/cidoc_crm_v5.0.4_english_label.rdfs#&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix sp: &lt;http://spinrdf.org/sp#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Document_Interpretation_Act a owl:Class ;<br />    rdfs:label &quot;Document interpretation act&quot;^^xsd:string ;<br />    rdfs:comment &quot;Class that represents the act of interpreting an historical document, to the purpose of extracting a &#39;factoid&#39; from it (that is, an assertion circa the existence of a state of things of some sort)&quot;^^xsd:string ;<br />    rdfs:subClassOf :Event,<br />        cidoc_crm:E13.Attribute_Assignment .</p>

<p></p>
```




### Instances of factoid:Document_Interpretation_Act can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="factoid:Document_Interpretation_Act" href="class-factoiddocument_interpretation_act.md" class="rdfclass">factoid:Document_Interpretation_Act</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="factoid:has_interpretation" href="prop-factoidhas_interpretation.md">factoid:has_interpretation</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="factoid:Temporal_Entity" href="class-factoidtemporal_entity.md" class="rdfclass">factoid:Temporal_Entity</a>

                    
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="factoid:has_source" href="prop-factoidhas_source.md">factoid:has_source</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="factoid:Document" href="class-factoiddocument.md" class="rdfclass">factoid:Document</a>

                    
                    
                </td>
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