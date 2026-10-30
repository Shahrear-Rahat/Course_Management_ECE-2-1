*(start)* | [🏠 Index](00-index.md) | [concise analysis ➡](Digital_Techniques_concise_analysis.md)

---

# 📊 ECE 2111 — Digital Techniques — Semester Final Question Analysis Report
### Department of Electrical & Computer Engineering | RUET
**Data Source:** 7 Previous Year Papers (2017, 2018, 2019, 2020, 2021, 2022, 2024) + 5 Class Tests

> **Source note:** The supplied PDF contains the 2017–2022 semester papers and CT-01–CT-05. The supplied screenshots add the complete 2024 semester paper: the first screenshot is the continuation containing Q6–Q8, while the second screenshot contains Q1–Q5. No 2023 semester paper was supplied.

---

## Section 1: Exam Format & Meta-analysis

| Year | Full Marks | Sections | Qs per Section | Answer | Time |
|------|-----------:|----------|---------------|--------|------|
| 2017 | 72 | A + B | 4 each | Any 6; 3 from each | 3 hrs |
| 2018 | 72 | A + B | 4 each | Any 6; 3 from each | 3 hrs |
| 2019 | 72 | A + B | 4 each | Any 6; 3 from each | 3 hrs |
| 2020 | 72 | A + B | 4 each | Any 6; 3 from each | 3 hrs |
| 2021 | 72 | A + B | 4 each | Any 6; 3 from each | 3 hrs |
| 2022 | 60 | A + B | 4 each | Any 6; 3 from each | 3 hrs |
| 2024 | 60 | A + B | 4 each | Any 6; 3 from each | 3 hrs |

> [!IMPORTANT]
> The supplied papers show a change from **72 marks to 60 marks** by 2022. The two-section, eight-question structure remains, with students selecting three questions from each section.

**Key observations:**
- The exam consistently uses **Section A + Section B**.
- Section A is dominated by Boolean algebra, codes, combinational circuits and basic digital design.
- Section B is dominated by flip-flops, counters, registers and sequential circuits.
- The 2024 paper continues the same structure and explicitly includes newer sequential topics such as vending-machine Moore design, asynchronous sequential design and hazards.

---

## Section 2: Raw Question-to-Topic Mapping

Every visible question from the supplied papers is grouped by its main Digital Techniques topic.

**Chapter Key:** NUM = Number Systems & Codes | BOOL = Boolean Algebra & Logic Gates | COMB = Combinational Logic | FF = Flip-Flops & Sequential Logic | CNT = Counters | REG = Registers | PLD/MEM = PLD & Memory | FSM = State Machines | TIM = Timing/Logic Families/Hazards

### 2017

| Q# | Topic Summary | Chapter |
|----|---------------|---------|
| 1a | Prove SOP = POS for a Boolean function | BOOL |
| 1b | Full adder using 3-to-8 decoder | COMB |
| 1c | S-R flip-flop as switch debouncer | FF |
| 2a | Implement Boolean function using XOR/AND gates | BOOL |
| 2b | NAND and XOR output waveform | BOOL/TIM |
| 2c | Decimal-to-BCD priority encoder | COMB |
| 3a | Logic function using two 4×1 MUX and one 2×1 MUX | COMB |
| 3b | Determine function of a circuit using three 2×1 MUXs | COMB |
| 4a | Build 1-of-32 decoder using 74LS138 ICs | COMB |
| 4b | Quine-McCluskey minimization | BOOL |
| 5a | Johnson vs ring counter; design MOD-12 ripple-up counter | CNT |
| 5b | Counter operation with/without reset using same logic | CNT |
| 6a | Excitation tables of S-R, J-K and D flip-flops | FF |
| 6b | D flip-flop as divide-by-2 counter | FF/CNT |
| 6c | Timing diagram of a flip-flop/counter circuit | TIM |
| 7a | Address/Data/Control bus connection | PLD/MEM |
| 7b | EPROM vs EEPROM | PLD/MEM |
| 7c | PLA implementation | PLD/MEM |
| 7d | Mealy vs Moore machine | FSM |
| 8a | Sequential circuit using J-K flip-flops | FF/FSM |
| 8b | State table/state diagram and state-machine design | FSM |
| 8c | Memory organization: 8K × 16-bit words | PLD/MEM |

### 2018

