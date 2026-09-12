# Jamal Johnson

I build agent platforms, AI-assisted development workflows, and the evaluation
harnesses that keep them honest. Lead developer, focused on putting LLMs into
real engineering workflows rather than demos.

## What I am working on now

An open evaluation harness for LLM agents and skills. Agent behavior is easy to
demo and hard to measure, so the harness runs a fixed set of cases against a
skill, scores the output with exact, fuzzy, and model-judged checks, and reports
what changed between runs. The goal is to make a regression in an agent's
behavior as visible as a failing unit test. Public repo to follow.

I am also rebuilding [ai-pr-review](https://github.com/MalTarDesigns/ai-pr-review)
to run as a GitHub Action on real projects, with the cost per review measured
rather than estimated.

## What I work with

- Claude API, MCP, agent and skill authoring
- LLM evaluation: case design, scoring, model-as-judge
- TypeScript, Python
- Angular, Node

## Projects

- **[ai-pr-review](https://github.com/MalTarDesigns/ai-pr-review)**, automated
  code review service that analyzes Git diffs with an LLM to flag risks and
  suggest improvements. Express API with configurable review endpoints and Azure
  DevOps CI/CD integration.
- **[ai-pdf-chatbot](https://github.com/MalTarDesigns/ai-pdf-chatbot)**,
  retrieval-augmented document analysis built with Angular and LangChain, using
  vector embeddings to answer questions against a PDF.
- **[email-auto-organizer](https://github.com/MalTarDesigns/email-auto-organizer)**,
  email triage and response drafting with a human-in-the-loop review step.
  Next.js, FastAPI, and PostgreSQL.
- **[ai-quiz-quest](https://github.com/MalTarDesigns/ai-quiz-quest)**, a CLI that
  generates adaptive multiple-choice quizzes with the Claude SDK, with scoring
  and explanations.
