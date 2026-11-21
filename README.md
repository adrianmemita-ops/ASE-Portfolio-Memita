# ASE Portfolio - Memita, Adrian Val A.

## Course Introduction
This repository is my portfolio for CPELX230/330 (Agentic Software Engineering). The course covers how modern software is built with and around AI agents: Agile and Scrum, version control with Git, intelligent agents, and responsible AI practices based on the NIST AI Risk Management Framework. I will use this repository to document my activities, projects, and reflections throughout the term.

## Personal Learning Goals
- Understand how AI agents differ from traditional software and how to design them.
- Become comfortable with Git and GitHub workflows (commits, branches, pull requests).
- Practice Agile and Scrum by planning work in small, reviewable increments.
- Learn to identify and reduce safety, security, and privacy risks in AI systems.
- Build at least one small agent-based project and document it well.

## Reflection from Part A
**What is Agentic Software Engineering?** Agentic Software Engineering is the practice of designing, building, testing, and maintaining software in which AI agents plan and act on their own toward goals, using tools and reacting to their environment. It extends classic software engineering with new concerns: specifying goals clearly, controlling tool access, setting guardrails, evaluating non-deterministic behavior, and monitoring agents after deployment.

**How does an AI agent differ from a traditional application?** A traditional application follows fixed logic written by developers, so the same input gives the same output. An AI agent, in Russell and Norvig's terms, perceives its environment and chooses actions to achieve a goal. It adapts to context, can carry out multi-step tasks with tools, and its outputs can vary between runs. This makes agents more flexible, but harder to predict, test, and debug.

**Why are Agile methods appropriate for agentic systems?** Agent behavior is often emergent and requirements change as teams learn what the agent can and cannot do reliably. Scrum's cycle of transparency, inspection, and adaptation fits this well. Short sprints produce small increments that can be observed, reviewed, and corrected, while sprint reviews and retrospectives surface unexpected behavior early. Version control with Git supports this by tracking code, prompts, and configurations, enabling collaboration through branches and pull requests and safe rollback when a change makes the agent worse.

**What risks should developers consider?** Following the NIST AI Risk Management Framework, key risks include incorrect or fabricated outputs, unintended real-world actions because agents operate tools, and security threats such as prompt injection, excessive permissions, and leaked credentials. Others are privacy violations, bias and unfair outcomes, lack of transparency and accountability, over-reliance by users, and cascading failures when agents chain many actions together.

**Why is human oversight important?** AI systems lack full context, judgment, and moral responsibility. Human oversight lets people approve high-impact actions, catch errors and bias, override or shut down the system, and keep accountability with people rather than the software. The NIST Govern function stresses clear roles, policies, and accountability, which keeps agentic systems trustworthy and aligned with human values.
