Vocabulary: [http://www.purl.com/net/artofmaking.owl](index.md) 



---	
	




    


## Class artofmaking.owl:Image


### Tree


* [artofmaking.owl:Document](class-artofmakingowldocument.md)

    * artofmaking.owl:Image


        * [artofmaking.owl:Digital_Image](class-artofmakingowldigital_image.md) 

        * [artofmaking.owl:Slide](class-artofmakingowlslide.md) 
        






### URI
http://www.purl.com/net/artofmaking.owl#Image

### Description
&quot;interesting for us as long as it depicts a sculpture
We&#39;ll add here some standard image metadata&quot;



### Inherits from (1)

- [artofmaking.owl:Document](class-artofmakingowldocument.md)





### Implementation
```
<p>@prefix : &lt;http://www.purl.com/net/artofmaking.owl#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Image a owl:Class ;<br />    rdfs:comment &quot;&quot;&quot;interesting for us as long as it depicts a sculpture<br />We&#39;ll add here some standard image metadata&quot;&quot;&quot; ;<br />    rdfs:subClassOf :Document .</p>

<p></p>
```




### Instances of artofmaking.owl:Image can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="artofmaking.owl:Image" href="class-artofmakingowlimage.md" class="rdfclass">artofmaking.owl:Image</a></span>
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

            

        

    

</table>













---

Documentation automatically generated with [OntoSpy](http://ontospy.readthedocs.org/ "Open") on 30th October 2016 19:16