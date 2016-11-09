_Vocabulary: [http://purl.com/net/phideas](index.md)_ 

---	
	




    


## Class ontology:philosurfical.owl#HUMANISTIC-DISCIPLINE


#### Tree


* [ontology:philosurfical.owl#GENERIC-FIELD-OF-STUDY](class-ontologyphilosurficalowlgeneric-field-of-study.md)

    * ontology:philosurfical.owl#HUMANISTIC-DISCIPLINE


        * [ontology:philosurfical.owl#BRANCH-OF-PHILOSOPHY](class-ontologyphilosurficalowlbranch-of-philosophy.md) 
        






#### URI
http://philosurfical.open.ac.uk/ontology/philosurfical.owl#HUMANISTIC-DISCIPLINE

#### Description
&quot;++PhiloSURFical :&quot;



#### Inherits from (3)

- [ontology:philosurfical.owl#GENERIC-FIELD-OF-STUDY](class-ontologyphilosurficalowlgeneric-field-of-study.md)

- [ontology:philosurfical.owl#PROBLEM-AREA](class-ontologyphilosurficalowlproblem-area.md)

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

<http://philosurfical.open.ac.uk/ontology/philosurfical.owl#HUMANISTIC-DISCIPLINE> a owl:Class ;
    rdfs:comment "++PhiloSURFical :" ;
    rdfs:subClassOf <http://philosurfical.open.ac.uk/ontology/philosurfical.owl#GENERIC-FIELD-OF-STUDY> .


```




#### Instances of ontology:philosurfical.owl#HUMANISTIC-DISCIPLINE can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="ontology:philosurfical.owl#HUMANISTIC-DISCIPLINE" href="class-ontologyphilosurficalowlhumanistic-discipline.md" class="rdfclass">ontology:philosurfical.owl#HUMANISTIC-DISCIPLINE</a></span>
            </th>
        </tr>       

            

        

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="ontology:philosurfical.owl#GENERIC-FIELD-OF-STUDY" href="class-ontologyphilosurficalowlgeneric-field-of-study.md" class="rdfclass">ontology:philosurfical.owl#GENERIC-FIELD-OF-STUDY</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#DEFINED-BY-VIEW" href="prop-ontologyphilosurficalowldefined-by-view.md">ontology:philosurfical.owl#DEFINED-BY-VIEW</a>         
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
            From <a title="ontology:philosurfical.owl#PROBLEM-AREA" href="class-ontologyphilosurficalowlproblem-area.md" class="rdfclass">ontology:philosurfical.owl#PROBLEM-AREA</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="ontology:philosurfical.owl#CONTAINS-PROBLEM" href="prop-ontologyphilosurficalowlcontains-problem.md">ontology:philosurfical.owl#CONTAINS-PROBLEM</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-CENTRAL-PROBLEM" href="prop-ontologyphilosurficalowlhas-central-problem.md">ontology:philosurfical.owl#HAS-CENTRAL-PROBLEM</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#HAS-SUB-AREA" href="prop-ontologyphilosurficalowlhas-sub-area.md">ontology:philosurfical.owl#HAS-SUB-AREA</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#RELATED-TO-AREA" href="prop-ontologyphilosurficalowlrelated-to-area.md">ontology:philosurfical.owl#RELATED-TO-AREA</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#SPECIFIED-BY-CRITERIA" href="prop-ontologyphilosurficalowlspecified-by-criteria.md">ontology:philosurfical.owl#SPECIFIED-BY-CRITERIA</a>         
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
                    <a class="propcolor" title="ontology:philosurfical.owl#SUB-AREA-OF" href="prop-ontologyphilosurficalowlsub-area-of.md">ontology:philosurfical.owl#SUB-AREA-OF</a>         
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