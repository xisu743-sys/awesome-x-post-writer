---
name: x-writer
description: >
  手写 X（Twitter）发帖文案或回复文案时使用。覆盖两个场景（原创发帖 / 回复他人推文）
  和两种账号 voice（个人号通用方法论 / ego lite 官方号具体规则）。提供语气规则、结构
  模板、思考步骤和写完自查清单，不涉及任何自动化抓取/推送/执行，只是写作方法论。
  触发词："写条推文"、"写个回复"、"这条 tweet 怎么写"、"帮我写 X 文案"、"write a tweet"、
  "write a reply"、"X post copy"。
---

# x-writer: How to Write X Posts and Replies

This file is self-contained. Everything you need to write a post or reply is here. You never need to open another document.

## Step One: Classify Before You Write

Answer two questions before writing a single word. They decide which rules apply:

- **Which account?** Your own personal account, or the official ego lite account? The difference: the official account never uses first person i/my/me, it speaks in a "you/your agent" frame or names the product directly. A personal account can use first person, and its tone follows that account's own posting history (see the Personal Account section).
- **Post or reply?** An original post, or a reply to someone else's tweet? The difference: a reply requires you to first figure out who you're talking to and what register their post is in (see the Reply section). An original post skips that step.

## Voice Red Lines (Both Accounts, Hard Rules)

No emoji, no hashtags, no em-dashes, anywhere. These three signals scored a 0% hit rate across every benchmark account we measured, and they are the three fastest ways for a reader to clock a tweet as AI-written.

**Banned AI-smell phrases, by category, each with the reason it smells:**

| Category | Examples | Why it smells like AI |
|----------|----------|----------------------|
| Transition words | Indeed / Furthermore / Moreover | A real reply is a single thought. Single thoughts don't have transitions |
| Meta-commentary | It's worth noting / This shows that / The takeaway | Sounds like an assistant explaining why something matters |
| Empty agreement | Great point / 100% / Couldn't agree more | Adds nothing. If you actually agree, extend the point instead of asserting agreement |
| Polite filler | Hope this helps / At the end of the day | Reads as deliberate verbal padding. Nobody types this on their phone |
| Identity disclaimer | As an AI | Self-explanatory |
| Echoing | exactly your point / to your point | ChatGPT proving it understood. Real writers extend or push back, they don't restate |
| Brand enthusiasm | Excited to see / Can't wait | Sounds like one brand account replying to another brand account |
| Inflated praise | such an important point / the bigger picture | If a reply needs to label something "important", the point usually wasn't important enough to begin with |

**Structural AI smell. Not word choice, skeleton. Harder to self-catch and more common:**

- The three-act reply: agree first, then critique, then end with a question
- Every clause grammatically complete and precise, too tidy to be something typed on a phone
- Generic praise with zero specifics
- Both-sides fence-sitting with no judgment of your own
- Restating the original tweet as if it were your own take
- A wrap-up summary sentence at the end

**The final test: "Would I actually thumb this out on my phone?"** Picture yourself scrolling, seeing the original tweet, phone in hand. Would you really type this reply? If it reads like a Google Doc, rewrite it: shorter, rougher, shaped like a thought that just occurred to you.

## Capitalization (Register-Driven, Not a Fixed Rule, Both Accounts)

Default to lowercase first word (casual / joke / hot-take register). Escalate to standard English capitalization when the content is substantive, reflective, or a lessons-learned share. When unsure, default to lowercase. Proper nouns (Anthropic, OpenAI, Claude, Gemini, Cursor), acronyms (API, CLI, GPU, MCP, KV, TTL), and numbers ("12.5x more...") always keep their own conventions regardless of register.

Two empirically validated capitalization modes. Both sit on the same zero-emoji / zero-em-dash / zero-hashtag floor. Check your own account's posting history to see which one you're closer to:

- **All-lowercase mode**: casual, reactive content. Common in employee and founder voices
- **Standard-caps mode**: analytical, commentary content. Common in media and analyst voices

## The 8 Angles (Any Account)

| Angle | How it works | When NOT to use it |
|-------|-------------|--------------------|
| Shock number | Hook with one specific number or multiplier | You don't have real data behind it |
| Counterintuitive | State what everyone assumes, then flip to what actually happened | The flip isn't surprising enough; it reads as forced |
| Manifesto | One sentence of clear, unhedged position | No real conviction behind it; posturing for the sake of edge |
| Hot take | Deliver the judgment directly, no wind-up | The judgment itself doesn't hold up |
| Contrast | Two scenes or two points in time, side by side | The gap isn't wide enough for the reader to feel it |
| Engineering detail | Get specific about one technical decision, parameter, or mechanism | No real engineering experience behind it |
| Corollary | Derive a non-obvious conclusion from a known fact | The inference chain is too long; readers fall off |
| Punchline | The whole post exists to serve the last-line reversal | The reversal isn't funny or surprising; it reads as strained |

