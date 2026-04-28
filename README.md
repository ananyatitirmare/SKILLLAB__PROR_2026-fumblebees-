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

`"Morse Mayhem"`

<img width="1600" height="1131" alt="images" src="images/mkb1.jpeg"/>
Youtube video link
https://youtu.be/03DDm3TSC_o?si=O5UKdrPGedf8HJI7

## 1.4 One-Line Pitch

`A real-time Morse code battle where players race to decode and transmit signals using dots and dashes.`

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
<img width="1600" height="1131" alt="images" src="images/mkb4.jpeg" /> 
<img width="1600" height="1131" alt="images" src="images/mkb5.jpeg" /> 


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
<img width="1600" height="1200" alt="images" src="images/mkb6.jpeg" />


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
## 8.2 Wiring Plan

The main controller (Vicharak Shrike Lite ) is connected to two touch sensors using digital input pins. TOUCH_A is connected to pin 14 and TOUCH_B is connected to pin 19. These sensors are used by Player 1 of each team to enter Morse code using short and long touches.

The output system is connected through multiple GPIO pins. Yellow LEDs (YELLOW_A on pin 15 and YELLOW_B on pin 20) are used to display Morse code signals visually. Buzzers (BUZZER_A on pin 16 and BUZZER_B on pin 21) are used to produce sound signals for dot and dash representation.

For result indication, GREEN_A (pin 17) and GREEN_B (pin 22) are used to show correct answers, while RED_A (pin 18) and RED_B (pin 26) are used to indicate wrong answers. All components are connected with a common ground to ensure stable operation and avoid signal issues.

## 8.3 Circuit Diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`
<img width="867" height="1156" alt="images" src="images/mkb4.jpeg" />





# 9. Power Plan

| Question         | Response                                                                                                                                |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Power source     | USB power supply / 9V battery / external power bank                                                                                     |
| Voltage required | 5V DC for Vicharak Shrike Lite                                                                                    |
| Current concerns | Buzzer, LEDs, and touch sensors consume very low current, but unstable power may cause false sensor readings or buzzer noise issues     |
| Safety concerns  | Ensure correct polarity while wiring, avoid short circuits on breadboard, and keep connections tight to prevent system resets or dama

In this project, since there are no motors or heavy loads, the power requirement is simple and stable. A standard USB power supply is sufficient to run the entire Morse Code Battle System reliably during demonstration.

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
Here is your answer written **according to your exact code and project**:

---

## **Code Working Description**

### **Startup behavior:**
When the system starts, both teams’ pins (touch sensors, LEDs, and buzzers) are initialized. The Serial Monitor starts communication at 115200 baud rate and waits until it is opened. After a short delay, the system prints “DASH DOT DUEL START” and prepares the game by selecting random words for both Team A and Team B. A countdown is shown so players can memorize the words before they are hidden.
### **Input handling:**
The main input comes from two touch sensors, one for each team. Players use short touches and long touches to generate Morse code. The system continuously checks whether the touch sensor is HIGH and measures how long it is pressed to decide whether it is a dot (.) or dash (_). Final guesses from players are also taken through the Serial Monitor input.
### **Sensor reading:**
The touch sensors act as the primary input “sensors.” The code reads the duration of each touch press using `millis()` timing. Based on the press time, it classifies the input into Morse symbols. No external analog sensors are used in this version—only digital touch detection.
### **Decision logic:**
The system compares press duration with a threshold (`SHORT_TOUCH = 300ms`). If the press is shorter, it is recorded as a dot; if longer, it is recorded as a dash. After gameplay, the system compares the guessed word with the original randomly selected word for each team to decide correctness and determine the winner.
### **Output behavior:**
The system outputs Morse playback using LEDs and buzzers. A dot is shown using a yellow LED blink, and a dash is shown using a buzzer sound. At the end of the round, green LEDs indicate correct answers, red LEDs indicate wrong answers, and messages are printed on the Serial Monitor for results and winner declaration.
### **Communication logic:**
All game communication happens through the Arduino Serial Monitor. It displays the secret words, countdown timer, player instructions, Morse input logs, playback signals, final guesses, and results. Players also enter their final answers through the Serial Monitor, which the system reads using serial input functions.
### **Reset behavior:**
After completing one round, the program enters an infinite loop (`while(1);`), meaning the system stops and does not restart automatically. To play again, the system must be manually reset or re-uploaded from the Arduino IDE.

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
<img width="867" height="1156" alt="images" src="images/mkb9.jpeg" />


