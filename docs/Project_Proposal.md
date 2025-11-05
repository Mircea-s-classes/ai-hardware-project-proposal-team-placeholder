# University of Virginia
## Department of Electrical and Computer Engineering

**Course:** ECE 4332 / ECE 6332 — AI Hardware Design and Implementation  
**Semester:** Fall 2025  
**Proposal Deadline:** November 5, 2025 — 11:59 PM  
**Submission:** Upload to Canvas (PDF) and to GitHub (`/docs` folder)

---

# AI Hardware Project Proposal Template

## 1. Project Title
Team Placeholder

Ziyu Xuan

Title: Detection and alarming of emergency status

## 2. Platform Selection
Select one platform category and justify your choice.
We should use TinyML, the scenario may contain unwanted data, and processing them locally would

## 3. Problem Definition
The emergency on ground by Monday is an alarming incident, so I thought why don't we use AI to automatically detect and send alarm to the security, in case there's danger for human to properly send alerts? The plan is to identify a specific sound, e.g. gunfire, train the AI with the data, and send them to the system.

## 4. Technical Objectives
1. Detection of emergency status, how likely is it to trigger with a single fire?
2. Determine the signal/noise ratio which will trigger the alarm.
3. Determine the latency of the system.

## 5. Methodology
We would implement a prototype in this project. First we need a microphone to collect ambient sound, then it is input to the hardware and TinyML to determine if there's an emergency, if there is then the alert is uploaded to the connected alarming system and send the alert. We need several datasets from different noises (footsteps, ambient music, chats etc.), ambient music, and different sounds of gunfire (or other sounds that is related to an emergency, for example someone yelling HELP!)
There would certainly be fake alerts in this situation, so we need to filter the sound first. Due to the characteristic of the emergency sound it would likely be very loud compared to the noise, we would do an reduction and then get training.

## 6. Expected Deliverables
Working demo, GitHub repository, documentation, presentation slides, and final report.

## 7. Team Responsibilities
List each member’s main role.

| Name | Role | Responsibilities |
|------|------|------------------|
| Ziyu Xuan | Team Lead | Coordination, documentation |
| [Student B] | Hardware | Setup, integration |
| [Student C] | Software | Model training, inference |
| [Student D] | Evaluation | Testing, benchmarking |

## 8. Timeline and Milestones
Provide expected milestones:

| Week | Milestone | Deliverable |
|------|------------|-------------|
| 2 | Proposal | PDF + GitHub submission |
| 4 | Midterm presentation | Slides, preliminary results, example code |
| 6 | Integration & testing | Working prototype |
| Dec. 18 | Final presentation | Report, demo, GitHub archive |

## 9. Resources Required
We would probably need raspberry pi and a microphone for this project.

## 10. References
Not yet.
