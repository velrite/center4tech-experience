# Laser security alarm

**Phase:** after the camp. **My role:** one of a team of three; I helped set up the optics. **Evidence:** none confirmed. A photograph may belong to this project but I have not confirmed it. Everything here is RECOLLECTION.

## Ownership

| | |
|---|---|
| Organization-owned | UNKNOWN. |
| Student-built | Nothing. |
| My contribution | With the team, the optical setup: reflecting the laser through several mirror pieces onto the sensor. |
| Public reconstruction | The diagram is generic. |

## What it was

A thick wooden structure with mirror pieces that folded a laser beam along a long path. A bare LDR (light-dependent resistor, which looks like a resistor) received the beam. An Arduino and a buzzer were meant to sound when the beam was broken.

## The hard part

Tuning the light so the beam stayed on the LDR was difficult. Whether I changed the beam angle, the intensity or a threshold is not recalled (UNKNOWN).

## Concept diagram (generic)

```mermaid
flowchart LR
  A[Laser] --> B[Mirrors fold the beam]
  B --> C[LDR receives light]
  C --> D[Controller]
  D -->|beam broken| E[Buzzer]
```

## Not recalled

Whether it worked reliably, the board model, the power supply, and the sensor threshold.
