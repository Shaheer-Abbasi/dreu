**Student:** Shaheer Abbasi 
**Mentor:** Dr. Michael Reiter  

# Week 1

**Dates:** 06-07 to 06-13

## Goals

- Meet with my faculty mentor and discuss the research project scope on false-claim attacks
- Read and understand the background paper on Untargeted Backdoor Watermarking (UBWC)
- Review literature on Perlin noise and universal adversarial patches
- Set up the experimental code repository
- Perform initial test experiments with Perlin noise triggers

## Approach and Implementation

I met with Dr. Reiter and his PHD student for 45 minutes on Monday to discuss the research direction on false-claim attacks targeting neural network data auditing methods. The primary objective is to evaluate whether an attacker can forge ownership claims without possessing the actual training data.

I focused on understanding Untargeted Backdoor Watermarking (UBWC) and how the audit process detects training data membership. I also studied procedural Perlin noise and universal adversarial patches to evaluate if they can trigger false positive matches.

For the implementation phase, I successfully configured the experimental repository, resolving basic environment setup and pathing issues. I then executed two pilot experiments: a blended-noise trigger (which yielded weak classifier response) and a localized Perlin-noise patch trigger (which achieved much stronger, target-trigger-like responses).

## Results

- Met with mentor to review research goals on false-claim attacks
- Completed background reading on Untargeted Backdoor Watermarking (UBWC) and Perlin noise
- Set up the starter repository on my local machine
- Evaluated a blended-noise trigger, finding it too weak to consistently influence the model
- Evaluated a Perlin patch trigger, which successfully simulated target-trigger behavior

## Notes



