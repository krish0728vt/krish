<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krish Ankur Shah - Electrical Engineer</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        #showcase {
            min-height: 400px;
            background: url('https://static.vecteezy.com/system/resources/previews/010/872/103/original/abstract-background-of-futuristic-digital-dark-blue-electronic-circuit-line-vector.jpg') no-repeat center center/cover;
            text-align: center;
            color: #fff;
            margin-top: 100px; /* Adjusted for the fixed header */
        }
        #showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        #showcase p {
            font-size: 20px;
        }
        #main {
            padding: 20px;
            background: #fff;
            margin-bottom: 20px;
            margin-top: 20px; /* Adjusted for reduced space */
        }
        .skills, .experience, .education, .projects, .contact {
            margin-bottom: 20px;
        }
        h2 {
            color: #333;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        .skills ul, .experience ul, .education ul, .projects ul {
            list-style-type: none;
            padding: 0;
        }
        .skills ul li, .experience ul li, .education ul li, .projects ul li {
            background: #eee;
            margin-bottom: 5px;
            padding: 10px;
            border-radius: 5px;
        }
        .skills ul li:hover, .experience ul li:hover, .education ul li:hover, .projects ul li:hover {
            background: #ccc;
        }
        .project-detail {
    margin-top: 0; /* Increased margin-top to create more space */
    padding: 20px;
    background: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    display: none;
    margin-bottom: 20px; /* Added margin-bottom to prevent overlap */
        }
        section[id] {
            padding-top: 80px; /* Adjusted for the fixed header height */
            margin-top: -80px; /* Compensate for the padding to ensure smooth scroll */
        }
    </style>
    <script>
    function toggleProjectDetail(id) {
    var project = document.getElementById(id);
    var allProjects = document.querySelectorAll('.project-detail');
    allProjects.forEach(function(detail) {
        if (detail !== project) {
            detail.style.display = 'none';
        }
    });
    project.style.display = (project.style.display === 'none' || project.style.display === '') ? 'block' : 'none';
    window.scrollTo(0, document.getElementById('projects').offsetTop);
}

    </script>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Krish Ankur Shah</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#experience">Work Experience</a></li>
                    <li><a href="#education">Education</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="showcase">
        <div class="container">
            <h1>Welcome to My Personal Webpage</h1>
            <p>Electrical Engineer | Robotics Enthusiast</p>
        </div>
    </section>

    <section id="main" class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>I am a Junior at Virginia Tech studying Electrical Engineering and seeking to explore options in Robotics, Artificial Intelligence, and Machine Learning. I have a keen interest in building and designing circuits.</p>
        </section>

        <section id="experience">
            <h2>Work Experience</h2>
            <h3>Engineer Embedded Systems at Krishna Defence and Allied Industries Ltd, Mumbai</h3>
            <p>May 2023 – August 2023</p>
            <ul>
                <li>Collaborated in the development of a circuit that powers a fan with a Solar/AC/8-hour battery prioritizing green energy.</li>
                <li>Aided in manufacturing the enclosure of the above-mentioned electronic circuit which enclosed the battery, circuit, and an external fuse in case of a short circuit.</li>
                <li>Helped in designing the CAD files for the enclosure.</li>
            </ul>

            <h3>Summer Trainee at RELIANCE RETAIL, Mumbai</h3>
            <p>June 2022 – August 2023</p>
            <ul>
                <li>Collaborated in creating "TRUUTH".</li>
                <li>Did market research for finding target audience for people who need home delivery of medication.</li>
                <li>Found a plan of how to reach out to people who needed the service.</li>
            </ul>

            <h3>Project Head at Automation Anywhere, Virtual</h3>
            <p>April 2022 – July 2023</p>
            <ul>
                <li>Created bots that help clear blurred images on bills.</li>
                <li>Identified and resolved project issues quickly and efficiently, minimizing their impact on project progress.</li>
            </ul>

            <h3>Student Intern at White Gold Technologies LLP, Mumbai</h3>
            <p>March 2021 – August 2021</p>
            <ul>
                <li>Assisted in assembling a patented product called Robotic Milk Collection Unit.</li>
                <li>Assisted the team in making new circuits.</li>
            </ul>
        </section>

        <section id="education">
            <h2>Education</h2>
            <h3>Virginia Polytechnic Institute and State University, Blacksburg</h3>
            <p>B.S in Electrical Engineering</p>
            <p>August 2021 – Present</p>
            <ul>
                <li>Junior studying Electrical Engineering</li>
                <li>Minor in Robotics</li>
            </ul>

            <h3>Jai Hind College, Mumbai</h3>
            <p>Associate of Science in Electronics Technology</p>
            <p>July 2019 – March 2021</p>
            <ul>
                <li>Graduated with 90%</li>
            </ul>

            <h3>St. Mary's School (ISCE), Mumbai</h3>
            <p>High School Diploma</p>
            <p>June 2009 – May 2019</p>
            <ul>
                <li>Graduated with 92%</li>
                <li>Awarded Technical Drawing Application Merit</ul>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li><a href="javascript:void(0)" onclick="toggleProjectDetail('project1')">Fire Alarm System Using IC555</a></li>
                <li><a href="javascript:void(0)" onclick="toggleProjectDetail('project2')">Obstacle Avoidance Car Using IC</a></li>
                <li><a href="javascript:void(0)" onclick="toggleProjectDetail('project3')">Pattern Flying Drone</a></li>
                <li><a href="javascript:void(0)" onclick="toggleProjectDetail('project4')">Heated Cup Holder</a></li>
                <li><a href="javascript:void(0)" onclick="toggleProjectDetail('project5')">Dinosaur Game on BOOSTXL-EDUMKII and MSP432</a></li>
                <li><a href="javascript:void(0)" onclick="toggleProjectDetail('project6')">Reaction Time Tester</a></li>
                <li><a href="javascript:void(0)" onclick="toggleProjectDetail('project7')">LED Pattern Circuit</a></li>
            </ul>
        </section>

  <section id="project1" class="project-detail" style="margin-top: 30px;">
    <h2>Fire Alarm System Using IC555</h2>
            <p><strong>Description:</strong></p>
            <p>The Fire Alarm System is a simple and cost-effective solution designed to detect fire and alert users. Utilizing the IC555 timer, the system is capable of sensing temperature changes and triggering an alarm when a specified threshold is exceeded.</p>
            <p><strong>Goals:</strong></p>
            <ul>
                <li>To develop a reliable and affordable fire alarm system.</li>
                <li>To understand and implement the IC555 timer in a practical application.</li>
                <li>To enhance safety measures by providing an early warning system for fire hazards.</li>
            </ul>
            <p><strong>Technologies Used:</strong></p>
            <ul>
                <li>IC555 Timer: The core component for the timing and detection circuit.</li>
                <li>Thermistor: A temperature-sensitive resistor used to detect temperature changes.</li>
                <li>Buzzer: An audio alert component to sound the alarm.</li>
                <li>Resistors and Capacitors: For circuit stability and proper functioning.</li>
                <li>Power Supply: To power the circuit components.</li>
            </ul>
            <p><strong>Features:</strong></p>
            <ul>
                <li>Temperature Detection: Senses temperature rise using a thermistor.</li>
                <li>Audible Alarm: Emits a loud sound to alert users of potential fire.</li>
                <li>Compact Design: Easy to install and maintain.</li>
                <li>Low Cost: Economical components ensure affordability.</li>
            </ul>
            <p><strong>Challenges:</strong></p>
            <ul>
                <li>Sensitivity Calibration: Adjusting the thermistor and IC555 circuit to accurately detect significant temperature changes without false alarms.</li>
                <li>Power Management: Ensuring the circuit operates efficiently with minimal power consumption.</li>
                <li>Component Sourcing: Finding high-quality and reliable components within budget constraints.</li>
            </ul>
            <p><strong>Outcome:</strong></p>
            <p>The project successfully produced a functioning fire alarm system that effectively detects temperature rises and sounds an alarm. It proved to be a valuable learning experience in circuit design and practical applications of the IC555 timer.</p>
        </section>

       <section id="project2" class="project-detail" style="margin-top: 30px;">
    <h2>Obstacle Avoidance Car Using IC</h2>
            <p><strong>Description:</strong></p>
            <p>The Obstacle Avoidance Car is an autonomous vehicle designed to navigate and avoid obstacles in its path. By using integrated circuits (ICs) for control and sensors for detection, the car can detect obstacles, stop, and change direction to find a clear path.</p>
            <p><strong>Goals:</strong></p>
            <ul>
                <li>To develop an autonomous car capable of avoiding obstacles using ICs.</li>
                <li>To integrate sensor technology with IC-based control for real-time decision-making.</li>
                <li>To gain experience in circuit design and practical applications of ICs.</li>
            </ul>
            <p><strong>Technologies Used:</strong></p>
            <ul>
                <li>IC555 Timer: For generating the control signals.</li>
                <li>Ultrasonic Sensors: To detect obstacles by measuring distance.</li>
                <li>Motor Drivers (e.g., L293D): To control the car's motors based on the IC output.</li>
                <li>Motors and Wheels: For the car's movement.</li>
                <li>Chassis: For the physical structure of the car.</li>
                <li>Power Supply: To power the sensors, ICs, and motors.</li>
            </ul>
            <p><strong>Features:</strong></p>
            <ul>
                <li>Obstacle Detection: Uses ultrasonic sensors to detect objects in the car’s path.</li>
                <li>Autonomous Navigation: Automatically stops and changes direction when an obstacle is detected.</li>
                <li>IC-Based Control: Utilizes IC555 timer and other ICs for control logic.</li>
                <li>Compact Design: Easy to assemble and modify for different terrains.</li>
            </ul>
            <p><strong>Challenges:</strong></p>
            <ul>
                <li>Sensor Integration: Ensuring the ultrasonic sensors accurately detect obstacles and interface correctly with the ICs.</li>
                <li>IC Logic Design: Designing the control logic using ICs for real-time obstacle avoidance.</li>
                <li>Power Management: Ensuring a stable power supply for continuous operation.</li>
                <li>Circuit Complexity: Managing the complexity of the circuit with multiple ICs and sensors.</li>
            </ul>
            <p><strong>Outcome:</strong></p>
            <p>The project successfully created an obstacle avoidance car that can detect obstacles, stop, and change direction autonomously using ICs. It provided valuable experience in circuit design, sensor integration, and practical applications of ICs.</p>
        </section>

     <section id="project3" class="project-detail" style="margin-top: 30px;">
    <h2>Pattern Flying Drone</h2>
            <p><strong>Description:</strong></p>
            <p>The Pattern Flying Drone is an innovative project where a drone is programmed to fly in a specific pattern. Using FPL code, the drone was made to fly in the pattern spelling out "ECE 2544," representing the class number for which the project was undertaken.</p>
            <p><strong>Goals:</strong></p>
            <ul>
                <li>To develop a drone capable of flying in a pre-defined pattern.</li>
                <li>To enhance skills in programming and controlling drones using FPL code.</li>
                <li>To demonstrate the practical application of drones in creating specific flight paths.</li>
            </ul>
            <p><strong>Technologies Used:</strong></p>
            <ul>
                <li>Drone: Equipped with the necessary hardware for flight and control.</li>
                <li>FPL Code: A flight programming language used to script the drone's flight pattern.</li>
                <li>GPS and IMU Sensors: For precise navigation and stability during flight.</li>
                <li>Remote Control System: For manual overrides and adjustments.</li>
            </ul>
            <p><strong>Features:</strong></p>
            <ul>
                <li>Pattern Flight: Programmed to fly in the pattern spelling "ECE 2544."</li>
                <li>Autonomous Navigation: Follows the programmed flight path autonomously.</li>
                <li>Precision Control: Utilizes GPS and IMU sensors for accurate navigation.</li>
                <li>Customizable Patterns: The flight pattern can be modified for different applications.</li>
            </ul>
            <p><strong>Challenges:</strong></p>
            <ul>
                <li>Pattern Accuracy: Ensuring the drone accurately follows the pattern without deviations.</li>
                <li>Sensor Integration: Integrating GPS and IMU sensors for stable and precise flight.</li>
                <li>Code Optimization: Writing efficient FPL code to control the drone's movements smoothly.</li>
                <li>Environmental Factors: Managing external factors like wind and obstacles that could affect flight.</li>
            </ul>
            <p><strong>Outcome:</strong></p>
            <p>The project successfully created a drone that could fly in the specific pattern of "ECE 2544." This demonstrated the ability to program drones for precise and complex flight paths, providing valuable experience in drone technology and flight programming.</p>
        </section>

