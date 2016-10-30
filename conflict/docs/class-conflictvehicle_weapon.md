Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Vehicle_weapon


### Tree


* [conflict:Military_vehicle](class-conflictmilitary_vehicle.md)

* [conflict:Weapon_by_User](class-conflictweapon_by_user.md)

    * conflict:Vehicle_weapon


        * [conflict:Armoured_Car](class-conflictarmoured_car.md) 

        * [conflict:Dennis_Military_Lorry](class-conflictdennis_military_lorry.md) 

        * [conflict:Ford_Model_T_Patrol_Car](class-conflictford_model_t_patrol_car.md) 

        * [conflict:Tank](class-conflicttank.md) 
        






### URI
http://purl.com/net/conflict#Vehicle_weapon

### Description
&quot;Vehicle weapons are designed to be mounted on any type of vehicle, and form part of the mounted armament of a military vehicle. Common varieties of this style of weapon include missile launchers and cannons.&quot;



### Inherits from (5)

- [conflict:Military_vehicle](class-conflictmilitary_vehicle.md)

- [conflict:Single_Thing](class-conflictsingle_thing.md)

- [conflict:Physical](class-conflictphysical.md)

- [conflict:Weapon_by_User](class-conflictweapon_by_user.md)

- [conflict:Weapon](class-conflictweapon.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Vehicle_weapon a owl:Class ;<br />    rdfs:comment &quot;Vehicle weapons are designed to be mounted on any type of vehicle, and form part of the mounted armament of a military vehicle. Common varieties of this style of weapon include missile launchers and cannons.&quot;^^xsd:string ;<br />    rdfs:subClassOf :Military_vehicle,<br />        :Weapon_by_User .</p>

<p></p>
```




### Instances of conflict:Vehicle_weapon can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Vehicle_weapon" href="class-conflictvehicle_weapon.md" class="rdfclass">conflict:Vehicle_weapon</a></span>
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