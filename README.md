
All other powers of two contain digits outside this set.

## 🧩 Description

The proof is based on a *phase analysis modulo 6* and a simple *combinatorial invariant* on the distribution of digits.  
Key results:

- **Phase condition:** for odd exponents, \(2^n \equiv 2 \pmod 6\);
- **Digit invariant:** the numbers of 1’s and of digits in \{2,8\} satisfy \(a \equiv b \pmod 3\);
- **Finite tail set:** only the endings 12, 28, 88 (mod 100) and 112, 128, 288 (mod 1000) occur;
- **Structural restriction:** no valid number of 4 or more digits can satisfy all modular constraints.

The proof is self-contained and written in LaTeX, with detailed lemmas, examples, and appendices explaining how to derive the admissible endings and carry transitions.

## 📄 Contents

- `powers_of_two_128_detailed.tex` — full LaTeX source of the proof (in English)
- `proof_powers_of_two_128_utf8.tex` — earlier Russian draft
- `LICENSE` — MIT License
- (optional) compiled PDF version of the article

## ✍️ Author

**S. V. Goryushkin**  
2025

## 🔖 License

This project is released under the **MIT License**.  
You are free to use, modify, and distribute the materials, provided that attribution to the author is preserved.

---

### Example citation

If you use this work, please cite it as:

> Goryushkin, S.V. (2025). *Powers of Two with Digits from {1,2,8}: A Combinatorial Proof of Finiteness.* GitHub Repository. https://github.com/your-username/powers-of-two-128

---

## 🧠 Summary

This proof demonstrates that a deep modular pattern (phase \(2 \pmod 6\)) and a simple parity balance among digits entirely explain why the sequence terminates at **128**.  
No advanced number theory or computer search is required — the argument is purely combinatorial and modular.
