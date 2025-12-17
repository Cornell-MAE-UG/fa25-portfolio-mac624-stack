---
layout: project
title: Brake Rotor Thermal Analysis
description: Thermodynamics 2210 Project
technologies: [SOLIDWORKS 2025]
image: /assets/images/rotor_assy.png
---

For thermodynamics, we were asked to do a thermal analysis of a system of our choice. I chose to analyze a brake rotor. Specifically, I want to analyze one of the three brake rotors for the off road racing car that my project team is building. I am basing my calculations off of both CAD models and real-world testing that we have done as a team. 

The data that I am using for the testing comes from two places. First, the information about the rotor itself comes from the CAD model for the new rear rotor that we are manufacturing. 

![Render of the isolated rear rotor]({{ "/assets/images/rotor_alone.png" | relative_url }}){: .inline-image-l style="width: 400px"}

The properties of the rotor are automatically calculated by SOLIDWORKS. They are as follows: 
$\\\\\text{Mass: }127.5g= 0.1275kg.\\\\
\text{Surface Area: }20800mm^2= 0.0208m^2\\\\
\text{Material}: \text{ Stainless Steel} \\\\
\text{Specific Heat Capacity }c_s= 0.5\frac{kJ}{kg \cdot K}\\\\
\text{Vehicle Weight: } m_V=250kg \\\\
\text{Vehicle Top Speed: } v_{max}= 30mph=13.4\frac{m}{s}$

For the rotor's design criteria, it was determined that due to thermal expansion risk, the rotor must stay below $T_{max}=300\degree C$. For ambient temperature, I will use the worst case scenario: during our competition in Arizona, the temperature reached $T_{amb} = 40\degree C$

Another question I would like to answer is the question of how much energy is dissipated from the car when the rear brake is dragging. Previously, we have observed the rear brake rotor glowing red. This represents a temperature (in stainless steel) of about $T_{hot}= 600\degree C$

My questions are as follows: Q1: How hot will the brake rotor get in one full stop of the car? Q2: How long will it take the rotor to dissipate that heat into the air? Q3: How much power is dissipated by the brake system if the brakes stay at a constant temperature of 600 degrees?

Q1:

The first step is to calculate the total energy dissipated by the brakes system. This is calculated using $KE= \frac{m_V*V_{max}^2}{2}= 22.5kJ$. Because there are three brake rotors, 1/3rd of this value is the head added to the brake rotor. Using $\Delta U= m_{rot}*c_s*\Delta T$, we can calculate that $\Delta T= 117.6\degree C$. This means that the final temperature of the rotor after a full stop will be 117.6 degrees greater than it started. If the rotors are initially at ambient temperature, they will increase to a final temperature of **157.6 degrees**. In less than 3 full stops, the rotors will overheat, emphasising the imporance of cooling them off. 

Q2: 

The first step will be to calculate the amount of heat that needs to be dissipated for the rotor to cool by 117.6 degrees. Conviniently, this was already determined in the previous question as $\frac{22.5kJ}{3}= 7.5kJ$. Next we have to solve for the rate of heat dissipation into the air. For this we will use $\dot{Q}_{convection}= h*A*\Delta T$. I will use an approximate heat transfer coefficient of $h=0.100\frac{kJ}{m^2\cdot K \cdot s}$. This is based on the fact that the rotor is moving very rapidly in the air around it. I am using 200 celcius as the temperature of the rotor, to make my calulation simpler. Plugging in the numbers, we get $\dot{Q}_{200\degree C}= 0.333 \frac{kJ}{s}$. That means that it will take about **22 seconds** for the rotors to cool down.  

Q3:

This question is a steady-state question. I will use the equation $Q-W=0$. The final answer is the amount of work taken out of the car by the brakes system. Rearranging the equation gives $W= h*A*(600\degree - 40\degree)$. We find that the rate of work is $1.16\frac{kJ}{s}$. That is equal to about **1.6 horsepower**. Considering the fact that our engine only produces about 10hp, this is a very significant value, showing the importance of reducing drag in the brakes system. 