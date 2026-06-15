# FUTURE_PE_02 — AI Content Marketing using UGC Ads

**Intern:** Devansh Janakbhai Karia
**CIN ID:** FIT/MAY26/PE2971
**Program:** Prompt Engineering Internship — Future Interns
**Task:** Task 2 — AI Content Marketing using UGC Ads
**Tool Used:** Claude (claude.ai)
**Submission Date:** June 2026

---

## 📌 Project Overview

This project demonstrates how structured prompt engineering generates a complete **UGC (User-Generated Content) Ad Pack** for a real-style D2C product — the kind of authentic, scroll-stopping content brands now rely on instead of traditional polished ads.

| | Details |
|---|---|
| **Brand** | GlowRoot — Niacinamide Face Serum |
| **Category** | D2C Skincare (Direct-to-Consumer) |
| **Audience** | Adults 18–35, skincare-curious, active on Instagram/YouTube Shorts |
| **Content Type** | UGC-style scripts, hooks, captions, CTAs |
| **Platforms** | Instagram Reels, Facebook, YouTube Shorts |

UGC ads work because they don't *look* like ads — they look like a friend talking to camera. The entire prompt strategy below is built around recreating that authenticity through structured prompting, not polished "brand voice."

---

## 🧠 Prompt Engineering Framework for UGC

Traditional ad copy prompting focuses on persuasion. UGC prompting requires a different framework — one that prioritises **authenticity signals** over polish:

| Component | Purpose | UGC-Specific Note |
|---|---|---|
| **Role** | Assigns a creator persona, not a copywriter | "You are a 24-year-old skincare content creator..." |
| **Context** | Product details + platform + audience pain point | Must include a *real* problem, not just features |
| **Hook Type** | Specifies the scroll-stopping opening style | Pattern interrupt, bold claim, relatable confession, etc. |
| **Structure** | Problem → Solution → CTA, but conversational | Must sound spoken, not written |
| **Tone** | Casual, imperfect, first-person | Constraints must explicitly forbid "ad-speak" |
| **Platform Adaptation** | Same core message, different format/length | Reels = fast hooks; YT Shorts = slightly longer story |

> **Key Insight:** The biggest failure mode in AI-generated UGC content is sounding too polished. The prompts below explicitly instruct the model to write "the way someone actually talks," include filler words, and avoid marketing vocabulary like "revolutionary" or "game-changer."

---

## 🎯 Section 1: Multiple Hooks for the Same Product

### Prompt Used

```
Role: You are a Gen-Z skincare content creator who makes UGC-style ads for brands
on Instagram and TikTok. You are NOT a copywriter — you talk like a real person
sharing something they genuinely like.

Context: The product is "GlowRoot" — a niacinamide face serum that targets dark spots,
oily skin, and dullness. It's priced affordably (under ₹600) and is aimed at people
aged 18–30 who are into skincare but don't want a 10-step routine.

Task: Write 6 different scroll-stopping HOOKS (the first 1-2 lines of a UGC video)
for the same product. Each hook should use a DIFFERENT psychological angle:
1. Pattern interrupt / shocking statement
2. Relatable confession / vulnerability
3. Bold claim / result-focused
4. "POV" / story-format hook
5. Question hook that calls out the viewer directly
6. "I wasn't going to post this but..." curiosity hook

Format: Number each hook 1-6. Keep each hook under 15 words. Write exactly how
someone would SAY it on camera, not how they'd write it.

Constraints: No words like "amazing," "game-changer," "revolutionary," or "must-have."
No exclamation marks in every line — keep it casual. Include natural speech patterns
like "okay so," "ngl," "not gonna lie," "wait," where appropriate.
```

### ✅ Output

---

**1. Pattern Interrupt**
> "Okay wait — why did nobody tell me dark spots could just... fade?"

**2. Relatable Confession**
> "Not gonna lie, I gave up on serums after like 5 didn't work. Then this happened."

**3. Bold Claim / Result-Focused**
> "3 weeks. Same lighting, same camera, zero filter. Look at my skin."

**4. POV / Story Format**
> "POV: you finally find the one serum that doesn't break you out or burn your wallet."