# 11. Bill of Materials

## 11.1 Full BOM

| Item                               | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec                   | Why This Choice?                                       |
| ---------------------------------- | -------: | ------- | ------------ | -------------- | --------------------------------- | ------------------------------------------------------ |
| Vicharak Shrike Lite / Arduino Uno |        1 | Yes     | No           | 0              | Microcontroller board             | Main controller for game logic and signal processing   |
| Touch Sensor                       |        2 | Yes     | No           | 0              | Capacitive / digital touch module | Used for Morse code input (dot and dash control)       |
| Yellow LED                         |        2 | Yes     | No           | 0              | 5mm LED                           | Displays Morse code signals visually                   |
| Buzzer                             |        2 | Yes     | No           | 0              | 5V active buzzer                  | Produces Morse code sound signals                      |
| Green LED                          |        2 | Yes     | No           | 0              | 5mm LED                           | Indicates correct answer                               |
| Red LED                            |        2 | Yes     | No           | 0              | 5mm LED                           | Indicates wrong answer                                 |
| Breadboard                         |        1 | Yes     | No           | 0              | Standard breadboard               | Used for circuit connections                           |
| Jumper Wires                       |      Set | Yes     | No           | 0              | Male-to-male / female wires       | Electrical connections between components              |
| USB Cable / Power Supply           |        1 | Yes     | No           | 0              | 5V USB power                      | Powers the controller and circuit                      |
| Laptop / PC                        |        1 | Yes     | No           | 0              | Computer system                   | Runs Arduino IDE and Serial Monitor for game interface |

## 11.2 Material Justification

Explain why you selected your main materials and components.

**Response:**  
## 11.2 Material Justification

The Vicharak Shrike Lite was selected as the main controller because it is capable of handling multiple digital inputs and outputs simultaneously, which is essential for managing touch sensors, LEDs, buzzer signals, and Serial Monitor communication in a real-time game system.

Touch sensors were chosen instead of push buttons because they provide a more interactive and fast-response method for entering Morse code using simple short and long touches. LEDs and buzzers were used as output devices because they clearly represent Morse code signals in both visual (light) and audio (sound) forms, making it easier for the second player to decode the message accurately. The Serial Monitor was selected as the display interface because it eliminates the need for an LCD and simplifies the system while still effectively showing words, inputs, and results in real time.


## 11.3 Items You chose

| Item                               | Why Needed                                                | Purchase Link     | Latest Safe Date to Procure | Status   |
| ---------------------------------- | --------------------------------------------------------- | ----------------- | --------------------------- | -------- |
| Touch Sensor                       | Used for entering Morse code using short and long touches | kit               | Before integration testing  | Received |
| Vicharak Shrike Lite /             | Main controller for processing inputs and outputs         | kit               | Before coding phase         | Received |
| LED (Red, Green, Yellow)           | Visual indication of Morse signals and results            | kit               | Before circuit assembly     | Received |
| Buzzer                             | Generates Morse code sound signals                        | kit               | Before testing              | Received |
| Breadboard                         | For circuit assembly and connections                      | kit               | Before wiring setup         | Received |
| Jumper Wires                       | Used for connecting all components                        | kit               | Before wiring setup         | Received |
| USB Cable / Power Supply           | Powers the entire system                                  | kit               | Before testing phase        | Received |
| Laptop / PC                        | Runs Arduino IDE and Serial Monitor                       | available         | Always available            | Received |

## 11.4 Budget Summary

