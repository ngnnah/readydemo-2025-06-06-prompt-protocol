# todo. readynet. demo AI usage per Mike request:

https://readynet.slack.com/archives/C04J8FW0QQZ/p1747851570019009?thread_ts=1747846259.295889&channel=C04J8FW0QQZ&message_ts=1747851570.019009


## I need to prepare a demo 5-8 minutes tomorrow, online, to my SasS telecom B2G company of 50 people, target audience is non-technical. Walk them through how I use AI tools in my daily workflow to 10x productivity!

## I want to document what I am doing right: my protocol to use metaprompts and vibe code protocol to prepare and make demo deck/slides as example showcase in the demo

Note that there are so many AI news and releases daily as of now June 2025, this demo should help establish a path to use of AI tools and help audience know the key developments and strengths and limitation of AI tools and cut through the noise and hype.

# DEMO PLAN:
- disclosure: this is just how i am using AI tools atm; new and better tools are launching every day, and they are drastically changing existing (even established) workflows

MAIN WORKFLOW

- 1) 3-step AI workflow protocol https://github.com/snarktank/ai-dev-tasks
    - VSCode Copilot/Edit mode: generate PRD >> PRD to tasks (stage-gate) >> execute tasks step-by-step
- 2) https://aistudio.google.com/ for large CONTEXT: use on complex problems
    - prompt writer (Claude project) — XML system prompt
        - e.g. Calix Cloud integration coding assistant
    - https://repoprompt.com/ to select and format the right context to prompt!
        
        
- where I learned this: https://www.youtube.com/watch?v=fD4ktSkNCw4
    
    <aside>
    🔑
    
    **What you’ll learn:**
    
    1. A simple three-file system that transforms chaotic AI coding into a structured, reliable process
    2. How to create AI-generated PRDs and task lists that actually work
    3. A step-by-step workflow using Cursor to build features systematically
    4. Why slowing down to provide proper context is the secret to speeding up your AI development
    5. How to use model context protocols (MCPs) to extend your AI’s capabilities beyond just coding
    6. Why founders can now build entire companies with minimal engineering teams and how Ryan is doing it himself
    
    </aside>
    

- context:
    - prompting: you get out what you put in
    - what i have learned: LLM is best at both generating and answering prompts; so always ask LLM to create and improve prompts for you.
    - mentality: AI companion, assistant, mentor; not a tool
    - what most important atm: llm eval
- Project: prompt writer (XML structure): on my phone, to quickly craft a comprehensive prompt to one-shot any task eg "is now a good time for our team to start adopt Spark, or dbt? ask clarification questions to help craft best prompt"
    - “make a visual-appealing Memory matching game with engaging gameplay, with 3 levels of difficulty and 7 different themes for player to choose from: animals, country flags, planets, fruits, clothing items, foods, and one special theme that mix all other themes”
        - https://claude.ai/chat/9439fc81-33cc-4055-9a9e-d2b38448f208
    - v.s. ask Claude directly — https://claude.ai/chat/69c304a3-fcd3-4c33-bfcf-35152ebc04d5 example prompt#2: https://claude.ai/chat/ecbdeb50-8301-495e-b6cd-c51a9fff5ed6
    - 
    - 
- Calix Cloud integration: prompt writer, to Linear task requirements, to AI-generated description to mermaid diagram, to csv denoting diagrams, to import to Lucid Chart ERD and Process diagram.
- a long chat with many-shot prompts, generate and render html and markdown documents
- personal planner with knowledgebase = personal schedule and background
- Claude prompt writer to craft prompt to ask Gemini 2.5 Pro to suggest simple yet effective weekly learning and integration plan to adopt dbt into our existing airflow-athena/postgres data workflow in 4 weeks, one hour a day. Apply 80/20 rule for most efficient use of time. Our team size is 6, with average year of experience as data engineer of 5. Ask any clarification questions in order to craft most personal and optimal prompt.
- Also notebookLM: discover sources on many topics (airflow doc + awswrangler + dbt + athena trino) and summarize and plan, design https://www.youtube.com/watch?v=XN02F9ikYHI
- discover sources on new topic -- live demo: Spark in airflow, Spark in AWS, -- synthesize all sources to highlight the key concepts/topics/areas of technology, and to elaborate the relationships between all components, then save to note, then save as source, then choose that source and click mindmap;
- interactive audio convo -- doing something unusual for fun, active learning -- live demo: discover sources on Google IO 2025, Google IO 2025 performance of new products vs existing leaders -- repeat or summarize a point -- Veo3 is first model with native voice, how is it a breakthrough?; ask question: "any product that is completely new to the market, or is revolutionary?" comment: "wait, sorry, but i think Google claim on gemini 2.5 pro leading all benchmarks is bullshit".
- also Coding: VSCode Continue dev Claude 3.5 for quick simple coding task; use Copilot Claude 3.7 for more complicated task; (other tips: copy images of diagrams, import pdf of latest technical docs,....) for high-level task eg initial code design,
- use Prompt Writer to craft role and clarify requests, add necessary background, emphasize high-level design, avoid delving in too deep too early and quickly stuck in a loop!
- Best Practices to Avoid Getting Stuck:
    - **Experiment with examples:**
    Adjust the number and variety of examples based on the complexity of the task.
    - **Iterate and refine:**
    Prompt engineering is an iterative process, so don't be afraid to experiment and tweak the examples based on the output.
    - **Test different models:**
    Try different models to see which one performs best for your specific task.
    - **Consider alternative prompting techniques:**
    If few-shot prompting isn't enough, explore other techniques like Chain of Thought promptin

must review. prompting sota https://www.youtube.com/watch?v=DL82mGde6wo

meta-prompting techniques: system prompt xml, prompt folding (iterate on prompts), examples, graceful exits/escape hatch(complaint/debug info/suggestion to improve prompt), prompt + raw notes = improved prompt. EVAL is still Crown-jewel atm. also mentioned Palantir and latest batch of founders who are Forward Deployed Engineer who sit with customers and build demos solving their problems in days and close contracts.