# IEEE Student Activity: Week 28

## Content: Timer/Counter Peripheral

In this week's activity, we delve into the Timer/Counter peripheral, a crucial component in microcontroller programming. Understanding the Timer peripheral is fundamental for time-sensitive operations, scheduling tasks, and generating precise timing intervals within embedded systems.

### Timer Definitions

- **Tick Time**: The duration between consecutive timer interrupts or ticks.
- **Overflow Time**: The time taken for the timer/counter to overflow, i.e., reach its maximum value and restart from zero.
- **Preload Value**: The initial value loaded into the timer/counter register.

### Timer Modes

- **Overflow Mode**: The timer/counter counts up to its maximum value, then overflows back to zero, generating an overflow interrupt.

### Timer Overflow Mode at ATMega32

We explore how the Timer Overflow Mode operates specifically on the ATMega32 microcontroller.

### CTC Mode and Its Calculations

CTC (Clear Timer on Compare Match) mode is a timer operation mode where the timer is cleared to zero when its value matches a predefined compare value. We will discuss the calculations involved in setting up and utilizing this mode effectively.

### Timer CTC Mode at ATMega32

We will specifically look into how to configure and utilize the Timer in CTC Mode on the ATMega32 microcontroller.

## Resources

- [YouTube Video 1](https://youtu.be/Sr7aYoWgMbg?si=ZYQUadvyhJLXv5EA)
- [YouTube Video 2](https://youtu.be/lgFpJ1njeUI?si=J2GAPR_cfvZu7ZjG)

## Task

1. Watch the provided videos to grasp the concepts and understand the implementation details.
2. Implement the necessary drivers for Timer/Counter peripheral operations on the ATMega32 microcontroller.
