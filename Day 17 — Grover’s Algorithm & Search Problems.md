# Day 17 — Grover’s Algorithm & Search Problems  
**Date:** June 17, 2025  
**Challenge:** 21-Day Quantum Computing Challenge (QC-2)

---

## What I Set Out to Do  
After yesterday’s dive into breaking encryption with Shor’s algorithm, today’s focus shifted to **search problems** specifically, how quantum computing can **speed up unsorted database searches** using Grover’s algorithm. Unlike Shor, Grover doesn’t break cryptography, but it’s still powerful in its own right.

---

## What I Covered  
- The problem Grover’s algorithm solves: finding a target in an unsorted list of \( N \) items  
- Why classical search takes \( O(N) \) and Grover does it in \( O(\sqrt{N}) \)  
- The concept of the **oracle** a black-box function that tells us if we’ve found the right answer  
- How **amplitude amplification** boosts the probability of the correct answer  
- Circuit-level implementation using Hadamard gates, oracle, and diffusion operator  
- Real-world applications: password cracking, optimization, decision-making

---

## What I Learned  
- Grover’s algorithm doesn’t give exponential speedup, but a *quadratic one* and in some problems, that’s still game-changing.  
- The amplitude amplification technique feels almost magical — it's like giving the right answer a louder "voice" so it’s more likely to be heard when measured.  
- Understanding the **oracle** was the trickiest part — since it's abstract, imagining how it's built for real problems takes some effort.  
- Grover isn’t limited to database searches. It’s applicable in solving SAT problems, breaking symmetric encryption, or even speeding up AI decision trees.  
- Quantum computing doesn't just outperform classical — it changes how we *think* about problem-solving altogether.

---

## Resources I Used  
- [Grover’s Algorithm – Qiskit Overview](https://youtu.be/Ezc0cjsBG-M?si=6koBLWNtl0DYwreL)  
- [Grover’s Search Explained – CrashCourse Style](https://youtu.be/c30KrWjHaw4?si=-N5krOGMnKdrTN61)  
- [Grover's Circuit Walkthrough](https://youtu.be/hnpjC8WQVrQ?si=PH1lOjx-wMAO8Obo)

---

## Final Thoughts  
Grover’s algorithm was easier to grasp than Shor’s, but no less impressive. The idea that we can search faster not by looking harder but by *interfering smarter* is such a quantum mindset. I’m starting to see how these building blocks fit together. This one was genuinely fun to visualize and play around with.

---

## Progress  
✅ Completed Day 17  
🔜 Up next: Day 18 — *Variational Quantum Algorithms*
