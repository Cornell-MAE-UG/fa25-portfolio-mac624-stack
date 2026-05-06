---
layout: project
title: MAE 2250 Open Design Project
description: Pitch to clients about Spotted Lanternfly sorting device
image: /assets/images/SLF.png.jpg
---

  
[Client Pitch](#Client_Pitch)
[First Prototype](#Prototype_1)
[Client Report](#Client_Report)


<a name="Client_Pitch"></a>
  
  <h1>Client Pitch</h1>
  <h4>Client(s): </h4>
  <b>Cornell CALS Extension, E&J Gallo Winery, National Grape </b>

  <h2> Problem statement </h2>
  When grapes are harvested by mechanised harvesters, spotted lanternflies are collected along with them. Up to 80% of the SLF on a vine can be removed from the vine and end up in the final product. SLF can move to grape vines immediately before harvesting, making it hard to prevent their accidental harvesting. 
  
  <h2> Impact: </h2>
  Even a couple of SLF in a shipment can cause tons of grapes to be thrown out, so it is critical that they are removed at every stage of the harvest process in order to preserve the profits of the farm.

  <h3> Concept A: Airflow Distinguisher </h3>

  An adjustable fan will be attached to the harvesting system, applying a controlled amount of airflow to the yield. This artificial airflow separates the SLF from the grapes, blowing the significantly lighter SLF away from the valuable grapes and into a separate container. <br>  
  <b>How it would be used:</b> Immediately after harvesting and before the grapes make it to a final container, a custom fan will separate the lighter SLF from the grape collection

  <h3> Concept B: Grate Accumulator </h3>

  A specialized solution will be sprayed upon the harvestation of grapes and SLF, loosening their connection and separating them from one another. The separated grapes would fall through a custom built grid, accumulating in a new chamber and blocking the larger SLF from following. <br>  
  <b> How it would be used: </b> <br>

  1. After harvest, they will be sprayed with a certain solution to loosen their connection.  <br>
  2. Together they would be rolled over/displaced to our custom grid and filtration grate, where the smaller grapes would fall through the grid (similar to a honeycomb design) <br>

  <b>Why it’s better than the status quo (both concepts):</b> <br>
  Minimal labor is needed and minimal modifications need to be made to the harvester. This solution is intended as a set-and-forget attachment.  <br>
  <b>End-of-semester proof-of-concept (both concepts):</b>  <br> 
  With the resources available to us, we can create simple prototypes to validate the effectiveness of one of our concepts. We can use 3D printing to prototype a fan attachment or a grate, changing parameters like airflow, angle, hole spacing, and grate shape to analyse how they improve the effectiveness of our system. <br>

  <h2> Key risks & Unknowns: </h2>

  <ul>
  <li> <b>Yield Damage</b> — SLF’s can decimate crops, so while our approach may be significant in preventing contamination of end products, reduced yield presents a more systemic risk.  </li>
  <li> <b>Harvesting Practices </b> — Practices may differ depending on if they handpick the grapes or using tractors, the difference means incorporating our design to be modular  </li>
  </ul>

  <h2> Questions for the client: </h2>
  <i> We have limited knowledge of the state of SLF and grapes post-harvesting, so any information (pictures, videos, descriptions) would be a huge help. </i> 

  <ol>
  <li><b> What does the current harvesting vehicle look like, and where would there be space to safely implement a post harvesting separation device?</b> *Decision affected:* This will determine potential attachment and help visualize the overall final design. </li> 
  <li> <b>What are the grapes and SLF like immediately after they are harvested/before they end up in the shipping bin?</b> *Decision affected:* This will help us simulate the grape-lanternfly mixture in order to test our prototypes. </li>
  <li> <b>How does the grape inspection process work?</b> *Decision affected:* This will affect how we evaluate the effectiveness of our prototypes. </li>

  </ol>



<a name="Prototype_1"></a>
# YellowJackets ODP5: Functional Prototype I

## Design Documentation:

Full Photo:   
![]({{ "/assets/images/image4.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}
 ![]({{ "/assets/images/image15.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}





**Intent and functionality:**  
Main Components:  
The fan is ordered from McMaster (1939K96). It is powered by one of the supplied 12V power supplies and mounted to a custom 3d printed fan mount using M4 bolts and nuts , also from McMaster (91290A187, 90591A255). This allows for connection to the main structure and has holes designed for attaching a fan nozzle. Shown below is one side of the fan mount, which is also utilized for the other side. The fan’s hole pattern matches such that it can be directly mounted to each of the two fan mounts.  
![]({{ "/assets/images/image13.png" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}
**Nozzle** \- Designed in CAD then fabricated out of wood. Mounts to fan mount and directs airflow towards a more focused cross-section. Wood was marked to match the specified CAD dimensions, cut, and belt sanded to improve precision from rough-cuts.  
 ![]({{ "/assets/images/image8.png" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}
 ![]({{ "/assets/images/image14.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}  
**Loading Tray** \- Constructed out of balsa wood. Serves as a container for placing stand-in materials for SLF and grapes for the purposes of testing. It has a pivoting gate to restrict movement before a test which can be rotated to the open position when the test is started.

**Main Structure** \- Used balsa wood for the main structure. Marked up the wood to show where the holes will line up to attach the fan mount and loading tray. Using a handheld drill, we made 24 precise holes to allow for maximum configurability for the angle of the fan mount

**Supports** \- Cut four supports out of balsa wood connected to the base and the main structure. We used an X-Acto knife to cut the wood into triangular shapes and use wood glue to connect the supports. Using the extra wood, cut a final support piece that we glued on the main structure above the holes for the fan mount and below the holes for the loading tray. 

**Base** \- A square piece of balsa wood which we attached to our main structure and supports using wood glue.

**Sketches**:

Dimensions for fan attachment below:  
124mm x 95mm

## Design Documentation \- assembly process

1. The first step of the assembly was cutting out many different pieces of wood and drilling holes into them. We marked out all of the cuts and holes with a ruler and pencil first.   
2. The fan mounting plates were sent to the RPL to be 3D printed and the fan was ordered from McMaster  
3. We glued and taped together each of the structures. They had to sit for a day to dry.   
4. After the nozzle was dried, we assembled the fan assembly by putting the plastic side plates on and tightening their bolts down, then adding the nozzle and attaching it using the same bolts.   
5. Once each of the parts (chute, base, and fan assembly) is dried, we assembled them all together using bolts. 

# Testing 

Fan angle stability:

- Determine if the fan angled up, down, or straight separates the SLF (styrofoam) from the grapes (clay)  
- We will change the angle of the fan, then turn the fan on for one minute to see if the fan remains in the same position.

Main test: grape & SLF separation with fan:

- We will put a mix of simulated grapes and lanternflies in the chute.   
- The chute will be opened to allow the grapes and SLF to fall freely in front of the fan.  
- Taking a video and with a meter stick on the ground in front of the device, we will record the exact distances that the grapes fall and the SLF fall.   
- This test will be repeated with  different fan positions and angles, each time testing both with and without the nozzle that we fabricated. 

Structural integrity:

- Holding the base, we will shake the design with all parts attached, with a frequency of about 40hz and an amplitude of 4 inches.  
- This test will be repeated shaking in multiple horizontal directions.   
- The second part of this test will be lifting the structure off of the table by holding the top of the vertical panels. We will lift it 10 times. 

## Testing Results

Materials: 

* “Grapes”: Clay spheres, weighing in between 4-7 grams to simulate grapes  
* “SLF”: Styrofoam blocks, 1.5in by .75in, weighing it at a little less than 1 gram.  
  - Aluminum wires were inserted into the block to simulate a more weighed down version of the SLF (for when it is covered in grape slush)  
* Meter stick (placed in front of the structure, with 0in at the end of the base plate. 

Fan angle

- Out of 12 positions tested, 12/12 times the fan stayed in place.   
  - The fan was able to be placed in many different locations and angles. The pattern of holes that we built worked well and they were all aligned well enough.  
  - Here are a bunch of pictures of different fan locations (different heights and angles).  

![]({{ "/assets/images/image2.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}
![]({{ "/assets/images/image3.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}
![]({{ "/assets/images/image9.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}
![]({{ "/assets/images/image11.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}
![]({{ "/assets/images/image12.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}

Main test:   
First we ran a control where the fan was not on. The grapes and SLF all landed together between 2 and 6 inches from the base. Here is the rest of our data, parsed from our videos: 

| Fan pos: | Nozzle (Y/N) | Grapes min & max distance \[in\] | SLF min & max distance \[in\] | Separation? |
| :---- | :---- | :---- | :---- | :---- |
| High, 25 deg up | Y | 2, 4 | 4, 10 | N  |
| High, 25 deg up | N | 2, 5 | 12, 19 | Y (7in) |
| Low, 25 deg up | Y | 2, 4 | 3, 10 | N  |
| Low, 25 deg up | N | 2, 4 | 5, 15 | Y (1in) |
| Low, flat angle | Y | 2, 4 | 3, 5 | N |
| Low, flat angle | N | 2, 4 | 6, 20 | Y (2in) |
| High, flat angle | Y | 2, 5 | 6, 15 | Y (1in) |
| High, flat angle | N | 2, 5 | 8, 25 | Y (3in) |

Screenshots showing process:  
![]({{ "/assets/images/image7.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}  
SLF and grapes being released. The first grapes have landed. They tend to roll after landing, so it was important to take the video to ensure accurate data. 

![]({{ "/assets/images/image15.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"} 
SLF and grapes after landing. The effects of the grapes rolling is quite obvious, some of them travel up to 8 inches after landing. 

Structural integrity:

- The design did not fail after 30s of shaking in four different directions.   
  - Failure would count as any change to structure, i.e. one of the glued joints coming loose or a part falling off entirely.   
- The design did not fail when being lifted from the top 10 times. 

**Testing:**   
**Fan adjustment:**  
The way that we are attaching the fan is successful. The bracket and side walls held up perfectly. The only issue that we encountered was that the bolts used to attach the fan mount to the base structure were too long. We were unable to attach a nut to the end of the bolt, so it was a little bit unstable. This was because we only ordered a single length of bolt, which was correct for the fan but not for the rest of the design. For a final prototype where we want to lock everything down, we will need some shorter bolts. 

**Main Test:**   
First, the nozzle does not seem worth it based on our testing. We believe that the major issue with it was the fact that air escaped on the sides of the nozzle (picture of gaps below). We would like to try a different nozzle that is 3D printed and fits onto the fan better than our current design.   
![]({{ "/assets/images/image1.jpg" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"}\<- gap between fan and nozzle where air escaped  
The conclusion of the fan position was that the best position was high up (close to the chute), with an angle upwards. This allows us to really narrow down the position of the fan for our final prototype. 

**Structural test:**  
The way that our structure is braced is successful. If our final prototype has the same form, it will be braced in the same way. 

**Success Criteria:** 

Our main motive with our design is being able to create a structure that allows there to be a separation between the lantern fly and the grapes while still collecting usable harvest. Success is split into multiple categories for our SLFilter.

**Performance and Functionality (high priority):** This criterion assesses the overall performance and execution of our design. To measure these successes, we require smooth fan angle changes in 15° increments, from 0° to 45°. The fan should be able to rotate while the nozzle stays attached. Additionally, we will test the nozzle performance by using styrofoam blocks. Now that we are fabricating a nozzle that is flush to the fan, mitigating excessive air loss, we can assess how well the redirection of airflow performs. This will be done by seeing if the styrofoam samples fly at least 3 inches further on average than without a nozzle, or if the average distribution range of samples within 4 inches (to ensure the SLF will consistently land in their designated container). Furthermore, we will assess how well every component is held together with our bolts. To mitigate any sort of microcracking and crack propagation, we will ensure the holes we drill aren’t too small. This will be measured with repeated load testing on a sample, taking note of when the first crack appears. If the design undergoes 50 load cycles without visible cracking, we may assume successful structural cohesion. Lastly, we must assess the quality of our flow control device on the loading tray. This rotational gate will be able to adjust the amount of SLF/grapes released for separation, and will be assessed in two ways. When fully vertical, the gate must not allow any harvest through for a minimum of 1h. This will be tested with a sample harvest sitting in the loading tray for the designated time, and proven successful if less than 1oz of harvest is let through. We will also assess the functionality of the rotational dowel, testing the adjustability in flow control. This test will be proven successful if we can keep the gate at 2 different angles, the second angle releasing twice as much harvest as the first. To measure the output, we will be collecting the harvest in containers to compare. 

**Efficiency (high priority):** Our second criterion focuses on the overall effectiveness of the design. By using real grapes and temporary SLF, we will access the efficiency of the fan separation, with a goal of 100% separation. In a sample test containing 6 SLF, 20 grapes, and grape mush, we are aiming to capture all 6 SLF in our designated container to provide sufficient separation efficiency. Furthermore, we will attach string in the inside at the back of the nozzle to check if any additional air escapes besides out front. Using 5 strings, having 4 strings blow forward (towards the outlet) will validate our new design and ensure an efficient nozzle. 

**Usability/Application (medium priority):** The next criterion will assess the reality of this design. To measure success, we will have a selection of students try and use the device with limited prior knowledge. Given a selection of 10 students, having 8 students undergo SLF separation will suffice as success criteria, displaying the effect this device has. Additionally, we will test how the device reacts when in motion, to simulate real world application. To measure this, the device will be held by a student or placed on a moving cart, while the harvest is loaded into the tray as the device moves forward. As the whole device moves, we will analyze similarly to the stationary tests, looking for dislocations or malfunctioning components. To quantify success, we need to achieve 0 broken components and 100% SLF separation. 

**Exhibit Demonstration:** At the exhibit, we will be able to use our SLF models and grapes to simulate what the separation process will look like to display the efficiency of our design. Usability can also be tested at the exhibition, having guests try and use it to separate the SLF themselves to see what the effect is.



<a name="Client_Report"></a>


**Yellowjackets: The SLFilter**  
Aaron Grgurovic, Kevin Pezzulich, Magnus Carson, Jawad Mohamed, Johanna Stuard  

**Context and Problem Statement:** 

When grapes are harvested by mechanised harvesters, spotted lanternflies are collected along with them. Up to 80% of Spotted Lantern Flies (SLF) on a vine can be removed from the vine and end up in the final product. SLF can move to grape vines immediately before harvesting, increasing the difficulty to prevent their harvesting. Even a couple of SLF in a shipment can cause tons of grapes to be thrown out, so they must be removed at every stage of the harvesting process to preserve the profits of the farm. 

In the post-harvest, there is an opportunity to separate the SLF from the grape solution before the product is dumped into the bin. We shifted our focus to the post-harvest considering the inevitably that SLF's will stay with the product post-harvest. Our goal is to construct a prototype that can be used as a failsafe against the SLFs that end up in the product post-harvest, while also eliminating possibilities of contaminating the soil or damaging the grape vine through direct contact. 

During our research, we identified multiple constraints that our prototype would be subject to. The prototype would need to fit into the available space inside a harvester underneath the end of the conveyor belt. The government rejects grape mixtures where there is more than 1 gram of SLF per 1000 grams of grape, so the design should be precise enough to reach this separation threshold. The prototype would be required to be powerful enough to effectively separate the SLFs and grapes into two separate bins. 

**Final Prototype and Application:** 

Throughout our initial idea development, design iteration, and final prototype stages, we have developed a structural attachment to assist grape harvesting, which uses controlled airflow to separate Spotted Lanternflies (SLF) from harvested grapes. The structure consists of a DC powered fan integrated into supports which are adjustable in height and angle; this allows farmers to precisely tune the airflow based on the conditions of the crops. 

During grape harvesting, as grapes are processed and discharged from the conveyor belt, they will fall onto the loading tray, which is a part of our structure and is positioned above the fan. After the grapes/SLF fall onto the loading tray, the fan generates a stream of air. Due to SLF being significantly lighter than the grapes, they are blown into a separate collection area, while the heavier grapes fall into their own crates as well. 

Overall, our design provides a simple ‘add-on’ and adjustable solution that can be incorporated into the existing conveyor system. Allowing for an improvement in grape processing quality. 

**Conclusion and Recommendation:**

As far as next steps, while we have worked to demonstrate functionality using simulated SLF and grapes (weighted styrofoam and clay), this simply proved the concept’s small-scale feasibility. Moving forward, further testing would be necessary on a scale more on par with the expected grape and SLF quantities harvested by mechanical harvesters while also being in constant motion. Additionally, another redesign would be necessary in order to adapt this design to existing equipment’s mounting points. While this wouldn’t represent a significant difference in core design as far as fan angle, it would mean likely mounting the fan from above rather than below. This would require inverting the design such that it could be attached to a harvester at the end of the conveyor belt which drops the grape slurry into the bin.

This design would also greatly benefit from field testing using actual grape slush/SLF mixtures, as while we have done our best to simulate grapes and SLF falling through the system and being separated, utilizing the actual mixture itself would give the most helpful insight into the design’s feasibility.

**Testing and Results:** 

We are primarily focused on testing 2 main categories within our design: performance and efficiency. The main tests we are planning on conducting is if the fan can successfully separate the SLF from the grape slush, and determining the consistency of this separation. The project depends on the success of producing an SLF free product, making this our high priority test. On average, the SLF must land a minimum of 3.25in farther than the grapes, demonstrating a 100% separation rate. This data includes both ‘dry’ and ‘wet’ SLF, accounting for SLF mass difference from being soaked in rain or grape slush. 

Due to our design being a last resort failsafe, we need to ensure a highly reliable device, as examined by our cycling tests to both determine the separation consistency and design durability. We averaged consistent data across 3 tests for each setting, accounting for outliers. Through this, we witnessed a maximum separation of 7in, and a minimum at 1in, however, the 1in had been at the low fan position. The average for the higher position (indicating the fan being closer to the loading tray) was far greater than low, confidently allowing us to finalize a high fan position design.

Additionally, our initial design consisted of a nozzle for the fan, intended to allow for a more controlled airflow. We ran a fan efficiency test, consisting of precisely placed string on the interior of the custom nozzle design. During our first prototype, we discovered a large amount of pressure escaping through the edges and back end as our nozzle was not snug against the mounting brackets. This realization led to us redesigning the nozzle in order to mount flush to the fan and prevent any lost pressure. However, despite redesign efforts, during further testing we determined the nozzle to be less consistent than an open fan and chose to move past this idea. 

**Prototype and Testing Details:**

Fan angle stability:

- Determined if the fan angled up, down, or straight separates the SLF (styrofoam) from the grapes (clay)  
- We changed the angle of the fan, then turned the fan on for one minute to see if the fan remained in the same position.

Main test: grape & SLF separation with fan:

- We put a mix of simulated grapes and lanternflies in the chute.   
- The chute was opened to allow the grapes and SLF to fall freely in front of the fan.  
- Taking a video and with a meter stick on the ground in front of the device, we recorded the exact distances that the grapes fall and the SLF fall.   
- This test was repeated with different fan positions and angles, each time testing both with and without the nozzle that we fabricated. 

Structural integrity:

- Holding the base, we shook the design with all parts attached, with a frequency of about 40hz and an amplitude of 4 inches.  
- This test was repeated shaking in multiple horizontal directions.   
- The second part of this test was lifting the structure off of the table by holding the top of the vertical panels. We lifted it 10 times. 

| Fan pos: | Nozzle (Y/N) | Grapes min & max distance \[in\] | SLF min & max distance \[in\] | Separation? |
| :---- | :---- | :---- | :---- | :---- |
| High, 25 deg up | Y | 2, 4 | 4, 10 | N  |
| High, 25 deg up | N | 2, 5 | 12, 19 | **Y (7in)** |
| Low, 25 deg up | Y | 2, 4 | 3, 10 | N  |
| Low, 25 deg up | N | 2, 4 | 5, 15 | Y (1in) |
| Low, flat angle | Y | 2, 4 | 3, 5 | N |
| Low, flat angle | N | 2, 4 | 6, 20 | Y (2in) |
| High, flat angle | Y | 2, 5 | 6, 15 | Y (1in) |
| High, flat angle | N | 2, 5 | 8, 25 | Y (3in) |

![]({{ "/assets/images/image17.png" | relative_url }}){: style="display: block; width: 600px; height: auto; margin: 20px auto;"} 

**References and Bill of Materials**

| Part | Purpose | Quantity | Price | Manufacturer  |
| :---- | :---- | :---- | :---- | :---- |
| ¼” Acrylic Plate  | Cut to act as side panels, base, and loading tray | 1 | $52.81 | McMaster-Carr [https://www.mcmaster.com/8505K757/](https://www.mcmaster.com/8505K757/)  |
| M4x55mm Bolt | Securely attach the nozzle to the fan and fan mount. | 4 | $11.25/pack | McMaster-Carr [https://www.mcmaster.com/91290A187/](https://www.mcmaster.com/91290A187/)  |
| M4x25mm Bolt | Securely attach the loading tray and the fan mount to the side panels | 8 | Free from TDS | McMaster-Carr |
| M4 Nut | Tighten the connection with bolt and acrylic | 12 | $3.39/pack | McMaster-Carr [https://www.mcmaster.com/90591A255/](https://www.mcmaster.com/90591A255/)  |
| Acrylic Plastic Cement | Hold the structure together | 1 | $7.52 | McMaster-Carr [https://www.mcmaster.com/7352A101/](https://www.mcmaster.com/7352A101/)  |
| Square Blower Fan | Separate SLF from grapes | 1 | $75.00 | McMaster-Carr [https://www.mcmaster.com/1939K96/](https://www.mcmaster.com/1939K96/)  |
| Plastic Fan Bracket | Attach fan and nozzle to structure | 2  | $2.30 | RPL 3D Print |
| Plastic Nozzle | Direct airflow, used for testing but not final prototype | 1 | $5.65 | RPL 3D Print |
| Balsa Wood Boards | Prototype structure | 4 | $4 | Lab |
| Wood Glue | Hold together structure | 1 | $1 | Lab |

**Total Price: $162.92**   