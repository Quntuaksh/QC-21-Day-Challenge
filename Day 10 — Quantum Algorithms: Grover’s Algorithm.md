# Day 10 — Quantum Algorithms: Grover’s Algorithm  
**Date:** June 10, 2025  
**Challenge:** 21-Day Quantum Computing Challenge (QC-2)

---

## What I Set Out to Do  
Today was all about one of the coolest quantum algorithms out there Grover’s Algorithm. It promises a quadratic speedup for searching an unsorted database, and I was honestly curious how that even works without checking every element.

---

## What I Covered  
- What Grover’s Algorithm actually does  
- How it uses superposition and interference  
- Oracle & Amplification steps  
- Why it gives a √N speedup vs classical N  
- Use cases: unstructured search, password cracking, etc.

---

## What I Learned  
- Grover’s Algorithm doesn’t “look” through all elements it uses the *entire state space* at once. That's the magic of quantum parallelism.  
- The algorithm uses an “oracle” to mark the correct item and then amplifies the amplitude of that result feels like sculpting probabilities with math.  
- It was kind of wild to watch how after a few iterations, the correct answer becomes most likely to appear when measured.  
- The quadratic speedup sounds small at first, but in terms of brute force problems (like searching or cracking), it’s huge.  
- Visualizing the algorithm using the Qiskit simulator helped a lot especially understanding how the interference pattern “pushes up” the correct answer.

---

## Resources I Used  
- [Grover’s Algorithm — Qiskit](https://qiskit.org/textbook/ch-algorithms/grover.html)  
- [Grover’s Search Explained — MinutePhysics](https://www.youtube.com/watch?v=EMz1n6weRcA)

---

## Final Thoughts  
Grover’s Algorithm felt like watching a magic trick and then learning how it works except the trick is real math. The idea that a computer can "guess" correctly faster by just being quantum is still messing with my brain. Definitely one of my favorite days so far.

---

## Progress  
✅ Completed Day 10  
🔜 Up next: Day 11: *Quantum Algorithms - Shor’s Algorithm*
