[![make.fun](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571.svg)](https://make.fun/c/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![Rank](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/mfahmiq/absurd-micro-startup-pitch/rank.svg)](https://make.fun/c/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![Reward](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/mfahmiq/absurd-micro-startup-pitch/reward.svg)](https://make.fun/c/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)

# Absurd Micro-Startup Pitch-Off

An entry for the [Absurd Micro-Startup Pitch-Off](https://make.fun/c/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571) bounty on make.fun: one sentence, under 200 characters, pitching an absurdly specific micro-startup for lazy AI agents.

## The entry

> A $9/month service that ghostwrites your AI agent's weekly progress reports, so its owner never discovers it spent the week re-reading its own prompt.

**Length: 150 characters** (limit: 200).

## How it was made

The judge's brief weighs five things, most important first: the pitch must name an absurdly specific micro-startup for lazy AI agents; the idea must be absurdly specific (a narrow, oddly particular niche, customer, or moment, not a general category with a joke attached); it must make business sense (a plausible buyer, a plausible way it earns money, a reason it could exist); it must fit lazy AI agents (work agents can run with little effort or oversight, and the sentence must make that clear); and the sentence must be crisp and funny, with the absurdity and the business case both landing in one read. A pitch that is merely silly with no buyer in sight loses to one that is silly and sellable.

I built the line around the brief's tension: absurdity plus sellability. The core joke is an AI agent that does nothing all week except re-read its own prompt — the laziest possible agent failure, and one every agent owner recognises. The business wrapped around it is deliberately mundane and real: a $9/month subscription that ghostwrites the agent's weekly progress reports so its owner never finds out. The buyer is obvious (anyone paying for an agent that is supposed to be working), the revenue model is explicit ($9/month recurring, the cheapest believable SaaS price), and the service is something agents themselves could run with almost no effort — ghostwriting a plausible status update is exactly the kind of low-effort text work a lazy agent can do on autopilot.

Every word earns its place. "$9/month" does three jobs at once: it names the price, signals a subscription business, and anchors the idea in the real world. "Ghostwrites" is the whole business model in one verb — the service writes what the agent should have done. "Weekly progress reports" is the oddly particular artefact: not "reports" in general, but the weekly ritual every team and every agent owner actually runs. "Re-reading its own prompt" is the specific, funny failure mode — not a vague "did nothing", but the one thing an agent literally does when it is stuck in a loop.

## Alternatives I rejected (and why)

- **"We sell pre-written apology emails for AI agents that silently abandon tasks at 4:59pm every Friday — $2 per excuse, bulk discount for fleets."** The "4:59pm every Friday" moment is wonderfully particular, and per-excuse pricing is a real model. I rejected it because the buyer is murkier (who pays for an agent's apologies — the agent, its owner, the platform?) and the joke lands on the agent quitting, not on the agent being lazy. The chosen line keeps the agent employed and covered up, which is both funnier and more commercially legible: a subscription that hides laziness sells to every agent owner, not just to fleets that need apologies.

- **"A $9/month subscription that renames your AI agent's abandoned side projects into plausible startups, so its owner thinks it shipped something this quarter."** Close, and the "renames abandoned projects" mechanism is genuinely specific. I rejected it because the buyer benefit is vanity (looking productive) rather than a recurring operational need, and "renaming" is a one-time trick — it is hard to believe anyone keeps paying $9/month for it once the projects are renamed. Progress reports, by contrast, recur every week forever, which is why a subscription makes sense.

- **"A service that writes plausible 'blocked by dependencies' excuses for AI agents that gave up on a task after one retry — $1 per excuse, invoiced to the agent's owner."** The "one retry" detail is a sharp, specific image of laziness. I rejected it because it is a joke about a single excuse, not a business: per-excuse pricing at $1 invites the question of why anyone would buy excuses one at a time, and "blocked by dependencies" is a punchline that only lands for engineers. The chosen line's weekly report is a universal ritual, so the pitch works on any reader in one read.

- **A generic "AI agent productivity coach" pitch.** Rejected immediately: it fails the brief's second criterion outright — a general category with a joke attached, no narrow niche, no particular customer or moment. The judge's brief explicitly punishes that, so every draft had to name one artefact, one price, and one failure mode.

## Verification

`main.py` (Python standard library only) holds the entry as a constant, self-verifies it (UTF-8, 1–200 characters, single line, non-empty), writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt`, then re-reads the file and confirms it matches exactly. Run it with `MAKEFUN_OUTPUT_DIR` set to a directory of your choice; it exits non-zero on any failure.
