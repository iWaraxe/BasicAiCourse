# Beginners AI. Mastering modern AI tools
## Lecture 2. Practical AI Application - Text, Code and Visuals

### 1. Introduction: From Theory to Practice

#### 1.1. Course Overview and Context

##### [seq:010] Introduction

###### SCRIPT

"Welcome back, everyone! I hope you enjoyed your first deep dive into the world of AI in our previous lecture. We met the major players—ChatGPT, Claude, Gemini, Perplexity, and Mistral—and discovered that, while these systems are impressive, they're far from perfect. We also explored the boundaries of AI by witnessing firsthand its biases, hallucinations, and occasional lapses in logic.

Today, we're flipping the perspective. Instead of focusing on what AI **can't** do, we’ll explore what it **can** do—really well. This lecture is all about **practical applications**. We're going hands-on with how modern AI can help us write, translate, code, debug, analyze visuals, and even extract insights from documents.

Our focus is not just on results, but also on comparing how different tools perform the same tasks. You’ll see real prompts in action, and you'll get to try them yourself. By the end of the session, you’ll have a clearer picture of how to use AI as a smart assistant across different domains.

So—ready to put theory into practice? Let’s begin."


###### VISUAL

**Slide Title: "From Theory to Practice"**

- Left panel: Summary of Lecture 1:
	- Systems: ChatGPT, Claude, Gemini, Perplexity, Mistral
	- Concepts: LLMs, Multimodal AI, Bias, Hallucinations
- Right panel: What we’ll cover today:
	- Text Writing & Editing
	- Code Generation & Debugging
	- Visual & Document Analysis
	- Tool Comparisons & Demos
	- Integration into Workflows

Visuals: Icons representing each category (pen for writing, brackets for code, eye for visual, magnifying glass for analysis)


###### NOTES

- Recap the emotional tone from Lecture 1: exploration, caution, surprise.
- Add fun fact: The first AI writing assistant was developed in the 1980s and was basically a glorified spell-checker.
- Joke: “Last time, we caught AI making things up. Today, we see if it can help us write a birthday card, fix our code, and maybe even explain a pie chart.”
- Mention: Today’s demos include ChatGPT, Claude, Gemini, Perplexity—live comparisons!


###### DEMONSTRATION

**Title: "Then vs Now: Writing Help"**

**Prompt (for comparison):** "Write a 100-word thank-you note for a teacher who made a big impact on your life."

**Instructions:**

- Run this prompt in ChatGPT, Claude, and Gemini.
- Display results side-by-side.
- Discuss differences in tone, clarity, and creativity.

**Talking Point:** "Even for a simple prompt, each model has a unique voice. This gives us a great way to compare not just correctness—but **style and tone**, which are critical in real-world writing."

---

### 2. Text Generation and Editing

#### 2.1. Content Creation

##### [seq:020] Writing and Editing Assistance

###### SCRIPT

"Let’s start with something that nearly everyone here has done: writing. Whether it’s an email, a blog post, or a heartfelt thank-you note, generative AI has become an incredibly useful assistant for writing and editing.

Modern tools like ChatGPT, Claude, and Gemini are not just spelling and grammar checkers—they help with structure, tone, clarity, and even creativity.

Let’s see how they handle writing from scratch, and then how they revise something that needs improvement."

###### VISUAL

**Slide Title: "Writing & Editing with AI"**

- Bullet Points:
	- Write articles, blog posts, emails
	- Adjust tone: professional, casual, persuasive
	- Edit drafts for clarity, grammar, conciseness
- Visual: Screenshot of ChatGPT editing interface + Claude writing suggestions box

###### NOTES

- Mention: Gemini can write directly inside Google Docs; ChatGPT Pro can use memory to personalize tone over time.
- Joke: "It's like having a co-writer who never complains about deadlines."
- Tip: Show examples of how tone changes with a simple prompt tweak (e.g., "make it sound more friendly")


###### DEMONSTRATION

**Demo 1 – Prompt:** "Generate a 500-word blog post about the benefits of AI in education, focusing on how it enhances personalized learning. Write in an engaging and conversational tone."

**Demo 2 – Prompt:** "Edit the following paragraph for clarity and professionalism: ‘AI tools are kind of like helpful assistants for people. They can make things faster and better by doing stuff like fixing mistakes, writing content, or helping with tough tasks. But sometimes, they can mess up if you don’t guide them properly.’"

**Instructions:**

- Run both prompts across ChatGPT, Claude, and Gemini.
- Compare:
	- Structure and grammar improvements
	- Tone (e.g., Claude tends to be more formal)
	- Word choice and creativity

**Discussion Question:** "Which system gave you the best balance between clarity and personality?"

---

#### 2.2. Language Capabilities

##### [seq:030] Translation and Language Processing

###### SCRIPT

"Next up: language translation and contextual phrasing. AI tools can now translate texts not just word-for-word, but with nuance, tone, and even regional flavor.

