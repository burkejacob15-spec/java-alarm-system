# Multithreaded Alarm Clock

A Java-based alarm clock application that uses multithreading to manage countdown timing and audio playback concurrently.

## Features
- Countdown timer with precise timing
- Audio alert triggered when the countdown reaches zero
- Multithreaded design to separate timing and sound playback

## Technologies Used
- Java
- IntelliJ IDEA
- Java Threads

## How It Works
The application creates separate threads for:
- Managing the countdown timer
- Playing the alarm sound

This ensures the timer remains accurate while the audio plays without blocking the main program.

## How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/multithreaded-alarm-clock.git
