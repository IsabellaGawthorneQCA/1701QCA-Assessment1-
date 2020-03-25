
## Replication project choice ##
Banana keyboard 

## Related projects ##
*Find about 6 related projects to the project you choose. A project might be related through  function, technology, materials, fabrication, concept, or code. Don't forget to place an image of the related project in the* `replicationproject` *folder and insert the filename in the appropriate places below. Copy the markdown block of code below for each project you are showing, updating the number* `1` *in the subtitle for each.*

### Related project 1 ###
The extended clarinet 
https://www.nime.org/proceedings/2016/nime2016_paper0034.pdf

![Image](extendedclarinet.PNG)

This project relates on the basis of functionality and how the user interacts with the device. Both prioritise the inclusivity of the user in making the instrument work. the clarinets function relies on the user physically playing the instrument to send signals to the attachment created (the bell). This relates to the keyboard as we see this need for physical action to cause reaction in electrical sygnals. the augumented clarinet also focuses on maintaining the original form and way in which it is played, when comparing this to the banana keyboard it is evident that the pressing on the key motion maintains these aspects as well. this device uses a touch sensor technology to switch between differing modes, in the keyboard the same concept is used to send signals to the microbit and speaker. 

### Related project 2 ###
Sibilim
https://www.nime.org/proceedings/2019/nime2019_paper004.pdf

![Image](sibilim.PNG)
The sibilim is also an approach to the keyboard in a differing form. it demonstrates how light sensors may be used in place of touch sensors. Both the banana keyboard and sibilim focus on recreating the experience of a standard keyboard in a more technologicaly interactive way. This device uses a carboard frame as a lowcost effective approach, this may be used when creating the final project of the banana keyboard. the flow of this circuit works in a similar way as well , showing thisinteraction from user to key to phone/microbit. 

### Related project 3 ###
Otamatone 

https://otamatone.com/about-otamatone/

![Image](otamatone.PNG)

This project is related to mine because (insert reasons here).

### Related project 4 ###
The sponge

http://www.martinmarier.com/wp/?page_id=12

![Image](thesponge2.PNG)

This project is related to mine because (insert reasons here).

### Related project 5 ###
touch keys

https://www.nime.org/proceedings/2012/nime2012_195.pdf

![Image](touchkeys.PNG)

This project is related to mine because (insert reasons here).

### Related project 6 ###
Somacoustics

https://www.nime.org/proceedings/2019/nime2019_paper019.pdf

![Image](somacoustics.PNG)

This project is related to mine because (insert reasons here).

## Reading reflections ##
*Reflective reading is an important part of actually making your reading worthwhile. Don't just read the words to understand what they say: read to see how the ideas in the text fit with and potentially change your existing knowledge and maybe even conceptual frameworks. We assume you can basically figure out what the readings mean, but the more important process is to understand how that changes what you think, particularly in the context of your project.*

*For each of the assigned readings, answer the questions below.*

### Reading: Don Norman, The Design of Everyday Things, Chapter 1 (The Psychopathology of Everyday Things) ###

*What I thought before: Describe something that you thought or believed before you read the source that was challenged by the reading.*

*What I learned: Describe what you now know or believe as a result of the reading. Don't just describe the reading: write about what changed in YOUR knowledge.*

*What I would like to know more about: Describe or write a question about something that you would be interested in knowing more about.*

*How this relates to the project I am working on: Describe the connection between the ideas in the reading and one of your current projects or how ideas in the reading could be used to improve your project.*

### Reading: Chapter 1 of Dan Saffer, Microinteractions: Designing with Details, Chapter 1 ###

*What I thought before: Describe something that you thought or believed before you read the source that was challenged by the reading.*

*What I learned: Describe what you now know or believe as a result of the reading. Don't just describe the reading: write about what changed in YOUR knowledge.*

*What I would like to know more about: Describe or write a question about something that you would be interested in knowing more about.*

*How this relates to the project I am working on: Describe the connection between the ideas in the reading and one of your current projects or how ideas in the reading could be used to improve your project.*

### Reading: Scott Sullivan, Prototyping Interactive Objects ###

*What I thought before: Describe something that you thought or believed before you read the source that was challenged by the reading.*

*What I learned: Describe what you now know or believe as a result of the reading. Don't just describe the reading: write about what changed in YOUR knowledge.*

*What I would like to know more about: Describe or write a question about something that you would be interested in knowing more about.*

*How this relates to the project I am working on: Describe the connection between the ideas in the reading and one of your current projects or how ideas in the reading could be used to improve your project.*


## Interaction flowchart ##
*Draw a flowchart of the interaction process in your project. Make sure you think about all the stages of interaction step-by-step. Also make sure that you consider actions a user might take that aren't what you intend in an ideal use case. Insert an image of it below. It might just be a photo of a hand-drawn sketch, not a carefully drawn digital diagram. It just needs to be legible.*

![Image](missingimage.png)

## Process documentation