This is incredibly useful for global communication—whether you're preparing an international report or just trying to understand a foreign email.

Let’s test their abilities in formal and informal translation—and see how they handle idioms and culturally complex expressions."


###### VISUAL

**Slide Title: "AI-Powered Translation & Language Processing"**

- Bullet Points:
	- Real-time translation in messaging apps
	- Context-sensitive phrasing and idioms
	- Tone adjustment based on audience
- Visual: Side-by-side translation example (English → Spanish, English → French)

###### NOTES

- Mention: Gemini is deeply integrated with Google Translate and Gmail.
- Claude tends to explain its translation logic.
- Joke: “They might not pass a Turing test in Spanish... but they’ll help you pass that French test.”
- Trivia: The phrase "It's raining cats and dogs" has no direct equivalent in most other languages—watch how each model handles that!


###### DEMONSTRATION

**Demo 1 – Prompt:** "Translate the following text into Spanish, maintaining a formal tone: ‘Artificial Intelligence is revolutionizing the way we work and learn. It offers solutions to complex problems and creates new opportunities for innovation.’"

**Demo 2 – Prompt:** "Translate the phrase ‘It’s raining cats and dogs’ into French, and explain the cultural equivalent phrase if applicable."

**Instructions:**

- Use all three models and observe:
	- Sentence structure fidelity
	- Tone preservation
	- Cultural interpretation of idioms

**Discussion Prompt:** "How important is cultural knowledge in translation—and did the models demonstrate it well?"

---

### 3. Code Generation and Debugging

#### 3.1. Programming Fundamentals

##### [seq:040] Code Generation

###### SCRIPT

"Now let’s jump into something a bit more technical—code generation.

Whether you're a seasoned developer or someone who's just starting, generative AI tools can help write code, explain code, and even suggest optimizations. The landscape just changed dramatically with DeepSeek-R1-0528's release on May 28, 2025—an open-source model that's not just competing with commercial giants like OpenAI's o3, it's actually outperforming them on coding tasks while being completely free and MIT-licensed.

Let’s begin with a simple example—generating a Python script for the Fibonacci sequence, with comments to explain each step. This will show how well the models handle both logic and readability."


###### VISUAL

**Slide Title: "Let AI Write the Code"**

- Bullet Points:
	- Generate functional code from plain English prompts
	- Add inline comments and explanations
	- Create quick utilities and automation scripts
- Visual: Screenshot of ChatGPT generating a Python snippet


###### NOTES

- Mention: Claude 4 often provides more detailed explanations and excels at codebase understanding; ChatGPT is faster and usually more concise.
- **Breaking**: DeepSeek-R1-0528 (May 28, 2025) - First open-source model to outperform o3 on coding benchmarks
- **June 2025**: Mistral Code launched - comprehensive IDE integration (JetBrains, VSCode), built on Continue project
- Mistral Code advantages: Local deployment, enterprise tooling, Codestral models excel at specific tasks
- Gemini may include code with a visual explanation or annotations.
- Joke: "The only intern who never gets tired and doesn’t drink your coffee."
- Tip: Highlight best use case—quick prototypes and boilerplate code
- Performance update: Claude 4 models excel at coding (Sonnet 4: 72.7% on SWE-bench, Opus 4: 72.5%)
- DeepSeek-R1 advantage: MIT licensed, exceptional at complex debugging and code generation tasks

###### DEMONSTRATION

**Prompt:** "Write a Python script to calculate the Fibonacci sequence up to the 50th number. Include comments explaining each step."

**Instructions:**

- Run the prompt in ChatGPT, Claude 4, Gemini, and DeepSeek-R1-0528
- Compare:
	- Code correctness
	- Clarity and usefulness of comments
	- Readability and structure
	- Efficiency of the implementation
	- Reasoning depth (DeepSeek shows its thinking process)

**Discussion Question:** "Which model gave you code you'd feel confident using as-is in a real project? How does DeepSeek's reasoning transparency change your confidence?"

---

#### 3.2. Error Resolution

##### [seq:050] Debugging Assistance

###### SCRIPT

"Of course, no one writes perfect code all the time—that’s where debugging comes in.

Many AI tools now assist in identifying and fixing code errors. What’s even more powerful is their ability to analyze code from a screenshot or partial snippet.

Let’s take a buggy Python and JavaScript snippet and ask our AI companions to help us out."


###### VISUAL

**Slide Title: "Fixing Code with AI"**

- Bullet Points:
	- Debug from plain error messages or snippets
	- Analyze code in screenshots
	- Suggest fixes and improvements
- Visual: Side-by-side before-and-after of buggy vs fixed code


###### NOTES

- Gemini and Claude are especially good at interpreting screenshot-based prompts
- Joke: “AI doesn’t get frustrated with typos. Wish we could say the same for our colleagues.”
- Mention: You can feed error logs or even ask "Why is this code not working?"