| Q# | Topic Summary | Chapter |
|----|---------------|---------|
| 1 | Importance of digital techniques; number-system/code conversion; universal gates | NUM/BOOL |
| 2a | De Morgan's theorem | BOOL |
| 2b | Canonical/standard Boolean form and minimization | BOOL |
| 2c | K-map with don't-care condition | BOOL |
| 3a | Priority encoder | COMB |
| 3b | MUX as logic-function generator | COMB |
| 3c | 16×1 MUX using 8×1 MUXs | COMB |
| 4a | 2's-complement adder-subtractor | COMB/NUM |
| 4b | Quine-McCluskey minimization | BOOL |
| 4c | Expand Boolean expression to minterms/maxterms | BOOL |
| 5a | Combinational vs sequential circuit | FF |
| 5b | S-R flip-flop as switch debouncer | FF |
| 5c | Johnson MOD-6 ring counter | CNT |
| 6a | Characteristic equation of J-K flip-flop | FF |
| 6b | Timing diagram and state counts | FF/CNT |
| 6c | Pulse-train generator | TIM |
| 7a | Sequential circuit using J-K flip-flops | FF |
| 7b | PLA implementation | PLD/MEM |
| 7c | J-K to D flip-flop conversion | FF |
| 8a | State-machine design | FSM |
| 8b | Synchronous counter for a specified sequence | CNT |
| 8c | EPROM vs EEPROM | PLD/MEM |

### 2019

| Q# | Topic Summary | Chapter |
|----|---------------|---------|
| 1 | Number systems, weighted/non-weighted codes, 2's-complement subtraction | NUM |
| 2 | 10's complement, BCD/Gray/Excess-3/weighted-code conversion, Boolean identity | NUM/BOOL |
| 3a | Boolean simplification | BOOL |
| 3b | Logic circuit for a specified numerical range | COMB |
| 3c | Output waveform from input waveform | TIM |
| 4a | K-map simplification | BOOL |
| 4b | Full adder using two half adders + OR | COMB |
| 4c | Don't-care condition and race condition | BOOL/TIM |
| 5a | Latch vs flip-flop | FF |
| 5b | R-S latch using NOR gates | FF |
| 5c | 4-bit parallel-in/serial-out shift register | REG |
| 5d | Types of clocking | TIM |
| 6a | Counter vs register | REG/CNT |
| 6b | Left shift register with control input | REG |
| 6c | Advantages of synchronous counter; specified sequence | CNT |
| 7a | PLA vs PAL | PLD/MEM |
| 7b | Propagation delay in asynchronous counter | TIM/CNT |
| 7c | Counter for specified sequence | CNT |
| 8a | Ripple counter | CNT |
| 8b | MOD-8 binary counter using J-K flip-flops | CNT/FF |
| 8c | J-K flip-flop using D flip-flop | FF |

### 2020

| Q# | Topic Summary | Chapter |
|----|---------------|---------|
| 1a | Why digital techniques when real world is analog | NUM/BOOL |
| 1b | Binary codes: classification and advantages | NUM |
| 1c | Binary, octal and hexadecimal numbers for 0–15 | NUM |
| 2a | Encoder disadvantage and priority encoder | COMB |
| 2b | De Morgan's theorem | BOOL |
| 2c | 4-bit adder-subtractor | COMB |
| 3a | Boolean minimization | BOOL |
| 3b | MUX tree; 16×1 MUX using 8×1 MUX | COMB |
| 3c | 3×8 decoder usable for full-adder circuit | COMB |
| 4a | Boolean expression minimization | BOOL |
| 4b | POS/SOP | BOOL |
| 4c | Standard SOP conversion and K-map | BOOL |
| 5a | Basic-gate realization of Boolean expression | BOOL |
| 5b | POS and SOP | BOOL |
| 5c | K-map simplification | BOOL |
| 6a | J-K flip-flop and race-around condition | FF |
| 6b | 1:8 demultiplexer using 1:4 demultiplexers | COMB |
| 6c | Transparent latch | FF |
| 7a | Broadside loading in shift register | REG |
| 7b | Counter for 0,1,3,6,7 sequence | CNT |
| 7c | PLD; PLA vs PAL | PLD/MEM |
| 8a | Sequence detector for 3 or more consecutive 1s | FSM |
| 8b | Virtual memory and cache memory | PLD/MEM |
| 8c | MOD-10 counter | CNT |

### 2021