<section id="project4" class="project-detail" style="margin-top: 30px;">
            <h2>Heated Cup Holder</h2>
            <p><strong>Description:</strong></p>
            <p>The Heated Cup Holder is a practical project designed to maintain the temperature of beverages. Utilizing an Arduino and a heat sensor, the system controls the heating of a copper coil wrapped around a steel cup, ensuring the drink stays warm.</p>
            <p><strong>Goals:</strong></p>
            <ul>
                <li>To develop a device that keeps beverages warm using controlled heating.</li>
                <li>To integrate sensor technology with an Arduino for precise temperature control.</li>
                <li>To enhance understanding of heat transfer and temperature regulation.</li>
            </ul>
            <p><strong>Technologies Used:</strong></p>
            <ul>
                <li>Arduino: For controlling the heating process and managing sensor data.</li>
                <li>Heat Sensor (Temperature Sensor): To monitor the temperature of the cup.</li>
                <li>Copper Coil: Wrapped around the steel cup for efficient heat transfer.</li>
                <li>Steel Cup: The container for the beverage, chosen for its thermal conductivity.</li>
                <li>Power Supply: To provide power to the Arduino and the heating element.</li>
            </ul>
            <p><strong>Features:</strong></p>
            <ul>
                <li>Temperature Monitoring: Continuously monitors the temperature of the cup to maintain the desired warmth.</li>
                <li>Automated Heating: Activates the heating coil when the temperature drops below a set threshold.</li>
                <li>Efficient Heat Transfer: Uses a copper coil for quick and even heating of the steel cup.</li>
                <li>User-Friendly Design: Simple and safe to use with minimal setup required.</li>
            </ul>
            <p><strong>Challenges:</strong></p>
            <ul>
                <li>Temperature Regulation: Ensuring accurate temperature control to prevent overheating.</li>
                <li>Heat Distribution: Designing the copper coil arrangement for uniform heating.</li>
                <li>Power Management: Ensuring the system is energy-efficient and safe to use.</li>
                <li>Component Integration: Seamlessly integrating the heat sensor, Arduino, and heating element.</li>
            </ul>
            <p><strong>Outcome:</strong></p>
            <p>The project successfully created a heated cup holder that keeps beverages warm by maintaining a set temperature. It provided valuable insights into temperature control, sensor integration, and practical applications of Arduino in everyday devices.</p>
        </section>

