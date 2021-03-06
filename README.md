# Impossible Maps

**Instructor:** Mimi Onuoha  (cgo221@nyu.edu)  
**Term:** Spring 2018, NYU ITP  
**Time:** Tuesdays, 12:10pm - 2:40pm   
**Office Hours:** Wednesdays 10am- 12pm ([Link for scheduling](https://calendar.google.com/calendar/selfsched?sstoken=UUl0bkJBeEw5QmpTfGRlZmF1bHR8MTVmMGJiY2ZkYjkyNWQ0NGQ1Y2YzODliMDQ0MmRlODU)) or email

Submit homework [HERE](https://docs.google.com/forms/d/e/1FAIpQLSfocVAYIRgXef4dXbr-fu3qYdosTLTtE6ZwEQDbkuiJljYWCw/viewform?usp=sf_link). 

## Course Description 

Digital technologies have created new opportunities and resources for mapping, cartography, and geolocation-based visual investigation. They have also brought with them the need to consider issues concerning power, representation, and space.

In this seven-week course, students will learn the practical realities of working with spatial geographies in digital and web-based contexts. Time will also be devoted to investigating the conceptual questions that inform mapping and strategies for art-based counter-mapping. The course will address questions such as: What makes a good digital or web map? What do maps represent as visual information artifacts? What happens when we consider claims to space as topics for art-based investigations?

Students will gain exposure to a broad range of techniques in web and digital mapping, with the goal that they eventually focus on one or two. Throughout the course, students will be challenged to make maps (or map-based creations) that function as artful objects and challenge common conventions of the capabilities of maps. The class will be taught primarily in JavaScript, with assignments making use of git and Github. Other technologies taught will include mapshaper, Leaflet.js, Mapbox.js, and Carto.

## Expectations and Requirements
- Class attendance and punctuality 
- Participation during class discussions and presentations
- Weekly assignments + accompanying blogpost  
- Midterm and final project (completed individually or in groups)

This class is an inclusive and harassment-free space for everyone, with no tolerations of discimination based on gender, race, sexual orientation, religion, disability, or appearance. Please feel free to let me know privately if you have an academic accommodation.  

All students are allowed a maximum of one absence. It is worth stressing that because the class covers so much new material, it is very much to your advantage to attend all classes if possible. 

Homework should be submitted at least **one hour** before class begins. This gives me time to look at your work, provide feedback, and structure the class in response to what you've submitted. 


## Evaluation
Final evaluation will be based on the completion of all assignments, class participation, quality of work, and attendance. 

Be sure to complete the readings assigned for homework. Not only are they painless, useful, and interesting, but the in-class discussions will be far richer if everyone has completed the required reading.   

For the final projects, I am more interested in what you choose to do than in what you can do. We will elaborate on these distinctions in class. 

## Format 
Each class will begin with exposure to an interesting map or application of mapping, followed by students presenting assignments from the previous week. If there was a reading/viewing assigned, the class will include a brief discussion (no laptops open during discussion). The bulk of the class will be spent introducing and experimenting with more technical mapping methods and tools and teasing out the critical connotations of these objects and techniques. I will screen record some of these sections of class so that you can refer to them outside of class.

I can be reached via email at all times, but am slow to respond to emails sent over the weekend. If you are in need of a prompt response, please email during the week. I reserve 24 hours to respond, but typically will reply much sooner. 

## Syllabus
**WEEK ONE** (March 20): Introductions      
*Introductions to class and to each other/semester set-up:  What is a map, what is the history of mapping, what the different parts of a web map do and what they can be used for, what are impossible maps?* 

Reading:

- "Experimental Geography: From Cultural Production to the Production of Space", Trevor Paglen

Assignment:

- Go through [this](http://maptime.io/anatomy-of-a-web-map/#0) (may take a minute to load correctly)
- Create a map like the map we made in class. Consult the [leaflet documentation](http://leafletjs.com/) to figure out how to change the view of your map (based on lat and long values) and how to add a marker and popup. Get your map online in some fashion and submit it using the homework form (above).
- Along with your map, post a short 300-500 word entry about your thoughts on the readings, the process of making your first web map(s), or anything we talked about in class. What is interesting (or uninteresting) to you about maps, space, and digital representations of both? 
- If you're not used to the terminal or the command line, I highly suggest you read Allison Parrish's text on [UNIX text processing tools](http://rwet.decontextualize.com/book/unix/) up until the section that begins with "Structure of UNIX commands".

BONUS: (not required, we won't talk about it in class, but just for those of you who can't get enough): skim the intro to [this comparison](https://www.justinobeirne.com/cartography-comparison) between Apple and Google Maps. 



**WEEK TWO**  (March 27):  The Perils of Web Mapping    
*Slippy web maps, the differences between Leaflet and Mapbox and vector vs raster tiles.  What is geodata, how do we create it and add it to our maps?* 

Readings:

- ["Trap Streets"](http://www.cabinetmagazine.org/issues/47/bridle.php), James Bridle 
- "[Sorry, We Have No Imagery Here](https://www.atlasobscura.com/articles/investigating-censored-spots-on-google-earth)", Meg Van Huygen

Assignment:

- Create a map using mapboxgl.js. You should include data in the form of points, circles, or markers on top of the basemap (and are welcome to include more than that). You have options for what to map: either extend the mag that we began to create in class with earthquake data, remake your map from last week, or create your own dataset using [geojson.io](http://geojson.io/) and add that to the map. 

- Submit your homework using the homework form (see above). 

  NOTE: check the "useful things" document and the examples if you need any help on the things we spoke about. 


**WEEK THREE** (April 3): The Battle for Data    
*Diving deeper into geodata, working with external datasets, wrangling geodata to meet our needs.*

Readings:

- [Mapping's Intelligent Agents](https://placesjournal.org/article/mappings-intelligent-agents/) by Shannon Mattern 

Assignment:

- Take the map that you created last week and extend it by adding another data source. Think about the story of the map—what could be added that would contribute to what you did? For it to make sense, do you now have to remove something? Consider how the data are all working together to tell a greater story. 
  - [Optionally, you can take one of the exercises we did in class and expand on it]
- Find a way to make sure that your map is intelligible to someone coming to it for the first time (this might mean incorporating a title, legend, landing page, etc.)
- Get your map online in some way, shape, or form, so that we can see it with a link (consider using [github pages](https://pages.github.com/)).
- Submit your homework using the homework form (see above). 


**WEEK FOUR** (April 10): A Sense of Place (+ design considerations)   
*Changing geodata into useful forms, working with multiple datasets, design considerations for our maps.*

Readings:

- [Feminist Data Visualizatio](https://civic.mit.edu/feminist-data-visualization)n, Catherine D'Ignazio 
- "Representation and the Necessity of Interpretation", Laura Kurgan (find in readings folder as kurgan2

Assignment:

- This week you don't have to create a map. Instead, you should write two things:

  - A 200 word response to the readings (what are you thoughts? what do you disagree or disagree with? what are you thinking differently about?)
  - Your **decision for  what you want to do for your final project.** Post this on your blog and submit it using the homework form. (It's okay if this isn't completely finalized, but you should still post your general ideas and what you're thinking of.)

- NOTE: If you haven't completed the homework assignments up to this point, this week is your chance to catch up. 

  Look out for an email from me about this week's upcoming class. 

**WEEK FIVE** (April 17): Counter-Mapping as Practice   
*Exploring aerial imagery and the material experience of mapping.* 

You have no reading this week, and your assignment is optional. Use this week to start working on your final project (yes, you have two weeks to work on it). 

Assignment:

- OPTIONAL: Use [these images](https://www.dropbox.com/sh/rju8axnigf0injo/AABqFN8yU90U0imAVHsmozoPa?dl=0) gathered from a balloon mapping expedition at Bennington College in Vermont to create an aerial map! To do this, you will need to use [MapKnitter](https://mapknitter.org/). Watch the tutorial video on the main page to use the software (it is relatively straightforward.)
  - If you do this assignment, make sure to export it as an image and post it on your website. Submit the post/map using the homework form. If you haven't done another homework assignment, this can count as a make-up. 
- NOT OPTIONAL: Start working on your final project. 

NOTE 1: I won't be in class next week, but you should still show up at the normal time for a guest speaker. 

NOTE 2: Because I won't be in the next class, over the course of the week I'll be conversing with each of you about your final projects. Look out for emails from me! 

**WEEK SIX** (April 24): The View from Above    
*Guest Speakers* 

Your homework this week is to work on your final projects! 


**WEEK SEVEN**(May 1): Final Presentations     



