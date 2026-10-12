# Excalibots — Team Ownership

## Purpose

Record who owns each engineering area, with a primary owner and a backup.
Assignments are provisional until confirmed by the full team.

## Ownership Register

| Area | Primary Owner | Backup Owner | Responsibilities |
|---|---|---|---|
| Mechanical Design | Sarah | Sene | Chassis, gripper (110 mm stones), stacking mechanism, CAD, fabrication |
| Electrical & Electronics | Sene | Sarah | Power, wiring, sensors, electrical architecture, e-stop |
| Navigation & Localization | Ali | Bouchra | Nav2 tuning for the 3×2 m table, localization, return-to-throne-room goal |
| Mission State Machine | Ali | Bouchra | Mission FSM, retry logic, stone pick/place and return-home states |
| Computer Vision | Bouchra | Ali | ArUco detection (stone tag 13), stone pose estimation |
| Manipulation Control | Bouchra | Ali | Gripper control, pick/place and stacking sequences |
| System Integration & Testing | Bouchra | Ali | Interface coordination, integration tests, mock matches, homologation prep |

## Project Management Roles

| Role | Owner |
|---|---|
| Presentations | Ali |
| Meeting schedules and work breakdown | Bouchra |
| Documentation | Sarah |
| Meeting minutes | Sene |

## Owner Responsibilities

The owner of an area is responsible for:

- Maintaining the subsystem.
- Coordinating related tasks.
- Keeping the subsystem documented.
- Reporting progress and problems.
- Ensuring that the subsystem is tested.
- Communicating interface changes to other team members.

## Working Rules

- Track tasks and assign responsibility through GitHub Issues.
- Review changes through pull requests where practical.
- Update this register when responsibilities change.
