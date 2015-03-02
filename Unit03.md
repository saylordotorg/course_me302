---
layout: default
title: "ME302: Mechatronics"
course_description: "An examination of mechatronics, including the integration of mechanics, electronics, signal processing, and control systems, signal amplification, data sampling and filtering, machine programming, actuator and motor control, sensors, and robotics."
next: ../Unit04
previous: ../Unit02
---
**Unit 3: Actuators** <span id="3"></span> 
*Motion is the basic activity within a mechatronic system, whereby a
mechanical system is being controlled by the use of actuators under a
supervising control system. Position, speed, or both, are usually the
controlled variables in a mechatronic system. The following are examples
of mechatronic systems in which speed, position, or both, are monitored
and controlled: the speed of a conveyor belt has to be closely
controlled in order to ensure that items spend exactly the correct time
in a process; the position of a robotic arm manipulator has to be very
accurately controlled in order to successfully achieve a delicate task
(e.g., surgery); and in an elevator system, both speed and position have
to be accurately controlled.*  
  
 *In order to achieve motion, actuators are needed. An* actuator *is a
device that can produce force in order to achieve linear acceleration in
translational systems, or that can produce torque in order to achieve
rotational acceleration in rotational systems.*  
  
 *Thus, it is important to be aware of the different types of actuators
that can be used in mechatronic systems to bring about motion. This unit
will introduce you to the different types of actuators and will provide
you with guidance on the advantages and disadvantages of each actuator
to enable you to select the correct one for a given application.*

**Unit 3 Time Advisory**  
This unit should take approximately 49.5 hours to complete.  
  
 ☐    Subunit 3.1: 2.5 hours  
  
 ☐    Subunit 3.2: 3.5 hours  
  
 ☐    Subunit 3.3: 0.75 hours  
  
 ☐    Subunit 3.4: 39.5 hours

  
 ☐    Sub-subunit 3.4.1: 10 hours  
  
 ☐    Sub-subunit 3.4.2: 12.25 hours  
  
 ☐    Sub-subunit 3.4.3: 0.25 hours  
  
 ☐    Sub-subunit 3.4.4: 3.75 hours  
  
 ☐    Sub-subunit 3.4.5: 12.75 hours  
  
 ☐    Sub-subunit 3.4.6: 0.5 hours

  
 ☐    Subunit 3.5: 0.5 hours  
  
 ☐    Subunit 3.6: 2.25 hours  
  
 ☐    Subunit 3.7: 0.5 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Identify and describe the different types of actuators used in
    mechatronic systems.
-   Explain the principle of operation of induction motors, dc motors,
    stepper motors, and servomotors.
-   Select the correct type of actuator for an application.
-   Size an actuator for an application.

**3.1 Introduction to Actuators** <span id="3.1"></span> 
*Actuators are important in mechatronic systems as they bring about
motion. They can be translational or rotational. Electrical motors are
the most widely used type of actuator in mechatronic systems. Electric
motors are electromagnetic actuators that convert electrical energy into
mechanical energy. All electric motors provide mechanical energy in a
rotational form (torque and rotational speed). An actuator can be
thought of as a device that converts electrical energy into mechanical
energy.*  
  
 *A lead screw is a device that converts rotational motion into
