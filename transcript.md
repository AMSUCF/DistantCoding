*Live transcript from the MLA session, edited by Claude. Errors might remain.*

# AI Distant Coding Workshop
## MLA 2025

**Presenters:** Lai-Tze Fan and Anastasia Salter

---

## Part One: Introduction to Distant Coding (Lai-Tze Fan)

### What is Distant Coding?

You presumably came to this panel thinking about learning about distant coding, but what do we mean by that term? What do we mean by "vibe coding"? What do we mean by "agentic AI"?

What we're talking about is using a large language model-based agent to achieve a goal as part of our digital humanities work, however you want to describe digital humanities in your own terms.

We are using Simon Willison's description of agentic AI, which he describes as "an LLM agent that runs tools in a loop to achieve goals." Willison also says that agents as "human replacements" is his least favorite definition because he's not thinking about getting rid of the human in the project, but rather creating a back and forth. This is where it becomes interesting because it's no longer about having technical skill, but instead understanding a system and also understanding your own discipline and your own work well enough that you can use this tool to make things happen. If the agent does the technical work for you, then you just have to bring your own knowledge and expertise.

Willison also quotes an older computational principle: "A computer can never be held accountable. Therefore, a computer must never make a management decision."

### Transparency and Control

Tools like Claude Code include a permissible amount of agency. They will ask you permission: "I'm going to do this. Can I access this folder? Is this okay?" This starts to eliminate some of what we might consider the black box element of AI, because it will show you step by step what it's doing. "Now I'm going into your class assignment. Now I'm looking at the discussion and the assignment requirements. Now I'm starting to populate the assignment."

### A Speculative Example: Feminist Archives

Imagine you already have a folder full of feminist archives—small, limited. You've collected the lost archives of a writer whose work is not very well known, but you want to build an interactive, web-based archive that somebody can go through to see these digitized materials.

Perhaps knowing that you have the capacity to make it Live Journal-style, '90s-style, GeoCities-style, you can use that thematically and aesthetically as part of the experience. If you're thinking about archives, maybe you want to represent the fact that there has been absence or erasure, so as part of that interactive experience, you can ask that the text and metadata be deliberately ambiguous, and the user has to discover these elements on their own.

Instead of something like ChatGPT offering you code and then you going off to build it to see if it works, you're sharing an idea. You're defining parameters, values of the work, and what you think a successful outcome would be of this archival project. Claude Code makes recommendations on technical approaches. With your approval, it implements them into this archival system that can be adjusted until it matches what you've defined as a successful outcome.

You can make adjustments or suggestions for changes and edits that are akin to critical feedback. It's not like you're going in to fix code yourself. Instead, you're offering expert notes: "In existing feminist archives, we might have accompanying photographs—I need more of that. I need a visualization of the network: who is this author connected to relative to other authors?" These are suggestions you can include as you continue to edit the system until it looks like what you're hoping for. You're not the one coding; you're just offering up your ideas.

### Key Takeaways

The point of this workshop is to think about the value of large language models for coding and humanities projects, to lower the threshold and make code-based projects more accessible for all of us. It's not about eliminating critical thinking, but shifting the focus from mastering coding to thinking about project design.

What is project design going to look like, especially when it's collaborative with an AI agent? The question starts to shift from "Can I code this? Do I have the skills to code this? Who do I have to hire to code this?" to "What do I want this project to do?"

We can have a more focused attention on conceptual structure and narrative logic. You can work in a specific ethos: "I want this to look like existing archives, but to have an element of exploration" or "a stronger ethical framework."

### Increasing Coding Literacy

Large language models can help explain what existing code is doing. Humanists can ask for translations of the relationship between narrative logic (what we might be trained in) and conditional logic (as a computer might understand it). If you're seeing a decision that was made, you can literally ask Claude Code: "Why did you make that choice?" Not just to say you do or don't accept it, but to ask questions—you have your own personal assistant who also knows that stuff and can explain it to you.

This also allows us to think about translations between scholarly concepts and computational structures: "Why did you build it this way? What does this look like in terms of metadata or data management?" Claude Code can make recommendations for preferable platforms and tools, allowing us to experiment with technologies with lower commitment and lower risk because it's building things you can see as an experiment pretty much immediately.

### Making Code Critical

Finally, imagine the ways in which we can use agentic AI to make code itself more critical, allowing us to be part of the conversation, to analyze and interrogate coding structures and algorithmic choices. We can literally ask Claude Code: "What happens if I do this? What happens if I change that?" and see what tweaks that makes. You can say, "No, scrap that, go backwards." The code itself, and the things that it creates, becomes something we can also read and critique and revise—like a text.

---

## Part Two: Demonstration and Discussion (Anastasia Salter)

### Why This Matters

One of my big concerns—with apologies to people in the room who worked on certain statements—is that the way AI agents are being framed to educators right now is mostly through the conversation around plagiarism. I've had difficulty convincing some faculty to even go near this, much less understand the impact it has on the sorts of things they teach, as well as the sorts of things they do every day.

We've also got predatory edtech moves happening. Perplexity offered Chegg for free to students for a year with a marketing campaign and the obvious refrain that "your professors are using AI, therefore you should too." 