**5. Direct Question Hook**
> "If your skin looks dull by 2pm even after sleeping 8 hours... this is for you."

**6. Curiosity Hook**
> "I wasn't going to post this because it's kind of personal but — my skin texture changed."

---

## 📝 Section 2: Problem–Solution–CTA Ad Scripts

### Prompt Used

```
Role: You are a UGC creator filming a 30-45 second talking-head video for "GlowRoot,"
a niacinamide serum brand. You're speaking directly to camera, casually, like a voice note.

Context: Target viewer struggles with one of these: oily/shiny skin by midday,
stubborn dark spots from old acne, or dull/tired-looking skin despite sleep.
The brand wants 3 separate scripts — one per problem — using a Problem → Agitate
→ Solution → Result → CTA structure, but written conversationally, not like a sales pitch.

Task: Write 3 full UGC ad scripts (30-45 seconds spoken length, ~70-100 words each):
1. Script for "oily skin by midday"
2. Script for "dark spots / uneven tone"
3. Script for "dull skin despite good sleep"

Each script must:
- Open with a hook (can reuse hooks from Section 1 or write new ones)
- Briefly agitate the problem (1-2 sentences, relatable not dramatic)
- Introduce GlowRoot naturally — like recommending to a friend, not reciting an ad
- Mention ONE specific result/timeframe
- End with a soft, non-pushy CTA

Format: Label each script clearly. Write in spoken, first-person, casual tone.
Include natural pauses indicated by "..." where a creator would pause on camera.

Constraints: No corporate language. No "link in bio!!" energy — keep CTA chill.
Don't claim instant results. Don't use medical claims (e.g. "cures," "treats").
```

### ✅ Output

---

**SCRIPT 1 — "Oily Skin by Midday"**

*[Platform: Instagram Reels | Length: ~35 sec]*

> "Okay so... by like 1pm my face used to look like I dipped it in oil. Like, full shine, makeup sliding off, the whole thing.
>
> I tried like four different serums before this one and honestly gave up for a bit.
>
> Then I started using GlowRoot — it's a niacinamide serum, super lightweight, like water almost...
>
> And I'm not saying my skin is "oil-free" now because that's not realistic, but the shine by midday? Genuinely so much less. Like noticeably less, within like 2 weeks.
>
> If you deal with the same thing, I left it linked... no pressure though, just sharing what worked for me."

---

**SCRIPT 2 — "Dark Spots / Uneven Tone"**

*[Platform: YouTube Shorts | Length: ~40 sec]*

> "I have some old acne scars on my cheek that have literally been there for like... two years? Maybe more.
>
> I've tried so many "brightening" products and most of them just... did nothing. Or made my skin sting.
>
> A friend recommended GlowRoot — it's a niacinamide serum, and niacinamide is actually one of the more researched ingredients for this stuff, which is why I tried it.
>
> Around the 3-4 week mark I noticed my dark spots looked... softer? Less obvious in photos especially.
>
> Still not 100% gone, but honestly the most progress I've seen. If you've got similar marks, might be worth a look."

---

**SCRIPT 3 — "Dull Skin Despite Good Sleep"**

*[Platform: Facebook / Instagram Reels | Length: ~35 sec]*

> "This one's gonna sound dramatic but... I started sleeping SO much better this year, like 7-8 hours consistently...
>
> and my skin still looked tired? Like dull, kind of grey undertone, no glow at all.
>
> Turns out sleep alone doesn't fix everything — who knew.
>
> So I added GlowRoot into my morning routine, just a few drops before moisturizer...
>
> and within like 10 days my skin had this... actual glow? Not glowy-filter glow, just healthier looking.
>
> If you're sleeping fine but your skin still looks "meh" — this might be why."

---

## 🎬 Section 3: Platform-Adapted Captions

### Prompt Used

