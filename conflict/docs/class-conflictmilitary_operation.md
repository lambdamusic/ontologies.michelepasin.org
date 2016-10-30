Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Military_Operation


### Tree


* [conflict:Event](class-conflictevent.md)

    * conflict:Military_Operation


        * [conflict:Combat_Operation](class-conflictcombat_operation.md) 

        * [conflict:Non_Combat_Operation](class-conflictnon_combat_operation.md) 
        






### URI
http://purl.com/net/conflict#Military_Operation

### Description
&quot;Military operation is the coordinated military actions of a state in response to a developing situation. These actions are designed as a military plan to resolve the situation in the state&#39;s favor. Operations may be of combat or non-combat types, and are referred to by a code name for the purpose of security.

All the military operations can have as subject any of the miliraty forces.

TIP: has code name; add a shortcut for specifying the force involved in the operation

LIST OF MIL.OP. in WW1: http://en.wikipedia.org/wiki/List_of_military_operations#World_War_I&quot;



### Inherits from (2)

- [conflict:Event](class-conflictevent.md)

- [conflict:Temporal_Entity](class-conflicttemporal_entity.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Military_Operation a owl:Class ;<br />    rdfs:comment &quot;&quot;&quot;Military operation is the coordinated military actions of a state in response to a developing situation. These actions are designed as a military plan to resolve the situation in the state&#39;s favor. Operations may be of combat or non-combat types, and are referred to by a code name for the purpose of security.</p>

<p>All the military operations can have as subject any of the miliraty forces.</p>

<p>TIP: has code name; add a shortcut for specifying the force involved in the operation</p>

<p>LIST OF MIL.OP. in WW1: http://en.wikipedia.org/wiki/List_of_military_operations#World_War_I&quot;&quot;&quot;^^rdf:XMLLiteral ;<br />    rdfs:subClassOf :Event .</p>

<p></p>
```




### Instances of conflict:Military_Operation can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Military_Operation" href="class-conflictmilitary_operation.md" class="rdfclass">conflict:Military_Operation</a></span>
            </th>
        </tr>       

            

        

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="owl:Thing" href="class-owlthing.md" class="rdfclass">owl:Thing</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:creator" href="prop-dccreator.md">dc:creator</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:description" href="prop-dcdescription.md">dc:description</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:title" href="prop-dctitle.md">dc:title</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            

        

    

</table>













---

Documentation automatically generated with [OntoSpy](http://ontospy.readthedocs.org/ "Open") on 30th October 2016 19:14