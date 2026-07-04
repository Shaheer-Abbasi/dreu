**Student:** Shaheer Abbasi 
**Mentor:** Dr. Michael Reiter  

# Week 2

**Dates:** 06-14 to 06-20

## Goals

- Explore methods to attack UBWC without requiring access to the victim’s exact dataset
- Characterize the performance of random Perlin-noise universal adversarial patches
- Evaluate CIFAR-to-CIFAR vs. TinyImageNet-to-CIFAR cross-dataset false-claim attacks
- Assess whether CLIP-scored patch selection is necessary compared to random patches
- Prepare a preliminary findings presentation for the lab group

## Approach and Implementation

I attended our weekly 45-minute lab meeting on Monday to discuss progress. For experiments, my focus was analyzing the dependency of data ownership attacks on victim training dataset access. 

I conducted false-claim experiments using both 8x8 and 16x16 center-aligned random Perlin-noise patches across 20 trials. Specifically, I compared: (1) CIFAR-to-CIFAR random patches, (2) TinyImageNet-to-CIFAR random patches, and (3) TinyImageNet-to-CIFAR CLIP-scored patches. 

Additionally, I prepared a presentation detailing our current experimental setup and preliminary evaluation results.

## Results

- Conducted systematic UBW/UBWC false-claim attacks with 20 trials per experiment
- Tested Perlin-noise universal patches of sizing 8x8 and 16x16
- CIFAR-to-CIFAR random: 18/20 detections (8x8) and 19/20 detections (16x16)
- TinyImageNet-to-CIFAR random: 18/20 detections (8x8) and 20/20 detections (16x16)
- TinyImageNet-to-CIFAR CLIP-scored: 18/20 detections (8x8) and 20/20 detections (16x16)
- Found that random Perlin patches perform on par with CLIP-scored patches, indicating that dataset similarity is not required for the attack
- Saw that 16x16 patches yield higher attack reliability than 8x8 patches
- Initiated reading on LLM Dataset Inference to prepare for migrating the attack to text models

## Notes