But it's also true that there's a lot of repetitive labor asked of us that used to involve other staff members or perhaps a graduate assistant that many of us are doing now. If you're not using agents for that type of labor, I encourage you to think about doing so.

The MLA has made a point that I think is really critical around agentic AI: full faculty and structural involvement, particularly for those of us in the humanities, is absolutely critical when thinking about the types of tools we use and how we use them. Most universities are not involving humanities faculty in those decisions, and they're not making responsible decisions at all. My university is recommending Grok.

### Choosing Your Tools

One of the ways I pragmatically think about tool selection is to watch how different models are performing on coding benchmarks. What I care about is code, because ultimately everything useful you get from an agentic system comes down to the code it writes to solve your problem, the code it writes to manipulate tools, and how it's handling your data. What we used to do with Python or JavaScript, we are now asking these systems to do.

Right now, the top tier is really either Google's Gemini 3 Pro—which is terrifyingly good at other tasks as well, like handwriting recognition that has huge implications for digital humanities labor—or Anthropic's Claude. The reason I'm going to show you Anthropic is simple: while Gemini's tools look intimidating, Claude has much more accessible and teachable tools with a gentler learning curve for both faculty experimentation and incorporating agentic tools into your workflow.

### The Subscription Question

Here's the catch: if you are not paying for an AI system, you are the product. In order to use Claude and take advantage of anything useful with code and data, you do have to have a monthly subscription. It's $20 a month for Anthropic, and Anthropic is the least problematic of the big AI companies in a few ways. They don't play in image and video generation, which is automatically less harmful environmentally and in terms of the type of content they're putting out. They've been very focused on code. We have fewer concerning incidents associated with Anthropic tools than with OpenAI's tools.

If you're in a position to guide your institution toward certain tools, Anthropic is a strong choice, with a runner-up nod for Google campuses. Those of us with Microsoft Copilot subscriptions on our campuses—I'm so sorry. A lot of my colleagues have used that and think that's what AI can do, and that's probably the biggest challenge.

### The Progression: Artifacts to Claude Code

The standard Claude chatbot interface is actually where you can start students and yourself with useful things. You can ask it to build a '90s-style GeoCities-inspired blog, and it will generate HTML you can then download and work with.

But what Claude has introduced that makes it ideal for pedagogy is Claude Code Web. With standard chats, you talk to a bot and go back and forth until you get what you want. Projects are for working across multiple resource files. Artifacts are things you generate and save as shareable outputs.

But Claude Code Web has a lot of the capabilities of the command line tool while running all compute on Claude's servers. This gives us a sandbox where students can't accidentally delete things on their computer. It's training wheels because everything is isolated. It's also really friendly for students without dedicated laptops—you can work on it from your phone. Everything lives in two places: the conversation happens on Claude Code, and your actual code lives on GitHub.

### Working with GitHub

Once you've gotten your students onto GitHub—which with an educational account allows them to build just about anything—you can talk to any of your existing repositories or create new ones.

When you think about computational interfaces you've worked with before, from Turbo Pascal to Visual Basic, coding tools have already changed a lot about programming. They eliminated some syntax errors and made it more likely you were referencing attributes correctly. But those tools only understood the language—they didn't understand what you were trying to do.

Working with these agentic systems, it's all that contextual knowledge that makes it really interesting for how it's building and thinking about projects.

### Version Control and Iteration

Each input and back and forth becomes its own commit. Let's say you build something and it works, and then you ask for animations and you break it somehow. You can go back to a previous version and try again, giving it any errors you've observed or describing the problem.

For one open street map project, I really didn't know what I was doing. The class wanted to map periodicals in the US. We built something, changed default assumptions, used planning mode to clarify what we wanted, and the class voted on options. It was still trying to use a Python script, but I wanted it to run on GitHub Pages, so I made it rewrite until we had a working version.

It took us five commits to get to a version the students liked, each one with descriptions better commented than almost anything I've ever gotten from students. We deployed it on GitHub Pages as we went along, so everyone could see things without ever having downloaded anything on their computer. We got to a working deployed website without having ever installed anything—which if you're working with students with Chromebooks, has an incredible advantage.

### Data Quality and Verification

**Question:** How do you know the data is right?

For demos where we let it generate the dataset, I ask those who requested it whether the data looks accurate. The better approach, if not demoing, is to have students collect the data first, then convert it to JSON. That way we know everything is accurate. The generated data is basically placeholder data—the interface, timeline filter, everything's working. Now they can go in and make corrections, which are easy to do.

When I talk to students about making corrections, I don't take them into Visual Studio Code because that tends to shut people down. Since it's a well-structured project, you can go into the JSON files directly and edit, or you can prompt Claude Code to do it for you.

### Undergraduate vs. Graduate Approaches

For undergraduates, I assume they know nothing, which is why starting with artifacts works—they don't have to manage files, understand file structures, or know how to put things on a server. They can run Python code through Claude's interface instead of installing a Python environment. My philosophy is as few tools as possible. Claude can replace a lot of the tools I used to teach in an undergraduate DH class.

