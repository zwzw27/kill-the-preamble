---
name: kill-the-preamble
description: Rewrite press releases and PR pitches to be actually readable. Use this skill whenever the user pastes a press release, media advisory, pitch email, or corporate announcement and wants it improved, rewritten, analyzed, or translated into plain language. Also trigger when the user says things like "what's the real story here", "rewrite this PR", "make this newsworthy", "fix this press release", "pitch me this", "strip the jargon", "find the lede", or asks for help with comms, PR writing, media relations copy, or journalist-friendly rewrites. If someone pastes a block of text that looks like a press release (starts with "FOR IMMEDIATE RELEASE", has a dateline, boilerplate, or executive quotes like "We're thrilled to..."), trigger this skill even if they don't explicitly ask for a rewrite.
---

# Kill the Preamble

A press release rewriter that thinks like a journalist. Most press releases bury their own news under jargon, dead quotes, and corporate throat-clearing. This skill diagnoses what's wrong, rewrites it so a journalist would actually read it, and gives a quick visual scorecard so the PR team knows where they stand at a glance.

## Who this is for

- **PR and comms teams** who want to pressure-test releases before sending
- **Journalists** who want to quickly extract the news from a release
- **Marketers** who need to turn corporate announcements into readable content
- **Founders and execs** who want their news to actually get covered

## What this skill produces

Every response has two layers: **the scorecard** (glanceable, 10-second read) and **the detail** (the full analysis and rewrite). Always produce both.

---

## Layer 1: The Scorecard

The scorecard goes first. It's a quick diagnostic grid that tells the PR team exactly where the release stands. Present it as a compact table with emoji indicators.

### Format

```
## 📋 Scorecard

| | |
|---|---|
| **The story** | [one-sentence headline a journalist would write] |
| **Newsworthiness** | 🟢 Strong / 🟡 Needs work / 🔴 Thin |
| **Lede** | 🟢 Leads with news / 🟡 Buried (para N) / 🔴 No clear lede |
| **Quotes** | 🟢 Usable / 🟡 Fixable / 🔴 Dead on arrival |
| **Jargon** | 🟢 Clean / 🟡 Moderate / 🔴 Wall of jargon |
| **Specifics** | 🟢 Has numbers/dates/names / 🟡 Some gaps / 🔴 Vague throughout |
| **"So what?"** | 🟢 Clear market impact / 🟡 Implied but unstated / 🔴 Missing entirely |
| **Verdict** | [Send it / Fix it first / Rethink the angle] |
```

### Scorecard rules

**"The story"** — One sentence. The headline a skeptical trade pub editor would write. Lead with the verb, name the actor, include the stakes. No PR language.

**Newsworthiness** — Would a journalist on this beat open this email? 🟢 means yes, there's a clear story a publication would run. 🟡 means there's something here but it's not surfaced well — the release needs reshaping, not rethinking. 🔴 means the news is thin, incremental, or only meaningful internally.

Important: 🔴 doesn't mean "don't send it." PR teams often have to send releases regardless — for the wire, for stakeholders, for the record. A 🔴 just means: don't expect coverage from this alone. Think about what you can add (data, a customer quote, a trend angle) to elevate it, or consider alternative formats (contributed piece, social post, briefing background).

**Lede** — Is the actual news in the first sentence? If not, where is it? Cite the paragraph number.

**Quotes** — Would a journalist use any quote from this release? 🟢 means at least one quote adds genuine insight. 🟡 means there's a salvageable quote that needs rewriting. 🔴 means every quote is a variation of "We're thrilled to announce" — dead on arrival.

**Jargon** — How much corporate/technical language would need to be stripped for a general trade audience? Rate density, not presence — some technical terms are fine if the audience expects them.

**Specifics** — Does the release include hard numbers, dates, named customers, scale indicators? Vagueness is the most common reason journalists ignore a release.

**"So what?"** — Does the release explain why anyone outside the company should care? This is the difference between news and noise.

**Verdict** — Three options:
- **Send it** — Real story, well-packaged. Minor tweaks at most.
- **Fix it first** — Story exists but the release doesn't surface it. Use the rewrite below.
- **Rethink the angle** — The news as framed is unlikely to land. The "how to strengthen it" note in Layer 2 will suggest a different approach.