<section id="project5" class="project-detail" style="margin-top: 30px;">
            <h2>Dinosaur Game on BOOSTXL-EDUMKII and MSP432</h2>
            <p><strong>Description:</strong></p>
            <p>The Dinosaur Game project is a fun and interactive implementation of the classic browser-based game. Using CCS (Code Composer Studio) for coding, the game is designed to run on the BOOSTXL-EDUMKII booster pack and the MSP432 microcontroller, allowing users to play the game directly on a hardware board.</p>
            <p><strong>Goals:</strong></p>
            <ul>
                <li>To develop a playable version of the Dinosaur Game on an embedded system.</li>
                <li>To learn and apply programming skills using CCS and embedded C.</li>
                <li>To enhance understanding of microcontroller-based game development.</li>
            </ul>
            <p><strong>Technologies Used:</strong></p>
            <ul>
                <li>BOOSTXL-EDUMKII: The booster pack used for interfacing and input/output operations.</li>
                <li>MSP432 Microcontroller: The main processing unit for running the game code.</li>
                <li>CCS (Code Composer Studio): The integrated development environment (IDE) used for coding and debugging.</li>
                <li>Push Buttons and LEDs: For game control and visual feedback.</li>
                <li>LCD Display: To display game graphics and score.</li>
            </ul>
            <p><strong>Features:</strong></p>
            <ul>
                <li>Interactive Gameplay: Allows users to control the dinosaur and avoid obstacles using push buttons.</li>
                <li>Real-Time Processing: Ensures smooth gameplay with responsive controls.</li>
                <li>Score Tracking: Keeps track of the player's score and displays it.</li>
                <li>Visual Feedback: Uses LEDs and possibly an LCD for game indications and graphics.</li>
            </ul>
            <p><strong>Challenges:</strong></p>
            <ul>
                <li>Real-Time Performance: Ensuring the game runs smoothly on the microcontroller with minimal latency.</li>
                <li>Input Handling: Implementing responsive and accurate controls using the board's push buttons.</li>
                <li>Graphics Rendering: Creating simple yet effective graphics within the hardware limitations.</li>
                <li>Debugging: Identifying and resolving issues in the game logic and hardware integration.</li>
            </ul>
            <p><strong>Outcome:</strong></p>
            <p>The project successfully created a playable version of the Dinosaur Game on the BOOSTXL-EDUMKII and MSP432 board. It provided hands-on experience in embedded system programming, game development, and hardware-software integration.</p>
        </section>

