# claude-brand-strategist-skill

Nice — put it on GitHub as a small reusable Claude Code skill repo.

Use this structure:

```text
claude-brand-strategist-skill/
├── README.md
└── brand-strategist/
    └── SKILL.md
```

## 1. Create the files locally

```bash
mkdir -p claude-brand-strategist-skill/brand-strategist
cd claude-brand-strategist-skill
touch README.md brand-strategist/SKILL.md
```

Paste the skill content into:

```text
brand-strategist/SKILL.md
```

## 2. Add this `README.md`

````markdown
# Claude Brand Strategist Skill

A Claude Code skill for brand strategy, brand identity, brand positioning, messaging, tone of voice, visual identity direction, social media branding, and brand guidelines.

## What This Skill Does

This skill helps Claude create structured and practical branding work, including:

- Brand strategy
- Brand identity direction
- Brand positioning
- Brand messaging
- Brand voice and tone
- Visual identity guidance
- Social media branding
- Brand audits
- Brand guidelines
- Personal branding
- Startup and product branding

## Folder Structure

```text
brand-strategist/
└── SKILL.md
````

## Installation

Copy the `brand-strategist` folder into your Claude skills directory:

```bash
mkdir -p ~/.claude/skills
cp -r brand-strategist ~/.claude/skills/
```

The final path should look like this:

```text
~/.claude/skills/brand-strategist/SKILL.md
```

## Usage

After installing, Claude Code can use this skill when you ask for branding-related help, such as:

```text
Create a brand strategy for my skincare startup.
```

```text
Audit my personal brand and improve my positioning.
```

```text
Write brand guidelines for a luxury coffee brand.
```

```text
Create a tone of voice guide for my SaaS product.
```

## Skill File

The main skill is located here:

```text
brand-strategist/SKILL.md
```

## License

MIT License.

````

## 3. Upload to GitHub with Git

```bash
git init
git add .
git commit -m "Add Claude brand strategist skill"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/claude-brand-strategist-skill.git
git push -u origin main
````

Replace `YOUR_USERNAME` with your GitHub username.

## Suggested repo name

```text
claude-brand-strategist-skill
```

## Suggested GitHub description

```text
A Claude Code skill for brand strategy, positioning, messaging, visual identity, and brand guidelines.
```