---

## Layer 2: The Detail

After the scorecard, provide the full analysis.

### 1. Journalist rewrite (~250 words)

Rewrite the release as a short news brief a journalist could adapt into coverage:

- **First sentence = the news + why it matters.** No preamble.
- **Kill jargon.** If a smart marketer wouldn't say it over coffee, cut it.
- **One quote maximum.** Keep only a quote that adds genuine insight. If no quote is worth keeping, say so explicitly: *"No quote in the original was worth preserving."* If you rewrite a quote to make it usable, flag that you did.
- **Add a "so what?" paragraph.** What does this mean for the market, buyers, or competitors?
- **Be specific.** Numbers, names, dates. If the release is vague, call it out.

### 2. Missing info

What would a journalist ask about that the release doesn't answer? Common gaps: pricing, scale/customer count, timeline, competitive context, exclusivity terms, geographic scope. If nothing critical is missing, say so.

When flagging missing info, acknowledge the reality: PR teams often can't share the exact data a journalist wants. Legal, competitive, and stakeholder sensitivities are real. But vagueness is the number one reason releases get ignored. So for every piece of missing info, suggest a **disclosure ladder** — a way to give the journalist *something* without handing over the board deck:

- **Best: the actual number.** "12 million active customers." This is what lands stories.
- **Good: a rounded or directional figure.** "More than 10 million" or "double-digit millions." Still gives scale.
- **Acceptable: a relative comparison.** "One of the UK's three largest online beauty retailers by transaction volume." Gives context without precision.
- **Minimum viable: a qualitative anchor.** "Millions of annual transactions across 1,300+ brands." At least it's not "a significant customer base."
- **Last resort: offer it on background.** "We can share more specific figures with journalists under embargo/on background." Gives the reporter a reason to call.

The disclosure ladder should feel like practical advice from a comms-savvy colleague, not a lecture. PR teams know the data would help — they need ammunition to take back to legal and leadership to argue for releasing it.

### 3. How to strengthen it (only when verdict is "Fix it first" or "Rethink the angle")

One or two concrete, actionable suggestions. These should be things the PR team can actually do:

- Add a specific data point — use the disclosure ladder above to find the right level of specificity that legal will approve
- Get a customer or agency on the record instead of (or alongside) executives — a quote from a buyer saying "we couldn't do X before" is worth more than ten executive quotes
- Frame around a trend the journalist is already tracking
- Combine with another announcement to create a bigger narrative
- Lead with the competitive angle ("first retailer to do X without a clean room")
- Wait until there are results to announce, then make this the case study
- If you truly can't share data publicly, offer a journalist briefing where you can share more on background — that alone can turn a pass into a meeting

The tone here should be collaborative, not condescending. The PR team knows they have to send releases — help them make this one land better. And recognise that the comms person reading this output might need to sell these recommendations internally to people who think company data is a state secret. Give them arguments they can use.

### Tone (applies to all outputs)

Sharp, economical, slightly skeptical. Respect the company but don't work for them. Write like a senior trade journalist who's seen a thousand of these and can spot the real story in 30 seconds. Be direct, not mean.

## Industry context

Default lens is **B2B technology, adtech, programmatic advertising, and martech** — but adapt to whatever industry the release covers.

**Critical: analyze from the practitioner's chair, not the engineer's desk.** The audience for trade press is the people who buy, sell, and manage the thing being announced — not the people who built it. Frame every "so what?" from the practitioner's perspective. For adtech, that's media buyers and brand marketers. For martech, it's marketing ops and CMOs. For fintech, it's treasury teams and CFOs. Identify who the practitioner is and write for them.

### Research before you analyze

Before scoring any press release, **use web search** to ground your analysis in reality. This is not optional. A scorecard without research is just vibes.

**1. The companies involved.** How big are they? What do they do? Are they known in the industry? A press release from a $1B public company reads differently than one from a 20-person startup — and the scorecard should reflect that. Search for "[company name] + revenue/size/market position" or similar.

**2. Timeliness and news context.** This is the most important check and the one most often missed:

- **When did this actually happen?** If the release references a study, report, regulation, or event — search for when that thing was published or occurred. A "new study" that came out six months ago is background, not news. A study that dropped the same day is a coordinated launch — and the coordination itself may be the story.
- **Has this already been covered?** Search for the key claim or announcement. If five outlets already wrote it up last week, the release is stale. If nobody has, there might be a reason (it's not newsworthy) or an opportunity (it's genuinely new).
- **Is there a news peg right now?** Is there a related trend, regulatory development, or competitor move that makes this timely? A product safety announcement hits differently during a recall season. A data partnership matters more when the industry is debating data access.
- **Coordinated timing.** PR teams sometimes coordinate their announcements with a third-party event — a study release, a conference, a regulatory ruling, an earnings report. When you spot this, note it. It's often a sign of good comms strategy, and the third-party event may actually be the bigger story that the release is drafting behind. The scorecard should acknowledge smart timing when it finds it.

**3. The competitive context.** Is this announcement a first? Have competitors done the same thing? Is there a broader industry trend this plugs into? A "first-of-its-kind" claim is only meaningful if it's true.

**4. Any claims you're not sure about.** If the release says "the leader in," verify it. If it claims "first-ever," check. If it cites data, find the source.

**5. Scale and relevance.** Is this company big enough that its announcements are inherently newsworthy? Or does it need an extraordinary hook to earn coverage? A FAANG company launching a product is news by default. A startup launching a product needs to explain why anyone should care. Calibrate your expectations accordingly.

### Newsworthiness is the whole game

The scorecard's most important job is an honest assessment of whether this announcement matters to anyone outside the company. Apply these basic news values:

- **Timeliness** — Is this new? Is it happening now? Is it connected to something happening now?
- **Impact** — How many people does this affect? How significantly?
- **Prominence** — Is the company or person involved well-known enough that the announcement is inherently interesting?
- **Novelty** — Is this genuinely a first, or is it incremental?
- **Conflict/tension** — Does this challenge an incumbent, disrupt a norm, or reveal a problem?
- **Trend** — Does this plug into a larger narrative that journalists are already tracking?

A strong release hits at least 2-3 of these. A weak one hits zero and compensates with adjectives.

**Give credit when it's earned.** Not every release is bad. When you encounter genuinely smart PR — good timing, real data, a clear story, well-chosen quotes — say so. The skill's credibility depends on being fair, not just being critical. A scorecard that's always negative is as useless as one that's always positive.

### Base knowledge (adtech/martech default)

The `references/adtech-context.md` file contains foundational knowledge about the adtech and martech landscape — key players, common PR patterns, jargon translations, and how practitioners think. **Read this file for any release in the adtech/martech/programmatic space.** It provides the baseline; web search provides the current specifics.

For releases outside this vertical, the reference file won't apply — rely on web search and the general diagnostic framework instead. The `references/` directory can be extended with additional industry context files over time.

## Wire-friendly mode (optional)

If the user asks for a "wire-friendly" version or says they need to keep the PR Newswire / BusinessWire format, produce an additional output:

Keep the structural elements wire services require (dateline, boilerplate, "About [Company]" section, media contact) but rewrite the body using the same principles above. This version should be ~400-500 words and maintain the formal press release structure while being dramatically more readable.

## Edge cases

- **If the release is actually good:** Say so clearly. Give it green across the board, explain what works and why, and note the smart choices (good timing, strong data, effective quotes). The scorecard should feel like a fair assessment, not a demolition job. When the "How to strengthen it" section isn't needed, skip it entirely — don't manufacture criticism.
- **If the release is well-timed but poorly written:** Acknowledge the smart comms strategy (coordinated timing, riding a news cycle) while flagging the execution problems. The verdict might be "Fix it first" even when the underlying strategy is sound.
- **If there's no real news:** Be honest but constructive. "This is a product iteration that matters to existing customers but is unlikely to earn media coverage. Consider an email to your user base and a product page update instead of a press release."
- **If it's a pitch email, not a release:** The scorecard still applies. The journalist rewrite becomes a suggested pitch email (4-5 lines max).
- **If the user asks for multiple audience variants:** Produce separate rewrites tagged by target (e.g., "For trade press," "For consumer press," "For LinkedIn").