| Q# | Topic Summary | Chapter |
|----|---------------|---------|
| 1a | Universal-gate implementation | BOOL |
| 1b | Lift controller using basic logic gates | COMB |
| 1c | Simplify a logic circuit | BOOL |
| 2a | Boolean identity proof | BOOL |
| 2b | K-map: SOP and POS simplification | BOOL |
| 2c | Real-life MUX-DEMUX application | COMB |
| 3a | CMOS logic design for a copy-machine control system | COMB |
| 3b | 3-bit number to its square | COMB |
| 3c | De Morgan's theorem | BOOL |
| 4a | Decoder and decoder-to-demultiplexer conversion | COMB |
| 4b | 3-bit adder-subtractor | COMB |
| 4c | Boolean function realization using MUX | COMB |
| 5a | Switch debouncer | FF |
| 5b | 4-bit magnitude/equality comparator | COMB |
| 6a | J-K flip-flop and race-around condition | FF |
| 6b | Divide frequency by two using flip-flop; timing diagram | FF/TIM |
| 6c | Timing diagram of a flip-flop circuit | TIM |
| 7a | Counter for specified sequence with unused states | CNT |
| 7b | 4-bit up-down counter using T flip-flops | CNT |
| 7c | Characteristic equation of J-K flip-flop | FF |
| 8a | Fan-in, fan-out, propagation delay, noise immunity | TIM |
| 8b | MOD-12 counter | CNT |
| 8c | TTL vs CMOS | TIM |

### 2022

| Q# | Topic Summary | Chapter |
|----|---------------|---------|
| 1a | Difference between digital and analog electronics | BOOL |
| 1b | Why binary and hexadecimal are used in computers | NUM |
| 1c | 4-bit subtraction using 2's complement | NUM/COMB |
| 2a | BCD code vs Gray code | NUM |
| 2b | Boolean minimization | BOOL |
| 2c | K-map with don't-care conditions | BOOL |
| 3a | Multiplexer and working principle | COMB |
| 3b | 8×1 MUX using 4×1 MUXs | COMB |
| 3c | Adder-subtractor circuit | COMB |
| 4a | Priority encoder and its advantage | COMB |
| 4b | 8×3 priority encoder | COMB |
| 4c | Decoder as binary adder | COMB |
| 5a | Flip-flop vs latch; D and J-K timing/truth tables | FF |
| 5b | Shift-and-buffer register | REG |
| 6a | Register-to-register data transfer | REG |
| 6b | Serial adder using sequential logic | REG/FF |
| 6c | Binary counter and binary ripple counter | CNT |
| 7a | MOD-10 counter | CNT |
| 7b | Up-down counter | CNT |
| 7c | 4-bit ALU block diagram | COMB |
| 8a | Universal gates and IC design | BOOL |
| 8b | Logic-gate properties: fan-in, fan-out, propagation delay | TIM |

### 2024

| Q# | Topic Summary | Chapter |
|----|---------------|---------|
| 1a | Analog, digital and discrete signals | NUM |
| 1b | Digital-techniques-based room-heater temperature-control block diagram | COMB |
| 1c | Binary vs BCD for digital clock; 4-bit adder design | NUM/COMB |
| 2a | Why K-map is preferred; limitations | BOOL |
| 2b | Simplified SOP expression from given functions and don't-cares | BOOL |
| 2c | Prove SOP = POS for a 2-input OR gate | BOOL |
| 3a | Full adder used as adder and subtractor | COMB |
| 3b | Boolean expression reduced to specified number of literals | BOOL |
| 3c | Verify a circuit as exclusive-NOR | BOOL |
| 4a | Sequential logic; MOD-8 ripple-down counter | CNT |
| 4b | Boolean function using Type-2 multiplexer | COMB |
| 4c | 4×16 decoder using 2×4 decoders | COMB |
| 5a | Sequential circuit; types of state machine | FSM |
| 5b | 4-bit asynchronous down counter, 15 to 03, using D flip-flops | CNT/FF |
| 5c | Dynamic and static hazards | TIM |
| 6a | D flip-flop used as toggle | FF |
| 6b | Synchronous counter for specified sequence using T flip-flops | CNT |
| 6c | Difference between combinational and sequential circuit | FF |
| 7a | Moore vending machine: price Tk 15, accepts Tk 5/Tk 10, returns extra money | FSM |
| 7b | Sequential circuit using D flip-flops from given state table | FF/FSM |
| 8a | PLA implementation of two Boolean functions | PLD/MEM |
| 8b | Steps for designing an asynchronous sequential circuit | FSM |
| 8c | J-K flip-flop operation and excitation table | FF |

---

## Section 3: Chapter Frequency Heatmap

### 3.1 Appearance by Year

| # | Chapter | '17 | '18 | '19 | '20 | '21 | '22 | '24 | Count | Rate |
|---|---------|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:-----:|:----:|
| 1 | **Boolean Algebra & K-map** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | **7/7** | 🔴 100% |
| 2 | **Combinational Logic** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | **7/7** | 🔴 100% |
| 3 | **Sequential Logic & Flip-Flops** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | **7/7** | 🔴 100% |
| 4 | **Counters** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | **7/7** | 🔴 100% |
| 5 | **Registers & Shift Registers** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | **7/7** | 🔴 100% |
| 6 | **Number Systems & Codes** | — | ✅ | ✅ | ✅ | — | ✅ | ✅ | **5/7** | 🟠 71% |
| 7 | **PLD & Memory** | ✅ | ✅ | ✅ | ✅ | ✅ | — | — | **5/7** | 🟠 71% |
| 8 | **FSM / State Machines** | ✅ | ✅ | — | ✅ | — | — | ✅ | **4/7** | 🟡 57% |
| 9 | **Logic Families / Timing / Hazards** | — | — | ✅ | — | ✅ | ✅ | ✅ | **4/7** | 🟡 57% |