For graduate students, we do a more intensive approach. In my course, we spend five weeks going through how chatbots work, reading critiques, contextualizing it in digital humanities. We read Michael Littman's *Code to Joy* so they get the vocabulary for things like functions. By the end, they're building custom fine-tuned GPTs on datasets they pulled from Project Gutenberg, building dramatic multimodal resources. One person who teaches at three universities built sets of games for learning different style formats tailored to each institution. Another built a feminist erasure tool where you could upload materials, control it, and transform it. I would not ask that of someone in their first digital humanities course.

### Textual Analysis Workflow

I teach students some vocabulary, give them exact prompts we're going to use, and they pick their book. The first time we do it with one text, then we do it with five and have them do chart comparisons.

It writes a Python script to remove boilerplate. You can hide the script so students don't panic about the fact there's code, but I like to then go back and explain: "This is code. It's running a Python script. This is the same as the computational text analysis methods a grad student would use, but now they're accessible to you without knowing Python yourself."

Once you've told it what you're doing, it will overachieve—generating the clean text, normalized text, no-stop-words version, word frequency CSV, and stats. Then you look over it and decide what else you want: sentiment scoring, n-gram extraction.

**Question:** Are you just trusting the results?

For a few texts the first time, I bring up Voyant for comparison: "Here's how we establish trust—let's compare our results." I also encourage students to pick a text they know really well so they can decide how they feel not just about the tool, but about the thematic analysis it tries to do. One of my goals is to get them to think more about what it does computationally, where they can see patterns, and then feel more confident using it across texts they're less familiar with—and not relying on AI to tell them what the themes of Frankenstein are.

For professional work, we still have responsibility for code review. That's the step I take graduate students to: looking at the Python script, talking about critical code studies as a method for reading through it, building confidence in certain types of results.

### Where Human Expertise Matters

**Question:** How do you trust accuracy for complex projects like historical newspapers?

That's exactly where the human expertise is. My goal is that students who want to make a visualization like that spend most of their time on the quality of their data—less of their time worrying about syntax and interface. When I think about the time my students used to spend on teaching them every other part of those projects, we didn't spend as long on the data. Ideally, we're creating more time to really use human expertise in areas where it matters most.

### The Value Proposition Shift

The value proposition in software is absolutely shifting. Most AI startups—the ones people talk about as the "AI bubble"—are basically: "We took a model, put it in a fancy interface, and now it'll help you with recipes." Those value propositions are not going to hold.

Things like this, where the most powerful model is your computational interface, that holds. It can handle and provide customized interfaces for all sorts of things you want to do. The reality is that my students were never going to pay for qualitative coding software. The fact that I can take them through qualitative and thematic coding passes and have them build their own interface for working through their data—that's what they're going to use.

### The Pace of Change

**Question:** How long will it take for the rest of the academic world to catch up?

The speed of change and the accessibility of the interface is what's going to drive that change. Things like Claude Code Web are a transition point, because now I can take students who would never have been interested and show them something accessible. When Claude Code Web dropped, I rewrote the last half of my class. That was when I could also show this to faculty who weren't technical. I could bring in people confident with basic interfaces like GitHub, and I could give people a reason to build confidence with GitHub because they could see the results we can get.

Claude Code Web is already a little clunky, but the possibilities for how that interface can get easier, how more of the GitHub workflow can be integrated, the ways in which our procedural literacy still matters while a lot of other expertise we used to develop in DH classes doesn't—I think that's coming more rapidly than you think.

### A Closing Note on Labor

The flip side of this is that expectations for us workload-wise are also changing. If you're not using agentic workflows for some of the things you do, you can still expect the labor expectations to increase around you. That's the nature of every other software innovation we've dealt with. It becomes more expedient, so we can expect everyone to do everything else that used to be done by someone else—by staff, or one librarian, or one DH programmer.

Administratively, we will start to see changes when there are lowering enrollments in courses that require things like design. That will change demand for instruction. Courses have to adapt to consider these things, otherwise, as students pick up on the fact they can use agentic AI, there will be lowered enrollments and lower need for instruction.

---

*Resources and additional materials are available at the website linked from the session abstract.*

<button class="theme-toggle" onclick="toggleTheme()" aria-label="Toggle theme">
  <span id="theme-label">Light Mode</span>
</button>

<script>
  // Theme toggle functionality with localStorage persistence
  function toggleTheme() {
    const html = document.documentElement;
    const currentTheme = html.getAttribute('data-theme');
    const newTheme = currentTheme === 'light' ? 'dark' : 'light';

    html.setAttribute('data-theme', newTheme);
    localStorage.setItem('theme', newTheme);
    updateThemeLabel(newTheme);
  }

  function updateThemeLabel(theme) {
    const label = document.getElementById('theme-label');
    if (label) {
      label.textContent = theme === 'light' ? 'Dark Mode' : 'Light Mode';
    }
  }

  // Load theme from localStorage on page load
  (function() {
    const savedTheme = localStorage.getItem('theme') || 'dark';
    document.documentElement.setAttribute('data-theme', savedTheme);
    updateThemeLabel(savedTheme);
  })();
</script>