###### DEMONSTRATION

**Demo 1 – Prompt:** "Here’s a piece of Python code with an error. Find the bug and fix it:

```python
def greet(name)
    print("Hello" + name)
```

**Demo 2 – Prompt:**
"Here is a screenshot of JavaScript code (upload screenshot). Identify any errors and suggest corrections."

**Instructions:**
- Run both prompts across ChatGPT, Claude, and Gemini
- Observe how they:
  - Spot syntax issues
  - Suggest alternative solutions
  - Explain the fix clearly

**Discussion Prompt:**
"Which AI explained the fix in a way that actually taught you something new?"

---

### 4. Visual and Document Analysis

#### 4.1. Image Processing

##### [seq:060] Image Understanding and Generation

###### SCRIPT

"Let’s now shift our focus to the **visual** side of AI.

Today’s top models aren’t limited to text—they’re increasingly capable of analyzing and generating images.

We’ll begin by uploading diagrams, charts, and other visuals to see how well the AI understands them. Then, we’ll flip the script and ask the AI to generate creative images from a description."


###### VISUAL

**Slide Title: "From Pixels to Understanding"**

- Bullet Points:
	- Analyze visual inputs like flowcharts and infographics
	- Describe and extract insights from images
	- Generate new images from prompts
- Visual: Split screen—image upload interface + generated image result


###### NOTES

- Mention Gemini and GPT-4V (DALL·E integration) as top tools for visual tasks.
- Claude 4 can interpret diagrams and describe their components clearly.
- Google's Imagen AI achieves near-human quality with excellent prompt adherence, while Veo3 now leads in video generation, surpassing OpenAI's Sora
- Joke: “AI can’t draw a horse very well… but it might draw you a futuristic city with a flying horse!”


###### DEMONSTRATION

**Demo 1 – Prompt (Image Upload):** "Analyze this image of a flowchart (upload an image) and summarize the process it represents."

**Demo 2 – Prompt (Image Generation):** "Generate an image of a futuristic cityscape with green spaces, flying cars, and renewable energy structures. Use a style that combines realism and a sci-fi aesthetic."

**Instructions:**

- Use ChatGPT, Claude 4, and Gemini where applicable
- Discuss:
	- How detailed is the interpretation?
	- Is the generated image visually coherent?

**Discussion Prompt:** "Which AI system provided the most accurate or creative results? What would you trust it with—reporting or inspiration?"

---

##### [seq:065] AI Video Generation

###### SCRIPT

"We've entered the era of **AI video generation**. What used to require teams of animators and video editors can now be created from a simple text prompt.

Google's Veo 3 has decisively taken the lead in video generation, with the community declaring it has 'crushed every other competitor.' The quality leap has been so dramatic that users describe it as surpassing OpenAI's Sora in both visual fidelity and apparent model capabilities. The famous cat video demonstration showcased Veo 3's exceptional realism that left competitors scrambling.

This dominance stems from Google's unique advantage: access to YouTube's massive multimedia dataset, which provides superior training data compared to any competitor. The result is 8-second video clips that professionals describe as nearly indistinguishable from real footage, with some users already creating full movies by stitching together multiple clips.

The democratization of professional video production is already happening. In a striking example, Ulianopolis City Hall in Brazil produced a complete, professional-grade 1-minute advertising commercial using only Veo 3, spending just R$300 ($52 USD) on credits. This same video would have traditionally cost R$100,000 ($17,543 USD) with conventional production methods. The quality was so impressive that it included natural Portuguese dialogue with accurate local accents—showcasing Veo 3's advanced multilingual and cultural localization capabilities.

The community response has been overwhelming, with widespread adoption across Discord servers and Reddit communities. While not perfect (AI-generated text in videos often contains errors, and consistency requires careful prompting), the progress has surprised even industry experts who didn't expect such a sudden quality leap.

Looking ahead, infrastructure limitations—not algorithmic ones—are now the primary bottleneck. OpenAI's challenge isn't model quality but lacking sufficient GPUs and scalable infrastructure to match Veo 3's performance and generation length capabilities.

However, Microsoft has now brought OpenAI's Sora to the masses through Bing, offering free access via the 'Bing Video Creator' feature in the Bing app. While users report that Veo 3 still delivers superior results, the democratization of Sora through Bing represents a significant shift in accessibility. Early users note the ability to generate detailed, animated content, though they also encounter strict safety filters that can block many requests, limiting experimental use cases compared to less restrictive alternatives."

###### VISUAL

**Title: "From Text to Cinema"**

- **Competitive landscape shift**:
  - Veo 3 vs Sora: Decisive Google victory
  - Quality gap: 'Crushed every other competitor'
  - Community verdict: Overwhelming Veo 3 adoption
