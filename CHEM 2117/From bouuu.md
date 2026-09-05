# Atomic Model — Chemistry Quiz Notebook

---

## 1. Three Rules of Electron Configuration

### (a) Aufbau Principle
- **"Aufbau"** means *"building up"* (German).
- Electrons are filled into orbitals **starting from the lowest energy orbital to the highest**, one electron at a time.
- Filling order follows the **(n + l) rule**: an orbital with a lower (n + l) value is filled first. If two orbitals have the same (n + l), the one with lower *n* fills first.
- Standard filling order (memorize this):
  ```
  1s < 2s < 2p < 3s < 3p < 4s < 3d < 4p < 5s < 4d < 5p < 6s < 4f < 5d < 6p < 7s
  ```
- Example: Fe (Z = 26) → 1s² 2s² 2p⁶ 3s² 3p⁶ 4s² 3d⁶

### (b) Pauli's Exclusion Principle
- **No two electrons in the same atom can have the same set of all four quantum numbers (n, l, mₗ, mₛ).**
- Practical result: **an orbital can hold a maximum of 2 electrons**, and those 2 electrons must have **opposite (paired) spins** (↑↓).
- Example: 1s² — both electrons have n=1, l=0, mₗ=0, but one has mₛ=+½ and the other mₛ=−½.

### (c) Hund's Rule (Rule of Maximum Multiplicity)
- When electrons are filled into a set of **degenerate orbitals** (orbitals of the same energy, e.g., the three 2p orbitals), **each orbital gets one electron first (singly, with parallel spin) before any orbital gets a second electron**.
- Electrons prefer to remain unpaired as long as possible — this gives the atom maximum stability/multiplicity.
- Example — filling 2p³ (as in Nitrogen):
  ```
  Correct:   ↑   ↑   ↑        (each of 3 p orbitals singly filled)
             2p_x 2p_y 2p_z

  Wrong:     ↑↓  ↑   _
  ```

---

## 2. Quantum Numbers — Which Orbitals Are Possible

| Quantum Number | Symbol | Meaning | Allowed values |
|---|---|---|---|
| Principal | n | Shell / energy level | 1, 2, 3, 4, … |
| Azimuthal (subshell/orbital shape) | l | Sub-shell | 0 to (n − 1) |
| Magnetic | mₗ | Orientation of orbital | −l to +l (total 2l+1 values) |
| Spin | mₛ | Spin of electron | +½ or −½ |

**Subshell naming from l:**
| l value | 0 | 1 | 2 | 3 |
|---|---|---|---|---|
| Name | s | p | d | f |

### The Golden Rule for "possible or not"
An orbital **nl is possible only if l ≤ (n − 1)**.

| Notation | n | l needed | Max allowed l (=n−1) | Possible? |
|---|---|---|---|---|
| 1s | 1 | 0 | 0 | ✅ Yes |
| 1p | 1 | 1 | 0 | ❌ No (l can only be 0 when n=1) |
| 2s | 2 | 0 | 1 | ✅ Yes |
| 2p | 2 | 1 | 1 | ✅ Yes |
| 2d | 2 | 2 | 1 | ❌ No |
| 3d | 3 | 2 | 2 | ✅ Yes |
| 3f | 3 | 3 | 2 | ❌ No |
| 4f | 4 | 3 | 3 | ✅ Yes |

**Quick check trick:** write n, then check if l (from the letter s=0, p=1, d=2, f=3) is *strictly less than* n. If l ≥ n → impossible.

**mₗ check:** for a given l, the number of orbitals = (2l + 1).
- s → 1 orbital (mₗ = 0)
- p → 3 orbitals (mₗ = −1, 0, +1)
- d → 5 orbitals (mₗ = −2, −1, 0, +1, +2)
- f → 7 orbitals (mₗ = −3, −2, −1, 0, +1, +2, +3)

An mₗ value **outside this range for a given l is not possible** (e.g., mₗ = +2 for a p orbital is impossible since p allows only −1, 0, +1).

---

## 3. Heisenberg's Uncertainty Principle & de Broglie Equation (Math)

### Heisenberg's Uncertainty Principle
**Statement (in short):** It is impossible to simultaneously know the *exact* position and *exact* momentum of a microscopic particle (like an electron).

