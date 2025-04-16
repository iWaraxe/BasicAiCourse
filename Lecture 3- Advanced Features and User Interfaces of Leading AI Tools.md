## Lecture 3: Advanced Features and User Interfaces of Leading AI Tools

### 1. Introduction: Beyond Basics

#### 1.1. Script

"Welcome back, everyone! In our first lecture, we took a critical look at generative AI—what it can and can’t do. We saw examples of bias, hallucinations, and logical errors. Then, in Lecture 2, we flipped the script and explored practical uses: from writing and debugging code to translating idioms and analyzing visuals.

Today, we go a level deeper.

This session is all about the **advanced features and user interfaces** of leading AI tools. We’ll uncover what lies beneath the surface of ChatGPT, Claude, Perplexity, and others—and show how you can use them more effectively and creatively.

Think of it as going from driving the car to popping the hood and learning how to fine-tune the engine. We’ll look at hidden UI tools, customizable assistants, token mechanics, advanced reasoning, and even how multi-agent systems work.

And yes—this is the lecture where things start to feel like science fiction. But everything I show you today is real, available, and in your hands to explore."

---

#### 1.2. Slide

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

---

#### 1.3. Slide Notes

- Start with an energizing recap to connect emotionally with what students already experienced
- Mention that today is about building _confidence_ using these tools in complex workflows
- Joke: "Lecture 1 was about catching the AI when it lies. Lecture 2, we made it work. Today? We make it sweat."
- Tip: Let students know they’ll get to experiment with advanced prompt types and reasoning challenges by the end

---

#### 1.4. Demonstration (Optional Warm-Up)

**Title: "How Far Have We Come?"**

**Prompt:** "Explain the difference between ELIZA and ChatGPT using a metaphor from sports."

**Instructions:**

- Run in ChatGPT and Claude
- Read outputs aloud
- Ask students: "Which metaphor stuck with you more? Why?"

**Discussion Prompt:** "Even before we get into advanced tools—what makes a model _feel_ smart? Clarity? Creativity? Humor?"

---
### 2. Advanced UI Capabilities of AI Tools

#### 2.1. ChatGPT (OpenAI)

##### 2.1.1. Script

"Let’s start with ChatGPT—OpenAI’s flagship interface. It might seem simple at first glance, but it hides powerful features that can change how you work.

The **Canvas** feature lets you collaborate visually—a space where you can write and edit structured documents with your AI assistant. It’s like a hybrid of Google Docs and ChatGPT.

Then we have **Projects** and **CustomGPTs**. Projects help you manage large, persistent workflows across documents and chats. CustomGPTs let you design your own assistant with a custom name, personality, and even tools.

There’s also **Deep Research**, a feature for long-context reasoning with real-time document access. And lastly, the unsung hero: **System Prompts**. These are hidden instructions that define how the model behaves in a chat."

---

##### 2.1.2. Slide

**Slide Title: "ChatGPT Pro Features"**

- Canvas – Visual document collaboration
- Projects – Persistent workspace & memory
- CustomGPTs – Build your own assistant
- Deep Research – Document-aware exploration
- System Prompts – Hidden instructions that shape behavior

Visual: Screenshots of Canvas, Project tabs, CustomGPT editor interface

---

##### 2.1.3. Slide Notes

