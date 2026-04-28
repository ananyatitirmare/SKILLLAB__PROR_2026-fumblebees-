# SKILL LAB PRATICAL HACKATHON

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4/3 students  
> **Project Duration:** 8 hours  
> **Total Time Available:** 32 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository

After forking this repository, rename it using the format:

`SKILLLAB_PROR-2026-TeamName`

### Example

`SKILLLAB_PROR-2026-AuroWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the build period.  
By the final review, this README should clearly show:

- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules

- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Studio / Group Name

`Fumblebees`

## 1.2 Team Members

| Name           | Primary Role                    | Secondary Role | Strengths Brought to the Project |
| -------------- | ------------------------------- | -------------- | -------------------------------- |
| `Nirmiti Nalawade` | `[Electronics / ideation  ]` | `[Coding]`  | `Material Handling, Hardware `|
| `Ananya Titirmare`  | `[Electronics / Documentation]`   | `[coding]`     | `Documentation, Hardware`    |
| `Khushi Sayani`  | `[Electronics / Connections]`   | `[coding]`     | `Material Handling, Hardware`    |
| `Ishaan Pailwan`  | `[Electronics / PPT]`   | `[videography]`     | `Material Handling, gift of gab`    |



## 1.3 Project Title

`"Morse Mayhem"``

<img width="1600" height="1131" alt="image" src="image/mkb1.jpeg" />

## 1.4 One-Line Pitch

`A real-time Morse code battle where players race to decode and transmit signals using dots and dashes faster than their opponent.`

## 1.5 Expanded Project Idea

In 1–2 paragraphs, explain:

- what your project is,
- what kind of experience it creates,
- what technologies are involved.

**Response:**  
`Our project is a **Real-Time Morse Code Battle System**, an interactive game-based embedded system where two teams of two players compete using Morse code communication.

This project creates a fun, competitive, and educational experience by combining teamwork, quick thinking, signal-based communication, and real-time decision-making. 

The technologies involved include Vicharak Shrike Lite as the main controller, touch sensor for Morse code input, LED and buzzer for signal output, and the Arduino Serial Monitor for word display, result checking, and score tracking, making the project unique, engaging, and highly effective for demonstrating embedded systems and communication principles.`

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem

This module does **not** require your project to solve a large social problem.

You are allowed to build:

- toys,
- games,
- interactive objects,
- playful machines,
- kinetic artifacts,
- humorous devices,
- strange but delightful experiences,
- things that are entertaining to use or watch.



# 3. Inspiration

## 3.1 References

List what inspired the project.

