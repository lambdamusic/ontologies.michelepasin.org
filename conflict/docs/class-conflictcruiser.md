Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Cruiser


### Tree


* [conflict:Warship](class-conflictwarship.md)

    * conflict:Cruiser


        * [conflict:Armoured_Cruiser](class-conflictarmoured_cruiser.md) 

        * [conflict:Light_Cruiser](class-conflictlight_cruiser.md) 

        * [conflict:Protected_Cruiser](class-conflictprotected_cruiser.md) 

        * [conflict:Scout_Cruiser](class-conflictscout_cruiser.md) 
        






### URI
http://purl.com/net/conflict#Cruiser

### Description
&quot;&amp;quot;A fast independent warship. Traditionally, cruisers were the smallest warships capable of independent action.&amp;quot;

TIP: lost of info about cruisers here: http://en.wikipedia.org/wiki/List_of_cruiser_classes_of_the_Royal_Navy&quot;



### Inherits from (5)

- [conflict:Warship](class-conflictwarship.md)

- [conflict:Ship](class-conflictship.md)

- [conflict:Watercraft](class-conflictwatercraft.md)

- [conflict:Single_Thing](class-conflictsingle_thing.md)

- [conflict:Physical](class-conflictphysical.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Cruiser a owl:Class ;<br />    rdfs:comment &quot;&quot;&quot;&amp;quot;A fast independent warship. Traditionally, cruisers were the smallest warships capable of independent action.&amp;quot;</p>

<p>TIP: lost of info about cruisers here: http://en.wikipedia.org/wiki/List_of_cruiser_classes_of_the_Royal_Navy&quot;&quot;&quot;^^rdf:XMLLiteral ;<br />    rdfs:subClassOf :Warship .</p>

<p></p>
```




### Instances of conflict:Cruiser can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Cruiser" href="class-conflictcruiser.md" class="rdfclass">conflict:Cruiser</a></span>
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