> [!NOTE]
> The chapter count treats a chapter as present if at least one sub-question in that paper belongs to it. Therefore a chapter may have a 100% appearance rate even when its marks vary considerably from year to year.

### 3.2 Relative Marks Pattern

The strongest recurring mark concentration is in:
1. **Sequential logic + counters**
2. **Combinational logic**
3. **Boolean algebra/K-map**
4. **Registers**
5. **Number systems/codes and PLD topics**

Because several scanned papers have uneven or partially unclear margin marks, the analysis emphasizes **appearance frequency and repeated question types** rather than pretending that uncertain mark totals are exact.

---

## Section 4: Chapter Deep-Dives

### 4.1 🔴 Boolean Algebra & K-map (7/7)

| Sub-topic | Count | Years |
|-----------|:-----:|-------|
| Boolean simplification/minimization | 7 | '17, '18, '19, '20, '21, '22, '24 |
| K-map simplification | 6 | '18, '19, '20, '21, '22, '24 |
| De Morgan's theorem | 4 | '18, '20, '21, '24 |
| SOP/POS and canonical forms | 4 | '17, '18, '20, '24 |
| Universal gates | 4 | '18, '20, '21, '22 |
| Quine-McCluskey method | 3 | '17, '18, '19 |

> [!IMPORTANT]
> **Absolute must-prepare (Boolean):**
> 1. K-map with don't-care conditions
> 2. Boolean algebra simplification
> 3. SOP/POS and canonical/standard forms
> 4. De Morgan's theorems
> 5. Quine-McCluskey minimization
> 6. NAND/NOR as universal gates

### 4.2 🔴 Combinational Logic (7/7)

| Sub-topic | Count | Years |
|-----------|:-----:|-------|
| Multiplexer / MUX-tree / MUX-based realization | 7 | '17–'22, '24 |
| Adder/subtractor/adder-subtractor | 7 | '17–'22, '24 |
| Decoder design/application | 6 | '17, '18, '20, '21, '22, '24 |
| Priority encoder | 5 | '17, '18, '20, '22, '24 |
| Full adder design | 5 | '17, '18, '19, '20, '24 |
| Demultiplexer | 2 | '20, '21 |
| Comparator | 1 | '21 |
| ALU block | 1 | '22 |

> [!IMPORTANT]
> **Absolute must-prepare (Combinational):**
> 1. MUX as a logic-function generator
> 2. 4×1/8×1/16×1 MUX construction
> 3. Full adder and full adder/subtractor
> 4. Decoder construction and decoder applications
> 5. Priority encoder and decimal-to-BCD encoder
> 6. MUX/decoder-based implementation of Boolean functions

### 4.3 🔴 Sequential Logic & Flip-Flops (7/7)

| Sub-topic | Count | Years |
|-----------|:-----:|-------|
| J-K flip-flop | 7 | '17–'22, '24 |
| Flip-flop excitation/characteristic tables | 5 | '17, '18, '19, '21, '22, '24 |
| D/T/J-K conversion or application | 5 | '17, '18, '19, '21, '24 |
| Switch debouncer | 3 | '17, '18, '21 |
| Race-around condition | 3 | '19, '20, '21 |
| Timing diagrams | 5 | '17, '18, '19, '21, '22 |
| Latch vs flip-flop | 2 | '19, '22 |

> [!IMPORTANT]
> **Absolute must-prepare (Flip-Flops):**
> 1. J-K operation, characteristic equation and excitation table
> 2. S-R, J-K, D and T excitation tables
> 3. Race-around condition and its removal
> 4. D ↔ J-K/T conversions
> 5. Timing-diagram problems
> 6. Switch debouncer

### 4.4 🔴 Counters (7/7)

| Sub-topic | Count | Years |
|-----------|:-----:|-------|
| General counter design / specified sequence | 7 | '17–'22, '24 |
| MOD counter | 5 | '17, '18, '19, '20, '21, '22, '24 |
| Ripple/asynchronous counter | 5 | '17, '19, '20, '22, '24 |
| Synchronous counter | 3 | '18, '19, '24 |
| Up/down counter | 2 | '21, '22 |
| Johnson/ring counter | 2 | '17, '18 |
| Counter propagation delay | 1 | '19 |

