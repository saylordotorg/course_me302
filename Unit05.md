**Unit 5: Signal Processing** <span id="5"></span> 
*In any mechatronic system, signals flow into and out of the system.
These signals are essential for controlling the system and feeding back
information about the system. These are effectively the nerve signals in
the system. The signals that are received from the physical world and
sent to the controller are not in a suitable format. They need to be
converted to a suitable format in order to allow the controller to make
use of them. This is the aim of signal processing or signal
conditioning. Signal processing or signal conditioning in the
mechatronics context is the conversion of feedback signals such that
they are suitable for use by the controller.*  
  
 *However, these signals require different types of processing. For
example, the signal could be mixed with noise; thus, it could be in need
of filtering. It could be weak and small in value; thus, it could be in
need of amplification. It could be in an analogue format; thus, it could
be in need of conversion to a digital format. These are examples of some
of the signal processing operations that are required.*  
  
 *This unit will introduce you to the principles of signal processing
and the electronic circuits that can achieve such processing.*

**Unit 5 Time Advisory**  
This unit should take approximately 6.25 hours to complete.  
  
 ☐    Subunit 5.1: 1.5 hours  
  
 ☐    Subunit 5.2: 0.75 hours  
  
 ☐    Subunit 5.3: 4 hours

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   identify types of signal processing that need to be applied to a
    signal;
-   explain how to design electronic circuits for amplification,
    summing, subtraction, comparison, integration, and filtering;
-   explain the reasons for converting signals from analogue to digital
    and from digital to analogue; and
-   identify a type of analogue to digital converter, and explain its
    principle of operation.

**5.1 Operational Amplifier Circuits** <span id="5.1"></span> 
*An* operational amplifier *is an electronic circuit building block that
can be used to build signal conditioning circuits. It saves the user
from the need to re-invent the wheel, such that he or she does not need
to build an amplifier circuit but merely needs to connect the
operational amplifier such that the function of the circuit is achieved.
The operational amplifier is often referred to as op-amp for brevity.*

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif’s “Signal
    Conditioning and Processing”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif’s [“Signal
    Conditioning and
    Processing”](https://resources.saylor.org/archived/wp-content/uploads/2012/11/2-Signal-conditioning-and-processing-rev-3-090214.pdf) (PDF)  
      
     Instructions: Please click on the link above and read the first
    five sections of the document on pages 1–11. You will continue
    reading this text in subunit 5.2.  
      
     Studying these sections should take approximately 1 hour and 30
    minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).

**5.2 Filtering Circuits** <span id="5.2"></span> 
*In certain conditions, the signal is contaminated with noise. If the
noise has a frequency that is different to the frequency of the signal,
then it is possible to remove the noise from the signal by a process
known as filtering.* Filtering *removes components of a signal based on
frequency. Filters are one of four types*: *low pass filtering, high
pass filtering, band pass filtering, and bandstop filtering.*

-   **Reading: University of Jordan: Dr. Lutfi Al-Sharif’s “Signal
    Conditioning and Processing”**
    Link: University of Jordan: Dr. Lutfi Al-Sharif’s [“Signal
    Conditioning and
    Processing”](https://resources.saylor.org/archived/wp-content/uploads/2012/11/2-Signal-conditioning-and-processing-rev-3-090214.pdf) (PDF)  
      
     Instructions: Please click on the link above and read section 9 of
    the document on pages 15–18.  
      
     Reading this section should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0
    license](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Dr. Lutfi Al-Sharif and the original can be found
    [here](http://www2.ju.edu.jo/sites/Academic/l.sharif/Material/Forms/AllItems.aspx).

-   **Web Media: Colorado State University: Alciatore and Histand’s
    “Video Demonstrations from Introduction to Mechatronics and
    Measurement Systems”**
    Link: Colorado State University: Alciatore and Histand’s [“Video
    Demonstrations from Introduction to Mechatronics and Measurement
    Systems”](http://mechatronics.colostate.edu/book/video_demos.html) (Windows
    Media Player)  
      
     Instructions: Please click on the link above and then watch video
    number 11.6 titled “Robot Controlled by EMG Biosignal,” noting the
    different types of signal processing applied. In the robotic arm
    project shown in this video, notice how the signal extracted from
    the arm is band stop filtered in order to remove the noise from it.
    You will realize how important signal processing is in preparing a
    signal for use by the controller.  
      
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.3 Analogue and Digital Signal Conversion** <span id="5.3"></span> 
*Signals in the physical world exist in an analogue format, whereby the
signal magnitude is analogous or proportional to the physical variable
magnitude. In order to process a signal within a digital controller or a
laptop, it has to be converted to a digital format in which a signal is
represented in bits. It is important to convert analogue signals to
digital signals and vice versa. These two processes are denoted as
analogue to digital conversion (A to D conversion or ADC) and digital to
analogue conversion (D to A conversion or DAC).*  
  
 *ADC is necessary to acquire signals from the real world and use them
within the controller. DAC is necessary to allow the controller to
output a signal to the physical world to control a system.*

-   **Reading: All About Circuits: Tony R. Kuphaldt’s Volume IV,
    Digital: “Chapter 13: Digital Analogue Conversion”**
    Link: All About Circuits: Tony R. Kuphaldt’s *Volume IV, Digital*:
    [“Chapter 13: Digital Analogue
    Conversion”](http://www.allaboutcircuits.com/vol_4/chpt_13/1.html) (HTML
    or PDF)  
      
     Instructions: Please click on the link above and read “Chapter 13:
    Analogue Digital Conversion.” You may use the table of contents to
    read each section of this chapter in HTML format. You may also
    consider clicking on the PDF link in the upper right hand corner of
    the page to access the PDF version of the text.  
      
     Reading this chapter should take approximately 4 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