![Image](1.fruitwithearphones.jpeg)
This is a complete translation of the assigned 'banana keyboard' project, from this it was evident that the user became apart of the circuit and thus transfered the electirc current from the orange to the banana. In doing so code was given to make this interaction cause a tone to sound. To operate this action it is required that one hand touches the orange at all times, this is as the orange is connected via alligator clips to the ground source of the micro;bit. 
![Image](2.circuitformedfromorangetobanana.jpeg) 
Below shows a rough diagram of the connections between the elements of the circuit; 
![Image](flowdiagram2fruits.JPG)

Considerations from this intial project;
- how can I elaberate on or change the existing elements?
- adding another key 
-converting earphones to sepaker
-creating sound from other sources 
-display lights 

![Image](3.addidnganotherfruit.jpeg)
To utelize the spare pin 2 I connected another fruit to form another key tone, the following code was used 
![Image](code1replicationexactly.PNG)  
![Image](flowdiagram3fruits.JPG)  

It is evident that both keys give differing effects, ones tone increases while the other decreases to create contrast 

![Image](4.substitutingspeaker.jpeg)
By adding a speaker the project becomes much more inclusive of others to interact rather than just an individual expierence, this simply meant taking the alligator clips and unclipping them from the earphones, thus substituting the speaker in place


![Image](5.tryingtoaddafourthfruit.jpeg)
wanting to increase the complexity of the project i attempted adding yet another key. however on several attempts of altering code and checking the wire connections, this attempt did not follow through. when adding the key to pin 0 it will only play the key before the other keys are pressed, once a key on pin 1 or 2 is played you cannot play pin 0 again.
![Image](codeattempting4thfruitonpin0.PNG)

utelizing buttons A and B as substitues for keys i could not create using the aligator clips and pins, to add more sounds and thus create more of a keyboard concept. to identify these notes the LED screen displays lights arrange in the letter of the note played.
![Image](6.buttonAdisplayinglights.jpeg)
![Image](7.pin1lights.jpeg)
![Image](8.pin2lights.jpeg)
![Image](9.buttonBlights.jpeg)

these are the codes used; 
![Image](codemakingbuttonsnotes.PNG)
![Image](codeletters.PNG)

due to the perishable nature of fruit i decided to change the keys into pieces of alfoil, this is as alfoil works as an excellent conductor of electricity, later on in the final presentation the use of alfoil will be more tidy. 
![Image](10.changingfruittofoil.jpeg)

i tried another approach to adding more keys through the use of a breadboard. to do this i located a source online 'https://www.youtube.com/watch?v=ulKq5To9dmA' to assist with the coding and assembly of this project. however, i had to substitute certain wires as i did not have them and removed 2 keys in order to do so. As a result the piano would not play past the keys attached to pins 1 and 2. from this I gathered that the resistors may have not been the required type or that some step in this process went wrong. this is also why i decided to revert back to the original design as pins 1 and 2 where all that was required. 
![Image](11.attemptataddingmorenotesthroughbreadboard.jpeg)
![Image](12.attemptataddingmorenotesothersideview.jpeg)
![Image](codebreadboardattempt.PNG)
In attempting to fix the resistor problem i removed them all together, however this made the keys play by themselves as there are no signials indicating when the keys should stop or start playing. although this was an interesting concept it removed the element of interaction between user and device, therefore i moved on from this concept. 
![Image](13.didntworksoremovedotherelementsmadepianoplaybyself.jpeg)

reverting back to original concept design
for pins 1 and 2 i decided to add corresponding light signals to indicate when the sound is high or when it is low.
![Image](14.backtooriginaldesignshowignhighnotearrow.jpeg)
![Image](15.backtooriginaldesginshowinglownotearrow.jpeg)
code
![Image](codesLED-arrows.PNG)

Buttons A and B now become back tracks so that the key notes can be layered 
![Image](codebacktracks.PNG)

To increase sound i further looked into the guitar on the microbit page and located the use of acceleration, from this I coded the micro;bit to play notes when tilted left or right. This was done becuase I did not want to eliminate the sounds from buttons A and B. 
Guitar code;
![Image](microbitguitaracceleratometercode.PNG)
Tilting code for acceleration 
![Image](codenotwantingtosubstitutebuttonsthustilt.PNG)



## Project outcome ##

link to video presentation https://youtu.be/aXNmyKd1xpY

### Banana JamBoard ###

### Project description ###

*In a few sentences, describe what the project is and does, who it is for, and a typical use case.*

### Showcase image ###

![Image](final2.JPG)

### Additional view ###

![Image](final3.JPG)
![Image](final4.JPG)
![Image](finalpresentation1.JPG)

### Reflection ###

*Describe the parts of your project you felt were most successful and the parts that could have done with improvement, whether in terms of outcome, process, or understanding.*


*What techniques, approaches, skills, or information did you find useful from other sources (such as the related projects you identified earlier)?*


*What ideas have you read, heard, or seen that informed your thinking on this project? (Provide references.)*


*What might be an interesting extension of this project? In what other contexts might this project be used?*
