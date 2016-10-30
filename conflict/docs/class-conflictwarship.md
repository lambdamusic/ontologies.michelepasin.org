Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Warship


### Tree


* [conflict:Ship](class-conflictship.md)

    * conflict:Warship


        * [conflict:Battlecruiser](class-conflictbattlecruiser.md) 

        * [conflict:Battleship](class-conflictbattleship.md) 

        * [conflict:Cruiser](class-conflictcruiser.md) 

        * [conflict:Destroyer](class-conflictdestroyer.md) 

        * [conflict:Flotilla_Leader](class-conflictflotilla_leader.md) 

        * [conflict:Gunboat](class-conflictgunboat.md) 

        * [conflict:Monitor](class-conflictmonitor.md) 

        * [conflict:Q-Ship](class-conflictq-ship.md) 

        * [conflict:Seaplane_Carrier](class-conflictseaplane_carrier.md) 

        * [conflict:Submarine](class-conflictsubmarine.md) 

        * [conflict:Torpedo-Boat](class-conflicttorpedo-boat.md) 
        






### URI
http://purl.com/net/conflict#Warship

### Description
&quot;A ship equipped with weapons and designed to take part in warfare at sea; in particular, we refer here to ships that are designed to actively take part in combat actions (in opposition to auxiliary ships, that can be cargo ships re-purposed during a war).

TIP: it usually belongs to Navy&quot;



### Inherits from (4)

- [conflict:Ship](class-conflictship.md)

- [conflict:Watercraft](class-conflictwatercraft.md)

- [conflict:Single_Thing](class-conflictsingle_thing.md)

- [conflict:Physical](class-conflictphysical.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Warship a owl:Class ;<br />    rdfs:comment &quot;&quot;&quot;A ship equipped with weapons and designed to take part in warfare at sea; in particular, we refer here to ships that are designed to actively take part in combat actions (in opposition to auxiliary ships, that can be cargo ships re-purposed during a war).</p>

<p>TIP: it usually belongs to Navy&quot;&quot;&quot;^^rdf:XMLLiteral ;<br />    rdfs:subClassOf :Ship .</p>

<p></p>
```




### Instances of conflict:Warship can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Warship" href="class-conflictwarship.md" class="rdfclass">conflict:Warship</a></span>
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