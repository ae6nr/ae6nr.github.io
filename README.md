# About Me

Anyone who knows me knows I love math, radios, and reading. I am a graduate student in electrical engineering at Brigham Young University in Provo, Utah. I study carrier acquisition for aeronautical telemetry communication channels. I have many interests including signal processing, information theory, digital communications, and control systems.

Read about my [education](#education), [experience](#work-experience), [extra-curriculars](#extra-curricular), [publications](#publications), [awards](#awards-and-achievements), [projects](#projects), [skills](#skills), or [courses](#coursework) below. Feel free to connect with through any of the following platforms:

|Platform|Contact|
|-|-|
|Email|bryan.d.redd@gmail.com|
|LinkedIn|[Bryan Redd](https://www.linkedin.com/in/bryan-redd/)|
|Twitter|[bryandredd](https://twitter.com/bryandredd)|
|GitHub|[@ae6nr](https://github.com/ae6nr)|
|GitLab|[@ae6nr](https://gitlab.com/ae6nr)|

# Education

__Electrical Engineering__, BS, [_Brigham Young University_](https://www.byu.edu/), April 2020
* Minor in __Mathematics__
* Graduated __Summa Cum Laude__
* 4.0 GPA

# Work Experience

__Intern__, [_Rincon Research_](http://www.rincon.com/), June 2020-July 2020
* Implemented a [WAAS](https://www.faa.gov/about/office_org/headquarters_offices/ato/service_units/techops/navservices/gnss/waas/) signal demodulator in C++
* Created several general-use modules related to spread-spectrum signal demodulation
* Processed real data faster than real-time
* Successfully obtained all of the data they requested
* Completed project individually and remotely during COVID-19 outbreak

__Research Assistant__, [_Aeronautical Telemetry_](https://icelab.byu.edu/aeronautical-telemetry-systems), April 2019-Present
* Derived and implemented novel phase error detector for low-SNR 16-APSK
* Implemented novel carrier phase acquisition algorithm in [MATLAB](https://www.mathworks.com/products/matlab.html)
* Analyzed various carrier acquisition methods and evaluated respective BERs
* Advisors: [Dr. Michael Rice](https://ece.byu.edu/faculty/michael_rice) and [Dr. Willie Harrison](https://ece.byu.edu/faculty/willie_harrison)

__Intern__, [_FractureLab_](http://www.fracturelab.com/), May 2019-Present
* Designed and assembled custom PCB using KiCad for the [ZapperBox](http://www.fracturelab.com/products)
* Wrote controller for compliance calculations for [ADwin-Gold](https://www.adwin.de/us/produkte/gold.html)
* Developed associated GUI interface using [PyQt5](https://www.qt.io/).
* Created fracture simulations in [GNU Octave](https://www.gnu.org/software/octave/)
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

# Extra-Curricular

__Vice President__, [_Amateur Radio Club_](http://radio.byu.edu/), January 2018-April 2020
* Organized weekly club meetings to discuss and implement principles of amateur radio
* Assisted four members to obtain or upgrade their licenses
* Coordinated weekly over-the-air trainings for club members to test equipment and to learn principles of radio communication

__Student Mentoring__, _President's Leadership Council_, September 2019-Present
* Lectures regarding global leadership
* One-on-one interaction between current students and successful alumni
* Discussions ranging from ethics to entrepreneurship

# Publications

|Date|Title|Link|
|---|---|---|
|2019 October|_On Carrier Frequency and Phase Synchronization for Coded 16-APSK in Aeronautical Telemetry_|[Abstract](https://repository.arizona.edu/handle/10150/635271)|
|2019 October|_DFT-Based Frequency Offset Estimators for 16-APSK_|[Abstract](https://repository.arizona.edu/handle/10150/635273)|

# Awards and Achievements

* [__Best Conference Paper__](https://ece.byu.edu/content/rice-and-redd-presented-best-paper-award) at the International Telemetering Conference in Las Vegas Nevada for "On Carrier Frequency and Phase Synchronization for Coded 16-APSK in Aeronautical Telemetry"
* [__Second Place Undergraduate Paper__](https://ece.byu.edu/content/three-electrical-engineering-students-win-best-paper-award) for "DFT-Based Frequency Offset Estimators for 16-APSK"
* __Valedictorian__, Graduating Class of La Habra High School, 2014
* __Amateur Radio License__, Extra, AE6NR

# Projects

## WAAS Signal Demodulator

While at [Rincon](https://www.rincon.com), I wrote a WAAS signal demodulator in C++. I focused on general-purpose, reusable code that could easy be ported into other pojects. This project included several DSP principles, including spread-spectrum modulation, resampling filters, correlation filters, Viterbi decoding of convolutional codes, frame synchronization using distributed preambles, and interpreting received message packets. I was able to obtain all of the information that they asked for before my internship ended.

## Capstone Project

My team developed a test bench for various texture algorithms outlined in Haralick's famous paper ["Textural Features for Image Classification"](http://haralick.org/journals/TexturalFeatures.pdf) for [Sandia National Laboratories](https://www.sandia.gov). We are specifically developed three algorithms in C++: a single-threaded, multi-threaded, and CUDA implementations. We used SWIG to create a Python user interface for ease of use.

## Autonomous Vehicle

This graduate level course consisted entirely of controlling a small RC car to detect lanes, avoid obstacles, and follow the rules of the road. We used an Intel RealSense camera for image, depth, and speed information. We also used a Nvidia GPU for processing. Our car navigated a to-scale road using several types of lane-following algorithms. An article and video about the project can be found [here](https://news.byu.edu/intellect/byu-offers-crash-course-in-self-driving-car-technology).

## Laser Tag

For my Junior Design Project, I designed a fully-functional, real-time laser tag system with range of over 60 feet. I implemented analog receiver amplifier circuitry on a PCB, and developed software for the on-board FPGA signal processing unit in C. This unit interfaced well with other units designed by my classmates, so we were able to play laser tag by the end of the semester.

## Embedded Systems

The following projects were completed for an embedded systems lab. I programmed an FPGA in C to control a touchscreen display. All of these systems were real-time, interactive applications. These were done on bare-metal systems.

__Programmable Clock Display__: The system displays a digital clock. Depending on where the user touches the screen, either the hours, minutes, or seconds place increments or decrements.

__Simon Says__: The classic game of Simon Says where a sequence of colored rectangles appears, and the user must repeat the sequence to progress to the next level.

__Unbeatable Tic Tac Toe__: This system displays a tic tac toe opponent that can determine the optimal strategy real-time using a minimax algorithm. Thus the best the human player can do is tie.

__Whack-a-Mole__: This game is the classic whack-a-mole where the user must tap all of the moles before they disappear. As the game progresses, the game becomes progressively more difficult.

## Control Systems

__Python Simulations__: I created several simulations in Python from scratch that incorporate physics for three systems, including a mass-spring-damper system, a ball on beam system, and a quadcopter system. I then designed various controllers (PID, state-space, observer-based) to control the behavior of the systems. For example, I simulated a quadcopter in two dimensions with wind. I could command the quadcopter to go to various locations, and the controller would correctly control the motors to place the quadcopter where I commanded.

## Digital Signal Processing

__Direction-finder__: Using two microphones and MATLAB, I was able to correctly determine the direction from which an audible tone propagated through a room based on the phase difference between the two signals.

__Image processing__: Compared various methods of image filtering and evaluated their efficiency. Types of filters included edge-finding, blurring, and frequency-domain analysis.

__FIR and Adaptive Filter design__: Developed an FIR filter to separate several audible tones into their respective Morse code signals that could then be transcribed. I also created an adaptive filter that could adapt to noise and remove it from the signal.

__Spectrogram__: Created a real-time spectrogram using MATLAB and a microphone and analyzed how various filters affected frequency components of musical signals.

## Computer Science

__TensorFlow__: I trained a TensorFlow neural net to identify stop signs and stop lights for my autonomous vehicle project.

__Datalog__: I created a Datalog parser, then used that information to evaluate logical statements using SQL-like queries.


# Skills

|Programming    |Software   |               |Hardware       |
|---            |---        |---            |---            |
|C              |TensorFlow |Mbed           |NVIDIA Jetson  |
|C++            |OpenCV     |GNU Octave     |FPGA           |
|Python         |Linux      |Visual Studio  |ZYBO           |
|MATLAB         |KiCad      |Zilinx SDK     |RTL-SDR        |
|HTML           |LaTeX      |KiCad          |Raspberry Pi   |
|Git            |Audacity   |LTSpice        |Arduino        |
|Qt             |Ubuntu     |GitLab         |ADwin-GOLD     |
|Make           |Google Test|GNU Radio      |               |

## Coursework

### Engineering
* Information Theory
* Coding Theory
* Digital Communication Theory
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

### Computer Science
* Data Structures
* Discrete Structures

### Mathematics
* Linear Algebra
* Multivariable Calculus
* Differential Equations
* Information Theory

# More Information

## What does AE6NR mean?
AE6NR is my amateur radio callsign. It is a short sequence of letters that is unique to me, so you can often find me on the internet by searching for those letters.

## Slovencina

Aj hovorim po slovensky! Napriek tomu, ze som American, byval som na slovenksu dva roky v Nitre, Ziline, Kosiciach, Trencine, Bratislave, a Banskej Bystrici. Casto som sa prestavovaval. Ak hovorite po slovensky, prosim vas, aby ma kontaktovali! Rad sa so Slovakmi rozpravam. Treba pouzivat taky krasny jazyk.
