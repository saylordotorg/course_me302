---
layout: default
title: "ME302: Mechatronics"
course_description: "An examination of mechatronics, including the integration of mechanics, electronics, signal processing, and control systems, signal amplification, data sampling and filtering, machine programming, actuator and motor control, sensors, and robotics."
next: ../Unit07
previous: ../Unit05
---
**Unit 6: System Dynamics** <span id="6"></span> 
*Any mechanical, electrical, fluidic, or thermal system has certain
unique characteristics in how it responds to external excitation. Prior
to attempting to control a physical system, it is important to
understand its dynamic response to an external excitation. This unit
will introduce you to the concept of system dynamics and its importance
to mechatronic system design. Critical to the understanding and modeling
the dynamics of a system is the differential equation that relates the
input of the system to the output of the system. Differential equations
are the ideal tool for capturing the dynamics of a system and its
response to external inputs.*  
  
 *It is critical that prior to starting this unit, you review what you
have studied on differential equations, especially those used to
describe mechanical systems (mainly contained in ME202*: *Mechanics II).
If necessary, review*
*[ME202](http://www.saylor.org/courses/me202/) before beginning this
unit.*

**Unit 6 Time Advisory**  
This unit should take approximately 5.5 hours to complete.  
  
 ☐    Subunit 6.1: 3 hours  
  
 ☐    Subunit 6.2: 1.25 hours  
  
 ☐    Subunit 6.3: 1.25 hours

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Define the concept of a *system*.
-   Identify real-life examples of systems as well as their inputs and
    outputs.
-   Use ordinary differential equations to capture the dynamics of
    simple mechanical systems.
-   Identify examples of first-order mechanical systems, and solve
    problems using the Laplace transform method.
-   Identify examples of second-order mechanical systems, and solve
    problems using the Laplace transform method.

**6.1 System Dynamics** <span id="6.1"></span> 
*Understanding the dynamics of a system is very important in achieving
successful control. You will see from the video below how failure to
understand system dynamics can lead to disastrous outcomes, as can be
seen in the collapse of the Tacoma Narrows bridge.*

-   **Web Media: Archive.org: “Tacoma Narrows Bridge Collapse”**
    Link: Archive.org: [“Tacoma Narrows Bridge
    Collapse”](http://archive.org/details/CEP176) (Flash)  
      
     Instructions: Please watch this video.  
      
     Terms of Use: This resource is in the public domain. The original
    version can be found [here](http://archive.org/details/CEP176).

**6.1.1 The Concept of a System** <span id="6.1.1"></span> 
*The mechatronic system that we are trying to control is usually
referred to as the plant (e.g., mechanical system, electrical system,
etc.). The plant that we are attempting to control is a system. In the
case of the video below, the plant is mass vertically suspended on a
spring. A system is a set of interconnected components that interacts
with its environment. We are interested in the inputs and outputs to and
from the system. Below, you will watch a video on system modeling by
Kevin Craig.*

-   **Web Media: Rensselear Polytechnic Institute and Marquette
    University: Kevin Craig’s Multidisciplinary Mechatronic Innovations:
    “Intro to Modeling”**
    Link: Rensselear Polytechnic Institute and Marquette University:
    Kevin Craig’s *Multidisciplinary Mechatronic Innovations*: [“Intro
    to Modeling”](http://multimechatronics.com/movie.php) (QuickTime)  
      
     Instructions: Please click the link above, and watch the video by
    Dr. Kevin Craig that provides an introduction to the concept of
    system modeling. In this video, Dr. Craig looks at a mass suspended
    on a spring and attempts to find the dynamic model that represents
    it.  
      
     Watching this video and pausing to take notes should take
    approximately 1 hour and 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.1.2 The Use of Ordinary Differential Equations to Describe the
Dynamic Behavior of a System** <span id="6.1.2"></span> 
*In any mechatronic system, we are interested in a specific output
variable that we are attempting to control. We will usually control the
output variable by setting the input variable to the desired value.
Hence, the dynamic relationship between the input variable and the
output variable is very important. Most systems have multiple inputs and
multiple outputs, and their analysis become more involved. In the
material discussed in this unit, we will restrict the analysis to single
input single output (SISO) systems. The ideal tool to capture the
dynamic relationship between the input variable and the output variable
is the differential equation.*

-   **Web Media: YouTube: Dr. Ben Drew’s “Control Systems Engineering –
    Lecture 2 –Modeling Systems”**
    Link: YouTube: Dr. Ben Drew’s [“Control Systems Engineering –
    Lecture 2 –Modeling
    Systems”](http://www.youtube.com/watch?v=zGr_LS6OToE) (YouTube)  
      
     Instructions: Please click on the link above and then watch the
    video to learn about modeling systems.  
      
     Watching this video and pausing to take notes should take
    approximately 1 hour and 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.2 First-Order Systems** <span id="6.2"></span> 
*The simplest form of a dynamic model for a system is the first order
system. A first order system is typically represented by a time
constant. When we try to charge a capacitor in a resistor-capacitor
circuit, the response follows a first order system response. A tank full
of water that has a small hole at its lower end will also follow a first
order system response. The following video will discuss the response of
a first order system.*

-   **Web Media: YouTube: Dr. Ben Drew’s “Control Systems Engineering –
    Lecture 3 - Time Response”**
    Link: YouTube: Dr. Ben Drew’s [“Control Systems Engineering –
    Lecture 3 - Time
    Response”](http://www.youtube.com/watch?v=FS7nP9l61g4) (YouTube)  
      
     Instructions: Please click on the link above and then watch the
    video. Note how different types of signal can be injected into first
    order systems (impulse, step, and ramp). Also, note how the Laplace
    transform and the inverse Laplace transform are used to find the
    time domain response.  
      
     Watching this video and pausing to take notes should take
    approximately 1 hour and 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.3 Second-Order Systems** <span id="6.3"></span> 
*Few of the dynamic systems found in practice are not first order
systems. They are usually second order system or higher. Second order
systems are obviously more complicated, and their analysis is more
involved. The following video discusses the response of second order
systems to a step input. You will notice that the response of second
order system to a step input could either be over-damped, critically
damped, or under-damped.*

-   **Web Media: YouTube: Dr. Ben Drew’s “Control Systems Engineering –
    Lecture 4 – Second Order Time Response”**
    Link: YouTube: Dr. Ben Drew’s [“Control Systems Engineering –
    Lecture 4 – Second Order Time
    Response”](http://www.youtube.com/watch?v=03xrMzvcS8I) (YouTube)  
      
     Instructions: Please click on the link above and then watch the
    video. Note how the response of a second order system depends on the
    damping ratio, zeta. Where the damping ratio is more than 1, the
    response to a step input will be under-damped and no overshoot will
    result. Where the damping ratio is less than 1, the system is
    under-damped and you will notice an overshoot and decaying
    sinusoidal response.  
      
     Watching this video and pausing to take notes should take
    approximately 1 hour and 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


