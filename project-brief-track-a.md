# COMP7505 Group Project — Interactive Product Design (Simulated Entrepreneurship)

**Course:** COMP7505 User Interface Design and Development  
**Document type:** Group project description (excerpt focused on **Track A** and shared requirements)

---

## I. Core project brief

This project simulates an entrepreneurial team developing an **interactive product**. Teams execute the full product design workflow:

**User requirement definition → Interaction design → Prototyping → Usability evaluation → Iterative optimization → Product roadshow**

The focus is on core human–computer interaction (HCI) design competencies. **No coding development is required**—functions may be implemented through prototypes or simulations.

The project spans roughly **4 weeks**. A **Product Launch Day** is held on **Day 10** of COMP7505. Each team delivers a product roadshow and conducts on-site prototype demonstrations. Every team acts as both presenter and investor and **may not invest in its own group**.

### Basic rules

1. **Team formation:** Each team has **6–8 members** with clear role divisions simulating a startup team.
2. **Track selection:** Only **one** of three tracks may be chosen. Tracks differ in core design and evaluation focus; **general grading standards are identical**. Track-specific requirements are **minimum completion criteria**; failure to meet them can yield **point deductions** for the corresponding module (and in extreme cases the track module score may be reduced to zero).
3. **Core red lines:** Simple feature stacking is prohibited. Designs must be backed by **clear user needs** and **interaction design rationales**. Plagiarism of complete interaction solutions from existing products is forbidden; **all cited content must be sourced**.

---

## II. Mandatory deliverable components (all tracks)

Regardless of track, teams must submit **five core deliverable components**. These form a primary basis for grading.

### 1. User requirement & project definition

Foundation of all design work. Must include:

- **Target user personas:** Core user groups, characteristics, and key pain points.
- **Core user tasks:** At least **one** end-to-end core user task with **clear success criteria**.
- **Project scope & boundaries:** Constraints (usage scenarios, device limits, technical prerequisites), design assumptions, and **explicitly excluded** requirements.

### 2. Interaction design solution & interactive prototype

Tangible expression of product interaction logic. Must include:

- **Interaction design specification:** Interaction model, overall information architecture, and navigation structure.
- **Full workflow of core tasks:** Complete end-to-end interaction **flowcharts** (page transitions, operational feedback, **exception branches**) aligned with Deliverable 1.
- **Interactive prototype:** Appropriate fidelity (**high fidelity recommended**). Tools such as Figma or Axure are acceptable. Must cover the **entire** core task workflow.

### 3. Design evaluation & iteration optimization

Verify usability and close the iteration loop. Must include:

- **Evaluation plan:** Structured methods such as heuristic evaluation, cognitive walkthrough, or think-aloud usability testing—specify process, participants, and indicators.
- **Evaluation results:** Usability issues summarized and categorized by severity (**critical, severe, moderate, minor**).
- **Iteration evidence:** Actionable optimizations for key issues and materials for **at least one full design iteration** (e.g., before/after prototype comparisons, adjustment records, rationales).

### 4. Design principles & product development roadmap

Must include:

- **Reusable design principles:** **No fewer than three** reusable interaction design principles tailored to the track’s features and user profiles, each with supporting design-case explanation—forming a simple operational guideline.
- **Product development roadmap:** A **phased** expansion plan covering **at least three stages**, with core objectives per stage and expansion directions for scenarios, users, and interaction forms (e.g., multi-device adaptation, new modules, innovative interaction methods).

### 5. Product roadshow materials

For on-site roadshows and demonstrations on Product Launch Day (assesses current progress; **completing every item by Day 10 is not required**). Suggested contents:

- **Roadshow deck (PPT):** Core value, user pain points, solutions, interaction design highlights, evaluation and iteration process, and future plans.
- **Prototype demo script:** Step-by-step on-site demonstration of core tasks for a smooth presentation.
- **Core value proposition:** Differentiated highlights rooted in **user experience and interaction design**, not simple feature addition.

### Submission deadline