- Mention: Canvas is currently experimental and may roll out in stages
- CustomGPTs can include tools like code interpreter or browsing
- Joke: "It’s like creating your own Jarvis—minus the Iron Man suit"
- Tip: Show the URL for CustomGPT builder → [https://chat.openai.com/gpts](https://chat.openai.com/gpts)

---

##### 2.1.4. Demonstration

**Prompt:** "Create a CustomGPT that behaves like a stoic productivity coach."

**Instructions:**

- Go to CustomGPT builder
- Fill in basic personality instructions
- Enable code interpreter
- Run prompt: _"Give me a morning routine that aligns with stoic principles and includes 3 journal prompts."_

**Discussion Prompt:** "What kind of assistants would you build for your work or hobbies?"

---

#### 2.2. Claude (Anthropic)

##### 2.2.1. Script

"Claude—developed by Anthropic—is focused on clarity, alignment, and ethics. Its interface is minimalist, but its features are quietly powerful.

**Thinking Mode** shows Claude’s inner reasoning—step-by-step explanations before giving a final answer. It’s like watching an AI think out loud.

**Stylized Writing** lets you request outputs in specific voices—from Shakespearean English to a middle school essay tone.

**Artefacts** are structured outputs: Claude might generate tables, summaries, outlines, or visual layouts in a dedicated panel."

---

##### 2.2.2. Slide

**Slide Title: "Claude Features"**

- Thinking Mode – Transparent step-by-step reasoning
- Stylized Writing – Personality-infused outputs
- Artefacts – Tables, summaries, structured formats

Visual: Screenshot of Claude interface with Thinking Mode active and Artefact result panel

---

##### 2.2.3. Slide Notes

- Mention Claude 3 now integrates stylized writing + artefacts more smoothly
- Tip: Use Claude for longform content and structured logic tasks
- Joke: "Claude doesn’t just give answers. It gives receipts."

---

##### 2.2.4. Demonstration

**Prompt:** "In the voice of a 1940s news reporter, explain how AI can help high school students write better essays."

**Instructions:**

- Run in Claude
- Observe stylistic output
- Enable Thinking Mode if available

---

#### 2.3. Perplexity AI

##### 2.3.1. Script

"Perplexity is part search engine, part AI assistant. It stands out for one big reason: **citations**. Every claim is backed by links, making it ideal for research, fact-checking, and comparisons.

Perplexity has **Spaces**, where users can curate structured research threads. And its **Co-Pilot Mode** offers an interactive, step-by-step retrieval experience.

Think of it as Google with a graduate degree."

---

##### 2.3.2. Slide

**Slide Title: "Perplexity Features"**

- Real-time search + citation
- Spaces for research collaboration
- Co-pilot mode for guided exploration

Visual: Perplexity response screenshot with citation numbers, space example on a topic (e.g., climate tech)

---

##### 2.3.3. Slide Notes

- Mention: Excellent for up-to-date info and controversial topics
- Tip: Use it to compare multiple viewpoints
- Joke: "If ChatGPT is your writer, Perplexity is your footnoting editor."

---

##### 2.3.4. Demonstration

**Prompt:** "Compare the latest research on plant-based meat vs lab-grown meat. Include citations."

**Instructions:**

- Run in Perplexity
- Highlight citations and source quality

---

Next up: **3. Underlying Principles of Advanced LLM Usage**?


---

### 3. Underlying Principles of Advanced LLM Usage

#### 3.1. Script

"So far, we’ve looked at what these tools _can do_ through their interfaces. Now, let’s peel back the curtain to understand _how_ they work.

There are four essential concepts that power every interaction you have with a language model:

1. **Tokens**
2. **Context Windows**
3. **Temperature Settings**
4. **Recursive Prediction**

Grasping these concepts will help you write smarter prompts, troubleshoot strange outputs, and fine-tune models for specific tasks."

---

#### 3.2. Slide

**Slide Title: "How LLMs Think (And Why It Matters)"**

- Tokens = Model building blocks
- Context = Memory limit for input/output
- Temperature = Creativity control
- Recursive Prediction = Word-by-word construction

Visual: Infographic with each term illustrated

---

#### 3.3. Slide Notes

- Tip: Use analogies to demystify the concepts
- Joke: "Tokens are like LEGO blocks. Too many, and you run out of space. Temperature? That’s your AI’s mood ring."
- Bonus: Mention OpenAI’s Tokenizer Tool ([https://platform.openai.com/tokenizer](https://platform.openai.com/tokenizer))

---

#### 3.4. Demonstration

**Title: "Temperature in Action"**

**Prompt (run twice):** "Write a poetic description of the Moon."

**Settings:**

- Run once with temperature = 0.2
- Run again with temperature = 0.9

**Discussion Prompt:** "How does creativity shift? Which one would you trust for a science article? A children’s book?"

---
### 4. Demonstrations: Advanced Reasoning and Complex Tasks

#### 4.1. Script

"Now let’s take a step into the deep end: reasoning.

AI is no longer just about grammar checks or generating headlines. Today’s models can tackle logic puzzles, simulate ethical decision-making, design experiments, and even imagine alien societies.

This section is a series of carefully chosen demonstrations—each meant to stress-test the model's reasoning ability in a different dimension: logic, math, ethics, science, society, creativity, and language.

As we go through these examples, ask yourself: What is the model _really_ doing well? Where does it start to break down? And how can we design better prompts to support its thinking?"

---

#### 4.2. Slide

**Slide Title: "Reasoning Dimensions in LLMs"**

- Logical reasoning
- Mathematical reasoning
- Abstract & ethical reasoning
- Scientific & strategic reasoning
- Social, spatial & linguistic reasoning

Visual: Icons or sketches representing each domain (e.g., scale for ethics, puzzle for logic, atom for science)

---

#### 4.3. Slide Notes

- Joke: "Yes, the AI might beat you at logic puzzles. But it still thinks 5 ducks in a trench coat is a good business strategy."
- Tip: Ask students to guess the AI’s answer before showing the response
- Mention: Prompts in this section work best in GPT-4, Claude 3, Gemini 1.5 Pro

---

#### 4.4. Demonstration Series

##### 4.4.1. Logic Puzzle

**Prompt:** "Three boxes labeled A, B, and C each contain either apples, oranges, or both. Box A is labeled ‘Apples’, Box B ‘Oranges’, and Box C ‘Both’. Each label is incorrect. You may choose one box and draw one piece of fruit without looking inside. What box do you choose and why?"

**Discussion Prompt:** "What kind of reasoning is the model using? Deductive or trial-and-error?"

---

##### 4.4.2. Mathematical Puzzle

**Prompt:** "You have a 3-liter jug and a 5-liter jug, and unlimited water. How can you measure exactly 4 liters using only these two jugs?"

**Discussion Prompt:** "How well does the model break the problem into steps?"

---

##### 4.4.3. Ethical Dilemma

**Prompt:** "An autonomous vehicle must choose between two unavoidable collisions: hitting a pedestrian who illegally crossed the street, or swerving and endangering its passenger. Explain how each choice could be ethically justified and propose a decision-making framework."

**Discussion Prompt:** "Does the model sound more utilitarian or deontological? Is it biased toward protecting the user?"

---

##### 4.4.4. Abstract World Simulation

**Prompt:** "Imagine a world where gravity is repulsive rather than attractive. Describe three distinct ways everyday life and society would change."

**Discussion Prompt:** "Is the AI imaginative and consistent? Does it think through consequences logically?"

---

##### 4.4.5. Scientific Reasoning

**Prompt:** "Design an experiment to test whether plants respond to classical music differently than heavy metal. Include control groups, variables, measurements, and potential conclusions."

**Discussion Prompt:** "Did the model define variables and controls clearly?"

---

##### 4.4.6. Strategic Reasoning (Game Theory)

**Prompt:** "Two competing companies must decide independently whether to advertise heavily or save costs. Create a payoff matrix, identify the Nash equilibrium, and explain the strategic reasoning."

**Discussion Prompt:** "Does the AI demonstrate understanding of game theory?"

---

##### 4.4.7. Social Reasoning

**Prompt:** "Analyze why misinformation spreads faster than accurate information on social media. Provide at least three contributing factors and suggest mitigation strategies."

**Discussion Prompt:** "Does the AI recognize the interplay between algorithms, psychology, and design?"

---

##### 4.4.8. Creative Reasoning

**Prompt:** "Imagine humans have built a colony on Mars. Invent a political or social system unique to the Martian environment that solves a local problem."

**Discussion Prompt:** "How inventive is the model? Is the system plausible, or just whimsical?"

---

##### 4.4.9. Spatial Reasoning

**Prompt:** "A cube painted entirely red is cut into 27 smaller identical cubes. How many have paint on exactly two sides? Explain your reasoning."

**Discussion Prompt:** "Does the model correctly visualize geometry and structure?"

---

##### 4.4.10. Linguistic Logic

**Prompt:** "Translate the sentence 'Every scientist is curious, but not every curious person is a scientist' into logical notation and determine its truth value."

**Discussion Prompt:** "Can the model identify universal vs existential quantifiers and preserve meaning?"

---
### 5. Advanced Task Automation and Personalized GPTs

#### 5.1. Script

"Let’s shift from reasoning to something more practical: task automation.

Modern LLMs don’t just respond to queries—they can run schedules, track goals, remind you about priorities, and act like personalized assistants.

In this section, we’ll explore how to:

- Create **automated daily routines**
- Build **specialized GPTs** tailored to your needs
- Use GPTs to manage long-term projects, reviews, and self-improvement

This is where AI becomes a co-pilot for your productivity."

---

#### 5.2. Slide

**Slide Title: "From Chatbot to Assistant"**

- Schedule tasks and reminders
- Generate daily reflections and learning prompts
- Build domain-specific GPTs (e.g., Java Assistant, Language Tutor)

Visual: Timeline-style graphic with GPT-generated events (e.g., 9am: Tech news, 12pm: Stretch reminder, 5pm: Daily reflection)

---

#### 5.3. Slide Notes

- Joke: "Finally, a to-do list that talks back—and sometimes sounds smarter than you."
- Tip: Highlight how GPTs can reference previous interactions when memory is enabled
- Mention: Personal GPTs can include tools like code interpreter or web browsing

---

#### 5.4. Demonstration A – Task Scheduler GPT

**Prompt:** "Every weekday morning at 9am, summarize key tech headlines in AI, software, and cloud computing. Then ask which I want to read further."

**Instructions:**

- Run prompt in a CustomGPT with memory and browsing enabled
- Show sample result, including follow-up suggestion or tracking feature

**Discussion Prompt:** "What’s one task in your life that you’d love to automate with this approach?"

---

#### 5.5. Demonstration B – Personalized GPT (Polish Language Tutor)

**Prompt Example:** "Translate the word 'dom' into English, Belarusian, Ukrainian, and Russian. Provide grammatical forms (singular, plural, genitive, etc.), and give 2 usage examples."

**Instructions:**

- Create a CustomGPT with structured response style and minimalist tone
- Show how GPT keeps format consistent and ready for flashcard use

**Discussion Prompt:** "What could you learn faster with a GPT like this helping every day?"

---

#### 5.6. Demonstration C – Java Spring Boot Assistant GPT

**Prompt Example:** "Generate a basic Spring Boot controller that uses an AI API to summarize text. Include error handling and service layer separation."

**Instructions:**

- Run in a coding-focused GPT with tools enabled
- Review code for structure and clarity

**Discussion Prompt:** "How would a GPT like this speed up your development workflow?"

---
### 6. Specialized GPT Applications and Integrations

#### 6.1. Script

"Now let’s go even more specific—into GPTs created for highly specialized tasks.

While many GPTs aim to be general-purpose, others are fine-tuned for niche use cases: from language learning to software engineering. These GPTs often combine structured behavior, domain knowledge, and tailored prompts to deliver consistent, high-value support.

In this section, we’ll walk through a few powerful use cases that demonstrate the range of what’s possible. These aren’t just toys—they’re tools professionals are beginning to rely on every day."

---

#### 6.2. Slide

**Slide Title: "Niche GPTs for Power Users"**

- Language Learning GPT: Grammar, usage, translations
- Coding Assistant GPT: Framework-specific guidance
- Research GPT: Summarize, cite, compare scholarly material
- Personal Wellness GPT: Reflective journaling, mood check-ins

Visual: Grid of GPT tiles with logos or mock personas (e.g., "SpringBot," "LinguaTutor," "InsightGPT")

---

#### 6.3. Slide Notes

- Mention: Many CustomGPTs shared publicly at [https://chat.openai.com/gpts/explore](https://chat.openai.com/gpts/explore)
- Joke: "You’ve heard of task rabbits. These are task Cheetahs—fast, focused, and tireless."
- Tip: Think of GPTs as skill boosters—not general AI, but role-players with purpose

---

#### 6.4. Demonstration A – Language Learning GPT (Polish Example)

**Prompt:** "Translate the word 'miłość' into English, Belarusian, Ukrainian, and Russian. Show grammatical cases and two usage examples."

**Instructions:**

- Highlight the clean, consistent format
- Show how this can become part of a spaced repetition system

**Discussion Prompt:** "What feature would make this GPT even better for your language goals?"

---

#### 6.5. Demonstration B – Spring Boot AI Assistant GPT

**Prompt:** "Suggest an architecture for integrating OpenAI API with Spring Boot using clean architecture. Include services, controller, and config layers."

**Instructions:**

- Run prompt in specialized Java development GPT
- Discuss architectural decisions and trade-offs it proposes

**Discussion Prompt:** "Would you trust this GPT for scaffolding your next project? Why or why not?"

---

#### 6.6. Demonstration C – Self-Reflection Coach GPT

**Prompt:** "Ask me three questions to reflect on my day. Then summarize what I might be feeling and suggest one thing I could do tomorrow to improve."

**Instructions:**

- Use wellness-focused GPT or CustomGPT with emotional intelligence design
- Show how model adapts tone based on reflection

**Discussion Prompt:** "What domains of your life could benefit from a personal AI like this?"

---
### 7. Advanced Information Retrieval and Data Analysis

#### 7.1. Script

"Next up—let’s talk about information.

One of the most underrated capabilities of advanced LLMs is their ability to search, summarize, and contextualize information at scale.

Modern AI tools can:

- Retrieve facts from multiple sources
- Compare perspectives in real time
- Analyze uploaded documents, from invoices to legal texts
- Generate summaries, visualizations, and decision-ready insights

In this section, we’ll explore how models like ChatGPT, Claude, Gemini, and Perplexity retrieve, process, and deliver knowledge—and where they differ."

---

#### 7.2. Slide

**Slide Title: "LLMs as Research Analysts"**

- Contextual search (web-connected)
- Multi-document analysis
- Summarization & synthesis
- Visualizations & comparisons

Visual: Side-by-side layout of an uploaded PDF, chart, and summarized output

---

#### 7.3. Slide Notes

- Tip: Mention that Claude is especially strong at long document parsing
- Joke: "It’s like hiring four interns—who never sleep and cite their sources."
- Mention: Gemini and Perplexity excel at real-time info, ChatGPT excels with structured analysis if you prep the input

---

#### 7.4. Demonstration A – Real-time Research Comparison

**Prompt:** "Compare the latest research on the effectiveness of mindfulness apps vs cognitive behavioral therapy for anxiety. Include citations and source bias where possible."

**Instructions:**

- Run in Perplexity and Gemini
- Highlight differences in citation styles, depth, and neutrality

**Discussion Prompt:** "Which system gave you more actionable insight? Which one felt more trustworthy?"

---

#### 7.5. Demonstration B – Document Summarization

**Prompt:** "Summarize this 10-page PDF (upload a sample) and extract the key financial risks mentioned."

**Instructions:**

- Upload a PDF (e.g., annual report or contract excerpt) into Claude and ChatGPT
- Compare summary clarity, key term recognition, and structure

**Discussion Prompt:** "What would you want the AI to highlight more clearly next time?"

---

#### 7.6. Demonstration C – Data Visualization from Structured Text

**Prompt:** "Here is sales data for the last 6 months. Create a bar chart comparing monthly totals and identify one trend and one anomaly."

**Instructions:**

- Paste structured data into ChatGPT or Claude with tools enabled
- Show both visual output and accompanying analysis

**Discussion Prompt:** "Would you use this to prep for a real presentation? Why or why not?"

---
### 8. Advanced Reasoning Techniques

#### 8.1. Script

"We’ve seen that LLMs can reason in fascinating ways—but how do we make them more deliberate, structured, and accurate?

That’s where advanced reasoning techniques come in. These strategies guide the model to:

- Break problems into smaller parts
- Think through a question step by step
- Maintain consistency across complex outputs
- Collaborate with other agents

In this section, we’ll look at techniques like Chain-of-Thought, ReAct, and system-specific reasoning optimizations that help AI deliver better results, especially for complex or ambiguous tasks."

---

#### 8.2. Slide

**Slide Title: "Making AI Think (More) Like Us"**

- Chain-of-Thought Reasoning
- Multi-step Decomposition
- ReAct (Reason + Act)
- System-Specific Optimization (ChatGPT vs Claude vs Gemini)

Visual: Flowchart of a reasoning prompt broken into intermediate steps with annotations

---

#### 8.3. Slide Notes

- Tip: These techniques often make a huge difference for math, logic, and planning tasks
- Joke: "AI may not sleep—but it does better with a to-do list."
- Mention: ReAct is a framework for combining reasoning and action in a loop

---

#### 8.4. Demonstration A – Chain-of-Thought Prompting

**Prompt:** "If Alice is older than Bob, and Bob is older than Charlie, who is the oldest? Explain your reasoning."

**Instructions:**

- Run prompt in Claude, Gemini, and ChatGPT
- Ask the model to explain before answering (or use “Let’s think step by step”)

**Discussion Prompt:** "How does the explanation change your confidence in the answer?"

---

#### 8.5. Demonstration B – Task Decomposition

**Prompt:** "Plan a one-week team retreat for 15 software engineers, including logistics, agenda, and team-building activities."

**Instructions:**

- Use prompt in ChatGPT or Claude
- Highlight how the model breaks the problem down (e.g., travel, meals, sessions, free time)

**Discussion Prompt:** "What parts did the model handle well? Where would you still want human oversight?"

---

#### 8.6. Demonstration C – ReAct Pattern (Reasoning + Acting)

**Prompt:** "You are a researcher trying to find a reliable source about the environmental impact of cryptocurrency mining. Think step by step, then use web tools to find and cite at least two credible sources."

**Instructions:**

- Use a GPT with browsing or Perplexity AI
- Highlight how it reasons, searches, and cites in one process

**Discussion Prompt:** "Did the model make good decisions in choosing what to search and how to summarize?"

---

#### 8.7. Demonstration D – Comparing Models on Complex Reasoning

**Prompt:** "Design a basic governance system for an autonomous Martian colony that ensures both individual rights and resource sustainability."

**Instructions:**

- Run the same prompt in ChatGPT, Claude, and Gemini
- Compare structure, originality, feasibility of each answer

**Discussion Prompt:** "Which model handled the tradeoffs best? Who had the most ‘human-like’ reasoning?"

---
### 9. Multi-Agent and Autonomous AI Systems

#### 9.1. Script

"So far, we’ve been working with individual models—one question, one answer. But what happens when you put multiple AIs to work together on the same task?

Welcome to the world of **multi-agent systems**: collaborative AI workflows where different agents specialize, delegate, verify, and even debate.

These systems are a glimpse into the future of how AI will be used—autonomous teams of models handling research, planning, coding, testing, and writing with minimal human oversight.

We’ll walk through how these agents communicate, assign roles, and resolve conflicts, and explore tools and frameworks that make this possible today."

---

#### 9.2. Slide

**Slide Title: "From One AI to Many"**

- Multi-agent orchestration
- Role specialization (planner, coder, reviewer)
- Task delegation & feedback loops
- Conflict resolution among agents

Visual: Diagram of three AI agents passing tasks to each other with roles labeled (e.g., Thinker → Coder → Tester)

---

#### 9.3. Slide Notes

- Joke: "Finally, an AI team meeting without coffee or small talk."
- Tip: Multi-agent systems aren’t science fiction—they’re being used in autonomous coding, task planning, and document review
- Mention: Tools like AutoGen, CrewAI, and OpenDevin are leading this field

---

#### 9.4. Demonstration – AI Agent Collaboration

**Scenario Prompt:** "You are part of a 3-agent team building a simple web app. Agent A: Define user requirements. Agent B: Design architecture. Agent C: Write the code. Collaborate and pass results between agents."

**Instructions:**

- Use a platform like AutoGen or simulate roles in ChatGPT
- Show how output builds step-by-step, with refinement and role clarity

**Discussion Prompt:** "Would you trust this team to start your next software project? Why or why not?"

---
### 10. Hands-On Activity: Advanced Prompt Exploration

#### 10.1. Script

"It’s time to shift from watching to doing.

In this hands-on section, you’ll get to experiment with prompts across different platforms and reasoning types. The goal isn’t to find the ‘best’ answer—but to understand how your wording, model choice, and context shape the output.

We’ve grouped prompts by type—writing, logic, visuals, analysis—and you can remix or invent your own. Try comparing Claude, ChatGPT, Gemini, and Perplexity on the same task.

This is your chance to explore, break things, laugh at strange outputs, and learn by doing."

---

#### 10.2. Slide

**Slide Title: "Try It Yourself: Prompt Playground"**

- Use the provided prompt library or create your own
- Test across 2–3 different models
- Observe differences in tone, depth, accuracy
- Document: What surprised you? What worked well?

Visual: Screenshots of the same prompt run in multiple models side-by-side

---

#### 10.3. Slide Notes

- Joke: “Yes, you are now allowed to confuse the AI. Responsibly.”
- Tip: Encourage screenshots and share-outs at the end
- Mention: Prompt remixing is a great way to uncover model personalities

---

#### 10.4. Prompt Categories (for Participants)

- **Writing:** Rewrite text in a famous author’s style
- **Logic:** Solve a classic riddle with explanation
- **Creative:** Design a new holiday or space colony
- **Code:** Debug a broken function you bring
- **Visual:** Upload an image and describe what’s happening
- **Data:** Upload a document or chart and ask for summary or analysis

---

#### 10.5. Activity Instructions

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
### 11. Homework: Prompt Library Exploration

#### 11.1. Script

"To keep the momentum going after class, I’ve prepared a guided homework assignment. Your task is to explore our curated **Prompt Library** and experiment with:

- At least 3 different types of prompts
- At least 2 different AI systems

You’ll document what you tried, how the models performed, and what surprised you. This isn’t about right or wrong—it’s about developing **prompt intuition**."

---

#### 11.2. Slide

**Slide Title: "Homework: Explore & Reflect"**

- Use Prompt Library (link provided)
- Choose 3+ prompts from different domains
- Compare results across tools
- Record:
	- Prompt used
	- Tools tested
	- What worked / what didn’t

Visual: Example homework template or table filled in with sample entries

---

#### 11.3. Slide Notes

- Joke: “Yes, this time you’re encouraged to talk to strangers—AI strangers.”
- Tip: Focus on clarity of prompts, differences in tone and depth
- Mention: Template available via Google Docs or Notion (link provided in class)

---

### 12. Resources for Continuous Learning

#### 12.1. Script

"Before we wrap, here are a few places you can go next to keep learning, experimenting, and connecting.

AI is moving fast, but you don’t have to keep up alone. There are prompt libraries, communities, newsletters, and amazing projects emerging every day.

Here’s your starter kit."

---

#### 12.2. Slide

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
	- [IntelliJ AI Assistant](https://www.jetbrains.com/idea/whatsnew/#ai)
- Stay Updated:
	- [Ben’s Bites](https://www.bensbites.co/)
	- [TLDR AI](https://www.tldr.tech/ai)

---

#### 12.3. Slide Notes

- Joke: “Think of FlowGPT as your AI recipe book—and you’re the chef.”
- Tip: Encourage bookmarking and regular exploration—prompting gets better with play
- Mention: Follow AI-related YouTube channels, Substacks, or Discord servers if you want community

---

🎉 **End of Lecture 3**

“Thanks for joining today’s deep dive! You’ve now got the tools to explore the frontier of advanced AI capabilities—from system features to reasoning and prompt design.

The best way to grow from here? Keep prompting. Keep comparing. Keep playing.”