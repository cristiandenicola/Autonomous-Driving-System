
NuSMV Project: Symbolic Model Verification for Autonomous Driving Systems

Project Description

This project leverages NuSMV, a symbolic model checker, for the formal verification of finite and infinite systems. Specifically, we focus on the simulation and verification of an autonomous driving system. NuSMV allows us to verify that a model satisfies specific properties expressed in temporal logics, ensuring the safety and reliability of the autonomous driving system.

Project Contents

The project includes the following files:

Deterministic_model.smv: This file contains a deterministic model of the autonomous driving system. It is used to demonstrate how NuSMV can verify properties in a deterministic environment.
non-deterministic_model.smv: This file contains a non-deterministic model of the autonomous driving system. It is used to demonstrate how NuSMV can handle uncertainties and variable behaviors within the system.
Requirements

NuSMV: Ensure that NuSMV is installed on your machine. You can download it from the official NuSMV website.

NuSMV Features

NuSMV supports the verification of properties expressed in:

LTL (Linear Temporal Logic)
CTL (Computation Tree Logic)
The main features include support for deterministic and non-deterministic models and the ability to handle large models using symbolic representation techniques such as BDD (Binary Decision Diagrams).

