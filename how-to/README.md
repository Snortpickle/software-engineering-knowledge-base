# 🛠 How-To Guides

This directory contains practical step-by-step guides for repeatable development tasks.

The goal is to make common project workflows easy to reproduce without guessing, searching through old chats, or performing ritual sacrifices to Git.

---

## 📌 Purpose

Use this folder for instructions that explain **how to do something**.

Good examples:

- how to run the project;
- how to build the solution;
- how to push changes to GitHub;
- how to merge a Codex pull request;
- how to fix common XAML errors;
- how to create a new experiment log;
- how to check whether a GitHub file link is correct.

---

## 📚 Suggested Guides

Possible guide files may include:

```text
run-project.md
push-to-github.md
merge-codex-pr.md
fix-xaml-errors.md
create-experiment-log.md
submit-moodle-links.md
```

---

## 🧱 Guide Template

Use this structure when creating a new how-to guide:

```md
# How to [Task Name]

## Goal

What this guide helps accomplish.

## Prerequisites

What must already be installed, created, or available.

## Steps

1. First step.
2. Second step.
3. Third step.

## Expected Result

What should happen when the task is done correctly.

## Common Problems

Known errors or mistakes and how to fix them.

## Related Files

Project files or folders involved in the task.
```

---

## 🔁 Common Project Workflows

### Build the WPF Project

Open the solution in Visual Studio 2022 and run:

```text
Build → Build Solution
```

or:

```text
Ctrl + Shift + B
```

Expected result:

```text
Build succeeded.
0 errors.
```

---

### Push Local Changes to GitHub

1. Open GitHub Desktop.
2. Check changed files.
3. Write a meaningful commit summary.
4. Click `Commit to main`.
5. Click `Push origin`.

Example commit message:

```text
add spec driven UI experiment log
```

---

### Pull Changes After Merging a PR

After merging a GitHub pull request:

1. Open GitHub Desktop.
2. Click `Fetch origin`.
3. Click `Pull origin` if available.
4. Confirm the new files appear locally.

---

### Fix Basic XAML Syntax Errors

Common XAML problems include:

- unclosed tags;
- invalid comments;
- duplicate `Content` properties;
- missing `>`;
- unescaped XML characters.

Correct XAML comment:

```xml
<!-- This is a valid comment -->
```

Invalid comment:

```xml
<-- This breaks XAML -->
```

Because XML is apparently a delicate ancient creature.

---

## ✅ Usage Rule

A how-to guide should be practical, direct, and repeatable.

If the steps cannot be followed by someone else later, the guide is not finished.