> [!IMPORTANT]
> **Absolute must-prepare (Counters):**
> 1. MOD-8, MOD-10 and MOD-12
> 2. Arbitrary sequence counters
> 3. Synchronous vs asynchronous/ripple counters
> 4. Up-down counters
> 5. J-K/T/D flip-flop based counter design
> 6. State table/state diagram for unused states

### 4.5 🟠 Registers & Shift Registers (6/7)

| Sub-topic | Count | Years |
|-----------|:-----:|-------|
| Shift-register design/operation | 6 | '18, '19, '20, '21, '22 |
| Parallel/serial registers | 3 | '19, '20, '22 |
| Buffer/shift register | 2 | '22 |
| Register-to-register transfer | 1 | '22 |
| Broadside loading | 1 | '20 |
| Control-input shift register | 1 | '19 |

> [!IMPORTANT]
> **Must-prepare (Registers):**
> 1. SISO, SIPO, PISO and PIPO concepts
> 2. Parallel-in/serial-out design
> 3. Shift-and-buffer register
> 4. Register-to-register transfer
> 5. Broadside loading
> 6. Control-input shift register

### 4.6 🟠 Number Systems & Codes (5/7)

| Sub-topic | Count | Years |
|-----------|:-----:|-------|
| Number-system conversion | 4 | '18, '19, '20, '24 |
| 2's-complement arithmetic | 4 | '17, '18, '19, '22 |
| BCD / Gray / Excess-3 / weighted codes | 4 | '18, '19, '20, '22, '24 |
| Why binary/hexadecimal are used | 2 | '19, '22 |
| Analog/digital/discrete signals | 1 | '24 |

> [!IMPORTANT]
> **Must-prepare (Codes):**
> 1. Binary, octal, decimal and hexadecimal conversion
> 2. BCD, Gray and Excess-3
> 3. Weighted vs non-weighted codes
> 4. 2's-complement addition/subtraction
> 5. 10's complement
> 6. Number representation in digital systems

### 4.7 🟠 PLD & Memory (5/7)

| Sub-topic | Count | Years |
|-----------|:-----:|-------|
| PLA/PAL | 5 | '17, '18, '19, '20, '21 |
| Memory organization | 2 | '17, '20 |
| EPROM vs EEPROM | 2 | '17, '18 |
| Address/Data/Control bus | 1 | '17 |
| Cache/virtual memory | 1 | '20 |

> [!IMPORTANT]
> **Must-prepare (PLD/Memory):**
> 1. PLA implementation
> 2. PLA vs PAL
> 3. Basic memory organization and address lines
> 4. EPROM vs EEPROM
> 5. Address, data and control bus
> 6. Cache and virtual memory basics

### 4.8 🟡 FSM / State Machines (4/7)

| Sub-topic | Count | Years |
|-----------|:-----:|-------|
| State-machine design/state diagram | 4 | '17, '18, '20, '24 |
| Mealy vs Moore | 3 | '17, '18, '24 |
| Sequence detector | 1 | '20 |
| Moore vending machine | 1 | '24 |
| Asynchronous sequential design steps | 1 | '24 |

> [!IMPORTANT]
> **Must-prepare (FSM):**
> 1. State table and state diagram
> 2. Mealy vs Moore
> 3. Moore-machine design
> 4. Sequence detector
> 5. Basic asynchronous sequential-circuit design steps

---

## Section 5: 🏆 Golden Questions Master List (Appeared 3+ Times)

These are the strongest repeated patterns in the supplied papers.

| Rank | Question / Topic | Count | Chapter |
|:----:|------------------|:-----:|---------|
| 1 | Design a counter for a given sequence / MOD counter | **7** | Counters |
| 2 | J-K flip-flop operation / excitation / characteristic equation | **7** | Flip-Flops |
| 3 | Simplify/minimize Boolean expression | **7** | Boolean |
| 4 | Implement Boolean function using MUX | **7** | Combinational |
| 5 | Design adder/subtractor/adder-subtractor | **7** | Combinational |
| 6 | K-map simplification | **6** | Boolean |
| 7 | Decoder design/application | **6** | Combinational |
| 8 | Shift-register/register design | **6** | Registers |
| 9 | Priority encoder | **5** | Combinational |
| 10 | PLA/PAL | **5** | PLD |
| 11 | Number/code conversion | **5** | Codes |
| 12 | 2's-complement arithmetic | **4** | Codes |
| 13 | De Morgan's theorem | **4** | Boolean |
| 14 | Universal gates | **4** | Boolean |
| 15 | Full adder design | **5** | Combinational |
| 16 | Ripple/MOD counter | **5** | Counters |
| 17 | Timing-diagram problems | **5** | Sequential |
| 18 | State-machine/state-diagram design | **4** | FSM |
| 19 | J-K/D/T flip-flop conversion/application | **5** | Flip-Flops |
| 20 | Mealy vs Moore | **3** | FSM |
| 21 | Switch debouncer | **3** | Flip-Flops |
| 22 | Race-around condition | **3** | Flip-Flops |
| 23 | Quine-McCluskey | **3** | Boolean |
| 24 | EPROM vs EEPROM | **2** | Memory |
| 25 | Fan-in/fan-out/propagation delay | **2+** | Timing |

