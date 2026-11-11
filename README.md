# Agent Skills Repository

A curated collection of production-grade skills for AI coding agents (Google Antigravity, Claude Code, OpenAI Swarm, LangChain, etc.).

---

## 📦 Included Skills

### 🎓 [`codebase-masterclass`](skills/codebase-masterclass/SKILL.md)
Master any codebase, framework, or technology through a structured, mentor-led architectural deep dive.
- **Role**: Principal Systems Architect & Senior Staff Engineer.
- **Capabilities**:
  - Codebase reconnaissance and entrypoint discovery.
  - End-to-end curriculum generation (Foundations, Protocol Translation, Router/Load Balancing, Enterprise Security, Low-Level Stack Walkthrough, Production Engineering).
  - Validated Mermaid architecture and sequence diagrams.
  - Grounded code stack tracing with authentic file references.

---

## 🚀 Installation & Usage

### 1. In Antigravity Projects
To use these skills in any Antigravity workspace, copy the `.agents/skills` folder into your project root:

```bash
# Clone this repository
git clone https://github.com/<YOUR_USERNAME>/agent-skills.git

# Copy skills to your project
cp -r agent-skills/.agents/skills /path/to/your/project/.agents/
```

### 2. Global Antigravity Installation
To make skills available across all your Antigravity sessions globally:

```bash
# Copy to Antigravity global skills directory
cp -r agent-skills/skills/* ~/.gemini/antigravity-cli/skills/
```

---

## 🛠️ Adding New Skills

To add a new skill to this repository:
1. Create a new directory under `skills/<skill-name>/` and `.agents/skills/<skill-name>/`.
2. Add a `SKILL.md` file with standard YAML frontmatter:
   ```yaml
   ---
   name: your-skill-name
   description: >-
     A concise description of what the skill does and when the agent should invoke it.
   ---
   # Your Skill Title
   Detailed instructions, workflows, and prompts...
   ```
3. Commit and push to GitHub!

---

## 📄 License

MIT License. Feel free to use, share, and expand these skills for your agent workflows.
