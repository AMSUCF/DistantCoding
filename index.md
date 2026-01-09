# Distant Coding for the Digital Humanities at MLA 2026

**Presenters:**
- Anastasia Salter, University of Central Florida
- Lai-Tze Fan, University of Waterloo

<div class="elo-sponsor">
  <a href="https://eliterature.org/" target="_blank">Sponsored by the Electronic Literature Organization</a>
</div>

## About This Session

Scholars explore the relationship between generative AI and the future of digital humanities programming using agent-based tools. Participants will be introduced to a beginner-friendly method commonly referred to as "vibe coding," which emphasizes describing and solving problems through code rather than editing code directly, for tasks such as distant reading and digital humanities prototyping.

This session explores agentic AI as a cultural technology reshaping digital humanities practices, including:

- Distinctions between agentic and generative AI for scholarly work
- Agent-based coding tools (Claude Code) and research assistants (Perplexity.AI)
- Practical applications for distant reading, text analysis, and DH prototyping

---

## Demos and Examples

### Agentic Applications

- **[Perplexity.AI's Comet](https://www.perplexity.ai/help-center/en/articles/12590157-what-is-education-pro?q=ed)** - Bibtex citations, markdown archives, and Canvas updates for education

- **[Claude Code Web Workflow](https://anastasiasalter.net/HumanitiesAI/weektwelve.html)** - Practical workflow for web development with Claude Code

- **[Windows Command Prompt Game Demo](https://anastasiasalter.net/ClaudeGameDemo/)** - Interactive game generated with Claude Code / Sonnet 4.5 ([process documentation](https://github.com/AMSUCF/ClaudeGameDemo/blob/claude/init-project-011CUbppTYHhowVH4yMSJvE8/PROCESS.md))

- **[Agentic AI in Education Site](https://anastasiasalter.net/ClaudeEducationalDemo/)** - Educational site and text game generated with Claude Code / Sonnet 4.5 ([process documentation](https://github.com/AMSUCF/ClaudeEducationalDemo/blob/claude/init-project-011CUdfAbtzA4zFUnqcy3TAE/PROCESS.md))

- **[Getting Started with Claude in Chrome](https://support.claude.com/en/articles/12012173-getting-started-with-claude-in-chrome)** - Anthropic's official guide to using Claude as a browser extension

### Tools and Platforms

- **[Claude Code](https://www.claude.com/product/claude-code)** - Anthropic's official CLI for Claude AI

- **[WordPress MCP Adapter](https://meowapps.com/ai-engine/)** - Model Context Protocol adapter for WordPress

- **[Awesome Claude Skills](https://github.com/BehiSecc/awesome-claude-skills)** - Curated collection of Claude skills and capabilities

---

## Further Reading

- **[Marc Watkins to Perplexity AI](https://marcwatkins.substack.com/p/an-open-letter-to-perplexity-ai)** - An open letter examining AI tool development and ethics

- **[Simon Willison on Agents](https://simonwillison.net/2025/Sep/18/agents/)** - Understanding agent-based AI systems

- **[Living Dangerously with Claude](https://simonwillison.net/2025/Oct/22/living-dangerously-with-claude/)** - On dangerously skipping permissions and AI safety considerations

- **[MLA Statement on Educational Technologies and AI Agents](https://www.mla.org/Resources/Advocacy/Executive-Council-Actions/2025/Statement-on-Educational-Technologies-and-AI-Agents)** - Modern Language Association guidance on AI agents in educational contexts

- **[AI Is the Future. Higher Ed Should Shape It](https://www.chronicle.com/article/ai-is-the-future-higher-ed-should-shape-it)** - Chronicle of Higher Education on the role of higher education in shaping AI's development and implementation

- **[How AI Is Changing Higher Education](https://www.chronicle.com/article/how-ai-is-changing-higher-education)** - Chronicle of Higher Education article examining the transformative impact of AI on colleges and universities

- **[Humanities in the Age of AI](https://anastasiasalter.net/HumanitiesAI/)** - Complete syllabus and exercises for teaching with AI

- **[How I Use Every Claude Code Feature](https://blog.sshh.io/p/how-i-use-every-claude-code-feature)** - Shrivu Shankar's comprehensive guide to Claude Code features and best practices

- **[Everyone Should be Using Claude Code](https://www.lennysnewsletter.com/p/everyone-should-be-using-claude-code)** - Lenny's Newsletter on the transformative potential of Claude Code

- **[Why Anthropic's MCP is a Big Deal](https://blog.bytebytego.com/p/why-anthropics-mcp-is-a-big-deal)** - ByteByteGo analysis of the Model Context Protocol

---

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
