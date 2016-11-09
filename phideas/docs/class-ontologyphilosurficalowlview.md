_Vocabulary: [http://purl.com/net/phideas](index.md)_ 

---	
	




    


## Class ontology:philosurfical.owl#VIEW


#### Tree


* [ontology:philosurfical.owl#PHILOSOPHICAL-IDEA](class-ontologyphilosurficalowlphilosophical-idea.md)

    * ontology:philosurfical.owl#VIEW


        * [ontology:philosurfical.owl#PHILOSOPHICAL-SYSTEM](class-ontologyphilosurficalowlphilosophical-system.md) 

        * [ontology:philosurfical.owl#SCHOOL-OF-THOUGHT](class-ontologyphilosurficalowlschool-of-thought.md) 

        * [ontology:philosurfical.owl#THEORY](class-ontologyphilosurficalowltheory.md) 

        * [ontology:philosurfical.owl#THESIS](class-ontologyphilosurficalowlthesis.md) 
        






#### URI
http://philosurfical.open.ac.uk/ontology/philosurfical.owl#VIEW

#### Description
&quot;++PhiloSURFical : Generic class referring to propositions expressing a viewpoint, that is, descriptions defining other concepts and, in general, meanings. The property exists-in-area can have multiple values.Defines-method is excluded at this level cause a thesis is not enough to define a method. Another possible relationis defines-key-concept...&quot;



#### Inherits from (1)

- [ontology:philosurfical.owl#PHILOSOPHICAL-IDEA](class-ontologyphilosurficalowlphilosophical-idea.md)





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

<http://philosurfical.open.ac.uk/ontology/philosurfical.owl#VIEW> a owl:Class ;
    rdfs:comment "++PhiloSURFical : Generic class referring to propositions expressing a viewpoint, that is, descriptions defining other concepts and, in general, meanings. The property exists-in-area can have multiple values.Defines-method is excluded at this level cause a thesis is not enough to define a method. Another possible relationis defines-key-concept..." ;
    rdfs:subClassOf [ a owl:Restriction ;
            owl:allValuesFrom <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TEMPORAL-ENTITY> ;
            owl:onProperty <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#INTERPRETS-FACT> ],
        [ a owl:Restriction ;
            owl:allValuesFrom <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#PROBLEM-AREA> ;
            owl:onProperty <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#EXISTS-IN-AREA> ],
        [ a owl:Restriction ;
            owl:allValuesFrom <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#INTELLECTUAL-MOVEMENT> ;
            owl:onProperty <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#TYPIFIES> ],
        <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#PHILOSOPHICAL-IDEA> .


```




#### Instances of ontology:philosurfical.owl#VIEW can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="ontology:philosurfical.owl#VIEW" href="class-ontologyphilosurficalowlview.md" class="rdfclass">ontology:philosurfical.owl#VIEW</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#EXISTS-IN-AREA" href="prop-ontologyphilosurficalowlexists-in-area.md">ontology:philosurfical.owl#EXISTS-IN-AREA</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#INTERPRETS-FACT" href="prop-ontologyphilosurficalowlinterprets-fact.md">ontology:philosurfical.owl#INTERPRETS-FACT</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#TYPIFIES" href="prop-ontologyphilosurficalowltypifies.md">ontology:philosurfical.owl#TYPIFIES</a>         
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
            From <a title="ontology:philosurfical.owl#PHILOSOPHICAL-IDEA" href="class-ontologyphilosurficalowlphilosophical-idea.md" class="rdfclass">ontology:philosurfical.owl#PHILOSOPHICAL-IDEA</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-COMMON-NAME" href="prop-ontologyphilosurficalowlhas-common-name.md">ontology:philosurfical.owl#HAS-COMMON-NAME</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-DESCRIPTION" href="prop-ontologyphilosurficalowlhas-description.md">ontology:philosurfical.owl#HAS-DESCRIPTION</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-REFERRED-AUTHOR" href="prop-ontologyphilosurficalowlhas-referred-author.md">ontology:philosurfical.owl#HAS-REFERRED-AUTHOR</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#WAS-MADE-BY" href="prop-ontologyphilosurficalowlwas-made-by.md">ontology:philosurfical.owl#WAS-MADE-BY</a>         
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