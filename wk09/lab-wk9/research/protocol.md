# Evaluation Protocol — Week 9 Pilots

**Module**: COMP2850 HCI
**Activity**: Task-based usability pilots
**Date**: 2025-12-05
**Researcher**: Sanaa Ahmed

---

## Purpose

Evaluate task manager usability and accessibility through structured pilots. Data will inform Week 10 redesign and assessment submission.

## Consent script

Thank you for participating in my HCI evaluation. There will be 5 scenarios to work through, and it will take around 15-20 minutes. I'm testing the task management interface, not you -- there are no right or wrong answers. 

I will collect data about the current time, the time you take to complete tasks, where you click, any comments you make, and my observations of your experience. I will not collect any personally identifying information -- you will be under a pseudonym (e.g. P1) rather than your actual name. Any screenshots or notes I take will be removed of personally identifying information. 

This data will be stored locally on a personal, private Github repository (meaning no public access). The only ones who will have access to it are me, you, and the teaching staff marking the project.

You have the right at any point to withdraw consent, request access to the data I have collected, and request its deletion -- just contact me via email at wlxp3010@leeds.ac.uk with your pseudonym.

Do you consent to participate?

---

## Procedure

### Setup (5 minutes)
1. **Assign mode**: Participant 1 → HTMX, Participant 2 → No-JS (alternate)
2. **Disable JS if needed**: Chrome DevTools → Settings → Disable JavaScript
3. **Set session ID**: Open browser DevTools Console, paste:
   ```javascript
   document.cookie = "sid=P1_7a9f; path=/";  // P1 = Participant 1, random suffix

### Orientation
 You'll complete 5 tasks with a task manager. I will time you and take notes. Think aloud, especially if you're struggling with something. If you feel you are unable to complete the task and would like to move on, let me know.

 ### For each task
 1. Read task scenario
 2. Start timer when participant begins
 3. Observe clicks, hesitation, comments. Record any clicks on wrong elements or other navigation mistakes.
 4. Stop timer when participant finishes, gives up, or more than 2 minutes have passed.
 5. Record success of task (1=completed, 0=failed)
 5. "On a scale of 1-5, how confident are you that you completed the task correctly?"

### Final thoughts
Thank you. Do you have any final thoughts?