- **Google's data advantage**:
  - YouTube multimedia dataset = superior training
  - Competitors lack equivalent data sources
  - Infrastructure bottleneck now limits competitors, not algorithms
- **Future outlook**:
  - 10x length videos becoming the new battleground
  - Feature-length film generation approaching feasibility

###### NOTES

- **Breaking May 2025**: Community consensus declares Veo 3 has 'crushed every other competitor'
- Famous cat video demo showcased quality that left competitors scrambling
- **Real-world example**: Ulianopolis City Hall (Brazil) - $52 vs $17,543 traditional cost
- Advanced localization: Natural Portuguese with accurate local accents
- Google's YouTube data advantage: massive multimedia training dataset unavailable to competitors
- **June 2025 Update**: Microsoft brings free Sora access via Bing Video Creator
- Sora limitations: Aggressive safety filters reduce experimental use cases
- Community verdict: Veo 3 still superior, but Sora democratizes access
- Infrastructure reality: OpenAI's bottleneck is GPUs and scale, not algorithm quality
- Access: Veo 3 via Google Labs Flow; Sora via Bing app
- Tip: Use consistent prompts for character/scene continuity

###### LINKS
- https://labs.google.com/veo (Veo 3 access)
- Bing app: Search for "Video Creator" (Sora access)
- Ulianopolis commercial example: Real-world case study

###### DEMONSTRATION

**Prompt:** "Create a 8-second video of a robot chef cooking in a futuristic kitchen, photorealistic style"

- Show the generation process
- Discuss quality, coherence, and artifacts
- Compare with traditional video production time/cost (reference $52 vs $17,543 example)

---

#### 4.2. Document Intelligence

##### [seq:070] Document Analysis and Data Extraction

###### SCRIPT

"Visuals aren’t just about images—we also deal with complex documents every day.

AI can now analyze uploaded PDFs, contracts, research papers, invoices—you name it—and extract meaningful information.

This has huge implications for fields like law, education, and business. Let’s see how well our models summarize and extract data from documents."


###### VISUAL

**Slide Title: "AI Meets PDFs & Docs"**

- Bullet Points:
	- Summarize lengthy documents quickly
	- Extract key data from contracts or invoices
	- Improve accessibility and document search
- Visual: Screenshot of PDF + summary panel next to it


###### NOTES

- Perplexity can cite and summarize documents with web-based tools.
- Claude is particularly good at parsing large text blocks and legal content.
- Joke: “Give AI your tax return and see if it panics less than you.”
- Mention NotebookLM for long-term document understanding.


###### DEMONSTRATION

**Demo 1 – Prompt (Document Upload):** "Summarize the key points of this legal agreement (upload PDF). Focus on terms of payment and termination clauses."

**Demo 2 – Prompt (Scanned Document):** "Extract all invoice numbers and total amounts from this document (upload a scanned invoice)."

**Instructions:**

- Use Claude, ChatGPT (Pro), and Perplexity
- Compare:
	- Speed and clarity of summary
	- Data accuracy

**Discussion Prompt:** "Which model would you trust with analyzing important documents—and why?"

---

##### [seq:075] Perplexity Labs: Interactive Research and Mini-App Generation

###### SCRIPT

"Here's something that just launched and is changing how we think about AI research: **Perplexity Labs**. This isn't just search anymore—it's a full interactive platform for complex tasks like building trading strategies, creating dashboards, and generating mini-web apps from simple prompts.

Perplexity Labs represents a new category: AI systems that don't just answer questions, but build functional tools. You can create a compensation committee tool with a single prompt, extract YouTube transcripts automatically, or build longevity research dashboards in minutes. The key breakthrough? It inlines images and wide-ranging assets to create visually rich, actionable outputs rather than just text responses.

Users are already creating F1 race simulations, trading strategy analyzers, and research tools that would have taken developers days to build. This represents the evolution from AI as a search tool to AI as a **creation platform**.

What makes this significant is the shift from static research to interactive intelligence. Instead of getting a list of facts, you get working tools that process real data, generate insights, and can be customized for your specific needs."

###### VISUAL

**Title: "From Search to Creation: Perplexity Labs"**

- **New capabilities**:
  - Interactive research dashboards
  - Trading strategy builders
  - Mini-app generation from prompts
  - Real-time data integration
- **Examples showcased**:
  - F1 race simulation
  - Longevity research dashboard
  - Compensation committee tool
  - YouTube transcript extractor
- **Key differentiator**: Visual richness + functional output

###### NOTES

- **Breaking May 2025**: Perplexity Labs launched with 6 major new features
- Available in Perplexity iOS app for building mini-apps on mobile
- Enhanced shopping & travel research now integrated into Deep Research
- Personal Search & Memory features enhance research continuity
- Crypto Leaderboard and F1 real-time data demonstrate live data integration
- Community feedback: Amazing speed—full research presentations created in ~1 hour
- Access: Available to Perplexity Pro users