> [!TIP]
> If you prepare the first **15–20 items** thoroughly, you cover the dominant recurring patterns across the supplied semester papers.

---

## Section 6: 📈 Year-over-Year Trend Analysis

### 6.1 Rising Topics

| Topic | Status | Evidence |
|-------|--------|----------|
| **Moore vending-machine design** | 🆕 New in supplied latest paper | 2024 Q7 asks for a Moore vending machine with Tk 5/Tk 10 inputs, Tk 15 price and change return. |
| **Static & dynamic hazards** | 🆕 New in supplied latest paper | 2024 Q5(c) explicitly asks both. |
| **Asynchronous sequential-circuit design** | 📈 Rising | 2024 asks for design steps; 2024 also includes an asynchronous D-FF counter. |
| **Type-2 MUX implementation** | 📈 Repeated design style | MUX-based Boolean realization continues into 2024. |
| **4×16 decoder from 2×4 decoders** | 📈 Latest combinational design | 2024 Q4(c) uses hierarchical decoder construction. |

### 6.2 Stable Topics

| Topic | Pattern |
|-------|---------|
| Counter design | Present in every supplied year |
| J-K flip-flop | Present in every supplied year |
| Boolean simplification | Present in every supplied year |
| MUX | Present in every supplied year |
| Adder/subtractor | Present in every supplied year |
| Decoder | Appears in 6 of 7 supplied years |
| Registers | Appears repeatedly from 2018 onward |
| K-map | Recurs throughout the papers |

### 6.3 Less Frequent Topics

| Topic | Status | Evidence |
|-------|--------|----------|
| EPROM vs EEPROM | 📉 Less frequent | Seen in 2017 and 2018 only. |
| Address/Data/Control bus | 📉 Rare | Explicitly seen in 2017. |
| Cache/virtual memory | 📉 Rare | Explicitly seen in 2020. |
| Pulse-train generator | 📉 Rare | Explicitly seen in 2018. |
| Detailed Mealy/Moore comparison | 📉 Intermittent | Explicitly seen in 2017, 2018 and latest 2024 state-machine context. |

### 6.4 Prediction for the Next Exam

Based only on the supplied 2017–2022 and 2024 papers:

> [!WARNING]
> **High-confidence preparation priorities:**
> 1. **Counter design** will remain extremely important.
> 2. **J-K flip-flop** questions are highly persistent.
> 3. **Boolean simplification/K-map** should be treated as compulsory.
> 4. **MUX-based function realization** is a major recurring pattern.
> 5. **Adder/subtractor and decoder design** are very strong bets.
> 6. **Registers and shift registers** deserve full preparation.
> 7. **Priority encoder and PLA** are important secondary topics.
> 8. **Hazards and asynchronous sequential design** deserve extra attention because they appear in the latest supplied paper.
> 9. **Moore/Mealy/state-machine problems** should not be skipped.
> 10. **Number systems, BCD/Gray/Excess-3 and 2's complement** remain useful scoring topics.

---

## Section 7: Marks Distribution Pattern

### 7.1 Section Placement by Chapter

| Chapter | Section A | Section B | Notes |
|---------|:---------:|:---------:|-------|
| Boolean Algebra & K-map | High | Medium | Strongly represented in Section A |
| Combinational Logic | Very High | Medium | One of the main Section-A areas |
| Flip-Flops / Sequential Logic | Medium | Very High | Strongly represented in Section B |
| Counters | Medium | Very High | One of the strongest Section-B areas |
| Registers | Low–Medium | High | Mostly Section B |
| Number Systems & Codes | High | Low | Usually Section A |
| PLD & Memory | Medium | Medium | Appears in both depending on year |
| FSM / State Machines | Medium | High | More often linked to sequential questions |
| Timing / Hazards / Logic Families | Medium | High | Usually attached to sequential/timing questions |

> [!TIP]
> **Section A safe bets:** Boolean algebra, K-map, MUX, decoder, encoder, codes, adder/subtractor.
>
> **Section B safe bets:** Flip-flops, counters, registers, state machines, timing and hazards.

