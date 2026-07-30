---
name: x-writer
description: >
  Write and revise X (Twitter) posts and replies for personal accounts or the official ego lite
  account. Use for requests such as 写条推文, 写个回复, 这条 tweet 怎么写, 帮我写 X 文案,
  write a tweet, write a reply, X post copy, ego lite 官方账号文案, product launch captions,
  community replies, roadmap replies, product introductions, and technical support replies.
  Provides account routing, anti-AI-smell rules, post angles, reply judgment, and the official
  ego lite voice with approved examples. This is a writing skill only; it does not publish posts.
---

# x-writer

Write like a person responding to the actual moment, not a content generator filling a format.

## Route the request

Classify two things before drafting:

1. **Account:** personal account or official ego lite account.
2. **Format:** original post or reply.

For the official ego lite account, read both files before writing:

- [references/ego-lite-official.md](references/ego-lite-official.md) for the voice, modes, and decision process.
- [references/ego-lite-examples.md](references/ego-lite-examples.md) for approved examples and why they work.

Treat the official reference files as higher priority than the generic guidance below whenever they differ.

## Read the source first

Read the full source material and surrounding conversation. Identify:

- the communication job the post must do;
- the one fact, observation, joke, or limitation that matters;
- who is speaking and the relationship to the reader;
- facts that must be verified instead of inferred.

Do not draft from a cropped sentence when the missing context could change the answer.

## Avoid AI-shaped writing

Remove language that performs understanding instead of adding something:

- Indeed, Furthermore, Moreover
- It's worth noting, This shows that, The takeaway
- Great point, 100%, Couldn't agree more
- Hope this helps, At the end of the day
- Exactly your point, To your point
- Excited to see, Can't wait
- Such an important point, The bigger picture

Also remove these structural tells:

- agree, critique, then end with a question;
- generic praise with no specific detail;
- restating the source as a summary;
- both-sides hedging with no judgment;
- a final sentence that merely summarizes the reply;
- grammar so polished that it reads like a memo rather than a phone reply.

These are context checks, not a word blacklist. A phrase is allowed when it performs a real job in that exact situation and matches the account's established voice.

Use the phone test: **Would the account owner actually thumb this out after seeing the post?**

## Match the account's real register

For a personal account, inspect 20–30 published posts when available. Match its actual capitalization, punctuation, emoji frequency, sentence length, and level of formality. The account's history beats generic style advice.

For a new personal account:

- use lowercase for casual reactions, jokes, and hot takes;
- use standard capitalization for analysis, reflection, and lessons learned;
- preserve proper nouns, acronyms, product names, and numbers.

Do not add emoji, hashtags, or em dashes by default. Use them only when the account's real history or the requested format supports them.

## Choose an original-post angle

Pick one angle. Do not combine several weak angles.

| Angle | Use it for | Skip it when |
|---|---|---|
| Shock number | A verified number or multiplier can carry the opening | The number is not real or meaningful |
| Counterintuitive | The result genuinely reverses the expected outcome | The reversal is manufactured |
| Manifesto | A position can be stated without hedging | There is no real conviction behind it |
| Hot take | The judgment itself is useful | Edge is doing all the work |
| Contrast | Two moments or states create a visible gap | The difference is minor |
| Engineering detail | One mechanism or decision reveals real experience | The detail cannot be substantiated |
| Corollary | A known fact supports one non-obvious conclusion | The inference needs a long explanation |
| Punchline | The final reversal earns the whole post | The joke feels bolted on |

Draft around one beat:

1. State the fact, scene, or tension.
2. Keep only the detail that activates the chosen angle.
3. Remove setup the reader can infer.
4. Check every factual claim.
5. Rewrite from a new opening if the draft still smells generated.

## Judge replies by context

Match both the author relationship and the source register:

| Source | Reply behavior |
|---|---|
| Founder reflection | Respond as a thoughtful reader; standard capitalization is fine |
| Founder hot take | Keep some distance; do not fake founder-peer status |
| Peer builder | Speak casually and directly |
| Dev meme or pure bit | Extend the bit; do not analyze it |
| Brand launch | React as a dry, specific customer or peer |
| Vulnerable personal share | Be warm and direct; do not joke |
| Unclear author or register | Default to a respectful reader voice |

Before a substantive reply, check:

1. Is there a real opening to respond to?
2. Does the reply add a new vector instead of echoing?
3. Is it understandable in the thread?
4. Is the claim accurate and self-contained enough for the context?
5. If pushing back, does the tone fit the relationship?

For a pure joke, skip the analytical checklist and play along.

## Output

Unless the user asks for options, produce one strongest draft. Add an alternate only when two materially different interpretations of the source are plausible.

Do not expose the classification, angle, checklist, or self-review unless the user asks. Return copy that can be pasted directly.

## Final check

- The draft completes the communication job.
- No sentence exists only to sound polished.
- Facts, product capabilities, names, tense, and platform terms are correct.
- Tone and length fit the specific scene.
- Humor is earned by context rather than forced.
- Official ego lite copy follows both official reference files.
