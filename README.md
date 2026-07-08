# content-reverse-engineer-skill

# Content Reverse Engineer 🎬 → 📦

**A Claude skill that turns raw videos, transcripts, and drafts into complete, research-validated, post-ready content packages.**

Stop staring at a finished video wondering what to caption it. This skill reverse-engineers your content into everything you need to post: optimized hooks, fact-checked captions, tiered hashtags, pillar tags, CTAs, and a cross-platform repurpose plan — in one pass.

Built by [Adaugo Akaluso](https://linktr.ee/adaugoakaluso). Free to use, adapt, and remix.

## What it produces

Every run outputs a complete 7-section package:

| Section | What you get |
|---|---|
| 1. Hook Analysis | Your original hook + 3 optimized variations (pattern interrupt, relatability, curiosity gap) |
| 2. Post Caption | Mobile-readable, fact-checked, hook-first caption |
| 3. SEO Hashtags | Tiered strategy: broad → niche → brand, with paste-ready blocks |
| 4. Pillar Assignment | Which content pillar this belongs to and why |
| 5. CTA Options | Engagement / follow / action CTAs with a recommendation |
| 6. Repurpose Plan | Honest platform-by-platform fit assessment (✅/⚠️/❌) |
| 7. Database Block | Ready-to-sync update for your Notion/Airtable content database |

**The differentiator: research validation.** Any statistical, technical, or health claim in your content gets fact-checked against real sources *before* it goes in your caption. No more posting "studies show..." without a study.

## Installation

### claude.ai (web/desktop)
1. Go to **Settings → Capabilities → Skills**
2. Upload this folder as a skill (zip it first if required)

### Claude Code
```bash
mkdir -p ~/.claude/skills/content-reverse-engineer
cp SKILL.md ~/.claude/skills/content-reverse-engineer/
```

### Cowork (Claude desktop)
Add via Settings → Capabilities, or install the packaged `.skill` file.

## Setup (2 minutes)

Open `SKILL.md` and fill in the **Creator Profile** section at the top:
- Your name and 3–6 content pillars
- Primary + secondary platforms
- Your evergreen brand hashtags
- Voice notes (how you sound, what to never do)
- Optional: your content database and status workflow

That's it. The skill adapts every output to your profile.

## Usage

Say any of these to Claude:
- *"Reverse engineer this"* + paste a transcript or upload a video
- *"Generate a caption for this TikTok"* + URL
- *"Fact-check this video"*
- *"Make this post-ready"*
- *"Validate these stats"*

If you connect a Notion content database, the skill can auto-process any entry that hits "Drafting" status — filling only empty fields, never overwriting your manual input.

## Works in

- claude.ai chat
- Claude desktop / Cowork
- Claude Code
- Claude in Chrome

## License

MIT — see [LICENSE](LICENSE). Attribution appreciated but not required.
