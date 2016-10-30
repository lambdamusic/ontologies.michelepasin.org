Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Weapon


### Tree


* [conflict:Single_Thing](class-conflictsingle_thing.md)

    * conflict:Weapon


        * [conflict:Weapon_by_Function](class-conflictweapon_by_function.md) 

        * [conflict:Weapon_by_Target](class-conflictweapon_by_target.md) 

        * [conflict:Weapon_by_User](class-conflictweapon_by_user.md) 
        






### URI
http://purl.com/net/conflict#Weapon

### Description
&quot;A weapon is a tool used with the aim of causing damage or harm (either physical or mental) to living beings. In human society weapons are used to increase the efficacy and efficiency of tasks such as hunting, fighting, the committing of criminal acts, the preserving of law and order, and the waging of war. [http://en.wikipedia.org/wiki/Weapon]

This is a first attempt for a list of weapons relevant to SAILS..... 
It seems possible to classify weapons in three ways:
1) by user: what person or unit uses the weapon
2) by function: the construction of the weapon and principle of operation
3) by target: the type of target the weapon is designed to attack&quot;



### Inherits from (2)

- [conflict:Single_Thing](class-conflictsingle_thing.md)

- [conflict:Physical](class-conflictphysical.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Weapon a owl:Class ;<br />    rdfs:comment &quot;&quot;&quot;A weapon is a tool used with the aim of causing damage or harm (either physical or mental) to living beings. In human society weapons are used to increase the efficacy and efficiency of tasks such as hunting, fighting, the committing of criminal acts, the preserving of law and order, and the waging of war. [http://en.wikipedia.org/wiki/Weapon]</p>

<p>This is a first attempt for a list of weapons relevant to SAILS..... <br />It seems possible to classify weapons in three ways:<br />1) by user: what person or unit uses the weapon<br />2) by function: the construction of the weapon and principle of operation<br />3) by target: the type of target the weapon is designed to attack&quot;&quot;&quot;^^xsd:string ;<br />    rdfs:subClassOf :Single_Thing .</p>

<p></p>
```




### Instances of conflict:Weapon can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Weapon" href="class-conflictweapon.md" class="rdfclass">conflict:Weapon</a></span>
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