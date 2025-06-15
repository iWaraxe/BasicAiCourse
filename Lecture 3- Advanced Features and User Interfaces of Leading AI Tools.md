# Beginners AI. Mastering modern AI tools

## Lecture 3: Advanced Features and User Interfaces of Leading AI Tools

### 1. Introduction: Beyond Basics

#### 1.1. Course Context and Overview

##### [seq:010] Introduction

###### SCRIPT

"Welcome back, everyone! In our first lecture, we took a critical look at generative AI—what it can and can’t do. We saw examples of bias, hallucinations, and logical errors. Then, in Lecture 2, we flipped the script and explored practical uses: from writing and debugging code to translating idioms and analyzing visuals.

Today, we go a level deeper.

This session is all about the **advanced features and user interfaces** of leading AI tools. We’ll uncover what lies beneath the surface of ChatGPT, Claude, Perplexity, and others—and show how you can use them more effectively and creatively.

Think of it as going from driving the car to popping the hood and learning how to fine-tune the engine. We’ll look at hidden UI tools, customizable assistants, token mechanics, advanced reasoning, and even how multi-agent systems work.

And yes—this is the lecture where things start to feel like science fiction. But everything I show you today is real, available, and in your hands to explore."

###### VISUAL

**Slide Title: "Lecture 3: Advanced AI Interfaces & Reasoning"**

**Layout: Split-panel slide**

- Left: Icons/logos of ChatGPT, Claude, Perplexity, Gemini
- Right:
	- "Today’s Focus:"
		- Canvas, Deep Research, and CustomGPTs
		- Claude Artefacts & Thinking Mode
		- Multi-agent AI workflows
		- Logic puzzles and reasoning tasks
		- Personal productivity automation

Visual: Sleek dashboard-style UI screenshot collage from ChatGPT, Claude, and Perplexity

###### NOTES

- Start with an energizing recap to connect emotionally with what students already experienced
- Mention that today is about building _confidence_ using these tools in complex workflows
- Joke: "Lecture 1 was about catching the AI when it lies. Lecture 2, we made it work. Today? We make it sweat."
- Tip: Let students know they’ll get to experiment with advanced prompt types and reasoning challenges by the end

###### DEMONSTRATION

**Title: "How Far Have We Come?"**

**Prompt:** "Explain the difference between ELIZA and ChatGPT using a metaphor from sports."

**Instructions:**

- Run in ChatGPT and Claude
- Read outputs aloud
- Ask students: "Which metaphor stuck with you more? Why?"

**Discussion Prompt:** "Even before we get into advanced tools—what makes a model _feel_ smart? Clarity? Creativity? Humor?"

---

### 2. Advanced UI Capabilities of AI Tools

#### 2.1. OpenAI Ecosystem

##### [seq:020] ChatGPT (OpenAI)

###### SCRIPT
"Let's start with ChatGPT—OpenAI's flagship interface. It might seem simple at first glance, but it hides powerful features that can change how you work.

With the introduction of GPT-4.1, ChatGPT can now handle exceptionally long conversations and documents, with a context window of up to 1 million tokens. This allows users to upload and analyze entire books, full project reports, or extensive datasets within a single session. It significantly enhances the depth, continuity, and scope of AI-powered assistance.

The **Canvas** feature lets you collaborate visually—a space where you can write and edit structured documents with your AI assistant. It's like a hybrid of Google Docs and ChatGPT.

Then we have **Projects** and **CustomGPTs**. Projects help you manage large, persistent workflows across documents and chats. Starting June 2025, Memory features became available to free ChatGPT users as well, providing lightweight context from recent conversations to improve response relevance—a significant democratization of personalized AI. CustomGPTs let you design your own assistant with a custom name, personality, and even tools.

There's also **Deep Research**, a feature for long-context reasoning with real-time document access. In another major June 2025 update, **Codex** rolled out to ChatGPT Plus users with optional internet access, though it's disabled by default due to complex security tradeoffs. This brings advanced coding capabilities with real-time information access—though users should be cautious about potential security implications.

And lastly, the unsung hero: **System Prompts**. These are hidden instructions that define how the model behaves in a chat."

###### VISUAL
**Slide Title: "ChatGPT Pro Features"**

- Canvas – Visual document collaboration
- Projects – Persistent workspace & memory (free users now get lightweight memory)
- CustomGPTs – Build your own assistant
- Deep Research – Document-aware exploration
- Codex – Advanced coding with optional internet access (Plus users)
- System Prompts – Hidden instructions that shape behavior
- Chart illustrating context window size differences between model versions (GPT-3, GPT-4, GPT-4.1)

Visual: Screenshots of Canvas, Project tabs, CustomGPT editor interface

