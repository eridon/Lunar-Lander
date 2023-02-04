# Lunar Lander Project

This repository contains the code for a lunar lander game where the player controls the descent of a Lunar Lander spacecraft onto the surface of the moon. This program communicates with the server via UDP and implements an application layer protocol. The purpose of communication with the server is to control the flight of the lander. The program also communicates with a dashboard display to show the current status of the lander and logs data to a file.

# Features

- Inputs from the keyboard to control the throttle and the strength of the rotational thrust of the lander.
- Communications with the Lander server using UDP datagrams.
- Communications with the dashboard using a custom protocol.
- Control logic to generate control signals and outputs.
- Data logging to a CSV file.
- Multithreaded implementation using at least 4 POSIX threads for user input, server communications, dashboard communications, and data logging.

# Requirements

- Clone this repository and follow the instructions to build the program.
- Skeleton codes are provided and can be compiled using make all.
- The controller can be executed using the command: ./controller 65200 65250.

# Usage

1. Start the LunarLander server using java -jar LunarLander.jar.
2. Start the LanderDash dashboard using java -jar LanderDash.jar.
3. Start the controller using ./controller 65200 65250.
4. Use the keyboard to control the descent of the lander.
5. Observe the status of the lander on the dashboard and in the data logging file.

# Background

- This game was developed as a university project to explore the capabilities of a networked application program.
- The code used in this repository was adapted from the example provided by the following repository: https://github.com/weibo053/LunarLander

# Note

Please note that this repository is for educational purposes only and is not intended for commercial use. The code and model provided in this repository are not guaranteed to be error-free and may not reflect best practices for a networked application program. Use at your own risk.
