# HighSchoolCourses
**Digital Logic Fundamentals - Introduction To Logic & Logic Systems**

This is a set of High School Course Modules for teaching Digital Logic, and Introduction to Chip making and the process to go from Logic, to RTL to GDS-II with the OpenROAD and OpenLANE process.

**Unit Topics, Modules & Lessons**
The following modules will have a set of Lessons.  Each Lesson will have 📰 Lecture Slides, will be acompanied by a 🖼️ Tutorial, 🛠️ LAB Activity, and links to ✨ Resources.  ALso each Lesson, will have 📖 📝 Reading/Writing, 🚀 Quiz, 🔎 Review and ✔️ Mastery Check assignments. The Lecture Slides and Tutorials will be linked to Google slides and docs, where as the assignments (📖 📝 Reading/Writing, 🚀 Quiz, 🔎 Review and ✔️ Mastery Check assignments) will be hosted in a Canvas LMS class Archive.

Key: 📰 Slides / Audio 🎧 / 📽️▶️ Video/YouTube / 🎧▶️📽️ Audio/Video / ✨ Resources / 🖼️ Tutorial / 📖 Reading Activity / 📝 Writing Activity / 📖 📝 Reading/Writing / 📟 Coding / 🛠️ LAB Activity / 🚀 Quiz /  🔎 Review /  ✔️ Mastery Check / ✍️ Sign Up /🍕 Extra Credit / 🕸️ Web Links / 👩🏽‍🎓🧑🏽‍🎓🧑🏿‍🎓👩‍🏫 Class / 🏵️📜📃 Certificate

