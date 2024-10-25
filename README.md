# SearchAndRescue
Project related to the exam of "Formal Methods for Concurrent and Real-Time Systems" at POLIMI (Polytechnic university of Milan)

# Introduction
This project adopts a framework that is currently under research, envisaging civilian survivors (i.e., referred to as zero-responders) helping those in need or asking the first-responders (i.e., professionals such as nurses and firefighters) to intervene. Specifically, when a drone surveying the area detects a potential zero-responder in the vicinity of a person in need, it must decide whether to instruct them to help directly or ask a first-responder to intervene.

# Goal
The aim of the project is to develop UPPAAL formal models of search-and-rescue scenarios (featuring drones, civilians, and first-responders) and provide formal verifications highlighting the most relevant features of each system.

# Project structure
Models "model$" and "model$_SMC" represent the same scenario (taking into account the environment's features), models "model$_DEADLOCK" instead represent a simplified version of it. Models with the same number are related to each other and model the agents in the same way (e.g. the same decision-making policy), the main difference is that SMC models also include stochastic features.

# Final grade
30/30
