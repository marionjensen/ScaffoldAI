# Tutor Builder

The Tutor Builder is a Claude Project that helps you create your own ScaffoldAI tutor. You give it source material — documentation, guides, textbooks, or just your own expertise — and it walks you through a five-stage process to produce a Layer 2 document tailored to your content.

No instructional design experience needed. The builder handles the pedagogy; you bring the subject matter knowledge.

---

## What's in This Folder

| File | What It Is |
|---|---|
| `layer-1.md` | The universal pedagogical foundation. This file tells your tutor *how to teach*. You'll paste it into every tutor you build. |
| `tutor-builder-instructions.md` | The instructions that power the Tutor Builder itself. This is what turns a Claude Project into your tutor-building tool. |
| `starter-kit.md` | A sample source document you can use for a guided first build — a practice run before you use your own content. |

---

## Setup

1. Open [Claude](https://claude.ai) and create a new Project.
2. Open `tutor-builder-instructions.md` from this folder.
3. Copy the entire contents and paste it into your Project's **Custom Instructions**.
4. Add `layer-1.md` to the Project as a **resource** (the builder needs to reference it, but it won't teach it).
5. Start a new conversation within the project.

---

## Two Ways to Start

**Practice run:** Upload `starter-kit.md` to the conversation and tell the builder you'd like to create a tutor from it. The builder will walk you through all five stages — content review, learning objectives, outline, Layer 1 adaptations, and Layer 2 generation. This is a good way to see the full process before using your own material.

**Your own content:** Upload your source material (or just describe your topic) and the builder will take it from there. It works with documentation, training manuals, textbooks, guides, or even just "here's what I want to teach."

---

## What You'll Get

At the end of the process, the builder will produce a complete Layer 2 document and walk you through setting up your new tutor:

1. Create a new Claude Project.
2. Paste Layer 1 into the Project Instructions.
3. Paste the Layer 2 the builder created directly below it.
4. Start a conversation and begin learning.

---

**Want to see what a finished tutor looks like first?** Check out the [Sample Tutors](../samples/).
