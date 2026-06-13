# LLM Council

A Claude skill that turns one question into five expert opinions, plus a final verdict.

Built by [Ole Lehmann](https://x.com/itsolelehmann). Based on Andrej Karpathy's [LLM Council](https://github.com/karpathy/llm-council) methodology.

Works in **Claude Code** and **Claude Cowork** (claude.ai).

---

## *What's GitHub?*

Think of GitHub as Google Drive, but for code. Instead of sharing photos and files, people use GitHub to share code and snippets like this skill. You're on a GitHub page right now.

---

## What's a skill?

A skill is a small set of instructions you give to your AI. Think of it like a job description for a specific task. Once installed, you can trigger it with a phrase and Claude knows exactly what to do.

This skill teaches Claude how to run a "council" whenever you need it. Ask a hard question or bring a tough decision, and Claude spins up five different advisors who each approach it from a completely different angle, review each other's thinking, and deliver one synthesised answer.

---

## What it does

When you ask AI a question, you get one answer. That answer might be great. It might be completely off. The problem is you only ever saw one perspective, so you have no way to tell.

The council changes that. Your question goes through five independent advisors, each thinking from a different angle. They review each other's reasoning. Then a chairman pulls it all together into a final recommendation — where the advisors agree, where they differ, and what you should actually do.

---

## When to use it

Good council questions:

- "Should I launch a $97 workshop or a $497 course?"
- "Which of these three positioning angles is strongest?"
- "I'm thinking of pivoting from X to Y. Does that make sense?"
- "Here's my landing page copy. What's not working?"
- "Should I hire a VA or build an automation first?"

Not the right tool for:

- "What's the capital of France?" (one right answer, no need for perspectives)
- "Write me a caption" (a creation task, not a decision)
- "Summarise this article" (a processing task, not a judgment call)

The council is most useful when there's genuine uncertainty and the cost of getting it wrong is high. If you already know what you want to do and are looking for validation, be warned: the council will likely tell you things you didn't expect. That's what it's for.

---

## How to install it (no terminal needed)

Pick whichever option feels easier. Both work in Claude Code and Claude Cowork.

### Option 1: Let Claude install it for you

Open a new chat in Claude and paste this in:

> Please install this Claude skill for me. The SKILL.md file lives in this GitHub repo: https://github.com/courtgoesai/public
>
> Set it up so I can start using it. Walk me through anything you need from me.

Claude will fetch the file and put it in the right place. If it can't do it automatically, it will tell you exactly what to do next.

### Option 2: Download the file and ask Claude to set it up

1. Click [SKILL.md](./SKILL.md) at the top of this repo.
2. Click the download button on the right side of the file view to save it to your computer.
3. Open Claude and paste this in:

> I just downloaded a file called SKILL.md for the LLM Council skill. Can you install it for me? Walk me through wherever you need me to put it.

Claude will guide you from there.

---

## How to use it

Once installed, in any Claude conversation just say one of these:

- "council this"
- "run the council on [your question]"
- "pressure-test this"
- "stress-test this"
- "war room this"

Claude will run the five advisors, complete the peer review, and deliver the chairman's verdict.

---

## Credit

This skill was built by [Ole Lehmann](https://x.com/itsolelehmann) — worth a follow.

The methodology is adapted from Andrej Karpathy's [LLM Council](https://github.com/karpathy/llm-council).
