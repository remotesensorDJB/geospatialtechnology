@title[geospatial technologies]
GIS and Geospatial Technologies 
-------------------------------
### @fa[globe fa-5x]
###### D.J. Biddle, GISP
###### Use the @fa[angle-down] and @fa[angle-right] arrows to navigate
---
@title[the plan]
#### the plan
- Everything happens..._________?
- What's in a GIS?
- GIS data basics
---
#### Complete the following statement...
> "Everything happens ..."
+++
> "Everything happens SOMEWHERE!"
+++
#### Geography is...
+++
#### Geography is...

> @size[.6em](Geography is the study of places and the relationships between people and their environments. Geographers explore both the physical properties of Earth’s surface and the human societies spread across it. They also examine how human culture interacts with the natural environment, and the way that locations and places can have an impact on people. Geography seeks to understand where things are found, why they are there, and how they develop and change over time. )
- [National Geographic Society](https://www.nationalgeographic.org/encyclopedia/geography/)
+++
#### The spatial perspective
- Geographers know that where things happen, and how the locations of different people, events, and natural phenomenon relate to each other is KEY in understanding the whole picture.
- Spatial analysis is the framework we use to answer geographic questions
- Geographic Information Systems (GIS) is the tool we use to do spatial analysis!
+++
#### spatial analysis
"You know ~~nothing~~ *where it's at* Jon Snow"
![Jon Snow](https://media.giphy.com/media/13f5iwTRuiEjjW/giphy.gif)
+++
![Video](https://www.youtube.com/embed/VJ86D_DtyWg)
+++
<iframe class="stretch" data-src="https://www.arcgis.com/apps/MapJournal/index.html?appid=781630562fea4ad88e94bd22e161ba06&webmap=f4d1c17a8f1544c8903060a1e329103a"></iframe>
+++
#### It's all too real today...
![Stefan](https://media.giphy.com/media/E99OMc6pkdvGw/giphy.gif)
+++
### Spatial analysis, in simple terms...
+++
#### Where? questions...
A GIS lets us ask many geographic questions, like...

- Where is it? What area does it cover? (**spatial questions**)
- What is there? How much is there? (**attribute questions**)
- How have the location or attributes changed over time? (**temporal questions**)
+++
#### More questions...
when considering multiple geographic entities...

- Do they overlap? 
- Are they connected to one another? 
- Are they within a certain distance of each other?
- Do they share the same attributes? Where? 
- How do nearby things relate to each other? 
+++
With these questions in mind...
+++
#### A Scenario!
- A dangerous chemical spills from a local factory, threatening the surrounding neighborhoods!
- The chemical spill will affect all residents within 1 mile of the factory
- But! Because the chemical flows downhill, houses that are on higher ground are safe!
- Who do we need to evacuate? 
+++
#### Mapwoman to the rescue!
![Map Woman](images/mapwoman.jpg)
--- 
#### what's in a gis? 
> @size[.6em](A geographic information system <GIS> is a framework for gathering, managing, and analyzing data. Rooted in the science of geography, GIS integrates many types of data. It analyzes spatial location and organizes layers of information into visualizations using maps and 3D scenes. ​With this unique capability, GIS reveals deeper insights into data, such as patterns, relationships, and situations—helping users make smarter decisions.) 
###### -Environmental Research Systems Institute (ESRI)
+++
##### A brief history of GIS mapping
<iframe src="https://drive.google.com/file/d/14NXbB7lDR-LTifBCatXSAXXGFQzf1EGU/preview" width="640" height="480"></iframe>
+++
@title[gis components]
![GIS Components](images/components.jpg)
+++
@title[gis layers concept]
![GIS Layers Concept](images/GIS-layers.jpg)
+++
@title[gis database concept]
![GIS Database Link](images/link.png)
+++
@title[gis applications]
![GIS Applications](images/gis-applications.jpg)
+++
##### Our Scenario...
- A dangerous chemical spills from a local factory, threatening the surrounding neighborhoods!
- The chemical spill will affect all residents within 1 mile of the factory
- But! Because the chemical flows downhill, houses that are on higher ground are safe!
- Who do we need to evacuate?
+++
@transition[fade]
![Scenario 1](images/scenario-1.JPG | width=70)
+++
@transition[fade]
- 1 mile buffer around site
![Scenario 2](images/scenario-2.JPG | width=70)
+++
@transition[fade]
- select buildings with elevation < factory
![Scenario 3](images/scenario-3.JPG | width=70)
+++
@transition[fade]
- select buildings with elevation > factory
![Scenario 4](images/scenario-4.JPG | width=70)
+++
@transition[fade]
- query land record to identify landowners for call list
![Scenario 5](images/scenario-5.JPG | width=70)
---
### Common GIS Applications
+++
##### Demographic Mapping/Social Sciences
- Where are vulnerable populations located?
- How do environmental hazards differential impact different social groups
- Environmental Justice? 
+++
@title[demographic mapping example]
[Demographic Mapper](http://www.ulcgis.org/flexviewers/KIPDA_Map)
![](images/demographic.JPG)
+++
@title[environmental justice example]
https://ejscreen.epa.gov/mapper/
![](images/env_justice.JPG | width=70)
+++
##### Physical Sciences
- Species habitat mapping/modeling
- Land cover change analysis
- Natural hazards vulnerability 
- Climate change monitoring
+++
##### Site Selection
- Where should a new business be located?
  - Where are the customers?
  - How far will they have to travel? 
  - Will they buy your product?
  - Where is the competition located?
+++
##### Example: Food Deserts
> [The Geospatial Revolution: Food Deserts](https://ket.pbslearningmedia.org/resource/psu10sci.vid.geospatial.fooddeserts/geospatial-revolution-food-deserts/?)
+++
##### Logistics/Transportation
- How can we minimize transportation costs?
- What is the best route for the UPS truck?
- Do we need a new TARC route due to population growth? 
+++

+++
##### journalism/storytelling
- Story Maps convey place-based narratives about a topic or idea
- Mashups of maps, text, and multimedia in an interactive web applications
- Effective and engaging communication in a web browser
- https://storymaps.esri.com

+++
@title[story map example 1]
<iframe class="stretch" data-src="https://centerforgis.maps.arcgis.com/apps/Cascade/index.html?appid=08c2849d3f1649758e40b8cfa67d0248"></iframe>
+++
@title[story map example 2]
<iframe class="stretch" data-src="https://centerforgis.maps.arcgis.com/apps/MapSeries/index.html?appid=e7fd5854dbab435b944c27913df01980"></iframe>
+++
@title[story map example 3]
<iframe class="stretch" data-src="https://centerforgis.maps.arcgis.com/apps/Cascade/index.html?appid=307e73fffa6f4206b9d356459998b607"></iframe>
+++
##### 1,000 Uses for GIS
There are literally thousands of ways to use GIS to answer questions, create new knowledge, and help people understand their world a little better!
https://gisgeography.com/gis-applications-uses/ 
+++
### What is GIS to YOU? 
Let's use the remainder of the class to share our perspectives on GIS from our own interests...
---


	


 