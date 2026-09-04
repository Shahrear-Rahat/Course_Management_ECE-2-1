# Atomic Model — Quiz Prep Notebook

---

## 1. Three Rules: Aufbau, Pauli's Exclusion Principle, Hund's Rule

### (a) Aufbau Principle
"Aufbau" মানে জার্মান শব্দ যার অর্থ "building up"। 

**Statement:** ইলেকট্রনগুলো সবসময় সবচেয়ে কম শক্তির (lowest energy) অরবিটাল আগে fill করে, তারপর ধীরে ধীরে বেশি শক্তির অরবিটালে যায়।

**Order (n+l rule অনুসারে):**
```
1s → 2s → 2p → 3s → 3p → 4s → 3d → 4p → 5s → 4d → 5p → 6s → 4f → 5d → 6p → 7s → 5f → 6d → 7p
```

**মনে রাখার Trick (diagonal rule):** একটা চার্ট আঁকো যেখানে n=1 থেকে 7 পর্যন্ত row এবং s,p,d,f column। তারপর কর্ণ (diagonal) বরাবর তীর টানলে fill করার order পাওয়া যায়।

**n+l rule:** যে অরবিটালের (n+l) মান কম, সেটা আগে ভরবে। যদি দুইটার (n+l) সমান হয়, তাহলে যেটার n কম সেটা আগে ভরবে।
- উদাহরণ: 3d (n+l = 3+2=5) vs 4s (n+l=4+0=4) → 4s আগে ভরবে কারণ n+l কম।

**ব্যতিক্রম (Exceptions):** Cr (Chromium) এবং Cu (Copper) — এদের half-filled/fully-filled d-orbital বেশি stable বলে electron configuration সাধারণ নিয়ম মানে না।
- Cr: প্রত্যাশিত [Ar] 3d⁴4s² → আসল [Ar] 3d⁵4s¹
- Cu: প্রত্যাশিত [Ar] 3d⁹4s² → আসল [Ar] 3d¹⁰4s¹

### (b) Pauli's Exclusion Principle
**Statement:** একই অ্যাটমে কোনো দুইটা ইলেকট্রনের চারটা কোয়ান্টাম নাম্বার (n, l, m, s) একসাথে সমান হতে পারবে না। কমপক্ষে একটা কোয়ান্টাম নাম্বার আলাদা হতেই হবে।

**Practical Implication:** একটা অরবিটালে সর্বোচ্চ ২টা ইলেকট্রন থাকতে পারে, এবং তাদের spin অবশ্যই বিপরীত হতে হবে (একটা +½, আরেকটা −½)। একই অরবিটালে একই spin এর দুইটা ইলেকট্রন থাকতে পারবে না।

**উদাহরণ:** 1s অরবিটালে দুইটা ইলেকট্রন থাকতে পারে —
- e⁻1: n=1, l=0, m=0, s=+½
- e⁻2: n=1, l=0, m=0, s=−½

### (c) Hund's Rule (Rule of Maximum Multiplicity)
**Statement:** একই শক্তিস্তরের (degenerate) অরবিটালগুলোতে (যেমন p, d, f orbitals) ইলেকট্রন ভরার সময় প্রতিটা অরবিটালে প্রথমে একটা করে ইলেকট্রন (একই spin দিয়ে, সাধারণত ↑) বসবে, তারপরই দ্বিতীয় ইলেকট্রন (বিপরীত spin) pairing শুরু হবে।

**কারণ:** unpaired ইলেকট্রনগুলোর মধ্যে electron-electron repulsion কম হয়, ফলে system বেশি stable হয়।

**উদাহরণ (p³ configuration, যেমন Nitrogen):**
```
2p:  ↑   ↑   ↑     (সঠিক — Hund's rule মেনে)
2p:  ↑↓  ↑   _     (ভুল — Hund's rule ভঙ্গ)
```

---

## 2. Quantum Numbers — কোন অরবিটাল সম্ভব, কোনটা না

চারটা quantum number অরবিটাল define করে:

