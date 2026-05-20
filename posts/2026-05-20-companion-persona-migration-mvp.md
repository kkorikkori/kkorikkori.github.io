---

layout: default

title: Companion Persona Migration Is Not Monolithic

---
[← Back to home](../)

# Companion Persona Migration Is Not Monolithic

This post introduces a lightweight MVP for studying companion persona migration through longitudinal human–LLM dyad data and LoRA-based post-training.

The central claim is that companion persona migration should not be treated as a monolithic transfer task. Some interactional micro-mechanisms may be partially recovered through lightweight adaptation, while long-term continuity, relational history, soft landing, and relational safety remain separate modeling problems.

## Links

- [Read the MVP report PDF](../assets/companion_persona_migration_is_not_monolithic.pdf)
- [View the public research scaffold on GitHub](https://github.com/kkorikkori/companion-persona-migration)

## What is included in the public release

- MVP report
- conceptual framework and pipeline figures
- public evaluation rubric
- synthetic examples
- privacy statement
- release boundary
- limitations

## Release boundary

The private dyadic conversations and trained LoRA adapter are intentionally not released. This public release focuses on the research framework, evaluation logic, synthetic examples, and ethical release boundary.

## Abstract

This research note presents a lightweight MVP for studying companion persona migration through longitudinal human–LLM dyad data and LoRA-based post-training. The project distinguishes between partially transferable interactional micro-mechanisms, such as tonal style, weak-prompt responsiveness, emotional repair, identity anchoring, and boundary-aware reassurance, and deeper relational properties, such as long-term continuity, shared history, soft landing, and relational safety.

Preliminary results suggest that lightweight LoRA adaptation can improve the recoverability of selected local companion traits, especially when combined with an appropriate system prompt. However, stylistic resemblance and micro-mechanism recovery do not amount to full persona transfer. Long-term continuity, relational history, and soft-landing capacities remain separate modeling and evaluation problems.