translational motion. Pulleys, sheaves, or sprockets are devices that
can convert rotational motion into translational motion and vice versa.
A gear box can change the speed and torque of rotational motion and is
thus a device that matches the motor to the load. More information about
gearboxes will be given in the last subunit of this unit.*

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif’s “Revision of
    Mechanics Basics”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif’s [“Revision of
    Mechanics
    Basics”](http://www.saylor.org/site/wp-content/uploads/2012/07/6a-Mechanics-rev-4-091115-CCupload.pdf)
    (PDF)  
      
     Instructions: Please click on the link above to download the PDF,
    and read pages 1 to 8 of the document, which presents an overall
    review of translational and rotational mechanics basic. You will
    read the remainder of the document in subunit 3.7.  
      
     Reading this chapter should take approximately 1 hour and 30
    minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    “Actuators” section, and select the link titled “Voice Coil Head
    Actuator and 3-Phase Stepper Spindle Motor in a Computer Hard-Drive”
    to download the video. View the brief demonstration, which shows an
    example of the use of actuators in a hard drive. As you watch the
    video, notice that there are two actuators: a motor that rotates the
    hard disk and another actuator that moves the reading head.  
      
     You will recall that in Unit 1, a number of possible mechatronic
    systems were discussed as follows: mechanical (translational),
    mechanical (rotational), fluidic (pneumatic), fluidic (hydraulic),
    and thermal.  
      
     Intuitively, the term *actuator* is immediately linked to
    mechanical actuators (whether rotational or translational). However,
    it is important to note that actuators could also be fluidic
    (hydraulic or pneumatic) and thermal (e.g., heater).  
      
     Watching this video and pausing to take notes should take less than
    10 minutes.

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    “Actuators” section, and select the “Hydraulic Gear Pumps” link to
    download the video. View the brief demonstration for an example of a
    hydraulic amplifier (similar to an electrical amplifier) that uses a
    pilot valve as the input. Notice that this pump is of the *positive
    displacement* type; a positive displacement pump moves known volumes
    of fluid with every rotation.  
      
     Watching this video and pausing to take notes should take
    approximately 5 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    section titled “Actuators,” and select the link titled “Hydraulic
    Pilot Valve Amplifier Cut-Away” to download the video. View the
    brief demonstration for an example of pneumatic actuators.  
      
     Watching this video and pausing to take notes should take less than
    10 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    “Actuators” section, and select on the link titled “Pneumatic
    Cylinders of Various Types and Sizes” to download the video. Another
    type of actuator is the *permanent magnet linear actuator*, also
    referred to as a *solenoid*. Watch this video for a demonstration of
    its construction.  
      
     Watching this video and pausing to take notes should take less than
    15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: YouTube: Jeri Ellsworth’s “Solenoid Basics Part 1”**
    Link: YouTube: Jeri Ellsworth’s [“Solenoid Basics Part
    1”](http://www.youtube.com/watch?v=hsoggQOoG4s&feature=related)
    (YouTube)  
      
     Instructions: Please click on the link above and view the entire
    video. This video shows you an example of a linear actuator. It is
    electromagnetically operated.  
      
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.2 Analogy between Electrical Circuits and Magnetic Circuits** <span
id="3.2"></span> 
*The videos that you watched in the previous subunit have introduced you
to different types of actuators (hydraulic, pneumatic, and
electromagnetic). Some were rotational and others were translational
(linear). We now will move on to have a detailed look at the different
types of actuators.* *Before introducing the four types of motors, some
basic electromagnetic principles are reviewed below. You will need to
revise the following basic principles in preparation for the rest of
this unit.*

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif ‘s “Analogy
    between Electrical Circuits and Magnetic Circuits”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif ‘s [“Analogy between
    Electrical Circuits and Magnetic
    Circuits”](http://www.saylor.org/site/wp-content/uploads/2012/07/1-system-analogies-rev-2-120217-CCupload.pdf)
    (PDF)  
      
     Instructions: Please click on the link above and read this article
    to study the analogy between electrical circuits and magnetic
    circuits.  
      
     Reading this chapter should take approximately 1 hour and 30
    minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).

-   **Reading: Rensselear Polytechnic Institute and Marquette
    University: Kevin Craig’s Multidisciplinary Mechatronic Innovations:
    “Electromechanics”**
    Link: Rensselear Polytechnic Institute and Marquette University:
    Kevin Craig’s *Multidisciplinary Mechatronic Innovations*:
    [“Electromechanics”](http://multimechatronics.com/mecha_notes.php) (PDF)  
      
     Instructions: Please click on the link above and then select the
    link titled “Electromechanics” to download the PDF. Note that all
    the links are arranged alphabetically. Read pages 25 to 38. This
    resource will provide you with a deep understanding of magnetic
    fundamentals and magnetic circuits. Magnetic circuits are
    fundamental to the operation of most actuators (e.g., electric motor
    and solenoids).  
      
     Reading this chapter should take approximately 2 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.3 Motor and Generator Principles** <span id="3.3"></span> 
*This subunit introduces some basic concepts necessary for understanding
DC motor operation.*

-   **Web Media: YouTube: David Colarusso’s “What Is the Magnetic
    Field?”**
    Link: YouTube: David Colarusso’s [“What Is the Magnetic
    Field?”](http://www.youtube.com/watch?v=uj0DFDfQajw&feature=BFa&list=SP305357ACC216006C)
    (YouTube)  
      
     Instructions: Please click on the link above and watch this video,
    which revises the concept of a magnetic field.  
      
     Watching this video and pausing to take notes should take
    approximately 10 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: YouTube: Yves Pelletier’s “Direct Current Electric
    Motor”**
    Link: YouTube: Yves Pelletier’s [“Direct Current Electric
    Motor”](http://www.youtube.com/watch?v=Xi7o8cMPI0E&feature=fvwrel)
    (YouTube)  
      
     Instructions: Please click on the link above and view the brief
    video, which discusses the principle operation of the DC motor.  
      
     Watching this video should take less than 5 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: YouTube: Fizzics.org’s “Fleming’s Left Hand Rule”**
    Link: YouTube: Fizzics.org’s [“Fleming’s Left Hand
    Rule”](http://www.youtube.com/watch?v=U9RezsWnPYs) (YouTube)  
      
     Instructions: Please click on the link above and view the brief
    video, which discusses Fleming’s left hand rule. Fleming’s left hand
    rule is used in order to determine the direction of force imposed on
    a current carrying conductor subjected to a magnetic field.  
      
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: YouTube: Yves Pelletier’s “Electric Generator”**
    Link: YouTube: Yves Pelletier’s [“Electric
    Generator”](http://www.youtube.com/watch?v=wchiNm1CgC4&feature=fvwrel)
    (YouTube)  
      
     Instructions: Please click on the link above and view the brief
    video, which introduces the principle of operation of a DC
    generator.  
      
     Watching this video should take approximately 5 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: YouTube: David Colarusso’s “How to Build a Simple
    Motor”**
    Link: YouTube: David Colarusso’s [“How to Build a Simple
    Motor”](http://www.youtube.com/watch?v=it_Z7NdKgmY) (YouTube)  
      
     Instructions: Please click on the link above and view the brief
    video, which further illustrates the principle of operation of the
    DC motor.  
      
     Watching this video and pausing to take notes should take
    approximately 10 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.4 Types of Actuators** <span id="3.4"></span> 
*This subunit will concentrate on the electromagnetic actuators used in
mechatronic systems.*

**3.4.1 General Introduction to Motors** <span id="3.4.1"></span> 
-   **Reading: Rensselear Polytechnic Institute and Marquette
    University: Kevin Craig’s Multidisciplinary Mechatronic Innovations:
    “Motors for Mechatronics – An Introduction”**
    Link: Rensselear Polytechnic Institute and Marquette University:
    Kevin Craig’s *Multidisciplinary Mechatronic Innovations*: [“Motors
    for Mechatronics – An
    Introduction”](http://multimechatronics.com/mecha_notes.php) (PDF)  
      
     Instructions: Please click on the link above and then select the
    link titled “Motors for Mechatronics – An Introduction” to download
    the PDF. Note that the names of the links are ordered
    alphabetically. Read this document (80 pages), which gives a general
    introduction on motors used in mechatronic systems.  
      
     Reading this document should take approximately 10 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.4.2 Brushed DC Motors** <span id="3.4.2"></span> 
*DC motors have traditionally been used as they offer high starting
torque and good speed control. DC motors are usually of the brushed
type; they have brushes that allow connecting the supply to the rotating
armature. Recently, brushless DC motors have become available, whereby
the switching function is achieved using solid state electronics.
Brushes and commutators require continuous maintenance and can be a
source of unreliability for DC motors.*

-   **Reading: Rensselear Polytechnic Institute and Marquette
    University: Kevin Craig’s Multidisciplinary Mechatronic Innovations:
    “Brushed DC Motors”**
    Link: Rensselear Polytechnic Institute and Marquette University:
    Kevin Craig’s *Multidisciplinary Mechatronic Innovations*: [“Brushed
    DC Motors”](http://multimechatronics.com/mecha_notes.php) (PDF)  
      
     Instructions: Please click on the link above and then select the
    link titled “Brushed DC Motors” to download the PDF. Note that the
    links are ordered alphabetically. Be careful not to select “Brushed
    DC Motors, PWM, H-Bridge, Optical Encoder, Arduino System” as this
    also begins with brushed DC motors. Read this presentation (104
    pages) by Kevin Craig about brushed DC motors.  
      
     Reading this presentation should take approximately 8 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif’s “Introduction
    to DC Motors”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif’s [“Introduction to
    DC
    Motors”](http://www.saylor.org/site/wp-content/uploads/2012/07/8a-DC-motors-rev-3-091115-CCupload.pdf) (PDF)  
      
     Instructions: Please click on the link above and read this chapter
    (30 pages). This text presents you with a detailed description of
    the construction and operation of the DC motor. When reading this
    document, concentrate on the following items: the principle of
    operation of the DC motor, the concept of wave winding in arranging
    the conductors inside a DC motor, methods of connecting the field of
    the DC motor, the concept of armature reaction, methods of
    overcoming the problem of armature reaction, and the basic model of
    the DC motor.  
      
     Reading this chapter should take approximately 4 hours.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    “Actuators” section, and click on the link for the title “DC Motor
    Components” to download the video. View the brief demonstration,
    which illustrates the different components of a DC motor.  
      
     Watching this video and pausing to take notes should take
    approximately 10 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.4.3 Brushless DC Motors** <span id="3.4.3"></span> 
*This sub-subunit examines the brushless type of DC motor. One of the
main disadvantages of brushed DC motors is the maintenance requirements
that are necessary for the brushes and commutators. A brushless DC motor
uses* Hall Effect *sensors to switch the current within the armature
without the need for mechanical brushes and commutators. This improves
the reliability of motor and reduces the maintenance requirements.*

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    section titled “Actuators,” and select the link titled “Brushless DC
    Motor from a Computer Fan” to download the video. Watch the video
    for a demonstration of a brushless DC motor and its method of
    operation.  
      
     Watching this video and pausing to take notes should take less than
    5 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    “Actuators” section, and select the link for the title “Brushless DC
    Motor Gear Pump” to download the video. View the brief
    demonstration, which shows a brushless DC motor used to drive a gear
    pump.  
      
     Watching this video and pausing to take notes should take less than
    5 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.4.4 AC Induction Motor** <span id="3.4.4"></span> 
*The squirrel cage induction motor (referred to as SCIM for short) is
the workhorse of the modern industry. It is used in 90% of industrial
applications. The reason it is widely used is because of its robustness
and reliability. It is effectively maintenance free. The main problem
with the AC induction motors is that it has been difficult to vary their
speed until power electronics has been applied in the design of variable
speed drives that can vary the speed of the AC induction motors.*

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif’s “Introduction
    to AC Induction Motors”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif’s [“Introduction to
    AC Induction
    Motors”](http://www.saylor.org/site/wp-content/uploads/2012/07/9a-AC-Induction-Motors-rev-3-100114-CCupload.pdf)
    (PDF)  
      
     Instructions: Please click on the link above to access the PDF, and
    read this article (16 pages). When reading the following document,
    pay special attention to the following items: the principle of a
    rotating constant magnitude magnetic field; how the intersection of
    the rotating magnetic field with the squirrel cage rotor; how to
    calculate the speed of rotation of the motor; and the concept of
    synchronous speed, asynchronous speed, and slip.  
      
     From this article, you will notice that a constant magnitude
    rotating magnetic field is produced by shifting three vectors of
    magnetic fields by 120 degrees in space (arrangement of the coils in
    a motor) and 120 degrees in time (three phase power supply).  
      
     Reading this article should take approximately 3 hours.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    “Actuators” section, and select the link titled “AC Induction Motor
    (Single Phase)” to download the video. View the brief demonstration,
    which shows the construction of a single phase squirrel cage
    induction motor. Notice how the bars in the rotor are skewed in
    order to reduce vibration or pulsation in the torque.  
      
     Watching this video and pausing to take notes should take less than
    15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: YouTube: Gotchacam’s “Assembly of AC Induction
    Motors”**
    Link: YouTube: Gotchacam’s [“Assembly of AC Induction
    Motors”](http://www.youtube.com/watch?v=7tEsJ-xAoEQ) (YouTube)  
      
     Instructions: Please click on the link above and watch this video.
    This video shows the construction of a three phase AC squirrel cage
    induction motor. Note the different stages of building the motor,
    starting with the stator and then the rotor. Also, note how special
    attention is paid to the balancing of the rotor to avoid vibration
    at full speed.  
      
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: YouTube: Gotchacam’s “Assembly of AC Induction
    Motors”**
    Link: YouTube: Gotchacam’s [“Assembly of AC Induction
    Motors”](http://www.youtube.com/watch?v=7tEsJ-xAoEQ) (YouTube)  
      
     Instructions: Please click on the link above and watch this video.
    This video shows the construction of a three phase AC squirrel cage
    induction motor. Note the different stages of building the motor,
    starting with the stator and then the rotor. Also, note how special
    attention is paid to the balancing of the rotor to avoid vibration
    at full speed.  
      
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.4.5 Stepper Motors** <span id="3.4.5"></span> 
*As opposed to the DC motors and the AC induction motors, stepper motors
move in specified steps. They are effectively* digital *motors. For
these reasons, they are ideal for accurate positioning applications.
However, they are generally limited to low power applications.*

-   **Reading: Rensselear Polytechnic Institute and Marquette
    University: Kevin Craig’s Multidisciplinary Mechatronic Innovations:
    “Step Motors”**
    Link: Rensselear Polytechnic Institute and Marquette University:
    Kevin Craig’s *Multidisciplinary Mechatronic Innovations*: [“Step
    Motors”](http://multimechatronics.com/mecha_notes.php) (PDF)  
      
     Instructions: Please click on the link above and then select the
    link titled “Step Motors.” Note that the names of the links are
    ordered alphabetically. Read the material from Kevin Craig about
    stepper motors (125 pages). Concentrate on the following points when
    reading the material: pages 10 and 11 show the advantages and
    disadvantages of stepper motors; and pages 46 through 48 explain the
    concepts of full stepping, half stepping, and micro-stepping.  
      
     Reading this chapter should take approximately 12 hours and 30
    minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    “Actuators” section, and select the link titled “Stepper Motor Step
    Response and Acceleration through Resonance” to download the video.
    View the brief demonstration, which shows the *stepped* response and
    movement of stepper motors.  
      
     Watching this video and pausing to take notes should take
    approximately 5 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    “Actuators” section, and select the link titled “DC and Stepper
    Motor Examples” to download the video. View this brief
    demonstration, which shows real life examples of stepper motors and
    DC motors.  
      
     Watching this video and pausing to take notes should take less than
    10 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.4.6 Servo-Motors** <span id="3.4.6"></span> 
*A* servo-motor *is a DC motor that has been fitted with position
feedback and a close loop control system. This makes a servo-motor ideal
for use in accurate positioning application such as robotic arms.
Similar to the stepper motor, it is limited to small power
applications.*

-   **Web Media: YouTube: Bartek Sliwinski’s “How Do Servos Work?”**
    Link: YouTube: Bartek Sliwinski’s [“How Do Servos
    Work?”](http://www.youtube.com/watch?v=-XSXfqd1N58) (YouTube)  
      
     Instructions: Please click on the link above and watch the video,
    which shows the construction of a servo-motor. From watching the
    video, you will notice the following: a servo motor is basically a
    DC motor with a closed loop control system; the angular position of
    the rotor is monitored using a potentiometer; a control circuit is
    used to compare the required angular position with the actual
    angular position of the rotor; the control circuit then moves the
    motor in order to eliminate the difference between the actual
    angular position and the required angular position; and the required
    position is communicated to the motor via a pulse that has a time
    duration corresponding to the required angle.  
      
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to the
    “Actuators” section, and select the link titled “Radio Control (RC)
    Servo Motor with Pulse-Width-Modulation Control” to download the
    video. View the brief demonstration, which clearly illustrates the
    aforementioned point about how the required angle is achieved.  
      
     Watching this video and pausing to take notes should take less than
    5 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Colorado State University’s “Video Demonstrations of
    Mechatronic Devices and Principles”**
    Link: Colorado State University’s [“Video Demonstrations of
    Mechatronic Devices and
    Principles”](http://video_demos.colostate.edu/mechatronics/) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll to the
    “Actuators” section, and select the link titled “Servo Motor System”
    to download the video. Watch the brief demonstration, which shows
    the use of two servo motors fitted with feedback devices and
    controllers.  
      
     Watching this video and pausing to take notes should take less than
    5 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.5 Criteria for Actuator Selection** <span id="3.5"></span> 
*A critical part of the mechatronics system design process is the
selection of a suitable actuator. There are a number of important
factors that must be taken into consideration when selecting a suitable
actuator.*

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif’s “Actuator
    Selection”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif’s [“Actuator
    Selection”](http://www.saylor.org/site/wp-content/uploads/2012/11/Actuator-Selection-rev-1-090908.pdf) (PDF)  
      
     Instructions: Please click on the link above to download the PDF.
    Study the brief document, which presents the various factors that
    must be taken into consideration when selecting an actuator. The
    reading also presents a comparison between the various types of
    motors.  
      
     Reading this document should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).

**3.6 Sizing of Actuators** <span id="3.6"></span> 
*When sizing a motor, the most important parameter that needs to be
calculated is the torque. This is usually referred to as the* rated
torque*. Once the rated torque has been calculated based on the
application, the necessary motor can be selected from the datasheet. The
following two problems illustrate the data needed to calculate the
required torque. The first problem is that of selecting an AC induction
motor for an elevator.*

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif’s “Sizing of an
    AC Induction Motor for an Elevator System”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif’s [“Sizing of an AC
    Induction Motor for an Elevator
    System”](http://www.saylor.org/site/wp-content/uploads/2012/07/11a-motor-sizing-and-selection-for-geared-hoisting-systems-rev-1-071221-CCupload.pdf)
    (PDF)  
      
     Instructions: Please click on the link above and read this chapter
    (9 pages).  
      
     Reading this chapter should take approximately 1 hour and 30
    minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif’s “The Sizing
    of a Permanent Magnet DC Motor for an Electric Vehicle”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif’s [“The Sizing of a
    Permanent Magnet DC Motor for an Electric
    Vehicle”](http://www.saylor.org/site/wp-content/uploads/2012/07/8b-motor-selection-for-an-electric-vehicle-rev-2-080517-CCupload.pdf)
    (PDF)  
      
     Instructions: Please click on the link above to access the PDF, and
    read this document (4 pages), which attempts to select a suitable
    motor. In the second problem, the document provides the necessary
    information for the sizing of a DC motor for an electric vehicle.  
      
     Reading this document should take approximately 45 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).

**3.7 Use of Gearboxes to Match Speed and Torque** <span
id="3.7"></span> 
*Gearboxes are extremely important in mechanical and mechatronic
systems. A* gearbox *is a device that can change both speed and torque.
It can be used to match the actuator output with the mechanical system
under control.*  
  
 *In many cases, the actuator speed (e.g., motor) is too high for the
application, and the torque it produces is too low. Using a gearbox
reduces the rotational speed and increases the rotational torque. Under
ideal conditions, the input power is equal to the output power. Under
such ideal conditions, the product of the input rotational speed and the
input torque is equal to the product of the output rotational speed and
the output torque. In reality, the output power will be less than the
input power, and the ratio of the output power to the input power is the
efficiency of the gearbox.*  
  
 *In most applications, gearboxes are used as step down devices, as they
reduce the speed and increase the torque.*

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif’s “Revision of
    Mechanics Basics”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif’s [“Revision of
    Mechanics
    Basics”](http://www.saylor.org/site/wp-content/uploads/2012/07/6a-Mechanics-rev-4-091115-CCupload.pdf)
    (PDF)  
      
     Instructions: Please click on the link above to access the PDF.
    Read pages 9 to 11, which provides more detail about the use of
    gearboxes in mechatronic systems.  
      
     Reading this document should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).


