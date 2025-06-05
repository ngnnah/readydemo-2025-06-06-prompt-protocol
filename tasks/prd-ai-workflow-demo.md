# Product Requirements Document: AI Tools Workflow Demo

## Introduction/Overview
This document outlines the requirements for creating a 5-8 minute demonstration of AI tools usage in a daily workflow for a SaaS telecom B2G company audience of 50 non-technical people. The demo will showcase how AI tools can 10x productivity using a structured workflow protocol, meta-prompting techniques, and other time-saving tips for working effectively with AI tools. The presentation will cut through AI hype and establish practical paths for AI tool adoption.

## Goals
1. Create a concise, engaging 5-8 minute presentation showcasing AI-powered productivity workflows
2. Demonstrate the 3-step AI workflow protocol with clear examples
3. Highlight meta-prompting techniques and show how they improve AI output quality
4. Present specific AI tools best suited for different tasks
5. Include artifacts/screenshots to provide concrete examples of the workflow
6. Ensure content is accessible to a non-technical audience while covering state-of-the-art techniques
7. Structure content to help audience establish their own path to AI tool adoption
8. Mention company's $2000 yearly AI upskilling stipend to make the presentation relevant to employees

## User Stories
1. As a non-technical employee, I want to understand how AI tools can be incorporated into my daily workflow so that I can improve my productivity.
2. As a manager, I want to see concrete examples of AI tool usage so that I can recommend adoption strategies to my team.
3. As a curious professional, I want to learn about current AI capabilities and limitations so that I can make informed decisions about which tools to invest time in learning.
4. As a company stakeholder, I want to understand the ROI of our AI upskilling investments so that I can justify continued support for these initiatives.
5. As a department lead, I want to identify which AI tools could best help my specific team function (sales, engineering, HR, etc.) so I can prioritize our learning efforts.

## Functional Requirements
1. **Presentation Format**: Create a structured slide deck or README-style document with screenshots that walks through the AI workflow. Consider a simple web app that generates/manages slides programmatically if time permits.

2. **Content Requirements**:
   1. Introduction to the concept of AI-assisted workflows (30 seconds)
      - Brief mention of AI landscape in 2025 and cutting through the hype
      - Position AI as companion/assistant/mentor, not just a tool
   
   2. Overview of the 3-step AI workflow protocol (1 minute)
      - Author: https://github.com/snarktank/ai-dev-tasks
      - Generate PRD
      - PRD to tasks (stage-gate)
      - Execute tasks step-by-step
      - Show real example of how this structures the work
   
   3. Demonstration of meta-prompting techniques (1-2 minutes)
      - XML system prompts (/prompts/prompt-gen.xml) with example
      - Prompt folding (iterating on prompts)
      - Examples and escape hatches
      - Show before/after quality improvement
   
   4. Showcase of specific AI tools and their optimal use cases (2-3 minutes)
      - VSCode Copilot/Edit mode - when to use
      - Google AI Studio - handling complex context
      - Claude Prompt Writer - crafting better prompts
      - NotebookLM - source discovery and synthesis
      - Lucid Charts with MermaidJS - diagram generation
      - RepoPrompt - context formatting
   
   5. Real-world application examples (1-2 minutes)
      - Creating this presentation (meta-example)
      - Calix Cloud integration workflow
      - Generating diagrams and process flows
      - Data workflow optimization with dbt/Spark
   
   6. Best practices and tips for effective AI tool use (30 seconds)
      - "You get out what you put in" - proper context setting
      - Tool selection based on task complexity
      - Iterative prompt refinement
      - Experiment with examples and alternative techniques
   
   7. Mention of company's $2000 yearly AI upskilling stipend (15 seconds)
      - How to leverage this for learning these tools
      - Quick ROI calculation showing productivity gains
   
   8. Q&A/conclusion (30 seconds)
      - Offer to share repo and resources
      - Poll interest in specific follow-up sessions

