# 🧠 Software Engineering Knowledge Base

Personal Knowledge Management repository for the **Software Engineering** project.

This repository stores project knowledge, engineering decisions, technical notes, experiment logs, and repeatable development guides used during the development of the **Student Registration System**.

---

## 📌 Purpose

The goal of this repository is to keep project knowledge organized, traceable, and reusable.

Instead of keeping important decisions and development notes scattered across chats, commits, screenshots, and human memory, this repository provides a structured place for:

- technical notes;
- architectural decisions;
- development guides;
- AI-assisted engineering experiments;
- lessons learned during implementation;
- references for future project work.

Because apparently trusting memory alone is how software projects become archaeological sites.

---

## 🎓 Project Context

This knowledge base supports the development of:

```text
Student Registration System
```

The main product repository contains a WPF MVVM desktop application for managing students, courses, and enrollments.

This PKM repository documents the thinking behind the implementation, including:

- BDD requirements;
- Mermaid architecture diagrams;
- pure function experiments;
- design pattern implementation;
- spec-driven UI generation;
- AI-assisted workflow evaluation.

---

## 🗂 Repository Structure

```text
software-engineering-knowledge-base
├── decisions
│   └── README.md
├── how-to
│   └── README.md
├── notes
│   └── README.md
└── README.md
```

| Folder | Purpose |
|---|---|
| `notes` | General technical notes, concepts, and learning material |
| `how-to` | Step-by-step guides for repeatable development tasks |
| `decisions` | Architectural and technical decisions made during the project |

---

## 📚 Knowledge Categories

### 📝 Notes

The `notes` folder is used for general knowledge and study material.

Examples:

- MVVM notes;
- WPF/XAML concepts;
- XML persistence notes;
- testing notes;
- AI-assisted engineering observations.

---

### 🛠 How-To Guides

The `how-to` folder stores practical instructions for repeating development tasks.

Examples:

- how to push changes to GitHub;
- how to fix XAML build errors;
- how to run the WPF project;
- how to create experiment logs;
- how to connect UI controls to ViewModel commands.

---

### 🧭 Decisions

The `decisions` folder documents important technical or architectural choices.

Examples:

- why WPF XAML was used instead of Streamlit or React;
- why the Command Pattern was selected for reset filters;
- why filter reset logic was separated into a module;
- why XML persistence was used;
- why AI outputs were constrained using design contracts.

---

## 🤖 AI Engineering Workflow

This project uses AI as an engineering assistant, not as a magic code vending machine.

The AI workflow is structured around:

1. **Requirements first**
   - BDD requirements using `Given / When / Then`.

2. **Architecture before implementation**
   - Mermaid diagrams used to describe flow and dependencies.

3. **Controlled AI prompts**
   - AI is given strict constraints instead of vague requests.

4. **Experiment logs**
   - Each AI-assisted task is evaluated and documented.

5. **Verification**
   - Generated code is checked through build results, manual inspection, and project structure review.

---

## 🧪 Experiment Types

The knowledge base supports experiment logs such as:

| Experiment Type | Purpose |
|---|---|
| Pure Function Experiment | Test whether AI can generate side-effect-free logic |
| Pattern Implementation | Evaluate whether AI correctly applies a design pattern |
| Spec-Driven UI | Check whether AI follows a strict UI design contract |

Example experiment file names:

```text
EXP-2026-05-17-pure-function.md
EXP-2026-05-17-pattern-implementation.md
EXP-2026-05-17-spec-driven-ui.md
```

---

## 🧱 Engineering Methods Used

### Behavior-Driven Development

Requirements are written before implementation using acceptance criteria.

```text
Given
When
Then
```

### Architecture-as-Code

Mermaid diagrams are used to make system behavior visible and reviewable.

### Pure Function Design

Business logic is separated from UI, database, and collection side effects where possible.

### Design Patterns

Patterns such as the **Command Pattern** are used to keep the architecture maintainable.

### Spec-Driven Development

UI generation is guided by a strict `DESIGN.md` contract instead of vague styling prompts.

---

## 🔗 Related Product Repository

Main application:

```text
StudentRegistrationSystem_st8495
```

The product repository contains the actual WPF application code, while this repository stores the supporting knowledge and project reasoning.

---

## ✅ Current Focus

Current documented work includes:

- reset filters feature;
- pure reset logic;
- Command Pattern module;
- WPF MVVM UI integration;
- spec-driven UI generation;
- AI-assisted development evaluation.

---

## 🧠 Summary

This repository acts as the memory layer for the Software Engineering project.

It documents not only **what** was built, but also **why** specific technical decisions were made and **how** AI-assisted development was controlled, tested, and evaluated.

In other words: this is where the thinking goes, so the project does not slowly mutate into “it works on my machine” folklore.
