Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Combat_Operation


### Tree


* [conflict:Military_Operation](class-conflictmilitary_operation.md)

    * conflict:Combat_Operation


        * [conflict:Campaign_Operation](class-conflictcampaign_operation.md) 

        * [conflict:Defensive](class-conflictdefensive.md) 

        * [conflict:Engagement_Operation](class-conflictengagement_operation.md) 

        * [conflict:Offensive](class-conflictoffensive.md) 

        * [conflict:Operational_Battle](class-conflictoperational_battle.md) 

        * [conflict:Theatre_operation](class-conflicttheatre_operation.md) 
        






### URI
http://purl.com/net/conflict#Combat_Operation

### Description
&quot;&amp;quot;Combat, or fighting, is a purposeful violent conflict meant to establish dominance over the opposition. Combat may take place under a certain set of rules or be unregulated. Examples of rules include the Geneva Conventions (covering the treatment of soldiers in war), medieval Chivalry,etc..

Combat in warfare involves two or more opposing military organizations, usually fighting for nations at war (although guerrilla warfare and suppression of insurgencies can fall outside this definition). Warfare falls under the laws of war, which govern its purposes and conduct, and protect the rights of soldiers and non-combatants.

We classify combat operations according to two orthogonal, non-exclusding criteria: 

1) Military operations can be classified by the scale and scope of force employment, and their impact on the wider conflict.

2) Military operations can be classified by the generic active or passive role forces have at the beginning of a conflict

&amp;quot;


TIP: in combat (and military operations at large) the actors involves take roles (eg a cruise is flotilla leader)... model this somehow!&quot;



### Inherits from (3)

- [conflict:Military_Operation](class-conflictmilitary_operation.md)

- [conflict:Event](class-conflictevent.md)

- [conflict:Temporal_Entity](class-conflicttemporal_entity.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Combat_Operation a owl:Class ;<br />    rdfs:comment &quot;&quot;&quot;&amp;quot;Combat, or fighting, is a purposeful violent conflict meant to establish dominance over the opposition. Combat may take place under a certain set of rules or be unregulated. Examples of rules include the Geneva Conventions (covering the treatment of soldiers in war), medieval Chivalry,etc..</p>

<p>Combat in warfare involves two or more opposing military organizations, usually fighting for nations at war (although guerrilla warfare and suppression of insurgencies can fall outside this definition). Warfare falls under the laws of war, which govern its purposes and conduct, and protect the rights of soldiers and non-combatants.</p>

<p>We classify combat operations according to two orthogonal, non-exclusding criteria: </p>

<p>1) Military operations can be classified by the scale and scope of force employment, and their impact on the wider conflict.</p>

<p>2) Military operations can be classified by the generic active or passive role forces have at the beginning of a conflict</p>

<p>&amp;quot;</p>

<p>TIP: in combat (and military operations at large) the actors involves take roles (eg a cruise is flotilla leader)... model this somehow!&quot;&quot;&quot;^^rdf:XMLLiteral ;<br />    rdfs:subClassOf :Military_Operation .</p>

<p></p>
```




### Instances of conflict:Combat_Operation can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Combat_Operation" href="class-conflictcombat_operation.md" class="rdfclass">conflict:Combat_Operation</a></span>
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