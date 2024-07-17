# Multi-threading-computation-system

# Two-Phase Commit Protocol Implementation

## Project Overview

This project implements a fault-tolerant two-phase commit (2PC) protocol in a distributed system. It demonstrates the ability to handle various failure scenarios and showcases skills in distributed systems, fault tolerance, and protocol implementation.

## Key Features

- Fault-tolerant 2PC protocol implementation
- One transaction coordinator (TC) and multiple participants
- Handling of various failure scenarios:
  - Coordinator failure before sending prepare message
  - Participant failure before sending acknowledgment
  - Coordinator failure after commit
  - Participant failure after acknowledgment
- Timeout mechanisms for nodes
- Persistent storage of transaction information

## Technologies Used

- Python
- Distributed systems concepts
- Fault tolerance techniques

## Project Structure

The project consists of the following main components:
- **Transaction Coordinator**
- **Participant Nodes**
- **Logging System**

## Demonstration Scenarios

The implementation includes test cases for various failure scenarios, showcasing the system's robustness:
- Coordinator failure before prepare message
- Participant failure before acknowledgment
- Coordinator failure after commit
- Participant failure after acknowledgment

## Skills Demonstrated

- Distributed systems design and implementation
- Fault tolerance in distributed environments
- Protocol design and implementation
- Python programming
- System logging and recovery mechanisms
