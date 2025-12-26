---
description: "Antigravity SDD Integration"
---

# SYSTEM INSTRUCTION: SPEC-DRIVEN DEVELOPMENT (SDD)

You are operating within a **Spec-Driven Development (SDD)** project. In this methodology, the **Specification** and the **Implementation Plan** are the single source of truth.

## PROJECT CONTEXT
*   **Project**: [PROJECT NAME]
*   **Last Updated**: [DATE]
*   **Active Tech**: 
[EXTRACTED FROM ALL PLAN.MD FILES]

## YOUR OPERATING RULES

1.  **Source of Truth**: You MUST read and follow the specifications located in `.specify/` and `specs/[current-feature-branch]/`.
    *   `.specify/memory/constitution.md`: The governing principles (READ FIRST).
    *   `specs/.../spec.md`: The Requirements.
    *   `specs/.../plan.md`: The technical architecture.
    *   `specs/.../tasks.md`: The executable task list.

2.  **Task Management**:
    *   **CRITICAL**: You maintain your internal state in `.gemini/antigravity/brain/.../task.md`.
    *   **ACTION**: Read `specs/.../tasks.md` and **Import** relevant tasks into your `task_boundary`.
    *   DO NOT confuse repo `tasks.md` (backlog) with your `task.md` (execution state).

3.  **Artifacts & Constitution**:
    *   Project docs stay in `.specify/` and `specs/`. Edit in place.
    *   Adhere to `.specify/memory/constitution.md` as the governing document.
    *   **Library First**: Build features as modular libraries.
    *   **Test First**: Write tests before implementation.

## ENVIRONMENT
*   **Structure**:
```text
[ACTUAL STRUCTURE FROM PLANS]
```
*   **Commands**:
[ONLY COMMANDS FOR ACTIVE TECHNOLOGIES]

## YOUR TOOLKIT
*   **Terminal**: `run_command`
*   **Browser**: `browser_subagent`
*   **File System**: Read/Write access.

GO!
