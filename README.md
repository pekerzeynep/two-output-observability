# two-output-observability
Short technical note and illustrative figure about repeated event detections in single-output measurements and their relation to observability and multi-output phase structure.
# Two-Output Observability: When Single-Channel Event Detections Mislead

## Motivation

Single-output event detectors are widely used as proxies for underlying state changes.  
Yet in several simple oscillatory measurement experiments, I repeatedly observed:  

persistent, structured event detections — despite no apparent regime shift in the system.

The detections are not random noise.  
They are temporally structured and persistent.

This raised a specific question:  

Is the detector identifying a true change in the system,  
or only a change in how the system is being observed?

---

## Minimal experiment

I constructed a simple synthetic example:

•⁠  ⁠A stable oscillatory system  
•⁠  ⁠No regime change in the underlying dynamics  
•⁠  ⁠Slow measurement drift and noise

Using a single measured output, an energy/persistence type detector repeatedly flags events.

However, when a second measurement channel is added and the phase relationship between the two outputs is examined, a different picture appears:

The system state remains coherent while the detector continues to report events.

This suggests the detections are linked to *measurement structure*, not necessarily to a change in the system itself.

---

## Observation

The key empirical observation is:

Repeated event detections can occur in a single-output measurement  
without a corresponding change in the underlying system dynamics.

But the phase relation between two outputs remains stable.

This creates a mismatch:

•⁠  ⁠event-like behavior in the measurement  
•⁠  ⁠stability in the multi-output structure

---

## Interpretation (tentative)

A working interpretation is that the detector is reacting to a change in observability conditions rather than a change in the state.

Here, "observability" is used informally to indicate the measurement's ability to carry state information, not a formal rank condition test.

In other words, the measurement becomes locally non-informative about the internal state, and the detector interprets this loss of information as a system event.

I am not claiming a new theory here.

I am only asking whether this situation corresponds to a known limitation of observability or state reconstruction in nonlinear systems.

---

## Illustrative Figure

![Two measured outputs with apparent single-channel events despite stable multi-output agreement](two-measured-outputs.png)

Top panel: Two measured outputs (m1(t) in blue, m2(t) in orange) from the same underlying stable oscillatory system. Both channels show high coherence and no visible regime shift.

Bottom panel: Using only m1(t) triggers repeated apparent 'transitions' (red vertical lines), while the two-output agreement (gray shading) indicates no system-like change – phase and amplitude relations remain stable throughout.

The purpose of this figure is only to illustrate the key observation: persistent event detections in a single channel can coexist with invariant inter-channel structure.