| Source Type | Title / Link                                                        | What Inspired You                                                                         |
| ----------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| `[movie ]`   | `https://youtu.be/YeOt1jSO9fQ?si=Diagco0IdMHI-YYL                 ` | `We were inspired by Raazi movie, where authentic coded communication and secret signal transfer motivated us to create a real-time Morse Code Battle System.

|             |                                                                     |                                                                                           |
|             |                                                                     |                                                                                           |

## 3.2 Original Twist

What makes your project original?

**Response:** 
Our project is original because it transforms traditional Morse code communication into a real-time team-based competitive game instead of a normal learning system. It combines encoding, live signal transmission using touch input with LED and buzzer output, and decoding under time pressure, creating an interactive battlefield-style experience. Unlike common automation or robot projects, it focuses on teamwork, strategy, and communication skills through a live multiplayer challenge.


---

# 4. Project Intent

## 4.1 User Journey 

Describe exactly how a user will use the project.Make it a story
**Response:**  
At the start of the game, two teams of two players are ready for the Morse Code Battle. Player 1 from each team stands near the system and looks at the Arduino Serial Monitor, where a secret word is displayed for a few seconds, such as “CODE” or “SIGNAL.” After a short time, the word disappears, so the player must remember it quickly. Using the touch sensor, Player 1 converts the word into Morse code by giving short touches for dots and long touches for dashes. As the touches are made, the system produces Morse signals through the LED and buzzer.

Meanwhile, Player 2 of each team carefully watches the LED blinking pattern and listens to the buzzer sounds to decode the Morse code. They try to identify the original word and write their answer on paper before submitting it. The guessed words are then entered into the Arduino Serial Monitor, where the system checks whether the answer is correct. The team that decodes the word accurately and faster wins that round, making the game exciting, competitive, and interactive.

                                                  



---

# 5. Definition of Success

## 5.1 Definition of “Usable”
The project is considered usable when two teams can successfully play the Morse Code Battle by viewing a secret word, converting it into Morse code using the touch sensor, transmitting the signals through LED and buzzer outputs, and allowing the second player to decode and guess the correct word. The system should correctly display the word, generate proper Morse code signals, and verify the final answer through the Arduino Serial Monitor.


## 5.2 Minimum Usable Version

What is the smallest version of this project that still delivers the core experience?
**Response:**  
The smallest version of this project that still delivers the core experience includes Vicharak Shrike Lite, one touch sensor for Morse code input, one LED and one buzzer for Morse signal output, and the Arduino Serial Monitor for displaying the secret word and checking the guessed answer. Even without advanced features like scoring, multiple rounds, or voice output, the basic gameplay of encoding, transmitting, and decoding Morse code should work properly.


## 5.3 Stretch Features

What features are nice to have but not essential?
Nice-to-have but non-essential features include multiple difficulty levels with longer or technical words, automatic score tracking for multiple rounds, timer-based speed competition, voice announcements using a voice module, separate team scoreboards, and bonus challenge rounds. We can also use a green LED to indicate a correct answer and a red LED to indicate a wrong answer, making the result more visual and interactive for the players. These features improve the user experience and make the game more exciting, but they are not necessary for the core functionality of the project.-

---

# 6. System Overview

## 6.1 Project Type

Check all that apply.

- [x] Electronics-based

- [ ] Mechanical

- [x] Sensor-based

- [ ] App-connected

- [ ] Motorized

- [x] Sound-based

- [x] Light-based

- [x] Screen/UI-based

- [x] Fabricated structure

- [x] Game logic based

- [x] Installation

- [ ] Other:

## 6.2 High-Level System Description

Explain how the system works in simple terms.

Include:

- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
**Input:**
The main input of the system is the two touch sensors used by Player 1 of each team to enter Morse code. A secret word such as “HI,” “CAT,” “DOG,” or “BAT” is first shown on the Arduino Serial Monitor for a few seconds so the players can memorize it. After the word disappears, Player 1 uses the touch sensor to convert the word into Morse code, where a short touch represents a dot (.) and a long touch represents a dash (-).

**Processing:**
The Vicharak Shrike Lite acts as the main controller and processes the touch sensor input. It measures how long the touch sensor is pressed and compares it with a fixed time threshold. If the touch is short, it is considered a dot, and if it is longer, it is considered a dash. The system then matches the input with the Morse code pattern of the selected word and prepares the signal output.

**Output:**
The system gives output using yellow LEDs and buzzers for both teams. The yellow LED blinks and the buzzer produces short and long beeps according to the Morse code pattern, helping Player 2 observe and listen carefully. After decoding, Player 2 enters the guessed word into the Arduino Serial Monitor. If the answer is correct, the green LED glows; if the answer is wrong, the red LED blinks.

**Physical Structure:**
The physical structure includes the Vicharak Shrike Lite board, two touch sensors, yellow LEDs for Morse signal output, green and red LEDs for result indication, two buzzers, jumper wires, breadboard, and power supply. All components are connected in a compact tabletop setup so that both teams can play and interact easily during the game.

**App Interaction (if any):**
There is no mobile app used in this project. The Arduino Serial Monitor acts as the display and interaction platform. It shows the secret word, game instructions, player turns, guessed answers, and final results, making the entire system simple and fully hardware-based.


## 6.3 Input / Output Map

| System Part                              | Type            | What It Does                                                               |
| System Part            | Type            | What It Does                                                                                   |
| ---------------------- | --------------- | ---------------------------------------------------------------------------------------------- |
| Touch Sensor 1         | Input           | Used by Player 1 of Team 1 to enter Morse code using short and long touches                    |
| Touch Sensor 2         | Input           | Used by Player 1 of Team 2 to enter Morse code using short and long touches                    |
| Arduino Serial Monitor | Input / Output  | Displays secret word, game instructions, player turns, and accepts guessed words from Player 2 |
| Vicharak Shrike Lite   | Processing Unit | Processes touch input, identifies dots and dashes, controls outputs, and checks final answers  |
| Yellow LED 1           | Output          | Blinks Morse code signals for Team 1                                                           |
| Yellow LED 2           | Output          | Blinks Morse code signals for Team 2                                                           |
| Buzzer 1               | Output          | Produces Morse code beep sounds for Team 1                                                     |
| Buzzer 2               | Output          | Produces Morse code beep sounds for Team 2                                                     |
| Green LED 1            | Output          | Glows when Team 1 gives the correct answer                                                     |
| Green LED 2            | Output          | Glows when Team 2 gives the correct answer                                                     |
| Red LED 1              | Output          | Blinks when Team 1 gives the wrong answer                                                      |
| Red LED 2              | Output          | Blinks when Team 2 gives the wrong answer                                                      |


---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch

Add an early sketch of the full idea.

**Insert image below:**  
`[<img width="1600" height="1131" alt="image" src="image/mkb4.jpeg" />]` 
`[<img width="1600" height="1131" alt="image" src="image/mkb5.jpeg" />]` 


Example:

```md

