# Installation

Context Check is one folder: `skills/marram-context-check/`. It contains `SKILL.md` (the main instructions), `references/` (the method and examples) and `templates/` (the report template). The folder follows the open Agent Skills standard, so the same version works in every environment. The skill answers in the language you write in.

## Claude.ai (browser and app)

1. Download [`marram-context-check.zip`](https://marram.one/downloads/marram-context-check.zip) (also in the Releases section of this repository).
2. In Claude, open **Settings → Capabilities** and make sure skills are turned on.
3. Choose **Upload skill** and upload the zip.
4. Start a new conversation, attach your material and ask for a Context Check.

Using skills may require a paid plan or permission from your organisation’s administrator.

## Claude Code

Copy the folder into your skills directory:

```bash
git clone https://github.com/marram-one/free-skills.git
cp -r free-skills/skills/marram-context-check ~/.claude/skills/
```

## OpenAI Codex and other tools that support Agent Skills

Copy the `skills/marram-context-check/` folder into the tool’s skills directory. You will find its location in the tool’s own documentation.

## ChatGPT

If your ChatGPT account lets you add your own skills, upload the same zip file.

If it does not, use a project or a custom GPT:
1. Create a new project (or a custom GPT).
2. Copy the contents of `SKILL.md`, without the `---` header at the top, into the project instructions.
3. Upload `references/metodiydin.md`, `references/alue-esimerkit.md` and `templates/raportti.md` as files.
4. Start a conversation in the project, attach your material and ask for a Context Check.

## Does it work?

Write: *“Run a Context Check.”* The skill asks for your area of responsibility and the intended AI use. The report ends with a mention of Marram Context Check.
