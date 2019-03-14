Final Project Guidelines
1. Requirement
Regarding the final project, you are expected to work individually or in pair to make a web map. The final project can be simple and focused in nature, but must include:

Host your web map on github; Then the map eventually can be visited via a url link such as https://burkr.github.io/storymap/index.html

The map should also include several map elements, such as map title, map description, overview map, legend, scale bar, north arrow, data source, credit, or acknowledgement.

The map's title is Culturally Significant Plants. The maps are described, there are legends for most of the maps, a scake bar, the source of data is in the citations/credits on the last page of the story map with links to the webpages. 

One or more basemap to give geographic context:

Basemap 1 was two images from http://www.native-languages.org/washington.htm  that I combined together in Adobe PhotoShop and Georeferenced in QGIS.  This first map I colored green in PhotoShop as well.  

The similiar base maps (that I used for Camas, Carrot, Huckleberry, and Oregon grape) in white I used a .CSV files from Oregon Flora (http://www.oregonflora.org/atlas.php), and put it in geojson.io.  I then Georeference the tribes base image to the geojson to get the plant points to go on the 'georeferenced' image.  

After making this map, I realized it really is the ONLY ONE of it's kind-showing distribution of plants over a map of traditional tribal territories.  I will be using this for my thesis presentation as well!!


The other base maps came directly from https://osugisci.maps.arcgis.com/apps/MapJournal/    as they have a whole 'library' of maps to choose from.  

One or more thematic layers that are separate from the basemap (e.g., Choropleth map, Heatmap, and etc.); and

I used heatmaps for the Camas map and for the Huckleberry varities I used dots that represented the color of the berry!

For the Oregon Grape I used the color of the dye made from the root of the plant.  

For the Wild Carrot I used orange dots, because we generally recognize carrots as orange. 

One or more interactive elements that reveal more information (e.g., click a feature to trigger pop-up window, hover to change the style of a feature).

The interactive elements in the story map are popups with the attribute table information for the particular point or polygon.

Also, The legend drops down when you click on it. 
The map zooms in and out with the scroll wheel of the mouse, and the story map side panel scrolls as well.  
There are clickable links to the Credits and Citations, and to my Github page. 
In the far right bottom corner is a link to share the story map web page. 
In the footer is a link to the CEOAS Home page.

A readme.md describes your web map, including, but not limited to:

Project title: Culturally Significant Plants
Project description: An overview of Culturally Significant Plants and related aspects such as Tribes of Oregon, Tribal Territories/borders, and Federal Agencies. 

Project goal (such as, what is the message you want to deliver through the map?)  
To be aware that plants are important to pay attention to when doing field surveys. 

Technical Summary: You are required to explain 
(1) system architecture, 
The main system of the story map is held within a iframe and is hosted on an ESRI map server

(2) the main functions of your web map using either a screenshot of the web map or a code snippet of the function, and a concomitant description.  
The main functions of the webmap include the scrolling side panel that holds the main story text and reference images.

Reflection on the course of designing your web map: 
This class was very very helpful.  I had a little HTML experience when I started the class, plus a few classes with ESRI Arc Software.  By the end of the class, I understand alot more about building websites and websites with maps in them.  The Storymap is like a master piece, and I will definitely use it for my final thesis presentation!!!

Data source: 
The main source of data for the final map is from ESRI map server, and Oregon Flora CSV. files, and it is all hosted by GitHub. https://burkr.github.io/storymap/index.html
Libraries (e.g., Leaflet) and Web Services (e.g., github, basemap) in use
Credits: 

~~Credits and Citations~~

 
Base maps & ArcGIS Online Storymap Builder

https://developerscorner.storymaps.arcgis.com/grow-your-story-maps-audience-with-open-graph-tags-b7639cb65d5c

George Washington’s Tree: Oppenheim, Maya 2018. 227-year-old tree planted by George Washington pulled down by wind. The Independent: https://www.independent.co.uk/news/world/americas/george-washington-tree-winds-pull-down-mount-vernon-a8239061.htmlOR: http://edition.independent.co.uk/

Estimated Traditional Tribal Territories-Native Languages of the Americas website © 1998-2015
http://www.native-languages.org/washington.htm

Plant Distributions-The Oregon Flora Project  
http://www.oregonflora.org/

Plant Voucher Specimen of Wild Carrot-http://oregonstate.edu/dept/botany/herbarium/

Quote about Williamette Valley: Boyd, R. (1999). Indians, fire, and the land in the Pacific Northwest (1st ed.). Corvallis, Or.: Oregon State University Press.

 

Plant Photos-Taken by Rene Burk 

Acknowledgement
Other things necessary to inform the audience of your web map.
you should use at least one web mapping technique that was NOT covered in the course materials, but may be introduced in the reading list or something you find over the Internet. This could, for instance, be a leaflet (or cesium) function. You don't have to specify this additional function when you draft the proposal, but as you work through the different practical exercises, you should stay aware of this function you could incorporate to meet this requirement.

Georeferencing maps was not covered in this course, or my other ArcGIS classes.  I learned about it at work, in ARC Gis version 10.  
Although, QGIS is new to me, so I needed some help from the Roman Archaeologist (name?), to Georeference the image in QGIS. 


2. Submission
Please submit the url link of your final project's github repository to the final project submission tab on Canvas. (on March 21st by 5:00pm).

3. Presentation and peer review
Each team (made up of an individual or pair) is expected to present their final project in ~10 minutes. And there will be a question session in 2 ~ 3 minutes. During the final presentation, each student will need to review all final projects and submit your review notes.

4. Timeline
Submit your project proposal to Canvas Dropbox. The proposal should at least contain the project topic, potential audience, and the possible data sources.

The instructor and the TA will help each team look for data, map libraries and fine-tune the web map interface design. Each team will have one month to work on the final project.

Submit the url link to the final project submission tab on Canvas on March 21st by 5:00pm.

**On March 19th during noon to 2:00pm **, we will hold a final project presentation meeting at digital earth lab.