```



## 7.2 Labeled Build Sketch

Add a sketch with labels showing:

- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`[Upload image and link here]`
<img width="1600" height="1200" alt="image" src="image/mkb6" />

## 7.3 Approximate Dimensions

| Dimension        | Value   |
| ---------------- | ------- |
| Length           | `16 cm` |
| Width            | `16 cm` |
| Height           | `8 cm`  |
| Estimated weight | `400 g` |

---

# 8. Electronics Planning

## 8.1 Electronics Used

| Component                | Quantity | Purpose                                                                       |
| ------------------------ | -------- | ------------------------------------------------------------------------------|                                        
| Vicharak Shrike Lite     |        1 | Main controller for processing Morse code inputs and outputs                   |
| Touch Sensor             |        2 | Used by Player 1 of each team to enter Morse code using short and long touches |
| Yellow LED               |        2 | Displays Morse code signals through blinking output                            |
| Green LED                |        2 | Indicates correct answer for each team                                         |
| Red LED                  |        2 | Indicates wrong answer for each team                                           |
| Buzzer                   |        2 | Produces Morse code beep sounds for each team                                  |
| Breadboard               |        1 | Used for circuit connections and component setup                               |
| Jumper Wires             | Multiple | Connects all components with the controller                                    |
| USB Cable / Power Supply |        1 | Powers the Shrike Lite board and the system                                    |
| Arduino Serial Monitor   |        1 | Displays secret words, player turns, guessed answers, and final results        |

## 8.2 Wiring Plan

Describe the main electrical connections.

**Response:**  
`The ESP32 is connected to the motor driver (L298N) using four GPIO pins (18,19; 22,23) to control motor direction (IN1, IN2, IN3, IN4). Two PWM-capable pins (ENA and ENB; 25 and 26) are connected to control the speed of each motor.

The motors are connected to the output terminals of the motor driver. The motor driver is powered directly by the battery pack (higher voltage), while the ESP32 receives regulated 5V from the buck converter.

All components share a common ground to ensure stable operation. The projector and camera are connected to the laptop, which handles tracking and game logic separately.`

## 8.3 Circuit Diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`
<img width="867" height="1156" alt="image" src="image/mkb4.jpeg" />





