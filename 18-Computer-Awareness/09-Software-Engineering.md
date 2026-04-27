# Software Engineering Basics

## 🔍 Why This Topic?

Software Engineering appears in **1–2 questions** every year. It covers the life cycle of building software, testing, and management concepts. Easy marks if you know the vocabulary!

---

## 📐 PART 1 — Software Development Life Cycle (SDLC)

SDLC is the **step-by-step process** used to plan, design, build, test, and deliver software.

### The 6 Phases of SDLC (Remember in Order!)

```
1. Requirement Analysis  →  What does the client want?
2. System Design         →  How will we build it? (architecture)
3. Implementation        →  Actual coding (programmers write code)
4. Testing               →  Find and fix bugs
5. Deployment            →  Release to users
6. Maintenance           →  Fix issues after release, add updates
```

> **Memory trick:** **R**ich **D**evelopers **I**nvest **T**ime **D**eveloping **M**asterpieces
> (Requirement → Design → Implementation → Testing → Deployment → Maintenance)

---

## 📐 PART 2 — SDLC Models

### 1. Waterfall Model
- **Linear, sequential** — each phase must complete before next starts
- Like a waterfall: water only flows down, never up
- Easy to understand but **inflexible** (no going back to change requirements)

```
Requirements → Design → Implementation → Testing → Deployment → Maintenance
```

**Best for:** Small projects with fixed, clear requirements

### 2. Agile Model
- **Iterative and incremental** — software is built in small cycles called **sprints** (usually 2 weeks)
- Customer sees working software early and gives feedback
- **Flexible** — requirements can change during development
- Most popular model today

**Best for:** Large, complex projects where requirements can change

### 3. Spiral Model
- **Risk-driven** — each cycle identifies and reduces risk
- Combines iterative development with risk analysis
- Used for large, high-risk projects

### 4. V-Model (Verification and Validation)
- Extension of Waterfall
- Every development phase has a **corresponding testing phase**
- Testing planned in parallel with development

```
Requirements ←——————————→ Acceptance Testing
  System Design ←————————→ System Testing
    Architecture ←——————→ Integration Testing
      Coding ←————————→ Unit Testing
```

---

## 📐 PART 3 — Software Testing

### Types of Testing

| Type | What it tests | Who does it |
|------|--------------|-------------|
| **Unit Testing** | Individual functions/modules | Developer |
| **Integration Testing** | Combined modules working together | Developer/Tester |
| **System Testing** | Complete software end-to-end | QA Team |
| **Acceptance Testing (UAT)** | Does it meet user requirements? | Client/User |
| **Regression Testing** | After bug fix, old features still work? | QA Team |
| **Black Box Testing** | Test without knowing internal code | Tester |
| **White Box Testing** | Test with full knowledge of code | Developer |
| **Alpha Testing** | Testing done by developer team internally | Developer |
| **Beta Testing** | Testing done by real users (limited release) | End Users |

### Key Terms

| Term | Meaning |
|------|---------|
| **Bug / Defect** | Error found during testing |
| **Error** | Mistake made by programmer |
| **Failure** | System produces wrong result |
| **Test Case** | Set of conditions to test a feature |
| **Test Plan** | Document describing what/how to test |

---

## 📐 PART 4 — Software Project Management

### Cost and Effort Estimation

**COCOMO Model** (Constructive Cost Model):
- Used to estimate development time and cost
- Based on lines of code (LOC)

### Software Metrics

| Metric | Measures |
|--------|---------|
| **LOC** (Lines of Code) | Size of software |
| **Function Points** | Functionality delivered |
| **Cyclomatic Complexity** | Number of independent paths through code |

---

## 📐 PART 5 — Key Concepts

### Coupling and Cohesion

| Concept | Meaning | Want |
|---------|---------|------|
| **Coupling** | How much one module depends on another | **LOW** coupling (independent modules) |
| **Cohesion** | How related the tasks within a module are | **HIGH** cohesion (focused modules) |

> 💡 **Remember:** LOW coupling, HIGH cohesion = good software design!

### Software Quality Attributes (ISO 9126)

