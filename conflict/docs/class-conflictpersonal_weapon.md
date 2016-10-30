Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Personal_weapon


### Tree


* [conflict:Weapon_by_User](class-conflictweapon_by_user.md)

    * conflict:Personal_weapon


        * [conflict:Bayonet](class-conflictbayonet.md) 

        * [conflict:Bolt_action_Rifle](class-conflictbolt_action_rifle.md) 

        * [conflict:Flamethrower](class-conflictflamethrower.md) 

        * [conflict:Pistol](class-conflictpistol.md) 
        






### URI
http://purl.com/net/conflict#Personal_weapon

### Description
&quot;These weapons are designed so that they can be carried and used by a single person, and are used by the military, police, and for personal defence. The term &#39;small arms&#39; is generally limited to firearms such as assault rifles, sniper rifles, pistols, revolvers, submachine guns, squad automatic weapons and light machine guns.

However, personal weapons can also include all types of weapon that can be wielded by one person, such as swords, knives, clubs, crossbows and bayonets.&quot;



### Inherits from (4)

- [conflict:Weapon_by_User](class-conflictweapon_by_user.md)

- [conflict:Weapon](class-conflictweapon.md)

- [conflict:Single_Thing](class-conflictsingle_thing.md)

- [conflict:Physical](class-conflictphysical.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Personal_weapon a owl:Class ;<br />    rdfs:comment &quot;&quot;&quot;These weapons are designed so that they can be carried and used by a single person, and are used by the military, police, and for personal defence. The term &#39;small arms&#39; is generally limited to firearms such as assault rifles, sniper rifles, pistols, revolvers, submachine guns, squad automatic weapons and light machine guns.</p>

<p>However, personal weapons can also include all types of weapon that can be wielded by one person, such as swords, knives, clubs, crossbows and bayonets.&quot;&quot;&quot;^^xsd:string ;<br />    rdfs:subClassOf :Weapon_by_User .</p>

<p></p>
```




### Instances of conflict:Personal_weapon can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Personal_weapon" href="class-conflictpersonal_weapon.md" class="rdfclass">conflict:Personal_weapon</a></span>
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