<section id="project6" class="project-detail" style="margin-top: 30px;">
            <h2>Reaction Time Tester</h2>
            <p><strong>Description:</strong></p>
            <p>The Reaction Time Tester is a project designed to measure and display the reaction time of a user. Utilizing the MSP432 microcontroller and the BOOSTXL-EDUMKII booster pack, the system uses a TimerA to precisely measure the reaction time when a user responds to a visual cue (an LED turning on).</p>
            <p><strong>Goals:</strong></p>
            <ul>
                <li>To develop a device that accurately measures and displays a user's reaction time.</li>
                <li>To enhance skills in embedded systems programming using CCS (Code Composer Studio).</li>
                <li>To understand and implement timing functions and interrupts on the MSP432 microcontroller.</li>
            </ul>
            <p><strong>Technologies Used:</strong></p>
            <ul>
                <li>MSP432 Microcontroller: The main processing unit for running the code and managing the timers.</li>
                <li>BOOSTXL-EDUMKII Booster Pack: Used for interfacing and I/O operations, including LEDs and push buttons.</li>
                <li>TimerA: Utilized for measuring reaction time accurately.</li>
                <li>CCS (Code Composer Studio): The integrated development environment (IDE) used for coding and debugging.</li>
                <li>LEDs and Push Buttons: For visual cues and user input.</li>
            </ul>
            <p><strong>Features:</strong></p>
            <ul>
                <li>Accurate Reaction Time Measurement: Uses TimerA to measure the time between an LED turning on and a button press.</li>
                <li>User Feedback: Displays the reaction time for each trial and the average reaction time on an LCD screen.</li>
                <li>Randomized Start: Starts each trial with a random delay to prevent user anticipation.</li>
                <li>Multiple Trials: Allows the user to configure the number of trials for a comprehensive test.</li>
            </ul>
            <p><strong>Challenges:</strong></p>
            <ul>
                <li>Timer Precision: Ensuring TimerA provides precise and consistent timing measurements.</li>
                <li>Randomized Delay: Implementing a randomized delay before the LED turns on to test genuine reaction times.</li>
                <li>User Interface: Designing a simple and effective interface for displaying instructions, results, and feedback.</li>
                <li>Code Debugging: Identifying and fixing issues in the embedded code for smooth operation.</li>
            </ul>
            <p><strong>Outcome:</strong></p>
            <p>The project successfully created a reaction time tester that accurately measures and displays a user's reaction time. It provided valuable experience in embedded systems programming, timing functions, and hardware-software integration.</p>
        </section>