**Source Links and Intermediate Builds:** The current location of most of the source files are on [Jim The STEAM Clowns Google Mechatronics - Digital Logic Site](https://sites.google.com/view/steam-clown-mechatronics/units/unit-6-digital-logic-fundamentals?authuser=0), where there is additional  links to Google Slides, Docs and Canvas LMS class Labs and Assignments.

# Modules #

## ✨ Digital Logic Introduction ##

This is a Module focused on the introduction of Digital Logic Gates and Flip/Flops. It will cover: Digital Logic Introduction, Binary Numbering systems, How Transistors make Gates, Basic logic gates like AND, OR, INV, NAND, NOT, XOR, and XNOR, Combinational Logic circuits, Multiplexers, Decoders and Encoders, Adding and Accumulators, Latches and Flip/Flops, Shifting and Counting

  **Modules deliverables will include:** (about 4 hours of 30 min Lectures & 8+ hours of Lab & Assessment activities)
  - **Google Docs:** Slide Presentation 📰, Lesson Tutorial 🖼️, Resources ✨
  - **Canvas LMS Module:** LAB Activities 🛠️ and Formative & Summative Assessments 🚀

  **Topics:**
  - Digital Logic Introduction
  - Transistor & Semiconductor Introduction
  - Logic Gates Introduction
  - Digital Logic Gates & Flip/Flops - AND'ing and OR'ing the World
  - Multiplexer, Decoders, Encoders, Adding, Accumulating, & Counting

## ✨ Digital Logic - 555 Timer (Kinda Digital, Kinda Analog)
This is a Module about focused on 555 timers and how they generate Pulse, Astable, Monostable, Bistable (flip-flop) and Schmitt trigger (inverter) mode.

  **Modules deliverables will include:** (about 2 hours of 30 min Lectures & 4+ hours of Lab & Assessment activities)
  - **Google Docs:** Slide Presentation 📰, Lesson Tutorial 🖼️, Resources ✨
  - **Canvas LMS Module:** LAB Activities 🛠️ and Formative & Summative Assessments 🚀

  **Topics:**
  - 555 Introduction and Timer Labs

## ✨ Digital Logic - Meet A Few More Chips - Counting, Shifting, and Math
This is a Module about focused on The different ways to count, and shift.  It will also focus on more complex chips like an ALU doing math. 

  **Modules deliverables will include:** (about 2 hours of 30 min Lectures & 4+ hours of Lab & Assessment activities)
  - **Google Docs:** Slide Presentation 📰, Lesson Tutorial 🖼️, Resources ✨
  - **Canvas LMS Module:** LAB Activities 🛠️ and Formative & Summative Assessments 🚀

  **Topics:**
- Counters, Shift, and ALU

## ✨ Digital Logic - VHDL/Verilog Introduction: 
This is a Module focused on the relationship between  schematic and text based description.  it will explore VHDL and Verilog implementations ot some of the logic studied in previous modules. 

  **Modules deliverables will include:** (about 2 hours of 30 min Lectures & 4+ hours of Lab & Assessment activities)
  - **Google Docs:** Slide Presentation 📰, Lesson Tutorial 🖼️, Resources ✨
  - **Canvas LMS Module:** LAB Activities 🛠️ and Formative & Summative Assessments 🚀

  **Topics:**
  - Digital Logic - VHDL/Verilog Introduction
  - VHDL/Verilog  Build some of the same logic  Schematic circuits using VHDL/Verilog

## ✨ Digital Logic - RTL-GDSII Introduction: 
This Module will cover the generation of RTL and the flow to generate GDSII

  **Modules deliverables will include:** (about 2 hours of 30 min Lectures & 4+ hours of Lab & Assessment activities)
  - **Google Docs:** Slide Presentation 📰, Lesson Tutorial 🖼️, Resources ✨
  - **Canvas LMS Module:** LAB Activities 🛠️ and Formative & Summative Assessments 🚀

  **Topics:**
  - RTL-GDSII flow Intro
  - RTL-GDSII simulation and verification flow

## ✨ Digital Logic - Introduction to the OpenROAD Project: 
This Module will cover the OpenROAD flows and Scripts

**Notes:** This is a comment from @dralabeing that I need to follow up on, where to add some more timing analysis: **Timing analysis is generally done at different stages- first time pre-layout after CTS, post-global-routing, after detailed routing and chip finishing. So this topic can be introduce sooner.**

  **Modules deliverables will include:** (about 4 hours of 30 min Lectures & 8+ hours of Lab & Assessment activities)
  - **Google Docs:** Slide Presentation 📰, Lesson Tutorial 🖼️, Resources ✨
  - **Canvas LMS Module:** LAB Activities 🛠️ and Formative & Summative Assessments 🚀

  **Topics:**
  - The-OpenROAD-Project Introduction
   - GitHub - https://github.com/The-OpenROAD-Project
  - RTL-GDSII simulation and verification flow
   - Building blocks of open-source design (this should introduce .libs. .v source and public pdks briefly if not covered in the previous module covering RTL-GDSII)
   - Running the OpenROAD flow from RTL-GDSII (key stages and intermediate results briefly)
   - Key advantages and features of OpenROAD flow
   - OpenROAD GUI Introduction
   - Validating the design for Tapeout - My First Chip Labs - 4-5 labs that incorporate the following steps, to complete a design ready for submission
    - Lab #1 - Initial tools and flow for placement setup
     - Initialize floorplan - define the chip size and cell rows
     - Place pins (for designs without pads )
    - Lab #2 - Using Macros and other Structures
     - Place macro cells (RAMs, embedded macros)
     - Insert substrate tap cells
     - Insert power distribution network
     - Macro Placement of macro cells
     - Global placement of standard cells
    - Lab #3 - Checking and Adjusting Timing and Placement
     - Repair max slew, max capacitance, and max fanout violations and long wires
     - Clock tree synthesis
     - Optimize setup/hold timing
    - Lab #4 - Finishing Touches
     - Insert fill cells
     - Global routing (route guides for detailed routing)
     - Antenna repair
     - Detailed routing
     - Parasitic extraction
    - Lab #5 - Final Analysis
     - Static timing analysis
  - Contributing to the open-source design community using the OpenROAD ecosystem
  - Links that will help us build this project:
   - https://github.com/The-OpenROAD-Project/HighSchoolCourses

## ✨ Digital Logic - Tiny TapeoutLogic Gates to Chip Layout: 
This is a Module about learning how to make a silicon chip and the process that goes into making it. I'll be posting my lessons, presentations, labs and other resources.  This is primarily a Resource Page, so that means it's a Mish-Mash of Silicon Wafer process content.

  **Modules deliverables will include:** (about 4 hours of 30 min Lectures & 8+ hours of Lab & Assessment activities)
  - **Google Docs:** Slide Presentation 📰, Lesson Tutorial 🖼️, Resources ✨
  - **Canvas LMS Module:** LAB Activities 🛠️ and Formative & Summative Assessments 🚀

  **Topics:**
  - Tools & Wokwi
  - Student project design
  - Git Flow
  - Submit design to verification flows
  - Final design submission
  - Silicon Prototype Verification