###### NOTES
- **Pricing (June 2025)**: ChatGPT Pro now $200/month, Memory available to free users
- **Major Update**: Codex now available to Plus users with optional internet access (disabled by default)
- Security note: Codex internet access has complex tradeoffs, use with caution
- Reference: See OpenAI product updates and changelogs for details on GPT-4.1 capabilities
- Mention: Canvas is currently experimental and may roll out in stages
- CustomGPTs can include tools like code interpreter or browsing
- Research features available on Pro plans
- Joke: "It's like creating your own Jarvis—minus the Iron Man suit"
- Tip: Show the URL for CustomGPT builder → [https://chat.openai.com/gpts](https://chat.openai.com/gpts)

###### DEMONSTRATION
**Prompt:** "Create a CustomGPT that behaves like a stoic productivity coach."

**Instructions:**
- Go to CustomGPT builder
- Fill in basic personality instructions
- Enable code interpreter
- Run prompt: _"Give me a morning routine that aligns with stoic principles and includes 3 journal prompts."_

**Discussion Prompt:** "What kind of assistants would you build for your work or hobbies?"

**Additional Demo:** Upload a 700-page policy manual and ask GPT-4.1 to extract specific policies or generate a summary.
---

#### 2.2. Anthropic Platform

##### [seq:030] Claude (Anthropic)

###### SCRIPT

"Claude—developed by Anthropic—is focused on clarity, alignment, and ethics. Its interface is minimalist, but its features are quietly powerful.

**Thinking Mode** shows Claude’s inner reasoning—step-by-step explanations before giving a final answer. It’s like watching an AI think out loud.

**Stylized Writing** lets you request outputs in specific voices—from Shakespearean English to a middle school essay tone.

**Artefacts** are structured outputs: Claude might generate tables, summaries, outlines, or visual layouts in a dedicated panel.

**Research** is now available on Claude Pro plans as of June 2025—a BETA feature that provides integrated research assistance with synthesized information rather than direct answers. Users report that it deploys 3-4 subagents to tackle queries from multiple angles using a depth-first approach, citing '300 sources and counting' for comprehensive research tasks.

**Projects** just received a massive expansion. As of June 6, 2025, Claude Projects now supports 10 times more content and activated a new retrieval mode. This update is rolling out to all paid Claude plans and has been called a 'game changer' by the community. Projects provide persistent context across conversations, allowing you to maintain ongoing workspaces with documents, code, and research materials. The new retrieval mode enhances how Claude accesses and references information within your project, making it significantly more powerful for complex, long-term work."

###### VISUAL

**Slide Title: "Claude Features"**

- Thinking Mode – Transparent step-by-step reasoning
- Stylized Writing – Personality-infused outputs
- Artefacts – Tables, summaries, structured formats
- Research – Multi-agent research with 300+ sources (Pro BETA)
- **Projects (10x expansion!)** – Massive persistent workspaces
- Claude Code – IDE integration for development workflows

Visual: Screenshot of Claude interface with expanded Projects sidebar showing multiple documents and new retrieval mode indicator

###### NOTES

- **Pricing (June 2025)**: Anthropic Pro $100/month
- **Availability concern**: Anthropic cut Claude 3.x capacity with <5 days notice (June 2025)
- **New Feature**: Research mode (BETA) - deploys 3-4 subagents for comprehensive analysis
- Research capability: Users report 300+ sources per query, depth-first approach
- **Breaking June 6**: Projects now support 10x more content + new retrieval mode
- Projects update rolling out to all paid plans - called "game changer" by users
- Mention Claude 4 now integrates stylized writing + artefacts more smoothly
- Claude Code brings Claude 4 directly into IDEs for seamless development workflows
- Tip: Use Claude for longform content and structured logic tasks
- Joke: "Claude doesn’t just give answers. It gives receipts."

###### DEMONSTRATION

**Prompt:** "In the voice of a 1940s news reporter, explain how AI can help high school students write better essays."

**Instructions:**

- Run in Claude
- Observe stylistic output
- Enable Thinking Mode if available

---

#### 2.3. Research-Oriented Systems

##### [seq:040] Perplexity AI

###### SCRIPT

"Perplexity is part search engine, part AI assistant. It stands out for one big reason: **citations**. Every claim is backed by links, making it ideal for research, fact-checking, and comparisons.

Perplexity has **Spaces**, where users can curate structured research threads. And its **Co-Pilot Mode** offers an interactive, step-by-step retrieval experience.

Think of it as Google with a graduate degree."

###### VISUAL

**Slide Title: "Perplexity Features"**

- Real-time search + citation
- Spaces for research collaboration
- Co-pilot mode for guided exploration

Visual: Perplexity response screenshot with citation numbers, space example on a topic (e.g., climate tech)

###### NOTES

- Mention: Excellent for up-to-date info and controversial topics
- Tip: Use it to compare multiple viewpoints
- Joke: "If ChatGPT is your writer, Perplexity is your footnoting editor."

###### DEMONSTRATION

**Prompt:** "Compare the latest research on plant-based meat vs lab-grown meat. Include citations."

**Instructions:**

- Run in Perplexity
- Highlight citations and source quality

---

#### 2.4. Technical Foundations

##### [seq:050] Underlying Principles of Advanced LLM Usage

###### SCRIPT

"So far, we’ve looked at what these tools _can do_ through their interfaces. Now, let’s peel back the curtain to understand _how_ they work.

There are five essential concepts that power every interaction you have with a language model:

1. **Tokens**
2. **Context Windows**
3. **Temperature Settings**
4. **Recursive Prediction**
5. **Advanced Architectures (MoE, Edge Computing)**

A breakthrough development is Apple's Parallel-Track MoE (Mixture of Experts) architecture, which enables high-quality AI inference on edge devices like phones and laptops. This innovation allows local processing without cloud dependency, ensuring privacy while maintaining performance—a significant step toward truly personal AI assistants.

Beyond traditional architectures, we're seeing emerging paradigms that challenge how we think about AI systems. The SEAL (Self-Adapting Language Models) framework represents a significant innovation—enabling LLMs to generate their own fine-tuning data and achieve recursive self-improvement. SEAL has demonstrated remarkable results, jumping from 0% to 72.5% accuracy on ARC-AGI tasks by directly updating model weights through self-generated training data.

There's also an ongoing industry debate about system architecture: single-agent versus multi-agent approaches. While companies like Cognition argue against multi-agent systems, preferring unified models, others like Anthropic explore multi-agent research architectures. This debate reflects deeper questions about how to build more capable and reliable AI systems—whether through scaling individual models or coordinating multiple specialized agents.

Grasping these concepts will help you write smarter prompts, troubleshoot strange outputs, and fine-tune models for specific tasks."

###### VISUAL

**Slide Title: "How LLMs Think (And Why It Matters)"**

- Tokens = Model building blocks
- Context = Memory limit for input/output
- Temperature = Creativity control
- Recursive Prediction = Word-by-word construction
- MoE Architecture = Smart routing for efficient processing
- SEAL Framework = Self-improving AI through generated training data
- Architecture Debate = Single-agent vs multi-agent system approaches

Visual: Infographic with each term illustrated, including Apple's edge computing diagram

###### NOTES

- Tip: Use analogies to demystify the concepts
- Joke: "Tokens are like LEGO blocks. Too many, and you run out of space. Temperature? That’s your AI’s mood ring."
- Bonus: Mention OpenAI’s Tokenizer Tool ([https://platform.openai.com/tokenizer](https://platform.openai.com/tokenizer))

###### DEMONSTRATION

**Title: "Temperature in Action"**

**Prompt (run twice):** "Write a poetic description of the Moon."

**Settings:**

- Run once with temperature = 0.2
- Run again with temperature = 0.9

**Discussion Prompt:** "How does creativity shift? Which one would you trust for a science article? A children’s book?"

---

### 3. Advanced Reasoning Capabilities

#### 3.1. Reasoning Frameworks

##### [seq:060] Demonstrations: Advanced Reasoning and Complex Tasks

###### SCRIPT

"Now let’s take a step into the deep end: reasoning.

AI is no longer just about grammar checks or generating headlines. Today’s models can tackle logic puzzles, simulate ethical decision-making, design experiments, and even imagine alien societies.

This section is a series of carefully chosen demonstrations—each meant to stress-test the model's reasoning ability in a different dimension: logic, math, ethics, science, society, creativity, and language.

As we go through these examples, ask yourself: What is the model _really_ doing well? Where does it start to break down? And how can we design better prompts to support its thinking?"

###### VISUAL

**Slide Title: "Reasoning Dimensions in LLMs"**

- Logical reasoning
- Mathematical reasoning
- Abstract & ethical reasoning
- Scientific & strategic reasoning
- Social, spatial & linguistic reasoning

Visual: Icons or sketches representing each domain (e.g., scale for ethics, puzzle for logic, atom for science)

###### NOTES

- Joke: "Yes, the AI might beat you at logic puzzles. But it still thinks 5 ducks in a trench coat is a good business strategy."
- Tip: Ask students to guess the AI’s answer before showing the response
- Mention: Prompts in this section work best in GPT-4, Claude 3, Gemini 1.5 Pro


---

#### 3.2. Logic and Mathematics

##### [seq:070] Logic Puzzle

###### DEMONSTRATION
**Prompt:** "Three boxes labeled A, B, and C each contain either apples, oranges, or both. Box A is labeled ‘Apples’, Box B ‘Oranges’, and Box C ‘Both’. Each label is incorrect. You may choose one box and draw one piece of fruit without looking inside. What box do you choose and why?"

**Discussion Prompt:** "What kind of reasoning is the model using? Deductive or trial-and-error?"

---

##### [seq:080] Mathematical Puzzle

###### DEMONSTRATION

**Prompt:** "You have a 3-liter jug and a 5-liter jug, and unlimited water. How can you measure exactly 4 liters using only these two jugs?"

**Discussion Prompt:** "How well does the model break the problem into steps?"

---

##### [seq:090] Spatial Reasoning

###### DEMONSTRATION

**Prompt:** "A cube painted entirely red is cut into 27 smaller identical cubes. How many have paint on exactly two sides? Explain your reasoning."

**Discussion Prompt:** "Does the model correctly visualize geometry and structure?"

---

##### [seq:100] Linguistic Logic

###### DEMONSTRATION

**Prompt:** "Translate the sentence 'Every scientist is curious, but not every curious person is a scientist' into logical notation and determine its truth value."

**Discussion Prompt:** "Can the model identify universal vs existential quantifiers and preserve meaning?"

---

#### 3.3. Ethical and Abstract Reasoning

##### [seq:110] Ethical Dilemma

###### DEMONSTRATION

**Prompt:** "An autonomous vehicle must choose between two unavoidable collisions: hitting a pedestrian who illegally crossed the street, or swerving and endangering its passenger. Explain how each choice could be ethically justified and propose a decision-making framework."

**Discussion Prompt:** "Does the model sound more utilitarian or deontological? Is it biased toward protecting the user?"

---

##### [seq:120] Abstract World Simulation

###### DEMONSTRATION

**Prompt:** "Imagine a world where gravity is repulsive rather than attractive. Describe three distinct ways everyday life and society would change."

**Discussion Prompt:** "Is the AI imaginative and consistent? Does it think through consequences logically?"

---

#### 3.4. Scientific and Strategic Thinking

##### [seq:130] Scientific Reasoning

###### DEMONSTRATION

**Prompt:** "Design an experiment to test whether plants respond to classical music differently than heavy metal. Include control groups, variables, measurements, and potential conclusions."

**Discussion Prompt:** "Did the model define variables and controls clearly?"

---

##### [seq:140] Strategic Reasoning (Game Theory)

###### DEMONSTRATION

**Prompt:** "Two competing companies must decide independently whether to advertise heavily or save costs. Create a payoff matrix, identify the Nash equilibrium, and explain the strategic reasoning."

**Discussion Prompt:** "Does the AI demonstrate understanding of game theory?"

---

#### 3.5. Social and Creative Intelligence

##### [seq:150] Social Reasoning

###### DEMONSTRATION

**Prompt:** "Analyze why misinformation spreads faster than accurate information on social media. Provide at least three contributing factors and suggest mitigation strategies."

**Discussion Prompt:** "Does the AI recognize the interplay between algorithms, psychology, and design?"

---

##### [seq:160] Creative Reasoning

###### DEMONSTRATION

**Prompt:** "Imagine humans have built a colony on Mars. Invent a political or social system unique to the Martian environment that solves a local problem."

**Discussion Prompt:** "How inventive is the model? Is the system plausible, or just whimsical?"

---

#### 3.5. AI Agents and Development Environments

##### [seq:162] Autonomous AI Agents

###### SCRIPT

"Beyond chatbots, we now have **AI agents**—programs that can actually do things for you. They can browse the web, fill out forms, write reports, and even build entire websites.

**Manus** is an AI agent with its own computer. It can research topics, create documents, and complete multi-step tasks autonomously. But be careful—users report privacy concerns, including increased spam after providing phone numbers.

**PicoCreator** focuses on reliability, achieving near 100% task completion on sites like Amazon, Gmail, and LinkedIn. It's designed for routine tasks you do every day.

These agents represent a shift from AI that answers questions to AI that takes actions. But with this power comes responsibility—and risk."

###### VISUAL

**Title: "AI That Acts, Not Just Answers"**

- Agent Comparison:
  - ChatGPT: Conversational, advisory
  - Manus: Full computer access, autonomous
  - PicoCreator: Reliable routine tasks
- Capabilities:
  - Web browsing and research
  - Form filling and data entry
  - Report writing and analysis
  - Website building

###### NOTES

- Manus requires phone number, privacy concerns reported
- PicoCreator targets 100% reliability on routine tasks
- Cost: Varies by usage, often credit-based
- Security tip: Use separate accounts/sandboxes for AI agents
- Warning: Agents can access sensitive data if not properly configured

###### DEMONSTRATION

Show an AI agent completing a multi-step task:
1. Research a topic online
2. Compile findings into a report
3. Format and save the document
Discuss security implications and best practices

---

##### [seq:164] AI Development Environments

###### SCRIPT

"For developers, AI has moved beyond chat interfaces into our code editors. These environments don't just suggest code—they understand entire projects.

**Cursor** pioneered AI-native development and just released version 1.0 in June 2025, featuring enhanced code review capabilities that remember previous mistakes, improved error tracking, and the ability to handle multiple background tasks simultaneously. However, it now faces significant competition. **Windsurf** offers similar features with Claude 4 support and better pricing. Both let AI see your entire codebase, suggest changes, and even implement features across multiple files.

**Claude Code** brings Anthropic's models directly into IDEs, excelling at understanding large codebases and maintaining context across complex projects. The community has declared Claude Code superior to Cursor for specific tasks, with users reporting successful one-shot refactoring of large, complex codebases that pass thousands of tests without errors.

The key innovation? These tools don't just complete lines of code—they understand architecture, suggest refactors, and can implement entire features with guidance."

###### VISUAL

**Title: "AI-Powered Development Environments"**

- Feature comparison table:
  - VS Code + Copilot: Basic completion
  - Cursor 1.0: Enhanced code review, error tracking, background tasks
  - Windsurf: Claude 4 support, competitive pricing
  - Claude Code: Superior context understanding, one-shot refactoring
- Workflow diagram: Code → AI Analysis → Suggestions → Implementation

###### NOTES

- **June 2025**: Cursor 1.0 released with enhanced features, background tasks
- Community verdict: Claude Code declared superior for specific refactoring tasks
- Cursor subscription concerns: $20/month may not be profitable
- Windsurf emerging as strong alternative
- Privacy: Code sent to cloud for analysis
- Best practice: Review all AI-generated code carefully
- Cost comparison: API usage can exceed subscription fees

###### DEMONSTRATION

Live coding session showing:
- AI understanding project structure
- Multi-file refactoring suggestions
- Bug detection and fixes
Compare traditional coding vs AI-assisted development

---

### 4. Task-Specific AI Solutions

#### 4.1. Personalized Assistants

##### [seq:170] Advanced Task Automation and Personalized GPTs

###### SCRIPT

"Let’s shift from reasoning to something more practical: task automation.

Modern LLMs don’t just respond to queries—they can run schedules, track goals, remind you about priorities, and act like personalized assistants.

In this section, we’ll explore how to:

- Create **automated daily routines**
- Build **specialized GPTs** tailored to your needs
- Use GPTs to manage long-term projects, reviews, and self-improvement

This is where AI becomes a co-pilot for your productivity."

###### VISUAL

**Slide Title: "From Chatbot to Assistant"**

- Schedule tasks and reminders
- Generate daily reflections and learning prompts
- Build domain-specific GPTs (e.g., Java Assistant, Language Tutor)

Visual: Timeline-style graphic with GPT-generated events (e.g., 9am: Tech news, 12pm: Stretch reminder, 5pm: Daily reflection)

###### NOTES

- Joke: "Finally, a to-do list that talks back—and sometimes sounds smarter than you."
- Tip: Highlight how GPTs can reference previous interactions when memory is enabled
- Mention: Personal GPTs can include tools like code interpreter or web browsing

---

#### 4.2. Productivity Applications

##### [seq:180] Demonstration A – Task Scheduler GPT

###### DEMONSTRATION
**Prompt:** "Every weekday morning at 9am, summarize key tech headlines in AI, software, and cloud computing. Then ask which I want to read further."

**Instructions:**

- Run prompt in a CustomGPT with memory and browsing enabled
- Show sample result, including follow-up suggestion or tracking feature

**Discussion Prompt:** "What’s one task in your life that you’d love to automate with this approach?"

---

##### [seq:190] Demonstration B – Personalized GPT (Polish Language Tutor)

###### DEMONSTRATION

**Prompt Example:** "Translate the word 'dom' into English, Belarusian, Ukrainian, and Russian. Provide grammatical forms (singular, plural, genitive, etc.), and give 2 usage examples."

**Instructions:**

- Create a CustomGPT with structured response style and minimalist tone
- Show how GPT keeps format consistent and ready for flashcard use

**Discussion Prompt:** "What could you learn faster with a GPT like this helping every day?"

---

##### [seq:200] Demonstration C – Java Spring Boot Assistant GPT

###### DEMONSTRATION

**Prompt Example:** "Generate a basic Spring Boot controller that uses an AI API to summarize text. Include error handling and service layer separation."

**Instructions:**

- Run in a coding-focused GPT with tools enabled
- Review code for structure and clarity

**Discussion Prompt:** "How would a GPT like this speed up your development workflow?"

---

#### 4.3. Domain-Specific Applications

##### [seq:210] Specialized GPT Applications and Integrations

###### SCRIPT

"Now let’s go even more specific—into GPTs created for highly specialized tasks.

While many GPTs aim to be general-purpose, others are fine-tuned for niche use cases: from language learning to software engineering. These GPTs often combine structured behavior, domain knowledge, and tailored prompts to deliver consistent, high-value support.

In this section, we’ll walk through a few powerful use cases that demonstrate the range of what’s possible. These aren’t just toys—they’re tools professionals are beginning to rely on every day."

###### VISUAL

**Slide Title: "Niche GPTs for Power Users"**

- Language Learning GPT: Grammar, usage, translations
- Coding Assistant GPT: Framework-specific guidance
- Research GPT: Summarize, cite, compare scholarly material
- Personal Wellness GPT: Reflective journaling, mood check-ins

Visual: Grid of GPT tiles with logos or mock personas (e.g., "SpringBot," "LinguaTutor," "InsightGPT")

###### NOTES

- Mention: Many CustomGPTs shared publicly at [https://chat.openai.com/gpts/explore](https://chat.openai.com/gpts/explore)
- Joke: "You’ve heard of task rabbits. These are task Cheetahs—fast, focused, and tireless."
- Tip: Think of GPTs as skill boosters—not general AI, but role-players with purpose

---

##### [seq:220] Demonstration A – Language Learning GPT (Polish Example)

###### DEMONSTRATION

**Prompt:** "Translate the word 'miłość' into English, Belarusian, Ukrainian, and Russian. Show grammatical cases and two usage examples."

**Instructions:**

- Highlight the clean, consistent format
- Show how this can become part of a spaced repetition system

**Discussion Prompt:** "What feature would make this GPT even better for your language goals?"

---

##### [seq:230] Demonstration B – Spring Boot AI Assistant GPT

###### DEMONSTRATION

**Prompt:** "Suggest an architecture for integrating OpenAI API with Spring Boot using clean architecture. Include services, controller, and config layers."

**Instructions:**

- Run prompt in specialized Java development GPT
- Discuss architectural decisions and trade-offs it proposes

**Discussion Prompt:** "Would you trust this GPT for scaffolding your next project? Why or why not?"

---

##### [seq:240] Demonstration C – Self-Reflection Coach GPT

###### DEMONSTRATION

**Prompt:** "Ask me three questions to reflect on my day. Then summarize what I might be feeling and suggest one thing I could do tomorrow to improve."

**Instructions:**

- Use wellness-focused GPT or CustomGPT with emotional intelligence design
- Show how model adapts tone based on reflection

**Discussion Prompt:** "What domains of your life could benefit from a personal AI like this?"

---

### 5. Advanced Information Processing

#### 5.1. Knowledge Retrieval Systems

##### [seq:250] Advanced Information Retrieval and Data Analysis

###### SCRIPT

"Next up—let’s talk about information.

One of the most underrated capabilities of advanced LLMs is their ability to search, summarize, and contextualize information at scale.

Modern AI tools can:

- Retrieve facts from multiple sources
- Compare perspectives in real time
- Analyze uploaded documents, from invoices to legal texts
- Generate summaries, visualizations, and decision-ready insights

In this section, we’ll explore how models like ChatGPT, Claude, Gemini, and Perplexity retrieve, process, and deliver knowledge—and where they differ."

###### VISUAL

**Slide Title: "LLMs as Research Analysts"**

- Contextual search (web-connected)
- Multi-document analysis
- Summarization & synthesis
- Visualizations & comparisons

Visual: Side-by-side layout of an uploaded PDF, chart, and summarized output

###### NOTES

- Tip: Mention that Claude is especially strong at long document parsing
- Joke: "It’s like hiring four interns—who never sleep and cite their sources."
- Mention: Gemini and Perplexity excel at real-time info, ChatGPT excels with structured analysis if you prep the input

---

#### 5.2. Research and Analysis Tools

##### [seq:260] Demonstration A – Real-time Research Comparison

###### DEMONSTRATION

**Prompt:** "Compare the latest research on the effectiveness of mindfulness apps vs cognitive behavioral therapy for anxiety. Include citations and source bias where possible."

**Instructions:**

- Run in Perplexity and Gemini
- Highlight differences in citation styles, depth, and neutrality

**Discussion Prompt:** "Which system gave you more actionable insight? Which one felt more trustworthy?"

---

##### [seq:270] Demonstration B – Document Summarization

###### DEMONSTRATION

**Prompt:** "Summarize this 10-page PDF (upload a sample) and extract the key financial risks mentioned."

**Instructions:**

- Upload a PDF (e.g., annual report or contract excerpt) into Claude and ChatGPT
- Compare summary clarity, key term recognition, and structure

**Discussion Prompt:** "What would you want the AI to highlight more clearly next time?"

---

##### [seq:280] Demonstration C – Data Visualization from Structured Text

###### DEMONSTRATION

**Prompt:** "Here is sales data for the last 6 months. Create a bar chart comparing monthly totals and identify one trend and one anomaly."

**Instructions:**

- Paste structured data into ChatGPT or Claude with tools enabled
- Show both visual output and accompanying analysis

**Discussion Prompt:** "Would you use this to prep for a real presentation? Why or why not?"

---

#### 5.3. Advanced Cognitive Techniques

##### [seq:290] Advanced Reasoning Techniques

###### SCRIPT

"We’ve seen that LLMs can reason in fascinating ways—but how do we make them more deliberate, structured, and accurate?

That’s where advanced reasoning techniques come in. These strategies guide the model to:

- Break problems into smaller parts
- Think through a question step by step
- Maintain consistency across complex outputs
- Collaborate with other agents

In this section, we’ll look at techniques like Chain-of-Thought, ReAct, and system-specific reasoning optimizations that help AI deliver better results, especially for complex or ambiguous tasks."

###### VISUAL

**Slide Title: "Making AI Think (More) Like Us"**

- Chain-of-Thought Reasoning
- Multi-step Decomposition
- ReAct (Reason + Act)
- AutoThink (Adaptive Reasoning - New!)
- System-Specific Optimization (ChatGPT vs Claude vs Gemini)

Visual: Flowchart of a reasoning prompt broken into intermediate steps with annotations

###### NOTES

- NEW: AutoThink technique improves reasoning performance by 43% on GPQA-Diamond benchmarks
- AutoThink classifies query complexity and dynamically allocates "thinking tokens"
- Works with any local reasoning model (DeepSeek, Qwen, Llama)
- These techniques often make a huge difference for math, logic, and planning tasks
- Joke: "AI may not sleep—but it does better with a to-do list."
- ReAct combines reasoning and action in a loop for better results

---

##### [seq:300] Demonstration A – Chain-of-Thought Prompting

###### DEMONSTRATION

**Prompt:** "If Alice is older than Bob, and Bob is older than Charlie, who is the oldest? Explain your reasoning."

**Instructions:**

- Run prompt in Claude, Gemini, and ChatGPT
- Ask the model to explain before answering (or use “Let’s think step by step”)

**Discussion Prompt:** "How does the explanation change your confidence in the answer?"

---

##### [seq:310] Demonstration B – Task Decomposition

###### DEMONSTRATION

**Prompt:** "Plan a one-week team retreat for 15 software engineers, including logistics, agenda, and team-building activities."

**Instructions:**

- Use prompt in ChatGPT or Claude
- Highlight how the model breaks the problem down (e.g., travel, meals, sessions, free time)

**Discussion Prompt:** "What parts did the model handle well? Where would you still want human oversight?"

---

##### [seq:320] Demonstration C – ReAct Pattern (Reasoning + Acting)

###### DEMONSTRATION

**Prompt:** "You are a researcher trying to find a reliable source about the environmental impact of cryptocurrency mining. Think step by step, then use web tools to find and cite at least two credible sources."

**Instructions:**

- Use a GPT with browsing or Perplexity AI
- Highlight how it reasons, searches, and cites in one process

**Discussion Prompt:** "Did the model make good decisions in choosing what to search and how to summarize?"

---

##### [seq:330] Demonstration D – Comparing Models on Complex Reasoning

###### DEMONSTRATION

**Prompt:** "Design a basic governance system for an autonomous Martian colony that ensures both individual rights and resource sustainability."

**Instructions:**

- Run the same prompt in ChatGPT, Claude, and Gemini
- Compare structure, originality, feasibility of each answer

**Discussion Prompt:** "Which model handled the tradeoffs best? Who had the most ‘human-like’ reasoning?"

---

### 6. Collaborative AI Systems

#### 6.1. Multi-Agent Frameworks

##### [seq:340] Multi-Agent and Autonomous AI Systems

###### SCRIPT

"So far, we’ve been working with individual models—one question, one answer. But what happens when you put multiple AIs to work together on the same task?

Welcome to the world of **multi-agent systems**: collaborative AI workflows where different agents specialize, delegate, verify, and even debate.

These systems are a glimpse into the future of how AI will be used—autonomous teams of models handling research, planning, coding, testing, and writing with minimal human oversight.

We’ll walk through how these agents communicate, assign roles, and resolve conflicts, and explore tools and frameworks that make this possible today."

###### VISUAL

**Slide Title: "From One AI to Many"**

- Multi-agent orchestration
- Role specialization (planner, coder, reviewer)
- Task delegation & feedback loops
- Conflict resolution among agents

Visual: Diagram of three AI agents passing tasks to each other with roles labeled (e.g., Thinker → Coder → Tester)

###### NOTES

- Joke: "Finally, an AI team meeting without coffee or small talk."
- Tip: Multi-agent systems aren’t science fiction—they’re being used in autonomous coding, task planning, and document review
- Mention: Tools like AutoGen, CrewAI, and OpenDevin are leading this field

###### DEMONSTRATION

**Scenario Prompt:** "You are part of a 3-agent team building a simple web app. Agent A: Define user requirements. Agent B: Design architecture. Agent C: Write the code. Collaborate and pass results between agents."

**Instructions:**

- Use a platform like AutoGen or simulate roles in ChatGPT
- Show how output builds step-by-step, with refinement and role clarity

**Discussion Prompt:** "Would you trust this team to start your next software project? Why or why not?"

---

#### 6.2. Agent Communication Standards

##### [seq:345] Model Context Protocol (MCP): The Language of AI Agents

###### SCRIPT

"Now that we've seen multi-agent systems in action, let's talk about how they actually communicate. One of the most significant developments from June 2025 is the rapid adoption of the **Model Context Protocol (MCP)**—essentially becoming the standard language for AI agents to talk to each other.

Think of MCP like HTTP for AI agents. Just as web browsers and servers needed a common protocol to exchange information, AI agents need a standardized way to share context, tools, and capabilities. MCP is solving this problem.

What makes MCP powerful is that it enables dynamic tool registration—agents can discover and use each other's capabilities on the fly. It's being adopted across major platforms including Claude Desktop, LlamaIndex, and HuggingFace. The community has rallied around it, with hackathons offering significant prizes for MCP-based innovations.

This means you can now connect different AI systems—your Claude desktop app can talk to specialized tools, your coding assistant can access external databases, and agents can collaborate without being from the same vendor. It's the foundation for truly interoperable AI systems."

###### VISUAL

**Slide Title: "MCP: The Universal Language for AI Agents"**

- What is MCP?
  - Model Context Protocol - standardized agent communication
  - Like HTTP but for AI systems
  - Enables tool discovery and sharing
- Key features:
  - Dynamic tool registration
  - Cross-platform compatibility
  - Human-readable strategies
- Adoption:
  - Claude Desktop integration
  - LlamaIndex and HuggingFace support
  - $16.5k in hackathon prizes driving innovation

Visual: Diagram showing multiple AI agents (Claude, GPT, custom agents) connected via MCP protocol

###### NOTES

- MCP uses stdio transport for local connections
- The schema.json/.ts file defines the protocol specification
- Practical applications: voice control of Android devices, AI browser automation
- MCP servers can now connect to knowledge stores for RAG (Retrieval Augmented Generation)
- Community-driven: rapid adoption shows the need for standardization

###### LINKS
- https://github.com/anthropics/model-context-protocol

###### DEMONSTRATION

**Demo - MCP in Action:**

"Let's see how MCP enables agent collaboration:"

1. "Show me how to connect a Claude desktop app to a custom MCP server"
2. "Demonstrate dynamic tool registration where one agent discovers another's capabilities"
3. "Create a simple workflow where agents pass context using MCP"

**Instructions:**
- Show MCP server setup using stdio transport
- Demonstrate tool discovery process
- Highlight the human-readable nature of exchanges

**Discussion:** "How could standardized agent communication change the way we build AI applications?"

---

### 7. Hands-On Learning

#### 7.1. Interactive Exercises

##### [seq:350] Hands-On Activity: Advanced Prompt Exploration

###### SCRIPT

"It’s time to shift from watching to doing.

In this hands-on section, you’ll get to experiment with prompts across different platforms and reasoning types. The goal isn’t to find the ‘best’ answer—but to understand how your wording, model choice, and context shape the output.

We’ve grouped prompts by type—writing, logic, visuals, analysis—and you can remix or invent your own. Try comparing Claude, ChatGPT, Gemini, and Perplexity on the same task.

This is your chance to explore, break things, laugh at strange outputs, and learn by doing."

###### VISUAL

**Slide Title: "Try It Yourself: Prompt Playground"**

- Use the provided prompt library or create your own
- Test across 2–3 different models
- Observe differences in tone, depth, accuracy
- Document: What surprised you? What worked well?

Visual: Screenshots of the same prompt run in multiple models side-by-side

###### NOTES

- Joke: “Yes, you are now allowed to confuse the AI. Responsibly.”
- Tip: Encourage screenshots and share-outs at the end
- Mention: Prompt remixing is a great way to uncover model personalities

---

##### [seq:360] Prompt Categories (for Participants)

###### DEMONSTRATION

- **Writing:** Rewrite text in a famous author’s style
- **Logic:** Solve a classic riddle with explanation
- **Creative:** Design a new holiday or space colony
- **Code:** Debug a broken function you bring
- **Visual:** Upload an image and describe what’s happening
- **Data:** Upload a document or chart and ask for summary or analysis

---

##### [seq:370] Activity Instructions

###### DEMONSTRATION

**Setup:**

- Choose one or more prompt categories
- Run in at least two different AI tools
- Note how models differ in tone, clarity, creativity, and structure

**Optional Challenge:**

- Try confusing the model—then try improving the prompt to help it recover

**Share & Reflect:**

- Choose one fun or insightful output to share
- Reflect on: What did the model miss? What was unexpectedly good?

---

#### 7.2. Continued Practice

##### [seq:380] Homework: Prompt Library Exploration

###### SCRIPT

"To keep the momentum going after class, I’ve prepared a guided homework assignment. Your task is to explore our curated **Prompt Library** and experiment with:

- At least 3 different types of prompts
- At least 2 different AI systems

You’ll document what you tried, how the models performed, and what surprised you. This isn’t about right or wrong—it’s about developing **prompt intuition**."

###### VISUAL

**Slide Title: "Homework: Explore & Reflect"**

- Use Prompt Library (link provided)
- Choose 3+ prompts from different domains
- Compare results across tools
- Record:
	- Prompt used
	- Tools tested
	- What worked / what didn’t

Visual: Example homework template or table filled in with sample entries

###### NOTES

- Joke: “Yes, this time you’re encouraged to talk to strangers—AI strangers.”
- Tip: Focus on clarity of prompts, differences in tone and depth
- Mention: Template available via Google Docs or Notion (link provided in class)

---

##### [seq:390] Resources for Continuous Learning

###### SCRIPT

"Before we wrap, here are a few places you can go next to keep learning, experimenting, and connecting.

AI is moving fast, but you don’t have to keep up alone. There are prompt libraries, communities, newsletters, and amazing projects emerging every day.

Here’s your starter kit."

###### VISUAL

**Slide Title: "Your AI Toolkit"**

- Prompt Libraries:
	- [OpenAI Prompt Library](https://platform.openai.com/examples)
	- [FlowGPT](https://flowgpt.com/)
- Tools to Bookmark:
	- [ChatGPT](https://chat.openai.com/)
	- [Claude](https://claude.ai/)
	- [Gemini](https://gemini.google.com/)
	- [Perplexity](https://www.perplexity.ai/)
- Exploratory Tools:
	- [ChatGPT macOS app](https://openai.com/chat)
	- [VS Code + GitHub Copilot](https://github.com/features/copilot)
	- [Windsurf](https://windsurf.ai/) - Cursor alternative with Claude 4 support
	- [IntelliJ AI Assistant](https://www.jetbrains.com/idea/whatsnew/#ai)
- Stay Updated:
	- [Ben’s Bites](https://www.bensbites.co/)
	- [TLDR AI](https://www.tldr.tech/ai)

###### NOTES

- Joke: “Think of FlowGPT as your AI recipe book—and you’re the chef.”
- Tip: Encourage bookmarking and regular exploration—prompting gets better with play
- Mention: Follow AI-related YouTube channels, Substacks, or Discord servers if you want community

---