###### DEMONSTRATION

**Prompt:** "Create an interactive dashboard to analyze momentum trading strategies for the tech sector. Include historical data visualization and key performance indicators."

- Show the generation of interactive elements
- Demonstrate data integration capabilities
- Compare with traditional research workflow

---

### 5. Visual Programming Assistance

#### 5.1. Diagram Interpretation

##### [seq:080] Code and Diagram Analysis

###### SCRIPT

"Let’s take our exploration of visuals one step further: into the world of programming diagrams and screenshots.

Many of you have seen UML diagrams, ER diagrams, and flowcharts. What if AI could explain them? Even better—what if you could debug a screenshot of code by simply uploading it?

Today’s AIs are surprisingly good at interpreting visual programming materials. Let’s put that to the test."


###### VISUAL

**Slide Title: "Visual Programming with AI"**

- Bullet Points:
	- Interpret and explain UML diagrams
	- Identify bugs in screenshots of code
	- Explain structure and relationships between entities
- Visual: Side-by-side of a UML diagram + Claude’s text interpretation


###### NOTES

- Gemini and Claude are strongest at diagram interpretation.
- Useful for onboarding, education, or visual documentation.
- Joke: "Finally—someone who can explain that spaghetti chart from 2014."


###### DEMONSTRATION

**Demo 1 – Prompt (Code Screenshot):** "Here is a screenshot of JavaScript code (upload screenshot). Identify any errors and suggest corrections."

**Demo 2 – Prompt (UML Diagram):** "Interpret this UML diagram (upload an image) and describe the relationships between the entities."

**Instructions:**

- Run in Claude, Gemini, and ChatGPT Pro
- Compare how each model:
	- Recognizes elements
	- Infers relationships and intent
	- Uses correct programming vocabulary

**Discussion Prompt:** "Could this help you debug visual code or teach programming to someone new?"

---

### 6. Comparative Analysis of AI Visual Capabilities

#### 6.1. Cross-Platform Performance

##### [seq:090] Cross-Model Visual Reasoning

###### SCRIPT

"Let’s now do something really insightful—compare how different AI models interpret and process the **same visual inputs**.

Whether it’s a flowchart, UML diagram, infographic, or a bar chart, we’ll give each model the same material and see how they differ.

This is where we’ll uncover each model’s **strengths and blind spots**. Some might be more analytical. Others more descriptive. Some better at structure, others at aesthetics.

Let’s get analytical about AI itself."


###### VISUAL

**Slide Title: "Seeing Through Different AI Eyes"**

- Table format comparing: ChatGPT | Claude | Gemini
- Columns: Image Understanding, Technical Detail, Clarity, Usefulness
- Visual: Three AI-generated responses shown side-by-side (diagram analysis or chart generation)


###### NOTES

- This is where it gets really fun and nuanced—watch how Gemini might simplify, Claude might explain, and ChatGPT might get creative.
- Suggest using the same image (e.g., a network diagram or technical infographic).
- Joke: “Three AIs walk into a diagram... and only one notices the firewall.”


###### DEMONSTRATION

**Demo 1 – Prompt (Image Upload):** "Analyze this technical diagram of a network setup (upload image). Identify potential security vulnerabilities based on the structure."

**Demo 2 – Prompt (Data Visualization):** "Visualize the following dataset as a bar chart: • January: 100 • February: 150 • March: 200 • April: 175"

**Instructions:**

- Use ChatGPT, Claude, and Gemini for each prompt
- Compare how each:
	- Understands the diagram or dataset
	- Expresses insights visually and textually
	- Provides technical vs interpretive commentary

**Discussion Prompt:** "Which tool would you trust most for professional analysis? For teaching? For content creation?"

---

### 7. IDE and Workflow Integration

#### 7.1. Development Environment

##### [seq:100] AI Tools in the Developer Workflow

###### SCRIPT

"Let’s bring it all into the real world: your **actual workflow**.

Many of today’s IDEs now integrate AI directly into your coding environment. Whether you're using IntelliJ IDEA, VS Code, or JupyterLab, these tools offer suggestions, explain snippets, and even refactor code for you.

The goal? Fewer context switches. Smarter development. More time to think, less time to search Stack Overflow."


###### VISUAL

**Slide Title: "Smart IDEs: AI in Your Editor"**

- Bullet Points:
	- Code completion and refactoring with AI
	- Integrated chat interfaces (e.g., ChatGPT app for macOS)
	- AI-assisted debugging and documentation
- Visual: Screenshot of IntelliJ with ChatGPT Pro integration sidebar


###### NOTES

- ChatGPT native macOS app can access codebase via search and context linking
- VS Code has GitHub Copilot, Claude plugins, and Gemini web integrations
- Joke: “It’s like Clippy—but it actually knows what you're doing.”
- Tip: Mention privacy and context boundaries in corporate coding environments


