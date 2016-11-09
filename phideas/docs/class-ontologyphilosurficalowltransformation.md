_Vocabulary: [http://purl.com/net/phideas](index.md)_ 

---	
	




    


## Class ontology:philosurfical.owl#TRANSFORMATION


#### Tree


* [ontology:philosurfical.owl#BEGINNING-OF-EXISTENCE](class-ontologyphilosurficalowlbeginning-of-existence.md)

* [ontology:philosurfical.owl#END-OF-EXISTENCE](class-ontologyphilosurficalowlend-of-existence.md)

    * ontology:philosurfical.owl#TRANSFORMATION





*NOTE* this is a leaf node.


#### URI
http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TRANSFORMATION

#### Description
&quot;E81-CIDOC - This class comprises the events that result in the simultaneous destruction of one E77Persistent Item and the creation of another E77 Persistent Item that preserves recognizable substance from the first but has a fundamentally different nature and identity. [...] Instances of E81 Transformation are therefore distinct from re-classifications (documented using E17 Type Assignment) or modifications (documented using E11 Modification) of objects that do not fundamentally change their nature or identity.
++Philosurfical : need some consideration here - cause it&#39;s a quite important class&quot;



#### Inherits from (5)

- [ontology:philosurfical.owl#BEGINNING-OF-EXISTENCE](class-ontologyphilosurficalowlbeginning-of-existence.md)

- [ontology:philosurfical.owl#EVENT](class-ontologyphilosurficalowlevent.md)

- [ontology:philosurfical.owl#PERIOD](class-ontologyphilosurficalowlperiod.md)

- [ontology:philosurfical.owl#TEMPORAL-ENTITY](class-ontologyphilosurficalowltemporal-entity.md)

- [ontology:philosurfical.owl#END-OF-EXISTENCE](class-ontologyphilosurficalowlend-of-existence.md)





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

<http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TRANSFORMATION> a owl:Class ;
    rdfs:comment """E81-CIDOC - This class comprises the events that result in the simultaneous destruction of one E77Persistent Item and the creation of another E77 Persistent Item that preserves recognizable substance from the first but has a fundamentally different nature and identity. [...] Instances of E81 Transformation are therefore distinct from re-classifications (documented using E17 Type Assignment) or modifications (documented using E11 Modification) of objects that do not fundamentally change their nature or identity.
++Philosurfical : need some consideration here - cause it's a quite important class""" ;
    rdfs:subClassOf <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#BEGINNING-OF-EXISTENCE>,
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#END-OF-EXISTENCE> .


```




#### Instances of ontology:philosurfical.owl#TRANSFORMATION can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="ontology:philosurfical.owl#TRANSFORMATION" href="class-ontologyphilosurficalowltransformation.md" class="rdfclass">ontology:philosurfical.owl#TRANSFORMATION</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#RESULTED-IN" href="prop-ontologyphilosurficalowlresulted-in.md">ontology:philosurfical.owl#RESULTED-IN</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#TRANSFORMED" href="prop-ontologyphilosurficalowltransformed.md">ontology:philosurfical.owl#TRANSFORMED</a>         
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
            From <a title="ontology:philosurfical.owl#BEGINNING-OF-EXISTENCE" href="class-ontologyphilosurficalowlbeginning-of-existence.md" class="rdfclass">ontology:philosurfical.owl#BEGINNING-OF-EXISTENCE</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#BROUGHT-INTO-EXISTENCE" href="prop-ontologyphilosurficalowlbrought-into-existence.md">ontology:philosurfical.owl#BROUGHT-INTO-EXISTENCE</a>         
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
            From <a title="ontology:philosurfical.owl#EVENT" href="class-ontologyphilosurficalowlevent.md" class="rdfclass">ontology:philosurfical.owl#EVENT</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#HAD-PARTICIPANT" href="prop-ontologyphilosurficalowlhad-participant.md">ontology:philosurfical.owl#HAD-PARTICIPANT</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#OCCURRED-IN-THE-PRESENCE-OF" href="prop-ontologyphilosurficalowloccurred-in-the-presence-of.md">ontology:philosurfical.owl#OCCURRED-IN-THE-PRESENCE-OF</a>         
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
            From <a title="ontology:philosurfical.owl#PERIOD" href="class-ontologyphilosurficalowlperiod.md" class="rdfclass">ontology:philosurfical.owl#PERIOD</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#CONSISTS-OF" href="prop-ontologyphilosurficalowlconsists-of.md">ontology:philosurfical.owl#CONSISTS-OF</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#FALLS-WITHIN" href="prop-ontologyphilosurficalowlfalls-within.md">ontology:philosurfical.owl#FALLS-WITHIN</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#IS-SEPARATED-FROM" href="prop-ontologyphilosurficalowlis-separated-from.md">ontology:philosurfical.owl#IS-SEPARATED-FROM</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#OVERLAPS-WITH" href="prop-ontologyphilosurficalowloverlaps-with.md">ontology:philosurfical.owl#OVERLAPS-WITH</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#TOOK-PLACE-AT" href="prop-ontologyphilosurficalowltook-place-at.md">ontology:philosurfical.owl#TOOK-PLACE-AT</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#TOOK-PLACE-ON-OR-WITHIN" href="prop-ontologyphilosurficalowltook-place-on-or-within.md">ontology:philosurfical.owl#TOOK-PLACE-ON-OR-WITHIN</a>         
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
            From <a title="ontology:philosurfical.owl#END-OF-EXISTENCE" href="class-ontologyphilosurficalowlend-of-existence.md" class="rdfclass">ontology:philosurfical.owl#END-OF-EXISTENCE</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#TOOK-OUT-OF-EXISTENCE" href="prop-ontologyphilosurficalowltook-out-of-existence.md">ontology:philosurfical.owl#TOOK-OUT-OF-EXISTENCE</a>         
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