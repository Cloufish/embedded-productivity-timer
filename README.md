# Embedded Productivity Timer
- **Not a Pomodoro**
	- Instead, it uses "Third Time"/"Rational Breaks". See [Third Time: a better way to work ~ bfinn](https://www.lesswrong.com/posts/RWu8eZqbwgB9zaerh/third-time-a-better-way-to-work)
## Concept of Third Time
1. **Work for as long or as short as you like** until you want a break
2. Break time is calculated to one-third (or any other *chosen* fraction) of work

## Other twists
- If the user doesn't use whole break time, then user can resume work earlier and the remaining break time gets postponed to the next Break
	- In the same way - If the user doesn't resume work after the break then additional "break debt" is added

## settings.h
- User can modify some variables
	- FRACTION="1/3 | 1/4 | 1/5 | 1/6 |"
	- VIBRATION-MODE="1|0"
	- PRECISE-CLOCK="1|0"

## The required gear to build this
- Display (*e-ink recommended* for low power-usage)
- Microcontroller
	- TODO: Create tests for various architectures in a virtualized and CI/CD manner
