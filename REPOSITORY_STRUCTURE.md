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

**Structure**:
```
01-electrical-fundamentals/
├── README.md              # Section overview
├── basic-quantities.md    # Voltage, Current, Resistance
├── ohms-law.md           # Theory and applications
├── power-energy.md       # Power calculations
├── examples/
│   └── practical-examples.md
└── resources/
    └── formulas-sheet.md
```

---

### 2️⃣ Electronics Fundamentals (`02-electronics-fundamentals/`)

**Purpose**: Understanding electronic components

**Contains**:
- Semiconductor theory
- Diode characteristics and applications
- Transistor operation (BJT, FET)
- Other electronic components
- Practical applications

**File Types**: `.md`, `.png` (circuit diagrams), `.txt` (datasheets)

**Structure**:
```
02-electronics-fundamentals/
├── README.md
├── semiconductors.md      # Theory basics
├── diodes.md             # Types and applications
├── transistors.md        # BJT and FET
├── basic-components.md   # Resistors, caps, inductors
├── examples/
│   ├── diode-applications.md
│   └── transistor-circuits.md
└── resources/
    └── component-reference.md
```

---

### 3️⃣ Number Systems (`03-number-systems/`)

**Purpose**: Digital representation and calculations

**Contains**:
- Binary number system
- Octal number system
- Hexadecimal number system
- Conversions between systems
- Arithmetic operations
- BCD and other codes

**File Types**: `.md`, `.py` (conversion scripts), `.txt` (lookup tables)

**Structure**:
```
03-number-systems/
├── README.md
├── binary-system.md       # Binary theory
├── octal-system.md        # Octal number system
├── hexadecimal-system.md  # Hex number system
├── conversions.md         # Conversion methods
├── arithmetic-operations.md
├── examples/
│   ├── conversion-examples.md
│   └── arithmetic-practice.md
└── resources/
    ├── conversion-tables.md
    └── conversion-scripts.py
```

---

### 4️⃣ Digital Electronics (`04-digital-electronics/`)

**Purpose**: Digital circuits and logic design

**Contains**:
- Logic gates and truth tables
- Boolean algebra and theorems
- Combinational logic circuits
- Sequential logic circuits
- Flip-flops and state machines
- Counters and registers

**File Types**: `.md`, `.cir` (SPICE files), `.dsn` (Proteus), `.png` (diagrams)

**Structure**:
```
04-digital-electronics/
├── README.md
├── logic-gates.md              # AND, OR, NOT, etc.
├── boolean-algebra.md          # Boolean theorems
├── combinational-circuits.md   # Multiplexers, encoders
├── sequential-circuits.md      # Flip-flops
├── counters-registers.md       # Counter designs
├── examples/
│   ├── logic-implementations.md
│   ├── state-machine-design.md
│   └── counter-examples.md
├── simulations/
│   ├── logic-gate-sim.cir      # SPICE file
│   └── counter-sim.dsn         # Proteus file
└── resources/
    └── digital-logic-reference.md
```

---

### 📚 Resources (`resources/`)

**Purpose**: Shared reference materials and study guides

**Contains**:
- Formula sheets
- Constants and conversion tables
- Glossary of terms
- Quick reference guides
- Key concepts summary
- External resource links

**Structure**:
```
resources/
├── reference-materials/
│   ├── formulas.md        # All formulas
│   ├── constants.md       # Physical constants
│   └── conversion-tables.md
├── study-guides/
│   ├── quick-reference.md
│   ├── glossary.md
│   └── key-concepts.md
└── external-links.md
```

---

### 🏗️ Projects (`projects/`)

**Purpose**: Practical, hands-on circuit projects

**Contains**:
- Complete project documentation
- Circuit diagrams and schematics
- Component specifications
- Simulation files
- Results and analysis