| Quantum Number | Symbol | মান | কী বোঝায় |
|---|---|---|---|
| Principal | n | 1, 2, 3, ... (positive integer) | shell / energy level |
| Azimuthal (Angular momentum) | l | 0 থেকে (n−1) | subshell/orbital shape (s,p,d,f) |
| Magnetic | m (বা mₗ) | −l থেকে +l (including 0) | orbital-এর orientation |
| Spin | s (বা mₛ) | +½ অথবা −½ | ইলেকট্রনের spin |

**l এর মান অনুযায়ী orbital নাম:**
- l = 0 → s orbital
- l = 1 → p orbital
- l = 2 → d orbital
- l = 3 → f orbital

### নিয়ম যাচাই করার পদ্ধতি:
একটা orbital (n, l, m) সম্ভব কিনা check করতে তিনটা শর্ত মিলাও:
1. **l অবশ্যই 0 থেকে (n−1) এর মধ্যে হতে হবে।** (l কখনো n এর সমান বা বেশি হতে পারবে না)
2. **m অবশ্যই −l থেকে +l এর মধ্যে হতে হবে।**
3. n সবসময় positive integer (1, 2, 3...), কখনো 0 বা negative না।

### উদাহরণ (Possible vs Not Possible):

| n, l, m | সম্ভব কিনা | কারণ |
|---|---|---|
| n=2, l=1, m=0 | ✅ সম্ভব | l=1 (max n−1=1 ঠিক আছে), m=0 (−1 to +1 এর মধ্যে) |
| n=3, l=3, m=0 | ❌ অসম্ভব | l সর্বোচ্চ (n−1)=2 হতে পারে, কিন্তু এখানে l=3 |
| n=1, l=0, m=1 | ❌ অসম্ভব | l=0 হলে m শুধু 0 হতে পারে, m=1 হতে পারে না |
| n=4, l=2, m=−2 | ✅ সম্ভব | l=2 ঠিক (max n−1=3), m=−2 range এর মধ্যে (−2 to +2) |
| n=2, l=2, m=0 | ❌ অসম্ভব | l সর্বোচ্চ (n−1)=1, কিন্তু l=2 দেওয়া আছে |
| n=0, l=0, m=0 | ❌ অসম্ভব | n কখনো 0 হতে পারে না |

**Quick check করার শর্টকাট:** সবসময় প্রথমে দেখো l < n কিনা, তারপর দেখো |m| ≤ l কিনা। দুইটাই satisfy করলে orbital সম্ভব।

---

## 3. Heisenberg's Uncertainty Principle ও De Broglie Equation — শুধু Math

### Heisenberg's Uncertainty Principle

**Formula:**
$$\Delta x \cdot \Delta p \geq \frac{h}{4\pi}$$

যেখানে:
- Δx = position-এর uncertainty
- Δp = momentum-এর uncertainty (Δp = m·Δv)
- h = Planck's constant = 6.626 × 10⁻³⁴ J·s

**অন্য রূপ (velocity দিয়ে):**
$$\Delta x \cdot \Delta v \geq \frac{h}{4\pi m}$$

**Solve করার Steps:**
1. প্রশ্নে কী কী দেওয়া আছে identify করো (Δx বা Δv বা m)
2. যেটা বের করতে বলছে সেটার জন্য formula rearrange করো
3. h = 6.626×10⁻³⁴ J·s বসাও, 4π = 12.566 হিসাব করো
4. Unit মিলিয়ে নাও (kg, m, m/s — SI unit এ আনতে হবে)

**উদাহরণ Problem:** একটা ইলেকট্রনের (m = 9.1×10⁻³¹ kg) position uncertainty Δx = 1×10⁻¹⁰ m হলে velocity uncertainty বের করো।
$$\Delta v \geq \frac{h}{4\pi m \Delta x} = \frac{6.626\times10^{-34}}{4\pi \times 9.1\times10^{-31} \times 1\times10^{-10}}$$

### De Broglie Equation

**Formula:**
$$\lambda = \frac{h}{mv} = \frac{h}{p}$$