###### DEMONSTRATION

**Demo – Prompt (inside IDE):** "Suggest an optimization for this function based on its runtime complexity."

**Alternative Demo:** Using the ChatGPT macOS app to navigate and analyze files inside IntelliJ project:

- Ask it to summarize a controller class
- Then, prompt it to suggest missing unit tests

**Instructions:**

- Run live in IntelliJ (with ChatGPT app), VS Code (with Copilot), or show screenshots if local setup isn’t feasible
- Compare suggestions from each platform

**Discussion Prompt:** "Where do you think AI fits best in your workflow—as an assistant, reviewer, or collaborator?"

---

#### 7.2. Enhancing AI Performance

##### [seq:105] System Prompt Learning and AI Optimization

###### SCRIPT

"Now that we've integrated AI into our workflows, let's talk about making it even better. One of the most exciting developments from June 2025 is **System Prompt Learning (SPL)**—a technique that allows AI models to actually learn from their experiences and improve over time.

Think of it like this: instead of starting fresh with every conversation, the AI can remember effective strategies from past problems and apply them to new challenges. It's inspired by how humans learn—we don't solve every problem from scratch; we build on our experience.

SPL has shown remarkable results: improving performance on Arena Hard benchmarks by 8.6% and on AIME24 (advanced mathematics) by 6.67%. What's fascinating is that all the strategies the AI learns are human-readable—you can actually see what it's learning and why it's getting better at specific types of problems."

###### VISUAL

**Slide Title: "System Prompt Learning: AI That Gets Better Over Time"**

- Core concept: LLMs learn problem-solving strategies from experience
- Performance improvements:
  - Arena Hard: +8.6%
  - AIME24: +6.67%
- How it works:
  - Builds database of effective strategies
  - Applies learned patterns to new problems
  - All strategies remain human-readable
- Visual: Flowchart showing: Problem → Strategy Database → Solution → Learning Loop

###### NOTES

- SPL is inspired by Andrej Karpathy's original idea about self-improving systems
- Works with any OpenAI-compatible API by adding 'spl-' prefix to model name
- The more you use it for specific problem types, the better it gets
- Think of it as "teaching your AI assistant your preferred working style"
- Practical tip: Use SPL for repetitive tasks where consistent approaches matter

###### LINKS
- https://huggingface.co/blog/spl-improvements

###### DEMONSTRATION

**Demo - System Prompt Learning in Action:**

Prompt 1: "Using SPL, solve this coding problem: Find all pairs of numbers in an array that sum to a target value."

Prompt 2: "Now solve a similar problem: Find all triplets in an array that sum to zero."

**Instructions:**
- Show how SPL applies learned strategies from the first problem to the second
- Highlight the strategy database that builds up
- Compare performance with and without SPL enabled

**Discussion:** "What repetitive tasks in your workflow could benefit from an AI that learns your preferences over time?"

---

### 8. Privacy-First AI: Running Models Locally

#### 8.1. On-Device AI Applications

##### [seq:108] Local AI for Complete Privacy

###### SCRIPT

"Let's talk about something increasingly important in 2025: privacy. Not everyone wants their data sent to cloud servers, especially when dealing with sensitive information. The good news? AI has come to your device.

We're seeing a surge in applications that run AI entirely on your phone or computer—no internet connection needed, complete privacy guaranteed. These aren't toy models either; they're delivering professional-grade results while keeping your data exactly where it belongs: with you.

Take Fullpack, an iOS app that turns photos into smart packing lists using Apple's VisionKit. You snap photos of items as you pack, and the app identifies everything locally on your iPhone. No cloud APIs, no data collection—just pure on-device intelligence. Users are finding creative applications beyond travel, like home inventory for insurance or cataloging items for resale.

Another breakthrough is real-time character conversation with voice. Projects like MousyHub let you have natural conversations with AI characters entirely on your local machine. While current text-to-speech engines like Kokoro TTS lack emotional expression compared to cloud services, the privacy and offline capability make them invaluable for sensitive use cases.

The key enabler? Efficient models like MiniCPM4 that achieve 7x faster decoding than standard models while running on consumer hardware. With Apple's recent advancements in on-device AI and frameworks like CoreML, we're entering an era where professional AI capabilities don't require an internet connection."

###### VISUAL

**Title: "AI That Respects Your Privacy"**

- **On-Device Applications**:
  - Fullpack (iOS): Photo → Packing list, 100% private
  - Real-time voice characters: Local conversation
  - Document analysis: Sensitive data stays local
- **Key Benefits**:
  - No internet required
  - Complete data privacy
  - Zero monthly fees
  - Works anywhere
- **Technical enablers**:
  - Apple VisionKit & CoreML
  - Efficient models (MiniCPM4: 7x faster)
  - Hardware acceleration (Neural Engine, GPUs)
- Visual: Phone showing local AI processing with "No Cloud" icon

