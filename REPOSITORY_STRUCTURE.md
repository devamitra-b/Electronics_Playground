# Repository Structure Guide

This document explains the recommended organization and structure for the Electronics Playground repository.

---

## 📁 Overall Structure

```
Electronics_Playground/
├── 📄 README.md                          # Main project documentation
├── 📄 CONTRIBUTING.md                    # Contribution guidelines
├── 📄 REPOSITORY_STRUCTURE.md            # This file
├── 📄 LICENSE                            # MIT License
├── 📄 .gitignore                         # Git ignore rules
│
├── 📁 01-electrical-fundamentals/
│   ├── README.md
│   ├── basic-quantities.md
│   ├── ohms-law.md
│   ├── power-energy.md
│   ├── examples/
│   │   ├── circuit-examples.md
│   │   └── calculations.md
│   └── resources/
│       └── reference-materials.md
│
├── 📁 02-electronics-fundamentals/
│   ├── README.md
│   ├── semiconductors.md
│   ├── diodes.md
│   ├── transistors.md
│   ├── basic-components.md
│   ├── examples/
│   │   ├── diode-circuits.md
│   │   └── transistor-applications.md
│   └── resources/
│       └── component-datasheets.md
│
├── 📁 03-number-systems/
│   ├── README.md
│   ├── binary-system.md
│   ├── octal-system.md
│   ├── hexadecimal-system.md
│   ├── conversions.md
│   ├── arithmetic-operations.md
│   ├── examples/
│   │   ├── conversion-examples.md
│   │   └── practice-problems.md
│   └── resources/
│       └── number-system-tables.md
│
├── 📁 04-digital-electronics/
│   ├── README.md
│   ├── logic-gates.md
│   ├── boolean-algebra.md
│   ├── combinational-circuits.md
│   ├── sequential-circuits.md
│   ├── flip-flops.md
│   ├── counters-registers.md
│   ├── examples/
│   │   ├── gate-circuits.md
│   │   ├── adders-subtractors.md
│   │   └── state-machines.md
│   ├── simulations/
│   │   ├── logic-gate-sim.cir
│   │   └── counter-sim.cir
│   └── resources/
│       └── digital-logic-reference.md
│
├── 📁 resources/
│   ├── README.md
│   ├── reference-materials/
│   │   ├── formulas.md
│   │   ├── constants.md
│   │   └── tables.md
│   ├── study-guides/
│   │   ├── quick-reference.md
│   │   ├── glossary.md
│   │   └── key-concepts.md
│   └── external-links.md
│
├── 📁 projects/
│   ├── README.md
│   ├── 01-led-circuit/
│   │   ├── README.md
│   │   ├── circuit-diagram.md
│   │   ├── components-list.md
│   │   ├── simulation-files/
│   │   └── results/
│   │
│   └── 02-counter-circuit/
│       ├── README.md
│       ├── circuit-diagram.md
│       ├── components-list.md
│       ├── simulation-files/
│       └── results/
│
└── 📁 assets/
    ├── diagrams/
    ├── images/
    ├── charts/
    └── graphs/
```

---

## 📚 Section Descriptions

### 1️⃣ Electrical Fundamentals (`01-electrical-fundamentals/`)

**Purpose**: Foundation of electrical concepts

**Contains**:
- Basic electrical quantities (V, I, R)
- Ohm's Law applications
- Power and energy calculations
- Circuit analysis fundamentals
- Series and parallel circuits

**File Types**: `.md` (Markdown documentation), `.png` (diagrams)

### 2️⃣ Electronics Fundamentals (`02-electronics-fundamentals/`)

**Purpose**: Understanding electronic components

**Contains**:
- Semiconductor theory
- Diode characteristics and applications
- Transistor operation (BJT, FET)
- Other electronic components
- Practical applications

**File Types**: `.md`, `.png` (circuit diagrams)

### 3️⃣ Number Systems (`03-number-systems/`)

**Purpose**: Digital representation and calculations

**Contains**:
- Binary number system
- Octal number system
- Hexadecimal number system
- Conversions between systems
- Arithmetic operations
- BCD and other codes

**File Types**: `.md`, `.py` (conversion scripts)

### 4️⃣ Digital Electronics (`04-digital-electronics/`)

**Purpose**: Digital circuits and logic design

**Contains**:
- Logic gates and truth tables
- Boolean algebra and theorems
- Combinational logic circuits
- Sequential logic circuits
- Flip-flops and state machines
- Counters and registers

**File Types**: `.md`, `.cir` (SPICE files), `.png` (diagrams)

---

## 📄 File Naming Conventions

### Markdown Files
```
✅ Good:
- binary-system.md
- logic-gates-introduction.md
- conversion-examples.md

❌ Avoid:
- Binary System.md (no spaces)
- LogicGates.md (use kebab-case)
- binarySystem.md (use kebab-case)
```

### Folders
```
✅ Good:
- 01-electrical-fundamentals/
- logic-gates/
- examples/

❌ Avoid:
- Electrical Fundamentals (use kebab-case)
- misc (be specific)
```

---

## 📝 Best Practices

1. **Use consistent naming** across all files
2. **Keep folder structure flat** (avoid deep nesting)
3. **Use descriptive names** that explain content
4. **Organize by topic**, not by document type
5. **Keep related content together**
6. **Use README.md** in each major folder
7. **Link between related content** using relative paths
8. **Update main README** when adding new sections
9. **Document your structure** in this file

---

## 🔗 Cross-References

Use relative links in markdown:
```markdown
[Link to topic](../01-electrical-fundamentals/basic-quantities.md)
[Link to resource](../resources/formulas.md#ohms-law)
```

---

**Last Updated**: June 12, 2026  
**Maintainer**: Devamitra B