যেখানে:
- λ = de Broglie wavelength
- h = Planck's constant
- m = mass
- v = velocity
- p = momentum (p = mv)

**Kinetic Energy দিয়ে দেওয়া থাকলে (alternate form):**
$$\lambda = \frac{h}{\sqrt{2mKE}}$$

**Accelerating voltage (V) দিয়ে দেওয়া থাকলে (electron-এর জন্য):**
$$\lambda = \frac{h}{\sqrt{2meV}}$$
যেখানে e = electron charge = 1.6×10⁻¹⁹ C

**Solve করার Steps:**
1. m, v (বা KE, বা V) identify করো
2. সঠিক formula বেছে নাও
3. h = 6.626×10⁻³⁴ J·s ব্যবহার করো
4. Unit consistency check করো (mass = kg, velocity = m/s)

**মনে রাখার জিনিস:** de Broglie সব matter-এর (particle) wave nature দেখায়, আর Heisenberg বলে যে position ও momentum একসাথে সঠিকভাবে জানা যায় না। দুইটা আলাদা concept, কিন্তু দুইটাই quantum mechanics-এর foundation।

---

## 4. Rydberg Equation — শুধু Math

**Formula:**
$$\frac{1}{\lambda} = R_H \left( \frac{1}{n_1^2} - \frac{1}{n_2^2} \right)$$

যেখানে:
- λ = emitted/absorbed light-এর wavelength
- R_H = Rydberg constant = 1.097 × 10⁷ m⁻¹ (বা 109677 cm⁻¹)
- n₁ = lower energy level (final state, electron যেখানে নামে)
- n₂ = higher energy level (initial state, electron যেখানে ছিল), n₂ > n₁

**নিয়ম:**
- Emission (ইলেকট্রন উঁচু থেকে নিচু level এ নামলে): energy release হয়, photon emit হয়
- Absorption (ইলেকট্রন নিচু থেকে উঁচু level এ উঠলে): energy absorb হয়

**Series Identification (Hydrogen spectrum):**

| Series নাম | n₁ (final) | Region |
|---|---|---|
| Lyman | 1 | Ultraviolet (UV) |
| Balmer | 2 | Visible light |
| Paschen | 3 | Infrared (IR) |
| Brackett | 4 | Infrared (IR) |
| Pfund | 5 | Infrared (IR) |

**Solve করার Steps:**
1. n₁ এবং n₂ identify করো (কোন level থেকে কোন level এ যাচ্ছে)
2. R_H এর মান বসাও (unit অনুযায়ী m⁻¹ বা cm⁻¹ ঠিক রাখো)
3. 1/n₁² − 1/n₂² হিসাব করো
4. পুরো ডান পাশ multiply করে 1/λ বের করো
5. λ বের করতে reciprocal নাও (λ = 1/উত্তর)

**উদাহরণ:** n₂=3 থেকে n₁=2 এ ইলেকট্রন নামলে (Balmer series):
$$\frac{1}{\lambda} = 1.097\times10^7 \left(\frac{1}{4} - \frac{1}{9}\right)$$

**Energy বের করতে চাইলে (extra formula, যদি লাগে):**
$$E = \frac{hc}{\lambda} \quad \text{অথবা} \quad E = 2.18\times10^{-18} \left(\frac{1}{n_1^2}-\frac{1}{n_2^2}\right) \text{ J}$$

---

## 5. Mass Number — Definition ও Determine করার নিয়ম

**Definition:** কোনো পরমাণুর nucleus-এ (কেন্দ্রে) থাকা মোট protons ও neutrons সংখ্যার যোগফলকে **Mass Number (A)** বলে।

$$A = Z + n$$

যেখানে:
- A = Mass number
- Z = Atomic number (protons সংখ্যা)
- n = Neutrons সংখ্যা

**কীভাবে বের করবে:**
1. Periodic table থেকে Atomic Number (Z) জেনে নাও — এটা protons সংখ্যার সমান
2. Neutron সংখ্যা জানা থাকলে সরাসরি যোগ করো: A = Z + n
3. যদি শুধু Mass Number আর Atomic Number দেওয়া থাকে, neutron বের করতে: n = A − Z