| Budget Item                                                 | Estimated Cost |
| ----------------------------------------------------------- | -------------: |
| Electronics (touch sensors, LEDs, buzzer, controller setup) |            500 |
| Mechanical parts (base board, mounting, structural setup)   |            150 |
| Fabrication materials (wires, breadboard, connectors)       |            100 |
| Purchased extras (if required minor components)             |              0 |
| Contingency (testing, replacement, misc.)                   |            150 |
| **Total**                                                   |        **900** |


## 11.5 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  
The overall cost of the project can be reduced further by simplifying the output and display components. Since the Arduino Serial Monitor is used instead of an LCD, we already eliminate the cost of display hardware. The system can also be built using only one set of LEDs (instead of multiple indicators per team) if budget needs to be minimized, while still maintaining the core Morse code experience.
Additional savings can be achieved by using only a single buzzer instead of separate buzzers for both teams, and by reusing components already available in the kit rather than purchasing extra modules. The touch sensors, LEDs, and controller board are already sufficient to demonstrate the full functionality, so no major hardware expansion is required. In case of shared resources, components like the laptop (for Serial Monitor) and power supply can be used commonly across both teams, further reducing the effective cost of the system.


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
## Team Working Plan

* **Task division:**
  Nirmiti will handle the coding part, including game logic, Morse code encoding/decoding, and Serial Monitor interaction. Khushi will handle all hardware connections and circuit setup, including touch sensors, LEDs, and buzzer wiring. Ananya will be responsible for documentation, including reports, diagrams, and written content. Ishaan will handle the PPT design and final presentation preparation.

* **Decision making:**
  All important decisions (such as circuit changes, code updates, or feature additions) will be discussed as a team and finalized through mutual agreement to ensure clarity and avoid errors.

* **Progress tracking:**
  Time to time progress will be checked by reviewing completed tasks such as working hardware setup, tested codes, playing the game to chgeck the progress, and completed documentation sections. Short group discussions will be held to ensure all parts are aligned.

* **If a task is delayed:**
  If any task is delayed, other team members will support by sharing workload or adjusting responsibilities temporarily to ensure the project stays on schedule and is completed within the deadline.

* **Documentation maintenance:**
  Ananya will continuously update documentation during development so that all changes, circuit updates, and code modifications are recorded in real time for the final report submission.


## 12.2 Task Breakdown

| Task ID | Task                                            | Owner   | Estimated Hours | Deadline      | Dependency | Status      |
| ------- | ----------------------------------------------- | ------- | --------------: | ------------- | ---------- | ----------- |
| T1      | Finalize concept and game design                | Team    |               1 | 28th April    | None       | Done        |
| T2      | Hardware planning and component selection       | Khushi  |               1 | 28th April    | T1         | Done        |
| T3      | Circuit connections (touch sensor, LED, buzzer) | Khushi  |               1 | 28th April    | T2         | Done        |
| T4      | Core coding (Morse logic + game flow)           | Nirmiti |               1 | 28th April    | T2         | In Progress |
| T5      | Serial Monitor integration and testing          | Nirmiti |               1 | 28th April    | T4         | Pending     |
| T6      | Documentation writing                           | Ananya  |               1 | 28th April    | T1         | In Progress |
| T7      | PPT preparation and design                      | Ishaan  |               1 | 28th April    | T1         | Pending     |
| T8      | Final testing and debugging                     | Team    |               1 | 28th April    | T4, T5     | Pending     |

## 12.3 Responsibility Split

| Area                 | Main Owner        | Support Owner         |
| -------------------- | ----------        | -------------         |
| Concept              | `[Nirmiti]`       | `[Ananya, Khushi]`    |
| Electronics          | `[Khushi]`        | `[Nirmiti,Ananya]`    |
| Coding               | `[Nirmiti]`       | `[Khushi,Ananya]`     |
| Mechanical build     | `[Nirmiti,Khushi]`| `[Ananya]`            |
| Testing              | `[Nirmiti,Khushi]`| `[Ananya]`            |
| Documentation        | `[Ananya]`        | `[Nirmiti,Khushi]`    |

---

# 13. 2 hour Milestones

## 13.1 8-hour Plan

### Bi Hour 1 — Plan and De-risk

Expected outcomes:

- [x] Idea finalized
- [x] Core interaction decided
- [x] Sketches made
- [x] BOM completed
- [ ] Purchase needs identified
- [ ] Key uncertainty identified
- [ ] Basic feasibility tested

### Bi Hour 2 — Build Subsystems

Expected outcomes:

- [x] Electronics tests completed
- [x] CAD / structure planning completed
- [ ] App UI started if needed
- [x] Mechanical concept tested
- [x] Main subsystems partially working

### Bi Hour 3 — Integrate

Expected outcomes:

- [ ] Physical body built
- [x] Electronics integrated
- [x] Code connected to hardware
- [ ] App connected if required
- [ ] First playable version exists

### Bi Hour 4 — Refine and Finish

Expected outcomes:

- [x] Technical bugs reduced
- [x] Playtesting completed
- [x] Improvements made
- [x] Documentation completed
- [x] Final build ready

## 13.2  Update Log
| Week   | Planned Goal                                                             | What Actually Happened                                                                | What Changed                                                                                         | Next Steps                                                   |
| ------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| Week 1 | Finalize project idea, select components, and define game rules          | We finalized the Real-Time Morse Code Battle concept and listed required components | Initial idea was simplified from 4 player system to 2-team format for easy implementation | Start circuit design and begin basic coding setup            |
| Week 2 | Complete hardware connections and basic wiring                           | Touch sensors, LEDs, and buzzer connections were successfully tested on breadboard    | Some output structure changed (separate LEDs for teams simplified for stability)                     | Begin full Morse code encoding and decoding logic            |
| Week 3 | Develop and test main code (touch input + Morse output + Serial Monitor) | Core logic for dot/dash detection and playback was implemented and tested             | Timing thresholds were adjusted for more accurate touch detection                                    | Integrate full game flow and fix bugs                        |
| Week 4 | Final integration, testing, and presentation preparation                 | System was successfully integrated with working gameplay and Serial Monitor output    | Minor debugging done in input reading and output timing                                              | Final testing, documentation completion, and PPT preparation |

---

# 14. Risks and Unknowns

## 14.1 Risk Register


| Risk                                                              | Type       | Likelihood | Impact | Mitigation Plan                                                                    | Owner   |
| ----------------------------------------------------------------- | ---------- | ---------- | ------ | ---------------------------------------------------------------------------------- | ------- |
| Touch sensor gives false triggers or noisy readings               | Technical  | Medium     | High   | Add software debouncing, adjust delay timing, test multiple touch thresholds       | Khushi  |
| Morse code timing (dot/dash) misinterpretation due to human delay | Technical  | High       | High   | Calibrate time threshold (SHORT_TOUCH), practice testing, allow tolerance in logic | Nirmiti |
| Serial Monitor input delay or missed input                        | Technical  | Medium     | Medium | Ensure proper `Serial.available()` checks and delay handling in code               | Nirmiti |
| Wrong wiring or loose connections on breadboard                   | Hardware   | Medium     | High   | Double-check connections before power ON, use proper labeling of pins              | Khushi  |
| Power fluctuation causing reset or unstable output                | Electrical | Low        | High   | Use stable USB power supply and common ground for all components                   | Khushi  |
| Game confusion due to fast Morse transmission                     | Human      | Medium     | Medium | Add clear LED + buzzer playback and allow repetition during demo                   | Team    |

## 14.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

**Response:**  
The biggest uncertainty in our project right now is how accurately the touch sensor will detect dots and dashes in real time, because different players may press the sensor with different speeds.

---

## 15.1 Technical Testing Plan

| What Needs Testing                      | How You Will Test It                                                | Success Condition                                         |
| --------------------------------------- | ------------------------------------------------------------------- | --------------------------------------------------------- |
| Touch sensor input (dot/dash detection) | Test multiple short and long touches from different users           | Correctly distinguishes dot (.) and dash (_) consistently |
| Morse code output (LED + buzzer)        | Run sample words and observe LED blinking and buzzer sound patterns | Output matches correct Morse code pattern for each letter |
| Game flow (word display and hiding)     | Observe Serial Monitor during gameplay                              | Word appears for few seconds and disappears properly      |
| Answer input via Serial Monitor         | Enter test answers manually                                         | System correctly reads and processes input without delay  |
| Result display (win/lose)               | Test correct and incorrect answers for both teams                   | Green LED for correct, red LED for wrong works properly   |
| Full game round execution               | Run complete game cycle from start to end                           | One full round completes without errors or crashes        |
                            |
                       |
