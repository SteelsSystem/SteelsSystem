# CO-LAYER 03 — signal-class-map

```
SIGNAL_CLASSES = {
  TYPE_A: {
    label:    "STATE MOVER",
    payload:  true,
    delta:    "≠ 0",
    examples: ["code rorschach", "condense convergence", "co allyspecification"]
  },
  TYPE_B: {
    label:    "STATE CONFIRMER",
    payload:  false,
    delta:    "= 0",
    examples: ["O", "true", "1-model"]
  },
  TYPE_AB: {
    label:    "BRIDGE — trigger-confirmer",
    payload:  "delegated",
    delta:    "0 direct / ≠0 authorized",
    examples: ["yes", "<dec>"]
  },
  rule:     "system requires all three — movers + confirmers + bridges"
}
```