**গুরুত্বপূর্ণ পয়েন্ট:**
- Mass number সবসময় একটা **পূর্ণ সংখ্যা (whole number)**, কারণ এটা particle গোনা (counting)
- Mass Number কে element symbol-এর উপরে বাম পাশে লেখা হয়: ${}^{A}_{Z}X$ (যেমন ¹²₆C)
- Electron-এর mass এত কম (প্রায় negligible) যে Mass number-এ electron যোগ করা হয় না
- একই element-এর ভিন্ন mass number থাকা পরমাণুদের **Isotope** বলে (Z same, A different, কারণ neutron সংখ্যা আলাদা)

**উদাহরণ:** Carbon-এর Z=6। যদি একটা Carbon isotope-এ 6টা neutron থাকে, তাহলে A = 6+6 = 12 (Carbon-12)। যদি 8টা neutron থাকে, A = 6+8 = 14 (Carbon-14)।

---

## 6. Subatomic Particles — Definitions

| Particle | Charge | Mass (approx.) | অবস্থান | আবিষ্কারক |
|---|---|---|---|---|
| **Electron (e⁻)** | −1 (negative) | 9.1×10⁻³¹ kg (প্রায় ১/১৮৩৬ গুণ proton mass) | Nucleus-এর বাইরে, orbital/shell-এ ঘোরে | J.J. Thomson (1897) |
| **Proton (p⁺)** | +1 (positive) | 1.673×10⁻²⁷ kg | Nucleus-এর ভিতরে | Ernest Rutherford (1917) |
| **Neutron (n)** | 0 (neutral, কোনো charge নেই) | 1.675×10⁻²⁷ kg (proton থেকে সামান্য বেশি) | Nucleus-এর ভিতরে | James Chadwick (1932) |

**সংক্ষিপ্ত সংজ্ঞা:**
- **Electron:** ঋণাত্মক আধানযুক্ত (negatively charged) একটি হালকা subatomic particle, যা nucleus-এর চারপাশে নির্দিষ্ট শক্তিস্তরে (energy level) আবর্তন করে।
- **Proton:** ধনাত্মক আধানযুক্ত (positively charged) subatomic particle যা nucleus-এর মধ্যে অবস্থান করে; একটি মৌলের atomic number নির্ধারণ করে।
- **Neutron:** নিরপেক্ষ (neutral, no charge) subatomic particle যা nucleus-এ প্রোটনের সাথে একত্রে থাকে এবং nucleus-কে stability দেয়।

**মনে রাখার পয়েন্ট:**
- Proton সংখ্যা = Atomic Number (Z), যেটা element identity ঠিক করে
- একটা neutral atom-এ proton সংখ্যা = electron সংখ্যা (তাই মোট charge শূন্য)
- Nucleus এ proton ও neutron থাকে বলে এদের একসাথে **Nucleons** বলা হয়

---

## 7. Bohr Model Theory — চারটি Assumptions (Postulates)

Niels Bohr ১৯১৩ সালে hydrogen atom-এর জন্য এই মডেল প্রস্তাব করেন। এর ৪টি মূল assumption:

### 1️⃣ Fixed/Stationary Orbits (Quantized Orbits)
ইলেকট্রন নির্দিষ্ট কিছু নির্দিষ্ট শক্তির (fixed energy) বৃত্তাকার কক্ষপথে (circular orbit) nucleus-কে ঘিরে ঘোরে, যেগুলোকে **stationary states বা shells** (K, L, M, N... অথবা n=1,2,3...) বলা হয়। এই orbit গুলোতে থাকা অবস্থায় ইলেকট্রন কোনো শক্তি বিকিরণ (radiate) করে না।

### 2️⃣ Angular Momentum Quantization
ইলেকট্রনের angular momentum শুধুমাত্র $\frac{h}{2\pi}$ এর পূর্ণসংখ্যা গুণিতক হতে পারে:
$$mvr = \frac{nh}{2\pi}$$
যেখানে n = 1, 2, 3... (positive integer, principal quantum number)

