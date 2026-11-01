# HW-01: Finite State Machine (FSM)

## Traffic Light FSM Model

In this exercise, we model a simple finite state machine (FSM) for a traffic light controller.

### States
- Green
- Yellow
- Red

### FSM Diagram (Mermaid)

```mermaid
stateDiagram-v2
    [*] --> Red
    Red --> Green : timer
    Green --> Yellow : timer
    Yellow --> Red : timer
