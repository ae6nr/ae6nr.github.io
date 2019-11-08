# Bryan Redd

## About Me

Anyone who knows me knows I love math, radios, and running. I'm currently a research assistant at Brigham Young University as an electrical engineering undergraduate. I study carrier acquisition for aeronautical telemetry communication channels. I have many interests including signal processing, autonomous vehicles, embedded programming, control systems, and electromagnetics.

Thanks for checking out my GitHub page! Read about my [education](#education), [experience](#work-experience), [extra-curriculars](#extra-curricular), [publications](#publications), [awards](#awards-and-achievements), [projects](#projects), [skills](#skills), or [courses](#coursework) below. Feel free to connect with me on social media at [Twitter](https://twitter.com/bryandredd) or [LinkedIn](https://www.linkedin.com/in/bryan-redd/), or send me an email at [bryan.d.redd@gmail.com](bryan.d.redd@gmail.com).

## Education

__Electrical Engineering__, BS, _Brigham Young University_
* Minor in __Mathematics__
* Graduate April 2020
* __4.0 GPA__

## Work Experience

__Research Assistant__, _Aeronautical Telemetry_, April 2019-Present
* Derived and implemented novel phase error detector for low-SNR 16-APSK
* Implemented novel carrier phase acquisition algorithm in MATLAB
* Analyzed various carrier acquisition methods and evaluated respective BERs
* Advisors: [Dr. Michael Rice](https://ece.byu.edu/faculty/michael_rice) and [Dr. Willie Harrison](https://ece.byu.edu/faculty/willie_harrison)

__Intern__, [_FractureLab_](http://www.fracturelab.com/), May 2019-Present
* Designed and assembled custom PCB using KiCad for the [ZapperBox](http://www.fracturelab.com/products)
* Wrote controller for compliance calculations for [ADwin-Gold](https://www.adwin.de/us/produkte/gold.html)
* Created fracture simulations in GNU Octave
* Worked with FractureLab's owner [Richard Pettit](http://www.fracturelab.com/contact-info)

__Research Assistant__, _RF Energy Harvesting Group_, September 2018–April 2019
* Investigated RF circuitry for wireless power transfer for low-power sensor applications
* Evaluated efficacy of various RF-to-DC Greenacher circuits
* Advisors: [Dr. Michael Rice](https://ece.byu.edu/faculty/michael_rice) and [Dr. Willie Harrison](https://ece.byu.edu/faculty/willie_harrison)

__Research Assistant__, _Battery Materials Research Group_, April 2018-September 2018
* Spearheaded new subgroup in solid-state batteries
* Measured diffusion coefficients for solid electrolyte LiPON
* Automated controls for temperature-controlled bath using Python and serial communication
* Advisor: [Brian Mazzeo](https://ece.byu.edu/faculty/brian_mazzeo)

## Extra-Curricular

__Vice President__, _Amateur Radio Club_, January 2018-Present
* Organized weekly club meetings to discuss and implement principles of amateur radio
* Assisted four members to obtain or upgrade their licenses
* Coordinated weekly over-the-air trainings for club members to test equipment and to learn principles of radio communication

__Student Mentoring__, _President's Leadership Council_, September 2019-Present
* Lectures regarding global leadership
* One-on-one interaction between current students and successful alumni
* Discussions ranging from ethics to entrepreneurship

## Publications

|Date|Title|Link|
|---|---|---|
|2019 October|_On Carrier Frequency and Phase Synchronization for Coded 16-APSK in Aeronautical Telemetry_|[Abstract](http://telemetry.org/images/stories/itc/2019/tech/2019_tech_program_sept25.pdf)|
|2019 October|_DFT-Based Frequency Offset Estimators for 16-APSK_|[Abstract](http://telemetry.org/images/stories/itc/2019/tech/2019_tech_program_sept25.pdf)|

## Awards and Achievements

* [__Best Conference Paper__](https://ece.byu.edu/content/rice-and-redd-presented-best-paper-award) at the International Telemetering Conference in Las Vegas Nevada for "On Carrier Frequency and Phase Synchronization for Coded 16-APSK in Aeronautical Telemetry"
* [__Second Place Undergraduate Paper__](https://ece.byu.edu/content/three-electrical-engineering-students-win-best-paper-award) for "DFT-Based Frequency Offset Estimators for 16-APSK"
* __Valedictorian__, Graduating Class of La Habra High School, 2014
* __Amateur Radio License__, Extra, AE6NR

## Projects

### Capstone

I am currently working on my Capstone Project at Brigham Young University for Sandia National Laboratory. We are developing a test bench for various texture algorithms outlined in Haralick's famous paper ["Textural Features for Image Classification"](http://haralick.org/journals/TexturalFeatures.pdf). We are specifically developing three algorithms in C++: a single-threaded, multi-threaded, and CUDA implementations. We are using SWIG to create a Python user interface.

### Autonomous Vehicle

This graduate level course consisted entirely of controlling a small RC car to detect lanes, avoid obstacles, and follow the rules of the road. We used an Intel RealSense camera for image, depth, and speed information. We also used a Nvidia GPU for processing. My car can now navigate the road using several types of lane-following algorithms.

### Laser Tag

For my Junior Design Project, I designed a fully-functional, real-time laser tag system with range of over 60 feet. I implemented analog receiver amplifier circuitry on a PCB, and developed software for the on-board FPGA signal processing unit in C. This unit interfaced well with other units designed by my classmates, so we were able to play laser tag by the end of the semester.

### Embedded Systems

The following projects were completed for an embedded systems lab. I programmed an FPGA in C to control a touchscreen display. All of these systems were real-time, interactive applications. These were done on bare-metal systems.

__Programmable Clock Display__: The system displays a digital clock. Depending on where the user touches the screen, either the hours, minutes, or seconds place increments or decrements.

__Simon Says__: The classic game of Simon Says where a sequence of colored rectangles appears, and the user must repeat the sequence to progress to the next level.

__Unbeatable Tic Tac Toe__: Using a minimax algorithm, this system displays a tic tac toe opponent that can determine the optimal strategy real-time. Thus the best the human player can do is tie.

__Whack-a-Mole__: This game is the classic whack-a-mole where the user must tap all of the moles before they disappear. As the game progresses, the game becomes progressively more difficult.

### Control Systems

__Python Simluations__: I created several simulations in Python from scratch that incorporate physics for three systems, including a mass-spring-damper system, a ball on beam system, and a quadcopter system. I then designed various controllers (PID, state-space, observer-based) to control the behavior of the systems. For example, I simulated a quadcopter in two dimensions with wind. I could command the quadcopter to go to various locations, and the controller would correctly control the motors to place the quadcopter where I commanded.

### Digital Signal Processing

__Direction-finder__: Using two microphones and MATLAB, I was able to correctly determine the direction from which an audible tone propagated through the lab based on the phase difference between the two signals.

__Image processing__: Compared various methods of image filtering and evaluated their efficiency. Types of filters included edge-finding, blurring, and frequency-domain analysis.

__FIR and Adaptive Filter design__: Developed an FIR filter to separate several audible tones into their respective Morse code signals that could then be transcribed. I also created an adaptive filter that could adapt to noise and remove it from the signal.

__Spectrogram__: Created a real-time spectrogram using MATLAB and a microphone and analyzed how various filters affected frequency components of musical signals.

### Computer Science

__TensorFlow__: I trained a TensorFlow neural net to identify various articles of clothing and another to identify stop signs and stop lights for my autonomous vehicle project.

__Datalog__: I created a parser for Datalog programs, then used that information to evaluate logical statements using SQL-like queries.


## Skills

|Programming    |Software   |               |Hardware       |
|---            |---        |---            |---            |
|C              |TensorFlow |Mbed           |NVIDIA Jetson  |
|C++            |OpenCV     |GNU Octave     |FPGA           |
|Python         |Linux      |Visual Studio  |ZYBO           |
|MATLAB         |KiCad      |Zilinx SDK     |RTL-SDR        |
|HTML           |LaTeX      |KiCad          |Raspberry Pi   |
|Git            |Audacity   |LTSpice        |Arduino        |

### Coursework

#### Engineering
* Discrete-Time Signal Processing
* Linear Signals and Systems
* Self-Driving Cars
* Control Systems
* Electricity and Magnetism
* Electromagnetic Fields and Waves
* Fundamentals of Digital Systems
* Embedded Programming
* Electronic Circuit Design
* Microelectronics

#### Computer Science
* Data Structures
* Discrete Structures

#### Mathematics
* Linear Algebra
* Multivariable Calculus
* Differential Equations

## More Information

### Contact Me
Connect with me on social media at [LinkedIn](https://www.linkedin.com/in/bryan-redd/) or [Twitter](https://twitter.com/bryandredd). Send me an email at [bryan.d.redd@gmail.com](bryan.d.redd@gmail.com).

### Why is the link to this page ae6nr.github.io when your name is Bryan?
AE6NR is my amateur radio callsign. It is a short sequence of letters that is unique on the internet and personal to me.

### Slovencina

Aj hovorim po slovensky! Napriek tomu, ze som American, byval som na slovenksu dva roky v Nitre, Ziline, Kosiciach, Trencine, Bratislave, a Banskej Bystrici. Casto som sa prestavovaval. Ak hovorite po slovensky, prosim vas, aby ma kontaktovali! Rad sa so Slovakmi rozpravam. Treba pouzivat taky krasny jazyk.