# 9. Power Plan

| Question         | Response                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Power source     | `Battery (Li-ion pack)`                                                                                                                           |
| Voltage required | `~6–8.4V for motors (via driver), stepped down to 5V for ESP32 (buck converter)`                                                                  |
| Current concerns | `Motors can draw high current under load, which may cause voltage drops affecting ESP32 and WiFi stability`                                       |
| Safety concerns  | `Avoid over-discharging Li-ion batteries, ensure proper voltage regulation, prevent short circuits, and secure wiring to avoid loose connections` |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform                 | Purpose                                                                |
| ------------------------------- | ---------------------------------------------------------------------- |
| Arduino IDE                     | Used to write and upload code to Vicharak Shrike Lite / Arduino Uno    |
| Arduino Serial Monitor          | Displays secret words, player inputs, guesses, and game results        |
| C / C++ (Arduino Language)      | Used to program logic for Morse code encoding, decoding, and game flow |
| Embedded C Libraries            | Used for handling GPIO control, timing, and sensor input processing    |


## 10.2 Software Logic

Describe what the code must do.

Include:

- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  
`

- **Startup behavior:**  
  The ESP32 initializes motor pins, PWM control, and starts a WiFi access point with a web server. The laptop initializes camera input, tracking system, and projection mapping.
- **Input handling:**  
  Movement commands are received from the laptop (pygame sends http requests)
- **Sensor reading:**  
  The camera continuously captures frames, and OpenCV detects ArUco markers to determine the car’s position and orientation.
- **Decision logic:**  
  The system maps the car’s position into a virtual coordinate system and checks for nearby obstacles or collisions. If movement is valid, the command is allowed; if not, it is blocked or replaced with a feedback action (like a slight shake).
- **Output behavior:**  
  The ESP32 drives the motors using PWM signals to control speed and direction. The projector displays the updated game environment, including obstacles, targets, and feedback visuals.
- **Communication logic:**  
  The laptop sends HTTP requests (e.g., `/forward`, `/left`) to the ESP32 over WiFi. The ESP32 parses these commands and executes motor actions.
- **Reset behavior:**  
  If no command is received within a short timeout, the ESP32 stops the motors. The game resets when a level is completed or restarted.`

## 10.3 Code Flowchart

Insert a flowchart showing your code logic.

Suggested sequence:

- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  
<img width="1600" height="1200" alt="image" src="" />
<img width="1600" height="1200" alt="image" src="" />




# 11. Bill of Materials

## 11.1 Full BOM

| Item                             | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec               | Why This Choice?          |
| -------------------------------- | --------:| ------- | ------------ | --------------:| ----------------------------- | ------------------------- |
| `[ESP32]`                        | `1`      | `Yes`   | `No`         | `0`            | `38 Pin ESP32`                | `[To control components]` |
| `[Motor Driver]`                 | `[1]`    | `[Yes]` | `[No]`       | `0`            | `[LN296]`                     | `[To drive both motors]`  |
| `[DC Motors and wheel]`          | `[2]`    | `[No]`  | `[Yes]`      | `[150]`        | `[BO Motors and 6 cm wheels]` | `[high torque motors]`    |
| `[Buck Converter]`               | `[1]`    | `[No]`  | `[Yes]`      | `[75]`         |                               |                           |
| `[Li-ion batteries with holder]` | `[1]`    | `[No]`  | `[Yes]`      | `[200]`        |                               |                           |

## 11.2 Material Justification

Explain why you selected your main materials and components.

**Response:**  
`DC motors (BO motors) were chosen instead of servos or steppers because the system requires continuous rotation for movement rather than precise angular control (Previously, we were considering using steppers as we were planning on tracking movement on the ESP using its relative position from an origin, but since we're using a camera now, this is not required). A motor driver (L298N) was used to allow bidirectional control and speed variation using PWM.`


## 11.3 Items You chose

