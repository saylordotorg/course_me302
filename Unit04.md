**Unit 4: Feedback Devices** <span id="4"></span> 
*In the last unit, you studied the types of actuators used in
mechatronic systems. The feedback devices are equally important to the
actuators. Feedback devices are effectively the eyes and ears of the
control system that enable it to accurately control the mechatronic
system. As mentioned in the last unit, it is generally necessary to
control position, speed, or both. Thus, it is important to have
available feedback devices for position and speed. This unit will
introduce you to the different types of feedback devices that are used
in mechatronic systems. Feedback devices in mechatronic systems are
mainly used to measure the position, speed, or orientation of the system
that is being controlled.*  
  
 *In the following three subunits, you will be introduced to three
groups of feedback devices that are used in mechatronic systems. In
order for a controller to properly control a mechatronic system, it
needs to possess accurate and up-to-date information about the velocity
and position of the system. This allows the controller to compare the
desired velocity (or position) with the actual velocity (or position)
and to adjust the actuator outputs accordingly. Providing such
information is the role of feedback devices.*

**Unit 4 Time Advisory**  
This unit should take approximately 4.25 hours to complete.  
  
 ☐    Subunit 4.1: 1.75 hours  
  
 ☐    Subunit 4.2: 0.75 hours  
  
 ☐    Subunit 4.3: 1.75 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   explain the need for feedback devices in mechatronic systems;
-   describe the principle of operation of an incremental shaft encoder;
-   describe the principle of operation of an incremental encoder;
-   describe the principle of operation of the linear variable
    differential transformer (LVDT); and
-   describe the principle of operation of an accelerometer and a
    tilt-meter.

**4.1 Shaft Encoders: Incremental and Absolute Shaft Encoders** <span
id="4.1"></span> 
*A* shaft encoder *is a device that is mechanically connected to a
rotating shaft, such that it rotates at exactly the same speed of the
shaft and attains exactly the same position, and it provides an
electrical output that represents the position, speed or both of the
mechanical shaft to which it is connected.*  
  
 *Shaft encoders are digital in nature. They provide an output in a
digital format in the form of pulses. Shaft encoders are of two types*:
*incremental and absolute. Incremental shaft encoders provide a stream
of pulses that are proportional to the rotational speed of the shaft. In
effect, incremental shaft encoders are ideally used for speed
feedback.*  
  
 *Absolute shaft encoders, on the other hand, provide a digital output
that represents the actual rotational position of the shaft. Absolute
shaft encoders provide an output in the form of a number of bits (e.g.,
12 bit; 14 bit; 18 bit). The angular resolution of the shaft encoder
increases as the number of bits increases.*

-   **Reading: Rensselear Polytechnic Institute and Marquette
    University: Kevin Craig’s Multidisciplinary Mechatronic Innovations:
    “Optical Encoder and the Arduino”**
    Link: Rensselear Polytechnic Institute and Marquette University:
    Kevin Craig’s *Multidisciplinary Mechatronic Innovations*: [“Optical
    Encoder and the
    Arduino”](http://multimechatronics.com/mecha_notes.php) (PDF)  
      
     Instructions: Please click on the link above and select the link
    titled “Optical Encoder and the Arduino.” While the links are mostly
    ordered alphabetically, note that this link appears at the top of
    the list. Read pages 1 to 11 of the presentation by Kevin Craig
    about optical encoders and the Arduino.  
      
     Reading this presentation and the information provided in this
    subunit should take approximately 1 hour and 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: The Saylor Foundation’s “Grey Code versus Binary Code”**
    Link: The Saylor Foundation’s [“Grey Code versus Binary
    Code”](https://resources.saylor.org/archived/wp-content/uploads/2013/01/ME302-4.1-GreyCodeBinaryCode.pdf)
    (PDF)  
      
     Instructions: Download and read this article.  
      
     Reading this article should take approximately 15 minutes.

**4.2 Linear Variable Differential Transformer: Principle of Operation**
<span id="4.2"></span> 
*The shaft encoders discussed in the last subunit are rotary in nature.
The* linear variable differential transformer *is the main feedback
device used for linear position feedback. It is very widely used in
industrial applications.*

-   **Reading: RDP Electronics Ltd.’s “How It Works – LVDT”**
    Link: RDP Electronics Ltd.’s [“How It Works –
    LVDT”](http://www.rdpe.com/displacement/lvdt/lvdt-principles.htm) (HTML)  
      
     Instructions: Read the material on the webpage linked above, and
    watch the LVDT animation. You will notice that as the ferromagnetic
    core moves left and right, it changes the coupling between the
    primary coil and the each of the two secondary coils.  
      
     Reading this article should take approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: InTech: Dr. Lutfi Al-Sharif et al.’s MATLAB for Engineers
    – Applications in Control, Electrical Engineering, IT, and Robotics:
    “Chapter 4: Linear Variable Differential Transformer Design and
    Verification Using MATLAB and Finite Element Analysis”**
    Link: InTech: Dr. Lutfi Al-Sharif et al.’s *MATLAB for Engineers –
    Applications in Control, Electrical Engineering, IT, and Robotics*:
    [“Chapter 4: Linear Variable Differential Transformer Design and
    Verification Using MATLAB and Finite Element
    Analysis”](http://www.intechopen.com/books/matlab-for-engineers-applications-in-control-electrical-engineering-it-and-robotics/linear-variable-differential-transformer-design-and-verification-using-matlab-and-finite-element-ana) (PDF)  
      
     Instructions: Please click on the link above and select “Download
    as PDF” to access the text. Read the first two pages of Chapter 4.
    Notice the details of the construction of the LVDT. In particular,
    notice the primary coil, secondary coils and the core. The LVDT is
    the main sensor used nowadays for measuring linear displacement
    accurately. It has very high sensitivity and can cover very small
    strokes. Unlike linear potentiometers, it does not suffer from
    friction.  
      
     Reading this chapter should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.3 Accelerometers: Principle of Operation** <span id="4.3"></span> 
*The feedback devices discussed in the last two subunits measure
velocity or displacement. It is also possible to measure acceleration
directly by the use of accelerometers. It is common in some applications
to measure acceleration and derive velocity by the use of integration.
One of the most widely used types of accelerometers is the so-called*
seismic accelerometer*.*

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif’s
    “Acceleration, Vibration, and Shock Measurement”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif’s [“Acceleration,
    Vibration, and Shock
    Measurement”](https://resources.saylor.org/archived/wp-content/uploads/2012/11/10-accleration-vibration-and-shock-measurement-rev-1-080525.pdf) (PDF)  
      
     Instructions: Please click on the link above to access the PDF, and
    read the material on accelerometers (7 pages). Note how a seismic
    accelerometer device can be used to convert acceleration into
    displacement.  
      
     A *gyroscope* is a device that can store the original orientation
    of a vehicle or an aircraft. It is based on the principle of
    conservation of angular momentum. In effect, it resists the change
    of its orientation.  
      
     Reading this chapter should take approximately 1 hour and 30
    minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).

-   **Web Media: YouTube: Science Online’s “Gyroscopes”**
    Link: YouTube: Science Online’s
    [“Gyroscopes”](http://www.youtube.com/watch?v=cquvA_IpEsA) (YouTube)  
      
     Instructions: Please click on the link above and watch the video on
    gyroscopes, noting their different applications.  
      
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


