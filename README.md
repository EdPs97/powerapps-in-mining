# Smart Worker – Power Apps Suite for Operational Data Capture

Smart Worker is a suite of low-code applications developed using Microsoft Power Apps within the Microsoft 365 ecosystem. The solution began as an initiative to digitize critical operational data—traditionally captured manually or through spreadsheets—and evolved into a scalable platform designed to strengthen data traceability, reduce human error, and accelerate decision-making in mining operations.

## 1. Fuel Consumption Registration

# Context and Problem

Fuel is one of the hardest consumables to control in open-pit mining operations, especially when equipment lacks reliable onboard gauges. Harsh site conditions caused recurring gauge failures, forcing operators to record fuel usage manually. This led to:

*Loss of traceability
*Frequent transcription errors
*Slow reporting cycles
*Unreliable consumption metrics
*Delays in SAP fuel reservation processes

# Solution Overview

The Fuel Consumption Registration App provides an intuitive interface for fuel operators to record all fill events directly from smartphones or tablets.

Key features include:

*Offline mode for full functionality inside the pit
*Equipment and location selection
*Hourmeter and fuel volume inputs
*Comment fields for operational notes
*Validation rules to avoid erroneous data
*Restricted editing and deletion for governance
*Automatic synchronization with Microsoft 365 services
*Integration and Analytics

Data collected is immediately available across:

*Power BI
*Excel
*SAP fuel reservation workflows

A companion Power BI dashboard visualizes:

*Fuel consumption (L/H)
*Variances against budget
*Operational trends and anomalies
*Impact
*Improved traceability
*Fewer manual errors
*Faster SAP processes
*Better data-driven decision-making
*Low-cost implementation using existing infrastructure

## 2. Processing Plant Reagents Registration

# Context

Following the success of the fuel application, the system was adapted to capture reagent consumption in the processing plant. Previously, operators recorded usage manually for reagents such as lime, cyanide, sodium hydrosulfide, and others—leading to inconsistencies and time-consuming reporting.

# Solution Overview

The Processing Plant Reagents App replicates the fuel app’s design while tailoring it to plant workflows.The key features and impact are the same as the Fuel Consumption module. 


## 3. Cyanide Flow Rate Registration for Leach Pad Optimization

# Context and Value Proposition

The leach pad represents a critical step in gold recovery, where cyanide solution percolates through stacked ore lifts and cells. Operators must decide how to divert solution streams (PLS, ILS, BLS) to maximize ounces sent to the processing plant. Traditionally, decisions were heavily based on grade alone, which risks overlooking additional optimization opportunities when actual ounces contributed per cell are not considered.

# Solution Overview

The Cyanide Flow Rate Registration App enables operators to digitally capture real-time solution flow rates from each leach pad cell. This structured dataset allows optimization models to determine the best derivation paths (PLS/ILS/BLS) based on ounces per cell, not only grades.

# Key features include:

*Full offline functionality, essential due to the leach pad’s distance and minimal connectivity
*Recording of flow rates, cell ID, lift, solution type, and relevant comments
*Dynamic input validation to detect inconsistent or unrealistic flow readings
*Automatic sync to Microsoft 365 once a connection is available
*Compatibility with optimization engines (e.g., Excel Solver, Python-based maximize functions, Power BI calculated models)

# Operational Impact

With accurate flow rate data:

*Optimization models can maximize ounces routed to the processing plant
*Operators can make decisions based on actual contribution rather than theoretical grade values
*Strategy adjustments become faster and better supported by field data
*Leach pad reporting gains consistency and traceability

# Why Offline Mode is Critical

The leach pad spans a large, remote area without internet coverage. Power Apps’ offline mode enables:

*Continuous data capture during leach pad rounds
*Zero dependency on network availability
*Automatic synchronization once operators return to connected zones
