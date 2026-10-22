# Codex Product Design Skills

**Make products easier to understand and use.**

A collection of six Codex skills for writing web content, improving forms and emails, simplifying workflows, reviewing design systems and auditing accessibility. Each skill turns a design question into concrete copy, findings or recommended changes.

## Choose a skill

| What you want to do | Skill | What it helps you produce |
| --- | --- | --- |
| Write content around readers’ questions | [Letting Go of the Words](letting-go-of-the-words/SKILL.md) | Clear page structures, headings, copy and links, with facts and necessary detail preserved |
| Improve a signup, checkout or settings form | [Form UX Best Practices](form-ux-best-practices/SKILL.md) | Prioritized findings, field rewrites and validation guidance |
| Write or review a product email | [Email UX Best Practices](email-ux-best-practices/SKILL.md) | Email critiques, rewrites, variants and lightweight HTML |
| Make a workflow easier to understand | [Product Design Simplicity](product-design-simplicity/SKILL.md) | Specific changes to choices, defaults, hierarchy and recovery without removing useful control |
| Find gaps in design-system documentation | [Review Design System Specs](review-design-system-specs/SKILL.md) | Findings about tokens, component specs and handoff coverage, with a remediation plan |
| Audit a web interface against WCAG 2.1 AA | [WCAG 2.1 AA Web UI Audit](wcag-21-aa-web-ui-audit/SKILL.md) | Evidence-based accessibility findings and a remediation backlog |

Use the content skill for the words and structure of a page; use the form or email skill when the task depends on that format’s behavior. The accessibility skill supports a scoped audit, not an automatic claim of conformance. The design-system skill includes additional guidance for Factory, alongside its generic audit workflow.

## Install a skill

Install the skill you need, including its supporting folders. For example, ask Codex:

```text
Use $skill-installer to install letting-go-of-the-words from
https://github.com/nicolas-m-design/codex-product-design-skills/tree/main/letting-go-of-the-words
```

For another skill, use its folder link from the table above. You can also copy a complete skill folder into your local Codex skills directory. Keep its `references/`, `assets/`, `scripts/` and `agents/` folders when present; they provide the guidance, examples, helpers and metadata used by that skill.

## Try it on your work

Provide the draft, screen, specification or implementation you want to improve. Include the audience, intended action and any facts or constraints that must stay intact.

```text
Use $letting-go-of-the-words to rewrite this service page.
Help readers understand who it is for, what it includes and what to do next.
Preserve the supplied prices, conditions and promises.
```

```text
Use $product-design-simplicity to review this onboarding flow.
Identify the choices we can simplify while keeping useful control and recovery.
```

```text
Use $review-design-system-specs to review these component specs.
Find the gaps that would leave a developer guessing, and propose focused fixes.
```

## About the content skill

[Letting Go of the Words](letting-go-of-the-words/SKILL.md) draws on Janice (Ginny) Redish’s *Letting Go of the Words: Writing Web Content That Works*, second edition. It covers planning, page structure, writing, illustrations, editing and content testing.

The package contains original paraphrases and practical interpretations, not the book or its illustrations. The [source and coverage notes](letting-go-of-the-words/references/sources-and-coverage.md) credit the underlying work and explain how dated advice is handled. [Evaluation cases](letting-go-of-the-words/references/evaluation-cases.md) describe expected behavior and common failure modes.

## Repository name

This collection was previously named `codex-ux-skills`. Its broader name reflects the work it covers. Existing skill folder names and `$skill-name` invocations are unchanged.