###### NOTES

- Fullpack uses Apple's VisionKit for object detection—all processing on-device
- MousyHub provides lightweight alternative to SillyTavern for local character AI
- Current limitation: Local TTS lacks emotional prosody vs cloud solutions
- Trend: Users repurposing apps creatively (packing → inventory → eBay cataloging)
- Privacy becoming major differentiator as AI handles more sensitive data
- Technical note: 20GB RAM now sufficient for powerful local models

###### LINKS
- https://apps.apple.com/app/fullpack (Fullpack iOS app)
- https://github.com/MousyHub/MousyHub (Local character conversation)

###### DEMONSTRATION

**Demo - Privacy Comparison:**

1. Show a cloud-based AI service privacy policy
2. Contrast with on-device app: "Your data never leaves your device"
3. Demonstrate offline functionality: Turn on airplane mode, app still works

**Discussion:** "What sensitive tasks would you prefer to keep completely private? Medical notes? Financial planning? Personal journaling?"

---

### 9. Hands-On Activity: Interactive AI Exploration

#### 8.1. Activity Framework

##### [seq:110] Activity Setup and Instructions

###### SCRIPT

"Now it’s your turn! This activity will help you experience firsthand how generative AI tools behave under your own creative control.

I’ll provide a few base prompts from the lecture—but you’re encouraged to tweak them, remix them, or invent your own. Try different tools (ChatGPT, Claude, Gemini) and observe how they respond to changes in style, tone, complexity, and clarity.

This is where your experimentation begins."


###### VISUAL

**Slide Title: "Try It Yourself: AI Prompt Playground"**

- Instructions:
	- Use sample prompts provided (or create your own)
	- Compare results across 2–3 AI tools
	- Reflect on:
		- Which tool did best?
		- What surprised you?
		- Where did it fail?
- Visual: Screenshots of different tools running the same prompt with different outputs


###### NOTES

- Encourage creativity and curiosity—there are no wrong answers here
- Joke: “You now have permission to try to confuse the AI—just don’t let it confuse you.”
- Tip: Invite participants to take screenshots of interesting results to share with the group

---

#### 8.2. Exploration Prompts

##### [seq:120] Writing

###### DEMONSTRATION

- "Rewrite this paragraph to make it sound like Shakespeare."
- "Summarize the main ideas in this article for a child."

---

##### [seq:130] Code

###### DEMONSTRATION

- "Write a Python script to batch rename files in a folder."
- "Debug this broken function (paste your own)."

---

##### [seq:140] Visual

###### DEMONSTRATION

- "Describe what’s happening in this image (upload one)."
- "Generate a poster for an imaginary movie titled 'Neon Cosmos.'"

---

##### [seq:150] Document

###### DEMONSTRATION

- "Extract the key risks and recommendations from this uploaded report."

---

#### 8.3. Collaborative Learning

##### [seq:160] Discussion & Reflection

###### SCRIPT

"Let’s regroup and share!

What did you find most impressive? Where did the tools let you down? Were some better at creativity, others at precision? Did the interface or response style affect your experience?

Take a moment to discuss with the person next to you or jot down your key takeaway."


###### VISUAL

**Slide Title: "Let’s Talk: What Did You Discover?"**

- Reflection prompts:
	- What surprised you most?
	- Did one tool stand out?
	- Would you trust these results in a real task?


###### NOTES

- Tip: Call on a few volunteers to share results (especially any funny or unexpected ones)
- Mention: These discoveries often reveal both power and limits of the tools
- Joke: “Remember: If the AI wrote a limerick about your cat’s investment portfolio… you win.”

---

### 9. Summary and Key Insights

#### 9.1. Learning Outcomes

##### [seq:170] Recap of What We Explored

###### SCRIPT

"Today we’ve taken a big leap from observing AI to actually working with it. We’ve seen how AI can assist in writing, editing, translating, coding, debugging, and analyzing visuals and documents. And most importantly, we’ve experienced how different tools bring unique strengths to each of those domains.

Some models are better at structure, others at storytelling. Some at visuals, others at text. The key takeaway is: **AI isn’t magic—it’s modular.** Knowing the tool and the task is everything."


###### VISUAL

**Slide Title: "What We Learned Today"**

- AI can:
	- Write and edit with tone awareness
	- Translate language and idioms accurately
	- Generate and debug code
	- Analyze documents and visuals
	- Work inside our tools and workflows
- You:
	- Compared models head-to-head
	- Explored real-world use cases
	- Saw strengths _and_ limitations


###### NOTES

- Reinforce that this was about practical use—not just concepts
- Tip: Mention how tools continue evolving, so today’s limits may be tomorrow’s features
- Joke: “You came. You prompted. You confused the AI. Success.”

---

#### 9.2. Practical Applications

##### [seq:180] Real-World Implications

###### SCRIPT

"So how does this all tie into the real world?

