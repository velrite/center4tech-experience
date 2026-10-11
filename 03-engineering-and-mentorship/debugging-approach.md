# Debugging approach

RECOLLECTION unless labelled otherwise.

## My method with student circuits

1. Read the circuit and check it against what was meant to be built.
2. Test wire connectivity with a multimeter.

To help students find faults themselves, they presented their work to me and to a classmate, and I corrected and encouraged them.

## Generic structure (the middle two steps are my stated method)

```mermaid
flowchart LR
  A[Observe the failure] --> B[Compare circuit with design]
  B --> C[Test connections with a multimeter]
  C --> D[Fix the faulty part]
  D --> E[Retest]
```

## Cases I remember

| Project | What failed | What changed | What I know |
|---|---|---|---|
| Robotic arm | Broken potentiometer, faulty wire, weak plastic part | Resoldered the potentiometer, replaced the wire, swapped the plastic for firmer foam board | It worked again. How I found the faults is UNKNOWN. |
| Moving toy baby | The first version moved awkwardly | Added balancing weight and rebuilt it so the balance sat at the midpoint | Movement smoothed out. The cause was imbalance (INFERENCE from the fix). |
| Custom lamp | The first design cast shadows | Added reflective silver lining after an instructor explained it | Light improved a lot. The shadows came from the geometry of the structure. |
| Laser alarm | Hard to keep the beam on the LDR | Tuned the light setup | What exactly I adjusted is UNKNOWN. |

I do not recall specific line-follower failures.
