# Why I Am Moving From Test Automation Into AI

I have spent years working in software engineering and test automation.

My background includes building websites, writing automation in Python, testing web applications with Playwright, working with CI/CD pipelines, and creating systems that help engineering teams catch problems before software reaches production.

Testing taught me something important:

**software should not be trusted just because it appears to work.**

It should be verified.

That principle is one of the main reasons I decided to move deeper into Artificial Intelligence.

## Why AI

AI is not just another technology trend.

It is becoming part of how software is designed, how companies automate work, how people search for information, how customer support is delivered, and how decisions are made.

For a software engineer, that changes the landscape completely.

Traditional applications usually follow deterministic logic:

```text
Input -> Code -> Output
```

AI applications are different:

```text
Input
  ->
Prompt
  ->
Model
  ->
Context / Tools / Data
  ->
Generated Output
  ->
Decision
```

The result may look perfectly correct and still be wrong.

That is what makes AI exciting to me from a testing perspective.

## My Background Fits This Problem

I am not entering AI by abandoning software engineering.

I am bringing my software engineering and test automation experience into AI.

My background includes:

- Python development
- Web application testing
- Playwright automation
- Pytest
- CI/CD integration
- Regression testing
- API testing
- Software quality engineering
- Debugging and failure analysis
- Building repeatable automated test systems

These skills are directly relevant to AI systems.

The tools are changing.

The engineering principle is not.

**If a system is important enough to use in production, it is important enough to verify.**

## AI Creates a New Kind of Testing Problem

With traditional software, a failure is often obvious.

A test fails.

An API returns an error.

A page does not load.

An exception appears.

AI systems can fail very differently.

An AI application may:

- produce a confident but incorrect answer;
- hallucinate information;
- ignore important context;
- answer a different question than the one asked;
- behave differently after a prompt change;
- regress after a model update;
- provide an answer unsupported by source documents;
- become slower or more expensive without anyone noticing.

The application may still be technically running.

That means traditional software testing is necessary, but it is no longer enough.

We also need to verify the **quality of the AI's behavior**.

## From Test Automation to AI Verification

This is the area I want to focus on.

I am interested in questions such as:

- How do we know whether an AI answer is correct?
- How do we detect prompt regressions?
- How do we compare two models objectively?
- How do we verify that a RAG system is using the correct evidence?
- How do we detect unsupported claims?
- How do we measure relevance, groundedness, latency, and quality?
- How do we create quality gates for AI applications?
- How do we produce evidence showing why an AI release should or should not go to production?

This is a natural extension of test automation.

The goal is still the same:

**find problems before the user does.**

But now the testing surface is much larger.

## What I Am Building

My current work is focused on **AI Test Lab**.

The idea is straightforward:

```text
Dataset
   ->
Model
   ->
Evaluation
   ->
Metrics
   ->
Evidence
   ->
Quality Gate
```

Instead of manually trying a few prompts and deciding that an AI application "looks good," I want the process to be repeatable and measurable.

A team should be able to run the same test dataset against:

- different prompts;
- different model versions;
- different configurations;
- different evaluation strategies.

Then compare the results and make a decision based on evidence.

## Why This Direction Makes Sense to Me

AI is clearly becoming a major part of the future of software.

But the more AI is used in real systems, the more important reliability becomes.

Companies will not only need people who can build AI applications.

They will also need engineers who can answer:

> **Can we trust this AI application in production?**

That problem sits directly between AI engineering and software quality engineering.

It is where my existing experience gives me a strong foundation, and it is the direction I have decided to pursue.

## The Principle I Am Taking With Me

My move into AI does not mean leaving test automation behind.

It means applying the discipline of test automation to a new class of software.

Traditional software is tested before production.

AI should not get a free pass.

**AI can sound right. Verification provides the evidence that tells us whether we should trust it.**

---

### Current Focus

- AI application verification
- LLM evaluation
- Prompt regression testing
- Evidence-driven quality engineering
- AI quality gates
- Python
- Pytest
- Playwright
- CI/CD

### Project

**AI Test Lab** — building repeatable verification for production AI systems.
