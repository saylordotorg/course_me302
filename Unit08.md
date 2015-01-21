**Unit 8: Mechatronics System Design** <span id="8"></span> 
*This final unit is the capstone unit of this course. Unit 8 attempts to
bring together everything that you have learned so far. You will become
familiar with a systematic procedure for designing a mechatronic system
by following a clear set of steps. It is important that you understand
the role of the client, or the user, of the future system in stating
his/her requirements and specifications for the future system. These
requirements will be stated in nontechnical terms. As an engineer, you
should be able to convert these nontechnical user requirements into
technical system specifications.*

**Unit 8 Time Advisory**  
This unit should take approximately 6.25 hours to complete.  
  
 ☐    Subunit 8.1: 0.75 hours  
  
 ☐    Subunit 8.2: 3 hours  
  
 ☐    Subunit 8.3: 2.5 hours

**Unit8 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Identify the user-requirement specifications for a mechatronic
    system.
-   Identify and describe a clear set of steps to be followed in
    designing mechatronic systems.

**8.1 User Requirements Specification (URS)** <span id="8.1"></span> 
*Take approximately 15 minutes to study the following information. The
design of any mechatronic system must not commence until a clear set of
user requirements has been specified. These are referred to as the* User
Requirements Specification (URS). *The user requirements specification
can encompass a number of different spheres. They can cover resolution,
accuracy, weight, speed, and acceleration requirements. For systems that
require a fast and accurate response, it can also cover dynamic response
and steady state requirements as expressed below.*  
  
 *1.   * *Rise time*: *This is the time that the system requires in
order to move to the new state (e.g., move from one position to the next
position, increase the speed from one speed to another speed, etc.). The
rise time is defined in different ways*: *it can be defined as the time
required for the output of the system to increase from 10% of its final
value to 90% of its final value. It can also simply be defined as the
time required to reach final value. The rise time is very important as
it is critical for systems that rely on a fast movement between
positions, such as robots and automation systems in manufacturing.*  
  
 *2.   * *Overshoot*: *When the plant is being moved to its final
position, it might overshoot that position and then return. This
overshoot is undesirable, and the user might decide to limit this value.
The overshoot is usually expressed as a percentage overshoot (MP%).*  
  
 *3.   * *Settling time*: *If the system does overshoot its final
position, it will oscillate around its final position before it settles
down. This time is denoted as settling time. This parameter is also
important for the user as it will cause further delay to the operation
of the system.*  
  
 *4.   * *Steady state error*: *Once the system has settled to its final
value/position, you will notice that there may still be an error between
the actual value and the desired value. This difference is referred to
as the* steady state error.  
  
 *The following video will help you further understand these
concepts.*  
  
 *When you study* [*ME401*: *Dynamic Systems and
Controls*](http://www.saylor.org/courses/me401/)*, you will go into more
detail regarding the design of control system in order to achieve the
dynamic system response requirements and the steady state error.*

-   **Web Media: Colorado State University: Alciatore and Histand’s
    “Video Demonstrations from Introduction to Mechatronics and
    Measurement Systems”**
    Link: Colorado State University: Alciatore and Histand’s [“Video
    Demonstrations from Introduction to Mechatronics and Measurement
    Systems”](http://mechatronics.colostate.edu/book/video_demos.html) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to video
    number 11.4, click on the link titled “PID Control of the Step
    Response of a Mechanical System,” and watch this video
    demonstration. You will note how the response of the system
    undergoes overshooting and steady state error. Also, note how the
    designer alters the type of controller used in order to reduce the
    overshoot, settling time and steady state error.  
      
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Colorado State University: Alciatore and Histand’s
    “Video Demonstrations from Introduction to Mechatronics and
    Measurement Systems”**
    Link: Colorado State University: Alciatore and Histand’s [“Video
    Demonstrations from Introduction to Mechatronics and Measurement
    Systems”](http://mechatronics.colostate.edu/book/video_demos.html) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to video
    number 10.6, select the link titled “Computer Hard-Drive Track
    Seeking Demonstration,” and watch the video demonstration. Please
    note that speed and accuracy that is required in the movement of the
    reading head.  
      
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2 Steps in Mechatronics System Design (MSD)** <span
id="8.2"></span> 
*The design of any mechatronic system must follow a series of clear
steps. This ensures that the final design meets the user requirements
specification as well as being functional and economical. These steps
are clearly set out in the following document.*

-   **Reading: University of Jordan: Dr. Ashraf Saleem’s “Mechatronics
    Design Procedure”**
    Link: University of Jordan: Dr. Ashraf Saleem’s [“Mechatronics
    Design
    Procedure”](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx?RootFolder=%2fsites%2fAcademic%2fl%2esharif%2fMaterial%2fMSD%20extra%20material&FolderCTID=&View=%7bA0E71073%2d59AD%2d4A99%2dACC6%2d800786A5413C%7d) (PDF)  
      
     Instructions: Please click on the link above and then select the
    link titled “23a Mechatronics Design Procedure Amended by LAS” to
    download the PDF. Read all six pages of the document carefully and
    note the six steps that must be followed in designing a mechatronic
    system.  
      
     Reading this document should take approximately 3 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.3 Case Studies** <span id="8.3"></span> 
*In this subunit, we will look at two case studies. The first examines
the design of a robot, based on a design developed in Clarence W. de
Silva’s* Mechatronics: An Integrated Approach.  
  
 *The second case study is shown in a video that shows the use of a
robotic arm to move an object based on a signal from a human’s bicep
muscle.*  
  
 *In subunit 5.2, you watched the video titled “Robot Controlled by EMG
Biosignal” in the context of transducers and signal processing, where
you were asked to note how the signal was processed (e.g., signal
rectification, filtering, and amplification). It is timely now to watch
this video again and examine the system from a component selection and
overall design point of view.*

-   **Reading: University of Jordan: Dr. Ashraf Saleem’s “Robot Design
    and Development”**
    Link: University of Jordan: Dr. Ashraf Saleem’s [“Robot Design and
    Development”](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx?RootFolder=%2fsites%2fAcademic%2fl%2esharif%2fMaterial%2fMSD%20extra%20material&FolderCTID=&View=%7bA0E71073%2d59AD%2d4A99%2dACC6%2d800786A5413C%7d) (PDF)  
      
     Instructions: Please click on the link above and then select the
    link titled “23c Robot Design” to download the PDF. Read all 22
    pages of the document carefully and notice how the design steps have
    been followed in the design of the robotic system.  
      
     Reading this document should take approximately 2 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Colorado State University: Alciatore and Histand’s
    “Video Demonstrations from Introduction to Mechatronics and
    Measurement Systems”**
    Link: Colorado State University: Alciatore and Histand’s [“Video
    Demonstrations from Introduction to Mechatronics and Measurement
    Systems”](http://mechatronics.colostate.edu/book/video_demos.html) (Windows
    Media Player)  
      
     Instructions: Please click on the link above, scroll down to video
    number 11.6, select the link titled “Robot Controlled by EMG
    Biosignal,” and watch the video demonstration. Please note the type
    of actuator used in this case (the robotic arm), the type of control
    algorithm used (simple multi-position), and the type of physical
    controller used (desktop PC in this case). Also, note how the
    designer carried out a process of calibration of the system.  
      
     Watching this video and pausing to take notes should take
    approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


