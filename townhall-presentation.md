---
marp: true
theme: default
paginate: true
backgroundColor: #1a1a2e
color: #eee
style: |
  h1 { color: #00d4ff; }
  h2 { color: #00d4ff; }
  strong { color: #00d4ff; }
  blockquote { border-left: 4px solid #00d4ff; padding-left: 1em; font-style: italic; }
  img { border-radius: 8px; }
---

# AI Enablement Workshop
## Our Journey to AI-First

**Noam Almosnino** — Lead Designer, Automattic for Agencies
**Natalia Vidal** — Griffin Team Lead, Day One (Web+Server)

January 2026 | NYC

<!--
Hey everyone, I'm Noam from the A4A design team, and I'm here with Natalia Vidal from Day One. We just spent two weeks at the AI Enablement Workshop in NYC, and we want to share what that experience was like — and what it means for all of us. I'll share my perspective as a designer first, then hand it over to Natalia for the dev perspective.
-->

---

# The Space

![bg right:60%](images/IMG_2693.jpeg)

**Every day:**
Workshop → Practice time

Space to form new skills&nbsp;into&nbsp;flow.

Conversations at lunch. Late-night chats. Learning&nbsp;together.

<!--
This is the NoHo office where we gathered. Every day had the same rhythm: a workshop session in the morning, then practice time in the afternoon.

That structure gave us space to form new skills into flow — not just learn concepts, but actually practice them.

And honestly, some of the best learning happened outside the sessions. Conversations at lunch, late-night chats at the hotel, random exchanges in the hallway. That's where ideas clicked.
-->

---

# Our Journeys

Most workshops: learn something → go home → maybe apply it → back to&nbsp;routine.

This workshop: learn → **practice** → apply → repeat for two&nbsp;weeks.

**Time to build muscle memory. Not just concepts —&nbsp;habits.**

<!--
Most workshops, you learn something new, go home excited, and then... life happens. You're back to your routine. Maybe you apply one or two things, but most of it fades.

This was different. Two weeks. Every day: learn something in the morning, practice it in the afternoon. Apply it to real work. Repeat. By the end, it wasn't just knowledge — it was muscle memory. Habits.
-->

---

# Noam's Journey

**Day 1:** "Am I behind? Am I doing this right?"

**Day 6:** Reaching for AI tools naturally — muscle memory kicking in

> The unknown creates doubt. But we were all learning together.
> That's when I realized: I got this.

<!--
Day one, I walked in with imposter syndrome. You know that feeling — "Am I behind? Is everyone else further along than me?"

But then I started talking to people. At lunch, during breaks, in the hotel lobby. And I realized — we were all in the same place. Everyone was learning. That's when something clicked: I got this.

By day six, I noticed something different. I wasn't thinking about whether to use AI anymore. I was just... reaching for it. Like muscle memory. Commands like /learned to capture insights, /smart-commit for git. It became natural — which is exactly what I hoped for when I wrote my day-one intention.
-->

---

# Example: Dynamic Copy

**Before:** Generic CTA for all users
```
"Explore Tiers and benefits"
```

**After:** Tier-specific, JTBD-focused labels
```
emerging-partner  → "Start growing"
agency-partner    → "Grow my tier"
pro-agency        → "Unlock more"
premier-partner   → "View my benefits"
```

AI saw the tier data in the code → suggested dynamic copy.
**Context that's hard to get in Figma.**

<!--
Here's a concrete example from the workshop.

I had a card in A4A with a generic call-to-action: "Explore Tiers and benefits." Same button for everyone.

I was working with AI in the codebase, and it suggested making the copy dynamic. Why? Because it could see the tier information was already available in the code — context I wouldn't have had in Figma.

That led to different copy based on where the agency is in their journey. "Start growing" for new partners. "Unlock more" for those ready to level up. "View my benefits" for premier partners who've already made it.

The AI helped me think through the jobs-to-be-done framing and write the code. I made a PR — it's in review now. A small example, but it shows how working in the codebase with AI opens up possibilities you wouldn't see in a design tool.
-->

---

# Example: Claude Code + Day One

**Input** (quick capture):
```
/learned collaboration shifting to source of truth,
prototype in codebase, make PR, not figma handoff
```

**AI refines → Day One**:
> "Collaboration is shifting to the source of truth: prototype in the codebase, make a PR, have engineers refine. Designer and engineer collaborating on the real thing — not Figma-to-handoff."

**Later**: `/learned-review` → synthesized summary of 27 entries

<!--
Here's another example that connects Claude Code with Day One.

I built a slash command in Claude Code called /learned. When I have an insight, I just type it quickly — messy, shorthand, whatever. Claude cleans it up, adds context so it'll make sense months later, and saves it directly to my Day One journal.

So far I've captured 27 learnings from this workshop. And when I need to review them — like when preparing this presentation — I run /learned-review and get a synthesized summary.

It's AI as a capture tool. Quick input, refined output, ready for future me.
-->

---

# Noam's Realization

**Before:** Figma → Handoff → "It doesn't work that way in production"

**Now:** Prototype in the codebase → PR → Iterate together

The more you integrate context, the more possibilities open up.
**This is just one example.**

Product + Design + Dev = **Full Stack Designer**

<!--
Here's what really changed for me.

We used to work like this: design in Figma, hand it off, cross our fingers. Then hear back: "It doesn't work that way in production."

Now I can collaborate on the source of truth — the codebase itself. I prototype in real code. I make a PR. Engineers refine it. I iterate on their work with AI. We're both working on the real thing.

I'm not just a designer anymore. With AI, I can pull in product context, understand the codebase, and ship features. Product, design, AND dev. A full-stack individual contributor.

Now let me hand it over to Natalia to share her perspective as a developer.
-->

---

# Natalia's Journey

**Before:** Ad-hoc AI usage — ask a question, get an answer

**During:** Building repeatable patterns — skills, commands, workflows

**After:** AI helps me learn unfamiliar codebases and break down big projects

> I went from random questions to systematic workflows.
> That's what made it stick.

<!--
I came in already using AI — asking it to explain code, generate snippets, help with debugging. But it was ad-hoc. Random questions here and there.

The workshop changed that. I started building repeatable patterns. Custom skills. Slash commands. Workflows I could rely on.

Now I use AI to systematically learn unfamiliar codebases. I have it break down big projects into detailed, actionable plans. It's not just answering questions anymore — it's a structured part of how I work.

I went from random questions to systematic workflows. That's what made it stick.
-->

---

# Natalia's Example

**Project:** Cleaning up technical debt in Day One (web + server)

**The problem:** Legacy API patterns — inconsistent, hard to maintain

**AI's role:** Identified existing patterns across the codebase to maintain consistency

**Impact:** Code is now clearer and easier for the team to modify

<!--
During the workshop, I tackled some technical debt in Day One — specifically, legacy API patterns that had accumulated over time. They were inconsistent and hard to maintain.

What was interesting: I didn't just ask AI to rewrite the code. I used it to scan the entire codebase and identify existing patterns. That way, when I refactored, I stayed consistent with what the team was already doing elsewhere.

The result? The code is clearer now. Easier for the team to understand and modify going forward. Not a flashy new feature, but this kind of work makes everything else easier.
-->

---

# Natalia's Realization

**Before:** AI writes code → I review it

**Now:** AI helps me think through the problem → We design together

> AI isn't just generating code.
> It's a thought partner for architectural decisions.

When AI has full codebase context, it can spot patterns I'd miss.
**That changes the conversation from "write this" to "what should we do here?"**

<!--
Here's what really shifted for me.

I used to think of AI as a code generator. I'd describe what I wanted, it would write code, and I'd review it. Pretty transactional.

Now? AI helps me think through the problem before writing any code. We design together. I'll ask: "How should I approach this?" and AI will pull context from the codebase — patterns we're already using, conventions the team follows.

It's not just generating code. It's a thought partner for architectural decisions.

When AI has the full codebase as context, it catches things I'd miss. That changes the whole dynamic — from "write this for me" to "what should we do here?"
-->

---

# The Possibilities

What excites us most:

- **Parse feedback** from Zendesk, Linear, Slack → then execute
- AI as a **second reaching hand** — commands, skills, context
- The process: **Integrate tools → Build context → Brainstorm → Execute**

<!--
[NOAM SPEAKS THIS SLIDE]

So what are we excited to try going forward?

Full stack workflows. Use AI to parse feedback from Zendesk, Linear, Slack — understand what customers are actually saying. Then execute on that feedback directly.

AI becomes a second reaching hand. We have commands and skills ready to go.

Here's a simple example: instead of manually checking Slack every morning, you can run a command that gathers messages from your channels and gives you a summary with actionables. AI does the gathering while you do other things.

The key insight: it's all about context. Not copy-paste context — integrated context. Tools that read the codebase and build understanding.

The process is: integrate your tools, build context, brainstorm and plan, then execute. Make it subconscious through repetition. That's when AI becomes a natural extension of yourself.
-->

---

# Key Principles

**We are responsible for our code.**
AI is a tool. You own the output.

**Quality in = Quality out.**
Better inputs drive better results.

**Verification is non-negotiable.**
Always review, test, and validate.

**Time spent before coding is more impactful.**
Planning and understanding beat rushing to write.

**AI as a learning accelerator, not a learning replacement.**
Use AI to learn faster, not to avoid learning.

<!--
[NATALIA SPEAKS THIS SLIDE]

These are the core principles that came up again and again during the workshop.

First: we are responsible for our code. AI is a tool that helps us, but we own the output. If something breaks, it's on us — not the AI.

Second: quality in equals quality out. The better your inputs — your prompts, your context, your questions — the better the results you'll get.

Third: verification is non-negotiable. Always review what AI generates. Test it. Validate it. Don't blindly accept code just because AI wrote it.

Fourth: the time spent before coding begins is more impactful. Planning, understanding the problem, thinking through the architecture — that's where the real value is. AI makes execution faster, which means we should invest even more in getting the approach right.

And fifth: AI is a learning accelerator, not a learning replacement. Use it to understand unfamiliar codebases faster, explore patterns, break down complex problems. But don't use it to avoid learning. The goal is to learn faster, not to skip learning entirely.
-->

---

# Voices from the Workshop

> "I finally get it — AI isn't replacing me, it's extending me."

> "Day three I stopped thinking about prompts and just started working."

> "The conversations at lunch were as valuable as the sessions."

<!--
[Speaker notes here]

Prompts:
- Quotes from participants
- What did people say about the experience?
-->

---

# The Vibe

> "How do we code by hand again, I forgot"

> "Sorry, got sucked in by Claude"

> "Someone should 'Claude edit the Kudos bot' to allow at least 10 kudos per person this month. Amazing two weeks."

> "Typo of the day: 'I'm attending an AI worship'"

<!--
And here's the vibe. These are real things people said during the two weeks.

The energy was infectious. People got so absorbed in what they were doing, they'd lose track of time. "Sorry, got sucked in by Claude" became a running joke.

Someone suggested we should Claude edit the Kudos bot to allow more kudos because everyone was doing such cool work.

And my favorite: someone had a typo that said "I'm attending an AI worship" instead of "workshop." Honestly? Not that far off.
-->

---

# The Investment

![bg left:40%](images/IMG_2681.jpeg)

> "I'm the most energized I've been in years." — Eric Binnion

Two weeks to learn, practice, and synthesize.

This is a **glimpse of the future** of how we work.

Automattic is getting ahead by being **close and native** to today's tools.

**The question isn't if — it's when.**

<!--
[NATALIA SPEAKS THIS SLIDE]

We want to end with something Eric Binnion said during the workshop. He said: "I'm the most energized I've been in years."

And honestly? That was the vibe in the room. This collective sense of possibility.

Getting two weeks to learn, practice, and synthesize with colleagues — through random chats at lunch, late-night conversations in the hotel — is one of the coolest benefits we can get. It's a huge investment in your future self.

We know it's not easy for everyone to do something like this. But if you get the chance — take it.

Because this isn't just about learning new tools. This is a glimpse of the future of how we work. It's a dramatic shift. And Automattic is getting ahead by being close and native to these tools — as James, our Director of AI, put it.

The question isn't if this changes everything. It's when.

Thanks.
-->