### 7.2 Typical Question Style

| Topic | Typical Style |
|-------|---------------|
| Boolean/K-map | Simplify, prove, minimize, draw circuit |
| MUX/Decoder/Encoder | Design circuit or implement function |
| Flip-flops | Explain + table + timing diagram + conversion |
| Counters | State sequence + excitation equations + circuit |
| Registers | Design + operation + loading/transfer |
| FSM | State diagram/table + implementation |
| PLA | Product-term/OR-plane implementation |
| Logic families | Short conceptual comparison |

---

## Section 8: Tiered Preparation Strategy

### Tier 1 — ⚡ GUARANTEED / MUST DO

**Topics:** Boolean, K-map, MUX, Adder/Subtractor, Flip-Flops, Counters

**What to prepare — Boolean:**
- Boolean algebra identities
- De Morgan's theorem
- SOP/POS
- Canonical/standard forms
- K-map with don't-care conditions
- Quine-McCluskey
- NAND/NOR universal-gate realization

**What to prepare — Combinational:**
- Half adder/full adder
- Adder-subtractor
- 2's-complement subtractor
- 4×1, 8×1 and 16×1 MUX
- MUX as a logic-function generator
- 1-of-8 and 1-of-32 decoder
- Decoder as a function generator
- Decimal-to-BCD and priority encoder

**What to prepare — Flip-Flops:**
- S-R, J-K, D and T flip-flops
- Characteristic and excitation tables
- J-K characteristic equation
- Race-around condition
- D/T/J-K conversion
- Timing diagrams
- Switch debouncer

**What to prepare — Counters:**
- Ripple/asynchronous counter
- Synchronous counter
- MOD-8, MOD-10, MOD-12
- Up/down counter
- Johnson/ring counter
- Arbitrary sequence counter
- Unused-state handling

### Tier 2 — 🔥 VERY LIKELY

**Topics:** Registers, Encoder/Decoder, PLA/PAL

**What to prepare — Registers:**
- SISO/SIPO/PISO/PIPO
- Parallel-in/serial-out
- Shift-and-buffer register
- Broadside loading
- Register-to-register transfer

**What to prepare — PLD:**
- PLA structure and implementation
- PLA vs PAL
- EPROM vs EEPROM
- Basic memory organization

### Tier 3 — 📘 LIKELY

**Topics:** Number Systems, Codes, FSM

**What to prepare:**
- Binary/octal/decimal/hexadecimal
- BCD
- Gray code
- Excess-3
- Weighted/non-weighted codes
- 2's complement
- State table/state diagram
- Mealy vs Moore
- Sequence detector
- Moore vending machine

### Tier 4 — 📗 POSSIBLE BUT IMPORTANT

**Topics:** Timing, Logic Families, Hazards, Memory

**What to prepare:**
- Fan-in
- Fan-out
- Propagation delay
- Noise immunity
- TTL vs CMOS
- Static and dynamic hazards
- Cache/virtual memory
- Address/Data/Control bus

> [!TIP]
> **Suggested 24-hour emergency allocation:**
> - Tier 1: **14 hours**
> - Tier 2: **5 hours**
> - Tier 3: **3 hours**
> - Tier 4: **2 hours**

---

## Section 9: Class Test Questions — Supplementary Analysis

> [!NOTE]
> The supplied PDF contains five class tests. They are shorter than semester finals but are useful indicators of teacher emphasis.

### 9.1 Class Test Summary

| CT# | Main Topics | Total Marks |
|-----|-------------|:-----------:|
| CT-01 | Boolean Algebra + K-map | 20 |
| CT-02 | MUX + Priority Encoder | 20 |
| CT-03 | Flip-Flops + Decoder | 20 |
| CT-04 | D/T Flip-Flop + Counter + Register | 20 |
| CT-05 | Counter + PLA | 20 |

### 9.2 CT-01: Boolean Algebra + K-map

| Q# | Topic |
|----|-------|
| 1 | Prove Boolean identity involving A + AB |
| 2 | Simplify Boolean expression and draw logic diagram |
| 3 | K-map simplification with don't-care conditions |

**Overlap with finals:** **Very high.** Boolean simplification and K-map are among the most repeated final topics.

### 9.3 CT-02: MUX + Priority Encoder

| Q# | Topic |
|----|-------|
| 1 | Design a data-selection/communication system using appropriate logic circuits; includes Boolean-expression implementation |
| 2 | Design a 4-input priority encoder and explain its working |

**Overlap with finals:** **Very high.** MUX/selection and priority encoder appear repeatedly in the semester papers.

### 9.4 CT-03: Flip-Flops + Decoder