```
Role: You are a social media content strategist writing captions to accompany
UGC video ads for "GlowRoot" niacinamide serum.

Context: The same video content (Script 1: "Oily Skin by Midday") will be posted
across Instagram, Facebook, and YouTube Shorts. Each platform has different caption
norms — Instagram is short + hashtag-heavy, Facebook is slightly longer + conversational,
YouTube Shorts captions are minimal since the title does more work.

Task: Write 3 platform-adapted captions for the SAME video:
1. Instagram Reels caption (with hashtags)
2. Facebook caption (slightly longer, conversational)
3. YouTube Shorts caption + title

Format: Label each platform. Keep Instagram caption under 30 words + 5-8 relevant
hashtags. Facebook caption can be 40-60 words. YouTube needs a title (under 60 chars)
+ short caption (under 20 words).

Constraints: No fake engagement bait ("comment YES if..."). Hashtags should be
realistic and specific to skincare, not generic (#love #instagood).
```

### ✅ Output

---

**📱 INSTAGRAM REELS**

> the midday oily skin struggle is real 😩 this has genuinely helped tho
>
> #niacinamide #skincareroutine #oilyskincare #glowroot #skintok #affordableskincare #serumforoilyskin

---

**📘 FACEBOOK**

> Anyone else's skin go from "fine" in the morning to full shine by lunch? Same. I started using a niacinamide serum a couple weeks ago and the difference in midday oiliness has actually been noticeable. Sharing in case it helps someone else dealing with the same thing — not sponsored, just genuinely impressed.

---

**▶️ YOUTUBE SHORTS**

**Title:** "Why does my skin get SO oily by midday? (found a fix)"

**Caption:** Niacinamide serum update — 2 weeks in, midday shine is way down.

---

## 🔄 Prompt Iteration Log

| Version | Change Made | Problem It Solved |
|---|---|---|
| v1 | "Write ad scripts for a skincare serum" | Output sounded like a brand, not a person |
| v2 | Added Role as "content creator" not "copywriter" | Tone shifted from sales-y to conversational |
| v3 | Added explicit forbidden words list (e.g. "game-changer") | Removed generic marketing clichés |
| v4 | Added "natural speech patterns" instruction (okay so, ngl) | Output started sounding spoken, not written |
| v5 | Added "..." pause markers | Scripts became usable for actual video pacing |
| v6 | Added per-platform caption rules | One video became 3 platform-ready assets |
| **v7 (Final)** | Combined creator persona + constraints + structure | Fully authentic, platform-ready UGC pack |

---

## 📊 Hook Strategy Breakdown

| Hook Type | Why It Works | Best Platform |
|---|---|---|
| Pattern Interrupt | Breaks scrolling pattern with unexpected phrasing | Instagram Reels |
| Relatable Confession | Builds trust through shared frustration | All platforms |
| Bold Claim / Result | Visual proof-based, works with before/after | YouTube Shorts |
| POV / Story Format | Trendy format, high completion rate | Instagram Reels |
| Direct Question | Filters audience — only relevant viewers stay | Facebook, YT Shorts |
| Curiosity / "Almost didn't post" | Creates intimacy, feels unscripted | Instagram Reels |

---

## 📋 Key Learnings

**1. Persona prompting beats copywriter prompting for UGC.**
Asking the AI to "be a content creator" rather than "write ad copy" fundamentally changes vocabulary, sentence structure, and rhythm — the single biggest lever for authenticity.

**2. Negative constraints define UGC more than positive ones.**
A list of *banned words and phrases* ("game-changer," "must-have," "link in bio!!") does more to create authentic tone than any amount of positive instruction.

**3. Pause markers ("...") make scripts production-ready.**
Adding spoken-pause notation transforms a script from "text to read" into "script to perform" — a small detail with outsized impact on usability.

**4. One asset, many formats.**
A single UGC video script needs different captions per platform. Prompting for "platform-adapted versions" of the same core content is far more efficient than writing each from scratch.

**5. Specificity in results builds trust.**
Vague claims ("amazing results!") feel fake. Specific, modest claims ("noticeably less shine within 2 weeks," "still not 100% gone") feel real — and ironically, this is *more* persuasive.

---

## 📁 Repository Structure

```
FUTURE_PE_02/
│
└── README.md    ← Complete task documentation (prompts + outputs + analysis)
```

---

*Submitted as part of the Future Interns Prompt Engineering Internship Program.*
*CIN: FIT/MAY26/PE2971 | Domain: Prompt Engineering | Task: 02*
