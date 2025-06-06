# AI Tools Workflow Demo

This repository contains the materials for a demonstration of AI tools and workflows created on June 6, 2025. The presentation showcases a structured approach to using AI tools to 10x productivity.

## What's Inside

This repository serves as both documentation of the AI workflow process and the product of that process. It demonstrates the "meta" example of using AI to create a presentation about AI workflows.

### Repository Structure

```
/
├── context/
│   └── background.md       # Initial brainstorming, demo plan, motivation, and broader context for the project and presentation.
├── prompting/
│   ├── create-prd.mdc      # Model Context Protocol (MCP) for guiding an AI to generate a Product Requirements Document.
│   ├── generate-tasks.mdc  # MCP for guiding an AI to generate a hierarchical task list from a PRD.
│   └── process-task-list.mdc # MCP outlining rules for managing and executing a generated task list.
├── slides/
│   ├── marp.config.js      # Configuration file for the Marp presentation tool.
│   ├── presentation.md     # The Marp-based Markdown presentation slides detailing the workflow and concepts.
│   └── theme.css           # Custom CSS theme for the Marp presentation.
└── readme.md               # This file.
```

## Key Concepts & Workflow

This project demonstrates several key concepts for effective AI utilization:

*   **3-Step AI Workflow Protocol:** A structured process for tackling complex tasks:
    1.  **Generate PRD (Product Requirements Document):** AI assists in creating a detailed PRD based on user input, emphasizing clarifying questions.
    2.  **PRD to Tasks:** AI converts the PRD into an actionable, hierarchical task list (often with a user approval stage-gate).
    3.  **Execute Tasks:** Systematically work through tasks with AI assistance, tracking progress.
*   **Meta-Prompting:** Using AI to help craft, refine, and improve prompts for other AI interactions, leading to more precise outputs. This includes detailed system prompts, iterative refinement (prompt folding), providing examples, and defining fallback behaviors.
*   **Model Context Protocols (MCPs):** Represented by the `.mdc` files, these are rule sets defining goals, processes, output formats, and interaction models for an AI assistant. They serve as comprehensive "meta-prompts" for specific, complex operations.

## Model Context Protocol (MCP): Manual Mode

The `.mdc` files in the `/prompting` directory define the "rules of engagement" for the AI assistant:

*   **`prompting/create-prd.mdc`:** Guides AI in generating a PRD, including asking clarifying questions and adhering to a specific structure.
*   **`prompting/generate-tasks.mdc`:** Outlines how AI should convert a PRD into a detailed, two-phase task list (parent tasks then sub-tasks).
*   **`prompting/process-task-list.mdc`:** Provides guidelines for AI and user collaboration during task execution, including progress tracking and task management.

## Getting Started: Viewing the Presentation

The presentation in `slides/presentation.md` explains this workflow in detail.

#### Option 1: Using Marp CLI
1.  Install Marp CLI: `npm install -g @marp-team/marp-cli`
2.  Preview: `marp slides/presentation.md -p` (opens in browser)
3.  Export to HTML: `marp slides/presentation.md --output slides/presentation.html`
4.  Export to PDF: `marp slides/presentation.md --output slides/presentation.pdf`

#### Option 2: Using VS Code with Marp Extension
1.  Install the "Marp for VS Code" extension from the VS Code Marketplace.
2.  Open `slides/presentation.md`.
3.  Click the "Open Preview" icon (usually a Marp logo or an eye icon) in the top-right corner of the editor.

## Contact

For questions or follow-up about this presentation:
- Slack: @nhat
- Email: nhat@ready.net

## Resources & Inspiration

*   **Original Workflow Concept:** [Snark Tank - AI Dev Tasks](https://github.com/snarktank/ai-dev-tasks)
*   **Google AI Studio:** [https://aistudio.google.com/](https://aistudio.google.com/)
*   **Claude (for Prompt Writing Assistance):** [https://claude.ai/](https://claude.ai/)
*   **RepoPrompt (Contextualizing Repositories for Prompts):** [https://repoprompt.com/](https://repoprompt.com/)
