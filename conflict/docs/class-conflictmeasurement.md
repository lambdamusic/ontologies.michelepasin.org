Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Measurement


### Tree


* [conflict:Recording](class-conflictrecording.md)

    * conflict:Measurement


        * [conflict:Weather_recording](class-conflictweather_recording.md) 
        






### URI
http://purl.com/net/conflict#Measurement

### Description
&quot;quantifiable recording events // or maybe a scientific measurement where some piece of technology was used


Problem: when recording on a ship or on a lighthouse, we need to work out who is doing the recording, what is the devide used, and what role is played by lighthouse or ship!&quot;



### Inherits from (3)

- [conflict:Recording](class-conflictrecording.md)

- [conflict:Event](class-conflictevent.md)

- [conflict:Temporal_Entity](class-conflicttemporal_entity.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Measurement a owl:Class ;<br />    rdfs:comment &quot;&quot;&quot;quantifiable recording events // or maybe a scientific measurement where some piece of technology was used</p>

<p>Problem: when recording on a ship or on a lighthouse, we need to work out who is doing the recording, what is the devide used, and what role is played by lighthouse or ship!&quot;&quot;&quot;^^rdf:XMLLiteral ;<br />    rdfs:subClassOf :Recording .</p>

<p></p>
```




### Instances of conflict:Measurement can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Measurement" href="class-conflictmeasurement.md" class="rdfclass">conflict:Measurement</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="conflict:used_instrument" href="prop-conflictused_instrument.md">conflict:used_instrument</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="conflict:Measuring_Device" href="class-conflictmeasuring_device.md" class="rdfclass">conflict:Measuring_Device</a>

                    
                    
                </td>
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