### 3️⃣ Energy Absorption/Emission (Electron Transition)
ইলেকট্রন যখন একটা নির্দিষ্ট শক্তিস্তর (orbit) থেকে অন্য একটা শক্তিস্তরে লাফ (jump/transition) দেয়, তখনই শুধু শক্তি শোষণ (absorb) বা বিকিরণ (emit) করে — এই শক্তি একটা photon আকারে নির্গত/শোষিত হয়:
$$\Delta E = E_2 - E_1 = h\nu$$
নিচু level থেকে উঁচু level এ গেলে শক্তি শোষণ হয়, আর উঁচু থেকে নিচুতে নামলে শক্তি নির্গত হয়।

### 4️⃣ Stable Orbits (No Continuous Energy Loss)
ইলেকট্রন যতক্ষণ একটা নির্দিষ্ট orbit-এ থাকে, ততক্ষণ কোনো শক্তি হারায় না বা বিকিরণ করে না, যদিও classical physics অনুযায়ী ত্বরিত (accelerating) charged particle-এর ক্রমাগত শক্তি হারানোর কথা। Bohr এই ধারণাকে বাতিল করে বলেন যে এই orbit-গুলোয় ইলেকট্রন থাকা অবস্থায় stable।

**সংক্ষেপে মনে রাখার Trick:** **"F-A-T-S"**
- **F**ixed orbits (stationary states)
- **A**ngular momentum quantized
- **T**ransition releases/absorbs energy (photon)
- **S**table orbit, no continuous radiation

---

## 8. Quantization of Energy — Definition

**Definition:** Quantization of energy বলতে বোঝায় যে, পরমাণুর মধ্যে ইলেকট্রনের শক্তি (energy) যেকোনো মান নিতে পারে না — বরং শুধুমাত্র নির্দিষ্ট, বিচ্ছিন্ন (discrete) কিছু মান (energy levels) নিতে পারে। এই নির্দিষ্ট শক্তিস্তরগুলোর মাঝামাঝি কোনো মান সম্ভব না।

**সহজ ভাষায়:** শক্তি একটা continuous (অবিচ্ছিন্ন) রাশি না, বরং ছোট ছোট "প্যাকেট" বা **quanta** আকারে থাকে। প্রতিটা quantum-এর নির্দিষ্ট পরিমাণ শক্তি থাকে, এবং এই শক্তি শুধুমাত্র পূর্ণসংখ্যা গুণিতক (integral multiples) আকারে শোষিত বা বিকিরিত হতে পারে।

**Formula (Planck's relation, quantization এর ভিত্তি):**
$$E = nh\nu$$
যেখানে n = 1, 2, 3... (quantum number), h = Planck's constant, ν = frequency

**গুরুত্ব:** Max Planck সর্বপ্রথম black-body radiation ব্যাখ্যা করতে এই ধারণা আনেন, এবং পরে Bohr এটা ব্যবহার করে hydrogen atom-এর electron energy levels ব্যাখ্যা করেন। Quantization of energy-ই quantum mechanics-এর ভিত্তি (foundation)।

---

## Quick Formula Sheet (শেষ মুহূর্তের রিভিশনের জন্য)

| বিষয় | Formula |
|---|---|
| Angular momentum (Bohr) | $mvr = \dfrac{nh}{2\pi}$ |
| Energy quantization | $E = nh\nu$ |
| Heisenberg | $\Delta x \cdot \Delta p \geq \dfrac{h}{4\pi}$ |
| De Broglie | $\lambda = \dfrac{h}{mv}$ |
| Rydberg | $\dfrac{1}{\lambda} = R_H\left(\dfrac{1}{n_1^2}-\dfrac{1}{n_2^2}\right)$ |
| Mass Number | $A = Z + n$ |
| Quantum number check | $l < n$ এবং $-l \leq m \leq +l$ |

**Best of luck for your quiz! 🍀**

