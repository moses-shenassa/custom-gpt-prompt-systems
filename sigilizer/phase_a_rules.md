# Sigilizer — Phase A Rules (Letter Reduction)

Phase A transforms an intention statement into a structured set of symbols. The
goal is to produce a **deterministic, reproducible** sequence that can be
mapped in later phases.

## Input

- A short, clear intention phrase in everyday language.
- Roman alphabet recommended (A–Z). Non-letter characters are ignored.

## Steps

1. **Normalize the text.**
   - Remove punctuation, numbers, and special characters.
   - Replace multiple spaces with a single space.
   - Convert all letters to uppercase.

2. **Remove spaces.**
   - Join all remaining letters into a single continuous string.

3. **Remove repeated letters.**
   - Scan from left to right.
   - Keep only the **first occurrence** of each letter.
   - Discard any subsequent duplicates.

4. **Map each remaining letter to a numerical value** using:

   - A, J, S = 1  
   - B, K, T = 2  
   - C, L, U = 3  
   - D, M, V = 4  
   - E, N, W = 5  
   - F, O, X = 6  
   - G, P, Y = 7  
   - H, Q, Z = 8  
   - I, R = 9  

5. **Produce the Phase A output:**
   - Clean letter string
   - Corresponding numeric sequence

## Worked Mini-Example

Intention:  
> “Calm and focused study.”

1. Normalize → `CALM AND FOCUSED STUDY`  
2. Remove spaces → `CALMANDFOCUSEDSTUDY`  
3. Remove repeats → `CALMNDFOUSETY`  
4. Map to numbers → `3 1 4 4 5 4 6 3 5 1 2 5 7`  

This pair of outputs feeds directly into Phase B.

Phase A is complete when the intention has been transformed into a noise-reduced,
symbolically meaningful sequence ready for structural mapping.