| Quality | Meaning |
|---------|---------|
| **Reliability** | Works correctly without failure |
| **Maintainability** | Easy to fix and update |
| **Efficiency** | Performance, speed, resource usage |
| **Usability** | Easy for users to learn and use |
| **Portability** | Works on different systems |
| **Functionality** | Does what it's supposed to do |

### Version Control

- **VCS (Version Control System):** Tracks changes to code over time
- Examples: Git, SVN, Mercurial
- **Repository:** Storage location for code
- **Commit:** Saving a version of code
- **Branch:** Separate line of development
- **Merge:** Combining branches

---

## 📐 PART 6 — Object-Oriented Concepts (OOP)

### 4 Pillars of OOP (Very Important!)

| Pillar | Meaning | Example |
|--------|---------|---------|
| **Encapsulation** | Wrapping data and methods in a class; hiding internal details | Car: you drive it, don't need to know engine details |
| **Abstraction** | Showing only essential features, hiding complexity | ATM: you see buttons, not internal circuits |
| **Inheritance** | Child class inherits properties of parent class | Dog inherits from Animal |
| **Polymorphism** | Same function/method works differently for different objects | `draw()` on Circle vs Rectangle |

### Key Terms

| Term | Meaning |
|------|---------|
| **Class** | Blueprint for creating objects |
| **Object** | Instance of a class |
| **Method** | Function inside a class |
| **Constructor** | Special method called when object is created |
| **Interface** | Contract that a class must fulfill |

---

## 📐 PART 7 — UML Diagrams (Basic)

UML = **Unified Modeling Language** — used to visualize software systems

| Diagram | Shows |
|---------|-------|
| **Use Case Diagram** | What users can do with the system |
| **Class Diagram** | Classes, attributes, methods, relationships |
| **Sequence Diagram** | Order of messages/events over time |
| **Activity Diagram** | Flow of activities (like flowchart) |
| **ER Diagram** | Entity-Relationship for databases |

---

## ⚡ 60-Second Revision

| Must Remember | Answer |
|---------------|--------|
| SDLC stands for? | Software Development Life Cycle |
| First phase of SDLC? | Requirement Analysis |
| Last phase of SDLC? | Maintenance |
| Waterfall model is? | Linear/sequential, phases go in order |
| Agile model is? | Iterative, small sprints, flexible |
| V-Model links what? | Each dev phase to a testing phase |
| LOW coupling means? | Modules are independent of each other |
| HIGH cohesion means? | Module does one focused job well |
| Unit testing done by? | Developer |
| Acceptance testing done by? | Client/User |
| 4 pillars of OOP? | Encapsulation, Abstraction, Inheritance, Polymorphism |
| Alpha testing is? | Testing by internal team |
| Beta testing is? | Testing by real users (external) |
| Black box testing? | Testing without knowing code |
| White box testing? | Testing with full knowledge of code |

---

## 📝 Practice Questions

**Q1.** Which SDLC model is most suitable for a project where requirements keep changing?
- (A) Waterfall  (B) Agile  (C) V-Model  (D) Spiral

**Answer: (B) Agile** — Agile is flexible and iterative, handles changing requirements well.

---

**Q2.** In which phase of SDLC is the actual programming done?
- (A) Design  (B) Testing  (C) Implementation  (D) Maintenance

**Answer: (C) Implementation** — This is the coding phase.

---

**Q3.** Which type of testing does NOT require knowledge of internal code?
- (A) White Box  (B) Unit Testing  (C) Black Box  (D) Integration

**Answer: (C) Black Box** — Tester treats the software as a black box, testing inputs and outputs only.

---

**Q4.** "LOW coupling and HIGH cohesion" is desirable because:
- (A) It makes code shorter
- (B) It makes modules independent and focused
- (C) It reduces the number of lines
- (D) It speeds up compilation

**Answer: (B)** — Independent modules are easier to maintain and debug.

---

**Q5.** Which OOP concept allows a class to use properties and methods of another class?
- (A) Encapsulation  (B) Polymorphism  (C) Abstraction  (D) Inheritance

**Answer: (D) Inheritance** — Child class inherits from parent class.

---

**Q6.** Which testing type is done after a bug fix to ensure no existing features broke?
- (A) Alpha  (B) Beta  (C) Regression  (D) Unit

**Answer: (C) Regression Testing**

---

> 📖 **[See more Computer Awareness topics →](./README.md)**
