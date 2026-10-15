# Cybersecurity Training Tool 

Interactive cybersecurity training tool developed with Unity to provide students with a controlled and gamified environment for learning fundamental cybersecurity concepts.

## Overview

The **Cybersecurity Training Tool** is an educational application developed to help students learn cybersecurity through practical interaction with simulated environments.

Instead of focusing exclusively on theoretical concepts, the application allows students to interact with a simulated terminal, complete cybersecurity exercises, and progress through different learning modules.

The project was developed as an academic initiative at **Universidad Autónoma de Bucaramanga (UNAB)**.

## Objectives

The main objectives of the project are:

- Provide a safe and controlled environment for cybersecurity training.
- Introduce students to fundamental Linux and cybersecurity concepts.
- Allow students to practice through interactive exercises.
- Encourage problem-solving and practical learning.
- Use gamification to make cybersecurity education more engaging.
- Track exercise completion and module progression.

##  Main Features

### Simulated Terminal

The application includes a simulated terminal that allows students to interact with the environment through command-line instructions.

The terminal system was developed to:

- Process user commands.
- Simulate command-line interactions.
- Execute actions within the learning environment.
- Connect terminal actions with specific cybersecurity exercises.
- Trigger changes in exercise states based on student actions.

### Interactive Exercises

Each learning module contains practical exercises that require students to perform specific actions.

The application evaluates the student's actions and determines whether the requirements of each exercise have been fulfilled.

This allows exercises to respond dynamically to the student's progress.

### Exercise Flags and State Management

The project uses flags to manage the state of individual exercises.

These flags allow the application to determine whether specific objectives have been completed and whether the student can continue progressing through the module.

A simplified exercise flow is:

Student action  
↓  
Action validation  
↓  
Exercise condition fulfilled  
↓  
Flag updated  
↓  
Exercise completed  
↓  
Next objective unlocked

This system connects the student's interaction with the simulated environment to the progression of the learning experience.

## Learning Modules

### Module 1 — Linux Fundamentals

The first module introduces students to fundamental Linux command-line concepts.

Topics include:

- Terminal navigation.
- File and directory exploration.
- Basic Linux commands.
- File interaction.
- Command-line problem solving.

The objective is to provide students with the command-line knowledge required for subsequent cybersecurity exercises.

### Module 2 — Network Reconnaissance

The second module introduces fundamental network reconnaissance concepts.

Topics include:

- Network discovery.
- Port identification.
- Service enumeration.
- Basic reconnaissance workflows.
- Interpreting scan results.

The module introduces concepts commonly encountered during the reconnaissance phase of cybersecurity assessments.

## Technical Architecture

The application is built using Unity and custom C# scripts.

The main systems can be represented as:

Cybersecurity Training Tool  
│  
├── Simulated Terminal  
│   └── Command Processing  
│  
├── Module System  
│   ├── Module 1  
│   └── Module 2  
│  
├── Exercise System  
│   ├── Exercise Logic  
│   ├── Validation  
│   └── Exercise Flags  
│  
└── Progression System  
    └── Module and Exercise State

The different systems interact through the state of the exercises and the actions performed by the student.

## Technologies

- **Unity** — Simulation and application framework.
- **C#** — Application and simulation logic.
- **Git** — Version control.
- **GitHub** — Source code management and collaboration.

## Cybersecurity Concepts

The project introduces students to several fundamental cybersecurity concepts, including:

- Linux command-line usage.
- File system exploration.
- Network reconnaissance.
- Port scanning.
- Service enumeration.
- Basic penetration testing concepts.
- Security-oriented problem solving.

All activities are performed within controlled or simulated environments.

## Educational Purpose

The project was designed as a cybersecurity education tool.

The objective is to allow students to learn through practical interaction and experimentation while maintaining a controlled environment.

The gamified approach combines cybersecurity exercises with interactive challenges and progression mechanics to encourage active learning.

## Disclaimer

This project is intended exclusively for educational and authorized cybersecurity training purposes.

All cybersecurity exercises are designed to operate within controlled or simulated environments. The techniques and tools presented should only be used against systems for which the user has explicit authorization.

## Authors

**Lyanna17** — Developer  
**Latorre655** — Developer

Developed as part of an academic cybersecurity education project at **Universidad Autónoma de Bucaramanga (UNAB)**.
