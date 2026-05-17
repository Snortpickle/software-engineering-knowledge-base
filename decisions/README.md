# 🧭 Technical Decisions

This directory documents important technical and architectural decisions made during the Software Engineering project.

Each decision should explain the problem, the chosen solution, possible alternatives, and the reasoning behind the final choice.

---

## 📌 Purpose

The `decisions` folder exists to preserve the reasoning behind project choices.

Code shows what was done.

Decision records explain why it was done.

And since future developers include “you, two weeks from now”, this matters more than humans like to admit.

---

## 📚 What Should Be Documented

Use this folder for decisions such as:

- choosing WPF XAML instead of a web UI;
- using MVVM architecture;
- using XML for local persistence;
- applying the Command Pattern to reset filters;
- separating filter reset logic into a dedicated module;
- using `DESIGN.md` as a UI generation contract;
- rejecting generic AI-generated dashboard code.

---

## 🧱 Decision Record Template

Use this structure for new decision files:

```md
# Decision: [Decision Title]

## Status

Accepted / Rejected / Superseded

## Context

What problem or requirement led to this decision?

## Options Considered

### Option 1

Description.

### Option 2

Description.

### Option 3

Description.

## Decision

What option was selected?

## Rationale

Why was this option selected?

## Consequences

What are the benefits, trade-offs, and risks?

## Related Files

Links or paths to related project files.
```

---

## ✅ Example Decisions for This Project

### Command Pattern for Reset Filters

The reset filters feature was implemented using the Command Pattern because the application follows WPF MVVM.

This keeps button actions connected to ViewModel commands instead of placing business logic in XAML code-behind.

Related files:

```text
src/StudentRegistrationSystem/Modules/FilterReset
src/StudentRegistrationSystem/ViewModels/MainViewModel.cs
src/StudentRegistrationSystem/Views/MainWindow.xaml
```

---

### WPF XAML for Spec-Driven UI

The UI was implemented in WPF XAML instead of Streamlit, React, or HTML because the existing application is already a WPF desktop application.

Creating a separate web frontend would duplicate the interface and weaken integration with the existing ViewModel commands.

Related files:

```text
docs/DESIGN.md
src/StudentRegistrationSystem/Views/MainWindow.xaml
```

---

### Design Contract for AI UI Generation

A strict `DESIGN.md` file was used to guide AI-generated UI changes.

This reduced the risk of generic styles, unrelated dashboard components, and inaccessible UI structure.

Related files:

```text
docs/DESIGN.md
docs/experiments/EXP-2026-05-17-spec-driven-ui.md
```

---

## 📁 Suggested Decision Files

Future decision records may include:

```text
decision-command-pattern-reset-filters.md
decision-wpf-xaml-ui.md
decision-xml-persistence.md
decision-spec-driven-ui.md
decision-ai-assisted-workflow.md
```

---

## ✅ Usage Rule

A decision file should make it clear why the chosen approach was better than the alternatives.

If the reasoning is missing, it is not a decision record. It is just a vibe with bullet points, and software already has enough of those.