Submit the **project portfolio** (one comprehensive written report + interactive prototype) and a completed **roadshow PPT** by:

**May 3, 23:59**

---

## III. Track-specific minimum requirements — Track A only

### Track A: Smart adaptive interfaces

**Suitable for:** Teams developing AI-powered productivity tools, intelligent assistance systems, and decision-support products.

**Core focus:** Design interfaces with **intelligent adaptive** capabilities and **proactive** human–machine collaborative interaction. Prioritize **user control**, **interaction transparency**, and **system exception handling** in AI interaction to avoid poor experience from an AI “black box.”

**Recommended product ideas:** AI-assisted productivity for learning/writing/planning; intelligent help for complex professional software; **decision-support tools for high-risk or ambiguous scenarios**.

#### Minimum mandatory standards (full compliance required)

Non-compliance can result in **severe penalties**, including **zero points** for the track-compliance module.

1. **Clearly define the system’s capability boundaries:** State explicitly what the intelligent system **can and cannot** do, without exaggerating capabilities.
2. **Design a comprehensive user control mechanism:** Give users adjustable control over system outputs (e.g., **manual override** of AI results, **secondary confirmation** for critical operations, **operation review** / **one-click undo**).
3. **Pre-design interface solutions for at least two types of system failures:** Address scenarios such as **incorrect AI outputs**, **system understanding deviations**, and **functional malfunctions**; specify how the interface **alerts** users, **guides** problem-solving, and **reduces harm**.
4. **Integrate at least one mechanism to communicate system limitations:** For example, surfacing uncertainty, confidence, coverage limits, or when human judgment or escalation is required—so users are not misled about reliability or scope.

#### Suggested evaluation focus

User trust, interaction transparency, cognitive load of operations, **error recovery**, and effectiveness of **user control** protections.

---

## IV. Product Launch Day — roadshow & simulated investor peer review

**Timing:** Day 10 (lecture time).

### Roadshow

- **Time limit:** **8 minutes** total (**6 minutes** presentation + **2 minutes** Q&A).
- **Required segments:**
  1. Explanation of **core value** and **design logic**.
  2. **On-site prototype demonstration** of core tasks.
- Content must align with mandatory deliverables. **Empty conceptual talk without design rationales** is not acceptable.

### Simulated investor peer review

Teams act as investors with a fixed virtual budget allocated to **other** teams (not their own). Investment decisions should reflect:

1. **Alignment:** Link between core user pain points and product/task design.
2. **Quality & rationale:** Prototype quality and strength of theoretical/practical rationales for interaction design.
3. **Evidence:** Completeness of empirical evidence for evaluation and iteration.
4. **Feasibility & risk:** Feasibility and risk management (e.g., privacy, accessibility, user control).
5. **UX highlights:** Differentiation through **experience**, not feature stacking.

**Note:** Peer review affects **extra course points and in-class recognition only**; it does **not** determine the main grade, which instructors assess from deliverable completeness and design quality.

---

## V. Main grading criteria

| Grading module | Core grading points |
| --- | --- |
| **Requirement & project definition** | Accuracy of personas, depth of pain-point analysis, clarity of tasks and boundaries |
| **Interaction design & prototype quality** | Soundness of interaction logic, clarity of information architecture, prototype completeness, integrity of core workflows |
| **Design evaluation & iteration optimization** | Standardization of evaluation methods, soundness of severity ratings, feasibility of iteration fixes, completeness of iteration evidence |
| **Roadshow & deliverable completeness** | Clarity of roadshow logic, demo effectiveness, full submission, expression of differentiated value |
| **Track-specific compliance** | Deductions for unmet track minima; module score may drop to **zero** in extreme cases |

---

## Team project focus (this repository)

**Product concept:** AI-assisted medical tool supporting **medical charting** and **clinical decision support** (e.g., documentation, differential suggestions)—designed under **Track A (smart adaptive interfaces)** with emphasis on transparency, control, and safe failure handling in high-stakes use.