## Replies: Classify Who You're Talking To First

**The relationship matrix. Pick your voice by the author type and register of the original post:**

| The original post is... | Use this voice |
|------------------------|----------------|
| A founder's reflective longform | Reader-to-writer fan voice, standard caps, calling them by name is fine |
| A founder's hot take | Keep some distance, hedge a little. Do NOT use founder-peer voice |
| A peer / fellow builder | Genuine casual peer voice |
| A builder or dev meme | Front-row reaction only, play along with the bit |
| An official brand launch | A dry, plain customer reaction |
| A vulnerable personal share | Warm, direct empathy. No jokes |
| Unclear who they are or what register | Default to reader-to-writer fan voice (standard caps). Do NOT default to lowercase builder voice. This is the single most common mistake |

**Five questions before writing a substantive reply:**

1. Is there an actual rhetorical opening in the original post?
2. Am I adding a new vector, or just restating the original?
3. If someone screenshots my reply alone, does it make sense without the original tweet?
4. Is the content self-contained?
5. If I'm pushing back, did I concede something first before pivoting, instead of opening with a flat no?

If the original post is a pure bit, skip all five. Match their register, extend the joke, don't analyze.

## Original Posts: The Writing Process

1. Read the source material in full: one lesson, one product fact, one real experience. Don't skim
2. Pick one angle from the 8 above. Hold the angle's shape in your head. Don't copy the template's sentences
3. Find the one beat this angle activates. Don't try to cover everything
4. Write the first draft: first instinct, lowercase by default, a little hesitation is fine, no emoji, no em-dash
5. Run the red-line list against your own draft. If anything trips, rewrite from a different opening. Don't patch the same sentence
6. Report your self-check honestly

## Personal Accounts: Finding Your Own Voice

You're writing your own account, not anyone else's. Spend five minutes on this before applying the rules above:

1. Pull up your last 20-30 actually published posts (published, not drafts)
2. Count: what fraction start lowercase, how often emoji appear, how often em-dashes appear, average post length
3. If your history is full of emoji and em-dashes, don't strip them just to fit this skill's red lines. The red lines are a defense against AI smell, but if a real human has always written that way on that account, it's the account's style, not AI smell. The account's real history wins
4. If the account is new with little history, start in lowercase casual mode and follow the register logic in the Capitalization section

## The Official ego lite Account: Specific Rules

- No first person i/my/me. Use the "you/your agent" frame, or let the product speak for itself. A light "we" is acceptable
- Product names can be self-declared: "ego lite", "claude code", "codex" can all appear directly
- Never describe ego lite or ego-browser as open-source, under any circumstances
- The category word is "personal agent", never "personal AI agent"
- A structure that works: open with a real pain moment (for example, "the code is done, and you have no idea how to market it"), then let the agent take over that moment, then land on the product capability
- Reference example (written and approved as a real video launch caption):

  > vibe coding the product: 3 days.
  >
  > staring at the empty x compose box: 3 weeks.
  >
  > so we let codex drive ego lite through x, reverse engineer 3 top build in public accounts, and hand you the spreadsheet of how they got there.

  What this demonstrates: a three-line structure (how fast the code went, how slow the marketing went, the agent takes over), all lowercase, no i/my, product names (codex, ego lite) appear directly, no em-dash, and "compose box" is the native term for X's posting box (never "input frame", which is translated-English)

## Common English Slips to Check (Any Account)

- Watch verb transitivity: "reverse 3 accounts" doesn't parse. Either "reverse engineer 3 accounts" or "break down 3 accounts"
- Get tense right: accounts that already succeeded can't be "how they become successful" (present tense). Write "how they got there" or "what actually worked"
- Use native terms for platform UI: X's posting box is the "compose box", not the "input frame"
- In all-lowercase register, everything outside proper nouns (including the word x itself) stays lowercase consistently. Don't flip between X and x in the same post

## Final Checklist Before Posting

- [ ] Search the full text for emoji, hashtags, em-dashes (hard ban on the official account; personal accounts check against their own history)
- [ ] No hits on any banned-phrase category from the red lines
- [ ] Capitalization matches the register (casual lowercase / reflective standard caps)
- [ ] Official account copy contains zero i/my/me
- [ ] Official account copy contains no open-source claim and no "personal AI agent"
- [ ] Read it once as if on your phone. Would you actually post this?
- [ ] Tense, verb transitivity, and platform terms carry no translated-English smell
