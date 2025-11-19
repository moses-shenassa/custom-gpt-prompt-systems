# Sigilizer — Phase A Rules (Letter Reduction)

Phase A transforms an intention statement into a structured set of symbols.

## Steps

1. **Remove punctuation, spaces, and non-alphabetic characters.**

2. **Convert all letters to uppercase.**
   Standardize the dataset for deterministic processing.

3. **Remove repeated letters**, keeping only the first occurrence.

4. **Map each remaining letter to a numerical value** using:
   A, J, S = 1  
   B, K, T = 2  
   C, L, U = 3  
   D, M, V = 4  
   E, N, W = 5  
   F, O, X = 6  
   G, P, Y = 7  
   H, Q, Z = 8  
   I, R = 9  

5. **Output format:**
   - Clean letter string  
   - Sequence of numeric values  

Phase A is complete when the intention has been transformed into a noise-reduced,
symbolically meaningful sequence ready for structural mapping.