| Item                 | Why Needed               | Purchase Link | Latest Safe Date to Procure | Status       |
| -------------------- | ------------------------ | ------------- | --------------------------- | ------------ |
| `BO Motors + Wheels` | `Drive system for car`   | `robu.in`     | `15th April`                | `[Received]` |
| `Buck Converter`     | `Stable power for ESP32` | `local store` | `before testing`            | `[Received]` |
| `Li-ion Batteries`   | `Portable power`         | `local store` | `before testing`            | `Recieved`   |

## 11.4 Budget Summary

| Budget Item           | Estimated Cost              |
| --------------------- | ---------------------------:|
| Electronics           | `[400]`                     |
| Mechanical parts      | `[200]`                     |
| Fabrication materials | `[0 (Available on campus)]` |
| Purchased extras      | `[0]`                       |
| Contingency           | `[300]`                     |
| **Total**             | `[900]`                     |

## 11.5 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  

---

# 12. Planning the Work

## 12.1 Team Working Agreement

Write how your team will work together.

Include:

- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  


## 12.2 Task Breakdown

| Task ID | Task                    | Owner    | Estimated Hours | Deadline     | Dependency | Status |
| ------- | ----------------------- | -------- | ---------------:| ------------ | ---------- | ------ |
| T1      | `[Finalize concept]`    | `[Both]` | `2`             | `1st April`  | `None`     | `Done` |


## 12.3 Responsibility Split

| Area                 | Main Owner | Support Owner |
| -------------------- | ---------- | ------------- |
| Concept              | `[Gopal]`  | `[Kader]`    |
| Electronics          | `[]`       | `[]`     |
| Coding               | `[]`       | `[]`     |
| Mechanical build     | `[]`       | `[]`    |
| Testing              | `[]`       | `[]`    |
| Documentation        | `[]`       | `[]`     |

---

# 13. 2 hour Milestones

## 13.1 8-hour Plan

### Bi Hour 1 — Plan and De-risk

Expected outcomes:

- [x] Idea finalized
- [x] Core interaction decided
- [x] Sketches made
- [x] BOM completed
- [x] Purchase needs identified
- [ ] Key uncertainty identified
- [x] Basic feasibility tested

### Bi Hour 2 — Build Subsystems

Expected outcomes:

- [x] Electronics tests completed
- [ ] CAD / structure planning completed
- [ ] App UI started if needed
- [x] Mechanical concept tested
- [x] Main subsystems partially working

### Bi Hour 3 — Integrate

Expected outcomes:

- [x] Physical body built
- [x] Electronics integrated
- [x] Code connected to hardware
- [ ] App connected if required
- [x] First playable version exists

### Bi Hour 4 — Refine and Finish

Expected outcomes:

- [x] Technical bugs reduced
- [x] Playtesting completed
- [x] Improvements made
- [x] Documentation completed
- [x] Final build ready

## 13.2  Update Log

| Week   | Planned Goal   | What Actually Happened | What Changed   | Next Steps     |
| ------ | -------------- | ---------------------- | -------------- | -------------- |
| Week 1 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Week 2 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Week 3 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Week 4 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |

---

# 14. Risks and Unknowns

## 14.1 Risk Register

| Risk                                                            | Type         | Likelihood | Impact   | Mitigation Plan                                                                       | Owner                |
| --------------------------------------------------------------- | ------------ | ---------- | -------- | ------------------------------------------------------------------------------------- | -------------------- |
| WiFi connection between laptop and ESP32 becomes unstable       | `Technical`  | `Medium`   | `High`   | Keep ESP32 close, ensure stable power supply, reduce network load, add fail-safe stop | `[Gopal]`           |


## 14.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

**Response:**  


---

# 15. Testing 

## 15.1 Technical Testing Plan

| What Needs Testing     | How You Will Test It                                                                 | Success Condition                                                                                    |
| ---------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| `[Wifi connection]`    | `[Check if motor spins via app button]`                                              | `[Both motors accurately respond to wifi signals]`                                                   |
                       |