**Formula:**
```
Δx · Δp ≥ h / 4π
```
or, since Δp = m·Δv:
```
Δx · Δv ≥ h / (4πm)
```
- Δx = uncertainty in position
- Δp = uncertainty in momentum
- Δv = uncertainty in velocity
- m = mass of the particle
- h = Planck's constant = 6.626 × 10⁻³⁴ J·s

**How to solve a problem:**
1. Identify what's given: Δx or Δv (or Δp), and mass.
2. Plug into Δx·Δv ≥ h/(4πm) and solve for the unknown.
3. Keep units in SI (kg, m, m/s) throughout.

**Worked example:** Find minimum uncertainty in velocity of an electron if Δx = 1 × 10⁻¹⁰ m. (mₑ = 9.1 × 10⁻³¹ kg)
```
Δv ≥ h / (4π · m · Δx)
Δv ≥ (6.626×10⁻³⁴) / (4π × 9.1×10⁻³¹ × 1×10⁻¹⁰)
Δv ≥ 5.8 × 10⁵ m/s (approx.)
```

### de Broglie Equation
**Statement (in short):** Every moving particle has an associated wavelength (matter waves).

**Formula:**
```
λ = h / p = h / (m·v)
```
- λ = de Broglie wavelength
- h = Planck's constant = 6.626 × 10⁻³⁴ J·s
- m = mass of particle (kg)
- v = velocity (m/s)
- p = momentum = m·v

**How to solve a problem:**
1. Find momentum p = m × v (convert mass to kg, velocity to m/s if needed).
2. λ = h / p.
3. If kinetic energy (KE) is given instead of velocity: use `v = √(2·KE/m)` first, then plug into λ = h/(mv). Or directly: `λ = h / √(2·m·KE)`.

**Worked example:** Find de Broglie wavelength of an electron moving at 1 × 10⁶ m/s.
```
λ = h / (m·v) = (6.626×10⁻³⁴) / (9.1×10⁻³¹ × 1×10⁶)
λ ≈ 7.28 × 10⁻¹⁰ m
```

---

## 4. Rydberg Equation (Math)

**Purpose:** Calculates the wavelength (or wavenumber) of light emitted/absorbed when an electron jumps between energy levels in a **hydrogen atom**.

**Formula:**
```
1/λ = R_H (1/n₁² − 1/n₂²)
```
- λ = wavelength of emitted/absorbed light
- R_H = Rydberg constant = 1.097 × 10⁷ m⁻¹ (sometimes written as 109677 cm⁻¹)
- n₁ = lower energy level (final state electron falls to, for emission)
- n₂ = higher energy level (initial state, n₂ > n₁)

**Related formulas often paired with it:**
```
ν (frequency) = c / λ
E = hν = hc/λ         (energy of photon)
c = 3 × 10⁸ m/s        (speed of light)
```

**Spectral series (know these — n₁ values):**
| Series | n₁ | Region |
|---|---|---|
| Lyman | 1 | Ultraviolet |
| Balmer | 2 | Visible |
| Paschen | 3 | Infrared |

**How to solve a problem:**
1. Identify n₁ and n₂ (which level → which level).
2. Plug into 1/λ = R_H(1/n₁² − 1/n₂²).
3. Solve for λ, then flip (reciprocal) — don't forget this step, a common mistake is forgetting to take the reciprocal at the end.
4. If frequency or energy is asked, use ν = c/λ or E = hc/λ afterward.

**Worked example:** Find λ for an electron transition from n=3 to n=2 (Balmer series).
```
1/λ = 1.097×10⁷ (1/2² − 1/3²)
1/λ = 1.097×10⁷ (0.25 − 0.111)
1/λ = 1.097×10⁷ × 0.1389
1/λ = 1.524×10⁶ m⁻¹
λ = 1 / (1.524×10⁶) ≈ 6.56 × 10⁻⁷ m (656 nm — red light, matches H-alpha line ✅)
```

---

## 5. Mass Number

**Definition:** The **mass number (A)** is the **total number of protons and neutrons (collectively called nucleons)** present in the nucleus of an atom.

**Formula:**
```
A = Z + N
```
- A = mass number
- Z = atomic number (number of protons)
- N = number of neutrons

