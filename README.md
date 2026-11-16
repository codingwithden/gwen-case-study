# Gwen: Case Study

A voice-first personal assistant I designed and built to run my day. It started as a tool for me, and it's turning into a product for anyone juggling too much at once.

**Status:** live and used every day on my phone, tablet and laptop. The code is private while I build a version to sell.

## The problem

I run a startup, work a job, run a small business and study for my next career move, all at the same time. I also have ADHD. Regular to-do apps didn't fail because they lacked features. They failed because they needed me to open them, look at a screen, and decide what to do next, which is the exact moment my day falls apart.

**The real job to be done:** tell me what matters right now, out loud, without making me look at a screen.

## Design principles

| Principle | What it means in the product |
| --- | --- |
| **Voice first** | Gwen talks, I answer. No screen needed in the first hour of the day |
| **One choice at a time** | She never shows a long list. She asks about one thing and waits |
| **Done list before to-do list** | The night routine starts with what I finished, to fight the "I did nothing today" feeling |
| **I stay in control** | Gwen never sends a message for me until I say "yes" out loud |
| **Read from the tools I already use** | No double entry. Calendar, task boards and team tools feed her automatically |

## What it does

- **Morning briefing:** today's schedule, top 3 priorities, countdowns to big days, and anything due this week, spoken in order of what matters
- **Night routine:** I start it when I'm ready. It reviews what got done, gives me space to brain dump, then sets up tomorrow
- **Ask me anything about my time:** "What does next Thursday look like?" works for any day, not just today
- **Team texts:** drafts a message to my Work & Brew team, reads it back, and only sends on my spoken yes
- **Startup check-ins:** pulls open tasks for each Work & Brew department so I know who to follow up with

## How I built it

- **Phased roadmap:** I shipped the smallest useful version first (a talking assistant with a free built-in voice), then added one integration at a time, starting with the calendar because it touches everything
- **Cost decisions:** launched on free system voices instead of a paid voice service to keep running costs near zero, with the paid voice saved for later
- **Tech:** a web app installed to the home screen, small serverless functions for each integration, and an AI model for conversation

## What I learned

- The best feature was removing friction, not adding features. Hands-free listening mattered more than any integration.
- Letting the user choose when a routine starts (instead of a fixed time) made me actually use it.
- A confirmation step ("say yes to send") builds trust fast, even for a tool you built yourself.

## What's next

A version anyone can set up for their own life: pick your tools, pick your routines, pick your voice.

Built by Denisse Medina Flores ([@codingwithden](https://github.com/codingwithden))