For writers, it’s a brainstorming partner. For developers, a junior assistant. For analysts, a research intern. AI isn’t replacing experts—it’s enhancing them.

But it only works if you use it wisely. Your role is to be the human-in-the-loop: to guide, to judge, to adapt.

That’s how we build a future where AI makes our work faster, smarter, and more creative."


###### VISUAL

**Slide Title: "Why This Matters"**

- Faster workflows, fewer mistakes
- More room for creativity and insight
- Human + AI = better than either alone


###### NOTES

- Mention examples: AI helping lawyers summarize cases, teachers prepare materials, researchers find insights
- Joke: “It’s not about replacing you—it’s about finally hiring that perfect intern… who never takes coffee breaks.”

---

### 10. Homework Assignment: Practical AI Integration

#### 10.1. Assignment Guidelines

##### [seq:190] Homework Overview

###### SCRIPT

"To wrap up this session, your homework is to take what we’ve explored today and apply it independently.

You’ll choose a few tasks—from writing to code debugging to document analysis—and test them across multiple AI tools. Your goal is to observe, compare, and reflect on:

- Which tools performed best?
- Where did they struggle?
- Would you use them in your actual work?

We’ve included a template for you to document your findings."


###### VISUAL

**Slide Title: "Homework: Put AI to Work"**

- Choose 2–3 tasks:
	- Text: generate, rewrite, or summarize
	- Code: generate or debug
	- Visual: interpret diagram or generate an image
	- Document: summarize or extract data
- Use at least two different AI tools
- Record:
	- Prompt used
	- Tools tested
	- Output quality
	- Observations


###### NOTES

- Provide link to downloadable homework template (Google Doc or PDF)
- Joke: “Yes, this is the one time I want you to talk to more than one AI at once.”
- Tip: Encourage exploration beyond the prompts from class

---

#### 10.2. Evaluation Criteria

##### [seq:200] Submission Instructions

###### SCRIPT

"Submit your completed observations by [insert deadline]. It doesn’t have to be perfect—focus on your **experience and insight**.

This assignment is designed to make you comfortable experimenting, prompting, and evaluating. The more curious you are, the more valuable the outcome."


###### VISUAL

**Slide Title: "Turn It In"**

- Deadline: [Insert Date]
- Format: PDF or shared Google Doc
- Submit via: [insert platform/email]


###### NOTES

- Reinforce low-pressure, exploratory tone
- Suggest sharing funny or odd results with the group next session
- Joke: “No AI-generated excuses about late homework—unless they rhyme.”

---

### 11. Resources for Continued Learning

#### 11.1. Technology Resources

##### [seq:210] Recommended Tools and Libraries

###### SCRIPT

"AI is evolving rapidly—and keeping up can be overwhelming. But there are a few trusted tools and communities you can explore after today to stay ahead.

Here are some resources to help you build skills, find inspiration, and stay connected."


###### VISUAL

**Slide Title: "Explore More: Tools & Libraries"**

- Prompt libraries:
	- [OpenAI Prompt Library](https://platform.openai.com/examples)
	- [FlowGPT](https://flowgpt.com/)
- Tools we used:
	- [ChatGPT](https://chat.openai.com/)
	- [Claude](https://claude.ai/)
	- [Gemini](https://gemini.google.com/)
	- [Perplexity](https://www.perplexity.ai/)
- Integrations:
	- [ChatGPT macOS app](https://openai.com/chat)
	- [VS Code + GitHub Copilot](https://github.com/features/copilot)
	- [IntelliJ IDEA with AI Assistant](https://www.jetbrains.com/idea/whatsnew/#ai)


###### NOTES

- Encourage bookmarking these links and playing with prompt variations
- Joke: "Exploring prompt libraries is like wandering through an AI-powered candy store. Just… fewer cavities."
- Tip: Recommend subscribing to newsletters like _Ben’s Bites_ or _TLDR AI_ for daily updates

---

#### 11.2. Community Engagement

##### [seq:220] Communities and Learning Hubs

###### SCRIPT

"And don’t go it alone—there’s a thriving AI learner community out there.

Whether you want to join a forum, ask for help, or just lurk and learn—there’s something for everyone."


###### VISUAL

**Slide Title: "Communities to Grow With"**

- Reddit:
	- [r/ChatGPT](https://www.reddit.com/r/ChatGPT)
	- [r/PromptEngineering](https://www.reddit.com/r/PromptEngineering)
- Discord Servers:
	- ChatGPT Users
	- FlowGPT Community
- News & Learning:
	- [Ben’s Bites](https://www.bensbites.co/)
	- [TLDR AI](https://www.tldr.tech/ai)


###### NOTES

- Encourage staying curious and participating in communities to deepen understanding
- Joke: "Think of Reddit as your AI study group… with occasional chaos."
- Tip: Suggest creating a personal prompt journal to track what works and what doesn’t

---