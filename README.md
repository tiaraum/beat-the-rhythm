
# Beat the Rhythm

**GAM100 · SIT–DigiPen Institute of Technology · 2025**

![Language](https://img.shields.io/badge/Language-C-blue)
![Framework](https://img.shields.io/badge/Framework-CProcessing-orange)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Project](https://img.shields.io/badge/Project-GAM100-purple)

## Project Overview

Beat the Rhythm is a four-lane rhythm game developed by Team CookiesEndCream, a four-member student team at SIT–DigiPen.

Players hit falling notes in time with music, build scoring streaks and receive real-time visual feedback based on their performance.

The project explores real-time gameplay programming, input handling, user interface development and collaborative software development.

## My Role

**Level Designer & Gameplay Programmer**

I contributed to gameplay feedback, user interface behaviour, screen transitions and executable build maintenance.

### Technical Contributions

- Implemented lane-specific visual feedback for successful note hits.
- Implemented Escape-key navigation to allow players to skip the credits screen.
- Calculated dynamic scrolling boundaries using content and window dimensions.
- Reworked credits completion logic by removing timer-based redirection.
- Refined credits-to-menu transitions, reducing update iterations from **120 to 40**.
- Maintained executable builds and improved gameplay code documentation.

## Technical Challenges & Solutions

### 1. Credits Navigation and Scrolling

**Problem:** The credits screen relied on timer-based redirection, with limited control over scrolling and navigation.

**Approach:** Implemented keyboard-triggered navigation and calculated the maximum scrolling distance based on content height and window dimensions.

**Result:** Added direct menu navigation and prevented scrolling beyond the calculated content boundary.

### 2. Screen Transition Logic

**Problem:** The credits-to-menu transition used a fixed loop of 120 update iterations.

**Approach:** Refined the transition logic and reduced the iteration count.

**Result:** Reduced transition update iterations from 120 to 40, a **66.7% reduction in iteration count**.

### 3. Gameplay Visual Feedback

**Problem:** Players needed clearer visual feedback when interacting with notes.

**Approach:** Integrated lane-specific glow activation into the existing note hit detection logic.

**Result:** Successful note hits activate visual feedback in the corresponding gameplay lane.

## Gameplay Screenshots

### Title Screen

<img width="800" alt="Beat the Rhythm title screen" src="https://github.com/user-attachments/assets/fd4911fc-70b2-44cc-8708-0c3e38845b2a" />

### Main Menu

<img width="800" alt="Beat the Rhythm main menu" src="https://github.com/user-attachments/assets/02c413b8-799b-4261-946c-720e92643462" />

### Rhythm Gameplay

<img width="800" alt="Four-lane rhythm gameplay and scoring interface" src="https://github.com/user-attachments/assets/762fe823-9505-4b44-ae04-a57afe73555d" />

### Team Credits

<img width="800" alt="Team CookiesEndCream credits and individual roles" src="https://github.com/user-attachments/assets/1b4ce951-17c7-48fe-aed7-e6de78b9e4d5" />

## Technologies Used

| Technology | Purpose |
| --- | --- |
| C | Gameplay and application programming |
| CProcessing | Rendering, input handling and game development |
| Visual Studio | Development and debugging |
| Git | Version control and team collaboration |
| Windows | Target platform |

## Key Learning Outcomes

Through this project, I developed practical experience in:

- Real-time gameplay programming
- Event-driven input handling
- Game state management
- UI boundary calculations
- Visual gameplay feedback
- Collaborative development and version control

This project established my foundation in interactive application development and working within a shared codebase.

## Source Code & Availability

Beat the Rhythm was developed collaboratively as part
of the GAM100 studio module at SIT–DigiPen.

The original source code is maintained in a private
academic team repository and is not publicly distributed
due to project ownership and access restrictions.

This showcase documents my individual technical
contributions, implementation decisions and project
outcomes.

*Academic Project · GAM100 · 2025*
