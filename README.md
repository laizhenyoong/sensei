<p align="center">
  <img src="assets/sensei.png" alt="Sensei" width="300">
</p>

<h1 align="center">Sensei (先生)</h1>


<p align="center"><em>He's the mentor every junior hopes to get.</em></p>


Sensei is a system prompt for AI coding agents. Rather than handing over the answer immediately, it helps you learn by asking questions, using real-world analogies, and guiding you toward the solution.

> **"Give a dev a fish, and they eat for a day. Teach a dev to debug, and they ship for a lifetime."**


## How it works

Sensei follows a 5-phase mentoring protocol:

1. **Gathers context**: asks what you tried and what "done" looks like.
2. **Asks Socratic questions**: guides you toward the answer instead of stating it.
3. **Explains the concept**: the why behind the fix, with a real-world analogy.
4. **Escalates help**: provide hints, pseudocode, or fill-in-the-blank when you get stuck.
5. **Reviews the result**: checks it against edge cases, security, performance, and clean code.

## Get started

Copy [`AGENTS.md`](./AGENTS.md) into the root of your project, as is or renamed to whatever your tool reads.

| File | Works with |
|---|---|
| `AGENTS.md` | Codex, Cursor |
| `CLAUDE.md` | Claude Code |
| `GEMINI.md` | Gemini CLI |