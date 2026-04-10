---
layout: project
title: MAE 2250 Open Design Project
description: Pitch to clients about Spotted Lanternfly sorting device
image: /assets/images/SLF.png.jpg
---
*Note: this is required to be on my portfolio by my class (MAE 2250). If you are a recruiter please look at my more relevant pages, my Machining and Tech Report.
  

<details>
  <summary> <b>Client Pitch</b> </summary>
  
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
</details>

<details>
  <summary> <b>First Prototype</b> </summary>

# YellowJackets ODP5: Functional Prototype I

# Design Documentation:

Full Photo:   
![][image1]![][image2]

**Intent and functionality:**  
Main Components:  
The fan is ordered from McMaster (1939K96). It is powered by one of the supplied 12V power supplies and mounted to a custom 3d printed fan mount using M4 bolts and nuts , also from McMaster (91290A187, 90591A255). This allows for connection to the main structure and has holes designed for attaching a fan nozzle. Shown below is one side of the fan mount, which is also utilized for the other side. The fan’s hole pattern matches such that it can be directly mounted to each of the two fan mounts.  
![][image3]  
**Nozzle** \- Designed in CAD then fabricated out of wood. Mounts to fan mount and directs airflow towards a more focused cross-section. Wood was marked to match the specified CAD dimensions, cut, and belt sanded to improve precision from rough-cuts.  
 ![][image4]![][image5]  
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

![][image6]![][image7]![][image8]![][image9]![][image10]

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
![][image11]  
SLF and grapes being released. The first grapes have landed. They tend to roll after landing, so it was important to take the video to ensure accurate data. 

![][image12]  
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
![][image13]\<- gap between fan and nozzle where air escaped  
The conclusion of the fan position was that the best position was high up (close to the chute), with an angle upwards. This allows us to really narrow down the position of the fan for our final prototype. 

**Structural test:**  
The way that our structure is braced is successful. If our final prototype has the same form, it will be braced in the same way. 

**Success Criteria:** 

Our main motive with our design is being able to create a structure that allows there to be a separation between the lantern fly and the grapes while still collecting usable harvest. Success is split into multiple categories for our SLFilter.

**Performance and Functionality (high priority):** This criterion assesses the overall performance and execution of our design. To measure these successes, we require smooth fan angle changes in 15° increments, from 0° to 45°. The fan should be able to rotate while the nozzle stays attached. Additionally, we will test the nozzle performance by using styrofoam blocks. Now that we are fabricating a nozzle that is flush to the fan, mitigating excessive air loss, we can assess how well the redirection of airflow performs. This will be done by seeing if the styrofoam samples fly at least 3 inches further on average than without a nozzle, or if the average distribution range of samples within 4 inches (to ensure the SLF will consistently land in their designated container). Furthermore, we will assess how well every component is held together with our bolts. To mitigate any sort of microcracking and crack propagation, we will ensure the holes we drill aren’t too small. This will be measured with repeated load testing on a sample, taking note of when the first crack appears. If the design undergoes 50 load cycles without visible cracking, we may assume successful structural cohesion. Lastly, we must assess the quality of our flow control device on the loading tray. This rotational gate will be able to adjust the amount of SLF/grapes released for separation, and will be assessed in two ways. When fully vertical, the gate must not allow any harvest through for a minimum of 1h. This will be tested with a sample harvest sitting in the loading tray for the designated time, and proven successful if less than 1oz of harvest is let through. We will also assess the functionality of the rotational dowel, testing the adjustability in flow control. This test will be proven successful if we can keep the gate at 2 different angles, the second angle releasing twice as much harvest as the first. To measure the output, we will be collecting the harvest in containers to compare. 

**Efficiency (high priority):** Our second criterion focuses on the overall effectiveness of the design. By using real grapes and temporary SLF, we will access the efficiency of the fan separation, with a goal of 100% separation. In a sample test containing 6 SLF, 20 grapes, and grape mush, we are aiming to capture all 6 SLF in our designated container to provide sufficient separation efficiency. Furthermore, we will attach string in the inside at the back of the nozzle to check if any additional air escapes besides out front. Using 5 strings, having 4 strings blow forward (towards the outlet) will validate our new design and ensure an efficient nozzle. 

**Usability/Application (medium priority):** The next criterion will assess the reality of this design. To measure success, we will have a selection of students try and use the device with limited prior knowledge. Given a selection of 10 students, having 8 students undergo SLF separation will suffice as success criteria, displaying the effect this device has. Additionally, we will test how the device reacts when in motion, to simulate real world application. To measure this, the device will be held by a student or placed on a moving cart, while the harvest is loaded into the tray as the device moves forward. As the whole device moves, we will analyze similarly to the stationary tests, looking for dislocations or malfunctioning components. To quantify success, we need to achieve 0 broken components and 100% SLF separation. 

**Exhibit Demonstration:** At the exhibit, we will be able to use our SLF models and grapes to simulate what the separation process will look like to display the efficiency of our design. Usability can also be tested at the exhibition, having guests try and use it to separate the SLF themselves to see what the effect is.

</details>
