# Hammad_23122005_Lab1_AI_6A

## Intelligent Agents Assignment

### Smart Irrigation Agent

**Student Name:** Hammad
**Roll Number:** 23122005  **Section:** 6A  **Semester:** 6

---

## Project Overview

This repository contains my submission for the Intelligent Agents assignment, focused on
the design and evaluation of a **Smart Irrigation Agent**.

The agent is built around a simple real-world problem: farmers often water their crops on
a fixed schedule or by guesswork, which leads to either overwatering or underwatering. This
project models an agent that senses soil moisture, temperature, and weather conditions, and
decides automatically whether the water pump should be turned on or off.

The assignment report covers four parts — problem identification, problem formulation
(with a graphical environment diagram), evaluation using the PEAS framework, and
classification of the agent's environmental properties.

As a small practical example, I also implemented a rule-based Travel Agent in Python to
demonstrate conditional decision-making using if / elif / else logic.

---

## Repository Contents

| File | Description |
|---|---|
| `Smart_Irrigation_Agent_Assignment.pdf` | Complete Intelligent Agents assignment report |
| `Hammad_Lab1_TravelAgent.ipynb` | Google Colab notebook containing the rule-based Travel Agent example |
| `README.md` | Project documentation and overview |

---

## Basic Travel Agent Example

As a small practical example, I created a simple rule-based Travel Agent.

The agent checks a customer's booking status and responds accordingly.

- If the booking is **Confirmed**, it prints a confirmation message with the destination.
- If the booking is **Pending**, it tells the passenger to wait for confirmation.
- If the booking is **Cancelled** (or anything else), it asks them to contact support.

### Python Code

\`\`\`python
booking_status = "Confirmed"
passenger = "Sara"
destination = "Lahore"

if booking_status == "Confirmed":
    print(f"Ticket confirmed for {passenger} to {destination}. Have a safe journey!")
elif booking_status == "Pending":
    print(f"Booking for {passenger} is still pending. Please wait for confirmation.")
else:
    print(f"Booking for {passenger} was cancelled. Please contact support to rebook.")
\`\`\`

---

## Key Concepts Applied

- **PEAS Framework** — Performance measure, Environment, Actuators, Sensors
- **Environment Properties** — Partially Observable, Stochastic, Sequential, Dynamic,
  Continuous, Single-Agent
- **Conditional Decision Making** — if / elif / else logic, as shown in the Travel Agent
  example above
