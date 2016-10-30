Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Recording


### Tree


* [conflict:Event](class-conflictevent.md)

    * conflict:Recording


        * [conflict:Measurement](class-conflictmeasurement.md) 

        * [conflict:Report](class-conflictreport.md) 
        






### URI
http://purl.com/net/conflict#Recording

### Description
&quot;Recordings are tricky: in our scenario it&#39;s important to have a class&#39; recording&#39; because we want to capture the difference between a piece of information as recorded and as happened / lived.  In the log books and service records, lots of events are recorded but often we are not sure how precise their correspondance with reality is. 

This duality generates a further problem: when should we also instantiate the actual event and when not (eg being on ship, vs the event of an official recording that someone was on a ship) ?&quot;



### Inherits from (2)

- [conflict:Event](class-conflictevent.md)

- [conflict:Temporal_Entity](class-conflicttemporal_entity.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Recording a owl:Class ;<br />    rdfs:comment &quot;&quot;&quot;Recordings are tricky: in our scenario it&#39;s important to have a class&#39; recording&#39; because we want to capture the difference between a piece of information as recorded and as happened / lived.  In the log books and service records, lots of events are recorded but often we are not sure how precise their correspondance with reality is. </p>

<p>This duality generates a further problem: when should we also instantiate the actual event and when not (eg being on ship, vs the event of an official recording that someone was on a ship) ?&quot;&quot;&quot;^^rdf:XMLLiteral ;<br />    rdfs:subClassOf :Event .</p>

<p></p>
```




### Instances of conflict:Recording can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Recording" href="class-conflictrecording.md" class="rdfclass">conflict:Recording</a></span>
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