**Structure**:
```
projects/
├── 01-led-circuit/
│   ├── README.md
│   ├── objective.md
│   ├── circuit-diagram.md
│   ├── components-list.md
│   ├── simulation-files/
│   │   ├── circuit.cir
│   │   └── circuit.dsn
│   ├── results/
│   │   └── analysis.md
│   └── lessons-learned.md
│
└── 02-counter-circuit/
    ├── README.md
    └── [similar structure]
```

---

### 🎨 Assets (`assets/`)

**Purpose**: Images, diagrams, and visual resources

**Contains**:
- Circuit diagrams (PNG, SVG)
- Graphs and charts
- Illustrations
- Screenshots

**Structure**:
```
assets/
├── diagrams/          # Circuit diagrams
│   ├── logic-gates.png
│   └── flip-flop.png
├── images/            # Photos and illustrations
├── charts/            # Data visualizations
└── graphs/            # Mathematical graphs
```

---

## 📄 File Naming Conventions

### Markdown Files
```
✅ Good:
- binary-system.md
- logic-gates-introduction.md
- conversion-examples.md
- quick-reference-guide.md

❌ Avoid:
- Binary System.md (no spaces)
- LogicGates.md (use kebab-case)
- 1-Binary.md (no leading numbers)
- binarySystem.md (use kebab-case)
```

### Folders
```
✅ Good:
- 01-electrical-fundamentals/
- logic-gates/
- examples/
- resources/

❌ Avoid:
- Electrical Fundamentals (use kebab-case)
- logicgates (not descriptive enough)
- misc (be specific)
```

### Simulation Files
```
✅ Good:
- logic-gate-sim.cir
- counter-circuit.dsn
- amplifier-test.net

❌ Avoid:
- simulation.cir (not descriptive)
- test (no extension)
```

---

## 📝 File Content Templates

### Markdown Document Template
```markdown
# Topic Title

## Overview
Brief introduction and context.

## Concepts
Main ideas and theory.

### Concept 1
Details about concept 1.

### Concept 2
Details about concept 2.

## Examples
Practical examples with explanations.

## Practice Problems
Exercises for reinforcement.

## Key Takeaways
Summary of important points.

## References
- [Reference 1](link)
- [Reference 2](link)
```

### Project README Template
```markdown
# Project Name

## Overview
What is this project about?

## Objectives
Learning goals.

## Components Required
- Component 1
- Component 2

## Circuit Diagram
[Link to diagram or embedded image]

## Step-by-Step Guide
1. Step 1
2. Step 2

## Simulation Results
[Results and analysis]

## Conclusion
Key learnings and takeaways.

## References
Links and resources used.
```

---

## 🔄 Adding New Content

### When Adding a New Topic:

1. **Create a folder** with naming format: `##-topic-name/`
2. **Add README.md** with section overview
3. **Create content files** for subtopics
4. **Add examples** in `examples/` subfolder
5. **Add resources** in `resources/` subfolder
6. **Update main README** with link to new section
7. **Update REPOSITORY_STRUCTURE.md** if needed

### When Adding a New Project:

1. **Create folder** in `projects/`: `projects/##-project-name/`
2. **Add detailed README.md**
3. **Include circuit diagrams**
4. **Add component lists**
5. **Provide simulation files**
6. **Document results**
7. **Update projects/README.md**

---

## ✅ Best Practices

1. **Use consistent naming** across all files
2. **Keep folder structure flat** (avoid deep nesting)
3. **Use descriptive names** that explain content
4. **Organize by topic**, not by document type
5. **Keep related content together**
6. **Use README.md** in each major folder
7. **Link between related content** using relative paths
8. **Update main README** when adding new sections
9. **Maintain a resources** folder for shared materials
10. **Document your structure** in this file

---

## 🔗 Cross-References

Use relative links in markdown:
```markdown
[Link to topic](../01-electrical-fundamentals/basic-quantities.md)
[Link to resource](../resources/formulas.md#ohms-law)
[Link to project](../projects/01-led-circuit/README.md)
```

---

**Last Updated**: June 12, 2026  
**Version**: 1.0  
**Maintainer**: Devamitra B