3. **Visual Elements**:
   1. Screenshots of each step in the workflow (PRD generation, task creation, execution)
   2. Examples showing improvement with better prompting techniques
   3. Simple LLM-generated diagrams-as-code illustrating the 3-step workflow
   4. Examples of generated artifacts (diagrams, code, documents)
   5. AI memes or visuals that make the content approachable and engaging

4. **Demo Flow**:
   1. Begin with this presentation itself as the concrete example (meta-demonstration)
   2. Show how the PRD for this presentation was created using AI
   3. Walk through how tasks were generated from the PRD
   4. Demonstrate how execution was assisted by AI tools
   5. Present the final output (this presentation) as proof of the workflow's effectiveness

5. **Key Messaging Points**:
   1. AI as a companion/assistant/mentor, not just a tool
   2. "You get out what you put in" - importance of proper prompting, meta-prompting techniques
   3. Structure leads to better results - less guesswork, better outputs
   4. Embrace "Vibe coding for serious adults" - structured yet natural workflow
   5. Using the right tool for the right job increases efficiency exponentially
   6. The goal is reducing research time and improving execution quality

## Non-Goals (Out of Scope)
1. Deep technical explanations of how AI models work
2. Extensive coding examples or complex technical implementations
3. Exhaustive coverage of all available AI tools
4. Hands-on workshop or extensive training (this is an overview demo)
5. Discussion of AI ethics or regulatory concerns
6. Comparison of specific vendor offerings or pricing details

## Design Considerations
1. Keep slides visually simple with minimal text (3-5 bullet points max per slide)
2. Use a consistent visual structure throughout with AI/LLM-related emojis and memes
3. Incorporate screenshots with highlighted areas to draw attention to key points
4. Use Ready.net color scheme (Purple, Blue, Black) for brand consistency
5. Create a visual flow that follows the 3-step workflow process
6. Include QR code linking to resources/repo on concluding slide

## Technical Considerations
1. Prepare all screenshots and examples in advance to avoid live demo risks
2. If creating a web-based presentation, use simple HTML/CSS/JS for reliability
3. Have backup examples ready in case of questions about specific use cases
4. Ensure all links and resources are included in the github repo
5. Test the presentation flow on the local laptop that will be used
6. Consider recording a screencast backup in case of technical difficulties

## Success Metrics
1. Audience engagement during the presentation (questions, note-taking)
2. Post-presentation inquiries about specific tools or techniques
3. Increased adoption of AI tools among team members
4. Requests for follow-up sessions or more detailed information
5. Positive feedback from management on practical applicability
6. Measurable increase in AI tool usage company-wide within 30 days

## Open Questions and My Answers
1. Should specific company projects or use cases be highlighted in the presentation?
   - Skip this to keep preparation effort low
   - Instead, focus on the meta-example (this presentation itself)

2. What is the technical setup for the online presentation (platform, screen sharing capabilities)?
   - Will share laptop screen in company-wide Slack huddle
   - Ensure presentation works well in this format (readable fonts, clear visuals)

3. Will there be time for a Q&A session after the presentation?
   - Yes, 1 minute
   - Prepare 2-3 anticipated questions and answers in advance

4. Should handout materials be provided for reference after the presentation?
   - Will share slide deck and repository
   - Include a "getting started" guide with links to tools mentioned

5. Is there interest in follow-up sessions on specific aspects of AI tool usage?
   - Will poll audience interest
   - Prepare a simple form/survey to collect specific interests

6. What are the primary pain points or workflow challenges that audience members currently face?
   - Overwhelmed by AI hype, many tools, many updates
   - Diverse audience (engineers, product, sales, PR, HR, designers)
   - Each group has different challenges and relevant AI tools
   - Address this by categorizing tools by department/function

7. Are there specific productivity metrics the company is trying to improve?
   - Annual Revenue per employee
   - AI adoption rates
   - Feature development velocity
   - Show how AI tools directly impact these metrics