**How to determine mass number:**
1. Count the number of protons (this equals the atomic number Z, found on the periodic table).
2. Count the number of neutrons (N).
3. Add them: A = Z + N.
4. Written in isotope notation as: ₙᴬZX (mass number on top-left, atomic number bottom-left of the element symbol).

**Key notes:**
- Mass number is always a **whole number** (no decimal, no unit — it's just a count of particles).
- Isotopes = atoms of the same element (same Z) but **different mass numbers** (different N).
  - Example: ¹²C, ¹³C, ¹⁴C — all carbon (Z=6), but N = 6, 7, 8 respectively.
- To find neutrons when A and Z are known: **N = A − Z**.

---

## 6. Definitions of Subatomic Particles

| Particle | Charge | Relative charge | Mass (kg) | Relative mass | Location | Discovered by |
|---|---|---|---|---|---|---|
| **Electron (e⁻)** | Negative | −1 | 9.109 × 10⁻³¹ | ~1/1836 (negligible) | Moves around the nucleus in orbitals/shells | J.J. Thomson |
| **Proton (p⁺)** | Positive | +1 | 1.673 × 10⁻²⁷ | 1 | Inside the nucleus | Ernest Rutherford |
| **Neutron (n)** | Neutral (no charge) | 0 | 1.675 × 10⁻²⁷ | ~1 (slightly > proton) | Inside the nucleus | James Chadwick |

**One-line definitions:**
- **Electron:** A negatively charged, extremely light subatomic particle that revolves around the nucleus and determines chemical behavior.
- **Proton:** A positively charged subatomic particle found in the nucleus; the number of protons defines the atomic number (identity of the element).
- **Neutron:** A neutral (chargeless) subatomic particle found in the nucleus, with mass nearly equal to a proton; adds to atomic mass without adding charge.

---

## 7. Bohr Model Theory — 4 Assumptions (Postulates)

1. **Stationary orbits:** Electrons revolve around the nucleus only in certain fixed, allowed circular paths called **orbits (or shells)**, without radiating (losing) energy — these are called **stationary states**.

2. **Quantized angular momentum:** Only those orbits are permitted for which the **angular momentum of the electron is an integral multiple of h/2π**:
   ```
   mvr = nh / 2π      (n = 1, 2, 3, ...)
   ```
   where m = mass of electron, v = velocity, r = radius of orbit, n = orbit number (principal quantum number).

3. **Definite (quantized) energy:** Each orbit/stationary state has a **fixed, definite amount of energy**. For hydrogen:
   ```
   Eₙ = −13.6 / n²  eV
   ```
   As long as the electron stays in the same orbit, it neither gains nor loses energy.

4. **Energy absorption/emission on transition:** An electron can **jump from a lower orbit to a higher orbit by absorbing energy**, and it **emits energy (as a photon) when it falls from a higher orbit to a lower orbit**. The energy of the photon equals the energy difference between the two orbits:
   ```
   ΔE = E₂ − E₁ = hν
   ```

---

## 8. Quantization of Energy — Definition

**Definition:** Quantization of energy means that **energy is not continuous/absorbed in any arbitrary amount — it exists and is exchanged only in discrete, fixed packets called "quanta."**

- Proposed by **Max Planck** (Planck's Quantum Theory).
- A body can emit or absorb energy only in whole-number multiples of a smallest unit (a quantum):
  ```
  E = nhν
  ```
  where n = 1, 2, 3, ... (a positive integer, the quantum number), h = Planck's constant, ν = frequency of radiation.
- This idea directly supports **Bohr's model**, where electron energy levels are quantized (only certain fixed energy values are allowed — not a continuous range).

---

### Quick Reference — Key Constants
| Constant | Symbol | Value |
|---|---|---|
| Planck's constant | h | 6.626 × 10⁻³⁴ J·s |
| Speed of light | c | 3 × 10⁸ m/s |
| Rydberg constant | R_H | 1.097 × 10⁷ m⁻¹ |
| Mass of electron | mₑ | 9.109 × 10⁻³¹ kg |
| Mass of proton | mₚ | 1.673 × 10⁻²⁷ kg |
| Mass of neutron | mₙ | 1.675 × 10⁻²⁷ kg |
