_Vocabulary: [http://purl.com/net/phideas](index.md)_ 

---	
	




    


## Class ontology:philosurfical.owl#TEMPORAL-ENTITY


#### Tree

* owl:Thing
    * ontology:philosurfical.owl#TEMPORAL-ENTITY


        * [ontology:philosurfical.owl#PERIOD](class-ontologyphilosurficalowlperiod.md) 
        






#### URI
http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEMPORAL-ENTITY

#### Description
&quot;E2-CIDOC  - This class comprises all phenomena, such as the instances of E4 Periods, E5 Events and states, which happen over a limited extent in time.  In some contexts, these are also called perdurants. This class is disjoint from E77 Persistent Item. This is an abstract class and has no direct instances. E2 Temporal Entity is specialized into E4 Period, which applies to a particular geographic area (defined with a greater or lesser degree of precision), and E3 Condition State, which applies to instances of E18 Physical Thing.
++Philosurfical: The slot has-time-span is of type time-specification rather than span as it may be a time point. This is consistent with the CIPHER time ontology.&quot;



#### Inherits from:
owl:Thing




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

<http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEMPORAL-ENTITY> a owl:Class ;
    rdfs:comment """E2-CIDOC  - This class comprises all phenomena, such as the instances of E4 Periods, E5 Events and states, which happen over a limited extent in time.  In some contexts, these are also called perdurants. This class is disjoint from E77 Persistent Item. This is an abstract class and has no direct instances. E2 Temporal Entity is specialized into E4 Period, which applies to a particular geographic area (defined with a greater or lesser degree of precision), and E3 Condition State, which applies to instances of E18 Physical Thing.
++Philosurfical: The slot has-time-span is of type time-specification rather than span as it may be a time point. This is consistent with the CIPHER time ontology.""" ;
    rdfs:subClassOf [ a owl:Restriction ;
            owl:allValuesFrom <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEMPORAL-ENTITY> ;
            owl:onProperty <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#MEETS-IN-TIME-WITH> ],
        [ a owl:Restriction ;
            owl:allValuesFrom <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEMPORAL-ENTITY> ;
            owl:onProperty <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#STARTS> ],
        [ a owl:Restriction ;
            owl:allValuesFrom <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEMPORAL-ENTITY> ;
            owl:onProperty <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#OVERLAPS-IN-TIME-WITH> ],
        [ a owl:Restriction ;
            owl:allValuesFrom <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEMPORAL-ENTITY> ;
            owl:onProperty <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#FINISHES> ],
        [ a owl:Restriction ;
            owl:allValuesFrom <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEMPORAL-ENTITY> ;
            owl:onProperty <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#OCCURS-DURING> ],
        [ a owl:Restriction ;
            owl:allValuesFrom <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEMPORAL-ENTITY> ;
            owl:onProperty <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#OCCURS-BEFORE> ],
        [ a owl:Restriction ;
            owl:allValuesFrom <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEMPORAL-ENTITY> ;
            owl:onProperty <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#IS-EQUAL-IN-TIME-TO> ],
        owl:Thing .


```




#### Instances of ontology:philosurfical.owl#TEMPORAL-ENTITY can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="ontology:philosurfical.owl#TEMPORAL-ENTITY" href="class-ontologyphilosurficalowltemporal-entity.md" class="rdfclass">ontology:philosurfical.owl#TEMPORAL-ENTITY</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#FINISHES" href="prop-ontologyphilosurficalowlfinishes.md">ontology:philosurfical.owl#FINISHES</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-TIME-SPECIFICATION" href="prop-ontologyphilosurficalowlhas-time-specification.md">ontology:philosurfical.owl#HAS-TIME-SPECIFICATION</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#IS-EQUAL-IN-TIME-TO" href="prop-ontologyphilosurficalowlis-equal-in-time-to.md">ontology:philosurfical.owl#IS-EQUAL-IN-TIME-TO</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#MEETS-IN-TIME-WITH" href="prop-ontologyphilosurficalowlmeets-in-time-with.md">ontology:philosurfical.owl#MEETS-IN-TIME-WITH</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#OCCURS-BEFORE" href="prop-ontologyphilosurficalowloccurs-before.md">ontology:philosurfical.owl#OCCURS-BEFORE</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#OCCURS-DURING" href="prop-ontologyphilosurficalowloccurs-during.md">ontology:philosurfical.owl#OCCURS-DURING</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#OVERLAPS-IN-TIME-WITH" href="prop-ontologyphilosurficalowloverlaps-in-time-with.md">ontology:philosurfical.owl#OVERLAPS-IN-TIME-WITH</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#STARTS" href="prop-ontologyphilosurficalowlstarts.md">ontology:philosurfical.owl#STARTS</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            

        

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="owl:Thing" href="class-owlthing.md" class="rdfclass">owl:Thing</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-ALTERNATIVE-FORM" href="prop-ontologyphilosurficalowlhas-alternative-form.md">ontology:philosurfical.owl#HAS-ALTERNATIVE-FORM</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-ALTITUDE" href="prop-ontologyphilosurficalowlhas-altitude.md">ontology:philosurfical.owl#HAS-ALTITUDE</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-BBOXEAST" href="prop-ontologyphilosurficalowlhas-bboxeast.md">ontology:philosurfical.owl#HAS-BBOXEAST</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-BBOXNORTH" href="prop-ontologyphilosurficalowlhas-bboxnorth.md">ontology:philosurfical.owl#HAS-BBOXNORTH</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-BBOXSOUTH" href="prop-ontologyphilosurficalowlhas-bboxsouth.md">ontology:philosurfical.owl#HAS-BBOXSOUTH</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-BBOXWEST" href="prop-ontologyphilosurficalowlhas-bboxwest.md">ontology:philosurfical.owl#HAS-BBOXWEST</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-LATITUDE" href="prop-ontologyphilosurficalowlhas-latitude.md">ontology:philosurfical.owl#HAS-LATITUDE</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-LONGITUDE" href="prop-ontologyphilosurficalowlhas-longitude.md">ontology:philosurfical.owl#HAS-LONGITUDE</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#TYPICAL-OF-AREA" href="prop-ontologyphilosurficalowltypical-of-area.md">ontology:philosurfical.owl#TYPICAL-OF-AREA</a>         
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

_Documentation automatically generated on 9th November 2016 with [OntoSpy](http://ontospy.readthedocs.org/ "Open") (v1.7.0-alpha)_