## 15.2 Testing and Debugging Log

| Date          | Problem Found                         | Type         | What You Tried                                | Result               | Next Action                                    |
| ------------- | ------------------------------------- | ------------ | --------------------------------------------- | -------------------- | ---------------------------------------------- |
| `18th April`  | `Car not balancing properly`          | `Mechanical` | `Add low-friction caster support to one side` | `Worked`             | `improve caster structure`                     |


## 15.3 Playtesting Notes

| Tester      | What They Did                        | What Confused Them                    | What They Enjoyed                         | What You Will Change                          |
| ----------- | ------------------------------------ | ------------------------------------- | ----------------------------------------- | --------------------------------------------- |
| `Gopal` | `Tried navigating through obstacles` | `Some obstacles ewren't clear enough` | `Liked projection + real car interaction` | `Add a slight red highlight around obstacles` |


---

# 16. Build Documentation

## 16.1 Fabrication Process

Describe how the project was physically made.

Include:

- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
`The fabrication process involved designing, manufacturing, assembling, and refining both the physical structure and electronic integration of the system.`

`Design (CAD Modeling):
The initial model was created using CAD software, where components were designed based on the actual dimensions of the electronic parts. This ensured accurate fitting and minimized errors during assembly.
Cutting (Laser Cutting):
The designed parts were fabricated using laser cutting techniques. Sheets were cut precisely according to the CAD model to create the structural base and mounts for components.`

`Components were fixed using adhesives and mechanical supports. Certain parts were intentionally kept modular (not permanently fixed) to allow easy replacement and modification of electronics.
Surface Finishing:
Some parts were sanded to smooth rough edges after cutting. Sawdust mixed with adhesive was used to fill gaps and uneven edges, improving structural finish. The final structure was then painted for better aesthetics and durability.`

`Environment Setup (Dark Room Fabrication):
To enhance projection visibility, a controlled dark environment was created using Z-boards, paper sheets, and bedsheets. This minimized external light interference and improved projection clarity.
Revisions and Iterations:
Multiple adjustments were made throughout the process, including refining alignment, improving structural stability, repositioning components, and optimizing the interaction between the physical car and projected environment.`

## 16.2 Build Photos

Add photos throughout the project.

Suggested images:

- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.
- <img width="960" height="1280" alt="WhatsApp Image 2026-04-24 at 9 46 02 AM (1)" src="https://github.com/user-attachments/assets/74baa570-5770-483e-be6d-d2f03386e37c" />





# 17. Final Outcome

## 17.1 Final Description

Describe the final version of your project.

**Response:**  


## 17.2 What Works Well



## 17.3 What Still Needs Improvement


## 17.4 What Changed From the Original Plan

How did the project change from the initial idea?

**Response:**  


---

# 18. Reflection

## 18.1 Team Reflection

What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  


## 18.2 Technical Reflection

What did you learn about:

- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  


## 18.3 Design Reflection

What did you learn about:

- designing ,
- delight,
- clarity,
- physical interaction,
- understanding,
- iteration?

**Response:**  


## 18.4 If You Had One More hour

What would you improve next?

**Response:**  

` `

---

# 19. Final Submission Checklist

Before submission, confirm that:

- [x] Team details are complete
- [x] Project description is complete
- [x] Inspiration sources are included
- [x] Sketches are added
- [x] BOM is complete
- [x] Purchase list is complete
- [x] Budget summary is complete
- [x] Mechanical planning is documented if applicable
- [ ] App planning is documented if applicable
- [x] Code flowchart is added
- [x] Task breakdown is complete
- [x] Weekly logs are updated
- [x] Risk register is complete
- [x] Testing log is updated
- [x] Playtesting notes are included
- [x] Build photos are included
- [x] Final reflection is written
<img width="1131" height="1600" alt="image" src="" />

---


---