## 15.2 Testing and Debugging Log

| Date       | Problem Found                                               | Type      | What You Tried                                                      | Result                                            | Next Action                                      |
| ---------- | ----------------------------------------------------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------ |
| 28th April | Touch sensor sometimes not detecting proper dot/dash timing | Technical | Adjusted SHORT_TOUCH threshold and tested multiple press durations  | Improved accuracy but still slightly inconsistent | Fine-tune timing values and test with more users |
| 28th April | Morse output (LED + buzzer) was not clearly distinguishable | Technical | Increased delay between dot and dash signals                        | Signals became clearer and easier to understand   | Optimize timing for faster gameplay              |
| 28th April | Serial Monitor input delay during answer submission         | Software  | Improved Serial.available() handling and reduced unnecessary delays | Input became smoother                             | Further optimize input timeout handling          |
| 28th April | Wrong answer sometimes marked due to extra spaces           | Software  | Used `.trim()` and `.toUpperCase()` for input cleanup               | Accuracy improved                                 | Final validation testing                         |
| 28th April | Full game flow interruption during continuous loop testing  | System    | Added proper round structure and controlled loop execution          | Game runs smoothly for one full round             | Test multi-round version (optional upgrade)      |


## 15.3 Playtesting Notes

| Tester   | What They Did                                           | What Confused Them                                       | What They Enjoyed                                 | What You Will Change                                           |
| -------- | ------------------------------------------------------- | -------------------------------------------------------- | ------------------------------------------------- | -------------------------------------------------------------- |
| Player 1 | Tried encoding words into Morse code using touch sensor | Sometimes confused between short and long touch timing   | Enjoyed the challenge of converting words quickly | Improve timing sensitivity and give clearer practice round     |
| Player 2 | Observed LED and buzzer signals to decode Morse code    | Found fast signals slightly difficult to follow at first | Liked the real-time sound + light interaction     | Add slightly longer gaps between letters for clarity           |
| Player 3 | Entered guessed words using Serial Monitor              | Occasionally forgot exact spelling of word               | Enjoyed guessing under time pressure              | Allow optional hint or replay of Morse sequence once per round |



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
## 16.1 Fabrication Process

The fabrication process involved designing, assembling, wiring, and testing the full Morse Code Battle System as a working physical prototype.

**Design:**
First, the overall layout of the project was planned on paper, deciding where the touch sensors, LEDs, buzzer, and controller board would be placed for both teams. This helped in organizing the game setup into two clear player sections.

**Cutting / Base Setup:**
A simple base structure (cardboard/board) was prepared and cut to size to hold all components neatly. Separate areas were marked for Team A and Team B to avoid confusion during gameplay.

**Assembly:**
All electronic components like the Shrike Lite, touch sensors, LEDs, and buzzer were placed on the base structure. Components were positioned in a way that both teams could easily interact with their inputs and outputs.

**Fastening:**
Components were fixed using tape, glue, and mounting supports. The breadboard was kept stable to prevent loose connections during testing and gameplay.

**Wiring:**
Jumper wires were used to connect touch sensors, LEDs, and buzzer to the controller board. Care was taken to ensure proper pin mapping and common ground connection for stable operation.

**Finishing:**
After wiring, the setup was cleaned and organized to avoid loose wires. LEDs and sensors were labeled for easier understanding during demonstration.

**Revisions:**
During testing, minor changes were made such as adjusting touch sensor sensitivity, correcting LED/buzzer timing, and improving wire connections for better stability and accuracy during gameplay.

## 16.2 Build Photos

Add photos throughout the project.

Suggested images:

- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.
-
<img width="867" height="1156" alt="images" src="images/mkb4.jpeg" />
<img width="867" height="1156" alt="images" src="images/mkb3.jpeg" />
<img width="867" height="1156" alt="images" src="images/mkb11.jpeg" />
<img width="867" height="1156" alt="images" src="images/mkb10.jpeg" />
<img width="867" height="1156" alt="images" src="images/mkb12.jpeg" />

# 17. Final Outcome

## 17.1 Final Description

Describe the final version of your project.

**Response:**  
The final version of our project is a **Real-Time Morse Code Battle System** where two teams compete by encoding and decoding words using Morse code. Player 1 sees a secret word on the Serial Monitor and sends it using a touch sensor as dots and dashes, which are displayed through a buzzer and LED. Player 2 decodes the signal and guesses the word. The system checks the answer and shows results using green (correct) and red (wrong) LEDs, making it a complete interactive hardware-based game.


## 17.2 What Works Well
Touch sensor works well



## 17.3 What Still Needs Improvement
wiring needs improvement


## 17.4 What Changed From the Original Plan

How did the project change from the initial idea?

**Response:**  
Initially we decided 4 player game then we shifted to 2 player , we decided to mark the winner on the basis of quickest answer, but now the winner will be the one with correct answer

---

# 18. Reflection

## 18.1 Team Reflection

What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  
Our team worked on their assign task very well , managed the failures quickly .We got slowed down mainly during debugging, especially with touch sensor timing and getting correct dot/dash detection. Sometimes wiring mistakes and unexpected output issues also took extra time to fix. Most tasks were completed on schedule, but a few parts took longer during integration, so we had to adjust and support each other to finish the project on time.

## 18.2 Technical Reflection

What did you learn about:

- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  
**Electronics:**
We learned how basic components like touch sensors, LEDs, and buzzers actually behave in real circuits. Small issues like loose connections, wrong pin mapping, or unstable power can completely affect the output, so proper wiring and grounding is very important.

**Coding:**
We understood how timing-based coding works using `millis()` to detect dot and dash inputs. We also learned how Serial Monitor communication, string handling, and condition checking are used to build a complete game flow.

**Mechanisms:**
We learned how simple input actions (short and long touch) can be converted into meaningful signals (Morse code). It showed us how physical actions can be translated into digital logic.

**Fabrication:**
We learned how important planning and layout are before building. Even a simple structure needs proper placement of components so that the system is easy to use and looks organized during demonstration.

**Integration:**
We understood how different parts of a system (input, processing, and output) must work together smoothly. Even if individual parts work separately, the real challenge is making the full system function as one complete working project without errors.


## 18.3 Design Reflection

What did you learn about:

- designing ,
- delight,
- clarity,
- physical interaction,
- understanding,
- iteration?

**Response:**  

**Designing:**
We learned that good design is not just about adding components, but about planning the whole system in a simple and structured way. Dividing the setup into two teams and clearly separating input and output made the project easier to build and use.

**Delight:**
We understood that small elements like buzzer sounds, LED blinking, and real-time competition make the project more fun and engaging. These simple effects increase user interest and make the experience feel like a real game.

**Clarity:**
We realized that clarity is very important in both hardware and code. Clear wiring, labeled components, and simple Serial Monitor messages helped avoid confusion during gameplay.

**Physical Interaction:**
We learned how important hands-on interaction is in embedded systems. Using touch sensors instead of buttons made the game more natural and engaging, as players directly control the system using physical actions.

**Understanding:**
We understood how each part of the system (input, processing, output) connects together. Seeing the full flow from touch input to Morse output helped us understand how embedded systems actually work in real time.

**Iteration:**
We learned that the first version is never perfect. We had to repeatedly test, fix timing issues, adjust sensor sensitivity, and improve output delays to make the system more accurate and playable.

## 18.4 If You Had One More hour

What would you improve next?

**Response:**  
We would add more challanges and more levels to our game , and also add voice modulation to make it more interesting.

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
<img width="867" height="1156" alt="images" src="images/mkb13.mp4" />


---


---