| Q# | Topic |
|----|-------|
| 1 | Logic diagram, truth table and timing diagram of positive-edge J-K and negative-edge T flip-flops |
| 2 | Use a decoder as a full adder |

**Overlap with finals:** **Very high.** Flip-flops, timing diagrams and decoder/full-adder design are recurring final questions.

### 9.5 CT-04: D/T Flip-Flop + Counter + Register

| Q# | Topic |
|----|-------|
| 1 | Design D flip-flop using T flip-flop |
| 2 | Counter counting 0 to 8 repeatedly using T flip-flops |
| 3 | Register usable as both buffer and shift register |

**Overlap with finals:** **Very high.** Flip-flop conversion, counters and registers are major final topics.

### 9.6 CT-05: Counter + PLA

| Q# | Topic |
|----|-------|
| 1 | Design counter for 0, 1, 3, 6, 7 repeatedly |
| 2 | Explain PLA design process with suitable example |

**Overlap with finals:** **Very high.** Arbitrary-sequence counters and PLA are both repeatedly examined.

### 9.7 Key Takeaway

| Metric | Finding |
|--------|---------|
| Total class tests | 5 |
| Total CT marks | 100 |
| Strong recurring final topics reinforced | Boolean, K-map, MUX, encoder, flip-flops, decoder, counters, registers, PLA |
| Overall signal | **Very strong** |

> [!IMPORTANT]
> The class tests provide a strong preparation signal: almost every CT is centered on a topic that also appears repeatedly in the semester-final papers.

---

## Section 10: 🎯 Final Top-10 Priority List

The final priority combines frequency, recency in the supplied 2024 paper, design importance and class-test reinforcement.

| Priority | What to Master | Frequency | Recent | CT? | Score |
|:--------:|----------------|:---------:|:------:|:---:|:-----:|
| **1** | Counter design + MOD/sequence counters | 7/7 | ✅ 2024 | ✅ CT-04/05 | ⭐⭐⭐⭐⭐ |
| **2** | J-K flip-flop + excitation/characteristic table | 7/7 | ✅ 2024 | ✅ CT-03 | ⭐⭐⭐⭐⭐ |
| **3** | Boolean simplification + K-map | 7/7 | ✅ 2024 | ✅ CT-01 | ⭐⭐⭐⭐⭐ |
| **4** | MUX-based Boolean function realization | 7/7 | ✅ 2024 | ✅ CT-02 | ⭐⭐⭐⭐⭐ |
| **5** | Adder/subtractor + full adder | 7/7 | ✅ 2024 | ✅ CT-03 | ⭐⭐⭐⭐⭐ |
| **6** | Decoder design and applications | 6/7 | ✅ 2024 | ✅ CT-03 | ⭐⭐⭐⭐ |
| **7** | Registers / shift registers | 7/7 | — | ✅ CT-04 | ⭐⭐⭐⭐ |
| **8** | Priority encoder | 5/7 | ✅ 2024 | ✅ CT-02 | ⭐⭐⭐⭐ |
| **9** | PLA / PAL | 5/7 | — | ✅ CT-05 | ⭐⭐⭐⭐ |
| **10** | Number systems, codes and 2's complement | 5/7 | ✅ 2024 | — | ⭐⭐⭐⭐ |

### Honourable Mentions

| Priority | Topic | Score |
|:--------:|-------|:-----:|
| 11 | De Morgan's theorem | ⭐⭐⭐ |
| 12 | Universal gates | ⭐⭐⭐ |
| 13 | State diagram / Mealy-Moore | ⭐⭐⭐ |
| 14 | Switch debouncer + race-around condition | ⭐⭐⭐ |
| 15 | Static/dynamic hazards + asynchronous sequential design | ⭐⭐⭐ |

> [!CAUTION]
> If you only have time for a short revision, **do not skip counters, J-K flip-flops, Boolean/K-map, MUX, adder-subtractor, decoder and registers**. These form the safest core based on the supplied papers.

---

## Final Study Order

**1. Boolean Algebra → 2. K-map → 3. MUX → 4. Decoder/Encoder → 5. Adder/Subtractor → 6. Flip-Flops → 7. Counters → 8. Registers → 9. PLA/PAL → 10. FSM → 11. Codes → 12. Hazards/Logic Families**

---

*Report generated from analysis of 7 supplied semester-final papers (2017, 2018, 2019, 2020, 2021, 2022, 2024) and 5 supplied class tests (CT-01–CT-05) for ECE 2111, Digital Techniques, Department of Electrical & Computer Engineering, RUET.*

---

*(start)* | [🏠 Index](00-index.md) | [concise analysis ➡](Digital_Techniques_concise_analysis.md)