<section id="project7" class="project-detail" style="margin-top: 30px;">
            <h2>LED Pattern Circuit</h2>
            <p><strong>Description:</strong></p>
            <p>The LED Pattern Circuit is a project designed to control LEDs to light up in a specific pattern using an Arduino. The circuit was built on a breadboard, and the Arduino was programmed to sequence the LEDs in the desired pattern.</p>
            <p><strong>Goals:</strong></p>
            <ul>
                <li>To create a visually appealing LED pattern using simple components.</li>
                <li>To enhance skills in circuit design and programming with Arduino.</li>
                <li>To understand the basics of controlling multiple outputs in a sequential manner.</li>
            </ul>
            <p><strong>Technologies Used:</strong></p>
            <ul>
                <li>Arduino: The main controller for the LED sequence.</li>
                <li>LEDs: For visual output, connected in a pattern on the breadboard.</li>
                <li>Breadboard: For assembling the circuit without soldering.</li>
                <li>Resistors: To limit the current through each LED.</li>
                <li>Wires: For making the necessary connections on the breadboard.</li>
            </ul>
            <p><strong>Features:</strong></p>
            <ul>
                <li>Custom LED Patterns: Programmable sequences to create various visual effects.</li>
                <li>Easy to Modify: The breadboard setup allows for easy changes and adjustments to the circuit.</li>
                <li>User-Controlled: Ability to change patterns or sequences through code modifications or input controls.</li>
                <li>Educational: Provides a hands-on learning experience in both electronics and programming.</li>
            </ul>
            <p><strong>Challenges:</strong></p>
            <ul>
                <li>Circuit Stability: Ensuring all connections are secure on the breadboard to prevent intermittent connections.</li>
                <li>Current Management: Properly sizing resistors to prevent LEDs from burning out.</li>
                <li>Code Optimization: Writing efficient code to control multiple LEDs without delay.</li>
                <li>Pattern Design: Creating interesting and complex patterns that are visually appealing.</li>
            </ul>
            <p><strong>Outcome:</strong></p>
            <p>The project successfully created an LED pattern circuit that can display various sequences using an Arduino. It provided valuable experience in basic electronics, circuit design, and embedded programming.</p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>★★★★★ Electronics</li>
                <li>★★★★★ Robotics</li>
                <li>★★★★★ Circuit Design</li>
                <li>★★★★★ Technical Drawing</li>
                <li>★★★★★ SolidWorks (CAD)</li>
                <li>★★★★★ Sheet Metal</li>
                <li>★★★★★ Laser Cutting</li>
                <li>★★★★☆ C++</li>
                <li>★★★☆☆ Artificial Intelligence</li>
                <li>★★★☆☆ Raspberry Pi</li>
                <li>★★★☆☆ Machine Learning</li>
                <li>★★★☆☆ Arduino</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Email: krish0728@vt.edu</p>
            <p>Phone: +91 8879001177</p>
            <p>Location: Mumbai, India</p>
        </section>
    </section>

    <footer>
        <p>Krish Ankur Shah &copy; 2024</p>
    </footer>
</body>
</html>
