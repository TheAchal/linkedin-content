# Peer insights

What comparable Indian PM, founder and AI-builder voices are posting, what
formats perform, and which gaps Achal could own. Maintained by
`linkedin-peer-watch`, Tuesdays and Fridays. Last run: 2026-07-28.

A note on sources: LinkedIn's own analytics are not visible to this
research. The format and algorithm claims below come from marketing and
SEO blogs describing LinkedIn's 2026 changes, not from Achal's own post
data or from any primary LinkedIn source. Where those blogs quote a
specific engagement percentage or multiplier, that number is a vendor
claim, not a verified fact, and it is labelled as such below. Nothing in
this file should be read as measured performance until Achal's own posts
have enough data to compare.

## Performing formats, and what each costs

- **Text-only opinion post.** Cost: low, just the write. This is the
  format Achal is already using. Several 2026 write-ups on LinkedIn's
  algorithm change describe a shift from rewarding raw reach toward
  rewarding dwell time and comment depth, with comments weighted far
  above likes and the first 60 to 90 minutes deciding most of a post's
  reach. That rewards a sharp, specific hook and a real point of view,
  which is what this format is for. Keep using it as the default.

- **Single image plus caption.** Cost: low to moderate, one clean visual
  per post (the image briefs already in `posts/` fit this). Cheaper than
  a carousel, works as a scroll-stopper, holds attention for less time
  than a carousel but far less production effort. Good default when the
  point is a single sharp idea rather than a framework.

- **Carousel.** Cost: high, needs real design time (Canva or similar) and
  a structured argument broken into slides. Multiple marketing sources
  claim carousels hold attention several times longer than a single
  image or text post and get outsized reach versus other formats, though
  the specific percentages in those write-ups are vendor benchmarks, not
  independently verified. Directionally credible: carousels suit how the
  NEET counselling funnel or the InfiNotes retention lesson could be
  broken into a numbered walkthrough. Worth trying occasionally for a
  framework post, not every day, given the cost.

- **Long-form or document-style posts.** Cost: high, meaningfully more
  writing and structuring than a normal post. Described in the same 2026
  algorithm write-ups as newly favoured. Fits a once-a-month deep dive
  rather than the daily cadence this pipeline runs.

- **Polls.** Cost: very low. Several of the same sources flag that
  LinkedIn is now actively penalising posts that read as engagement bait,
  including polls and "comment X to see the answer" prompts. Skip these;
  they cost little but the format itself works against reach right now.

## Saturated topics to avoid

- **Funding-reaction posts as a genre.** The trend files from the past
  three days (`trends/2026-07-26.md` through `2026-07-28.md`) already
  show how crowded this is: ProLearn's pre-seed, SigIQ.ai's seed and its
  "175/200 on UPSC prelims" headline, YoLearn.ai, Lytmus AI, Emergent's
  unicorn round. Every operator in this space reacts to the same funding
  news the same week it lands. Achal has already used two of these
  angles (2026-07-27, 2026-07-28). A third funding-reaction post in a row
  would read as the genre itself, not a distinct point. Let this rest for
  at least a week before returning to it.

- **"Vibe coding" as a buzzword.** LinkedIn itself just shipped a profile
  feature for showcasing vibe-coding skills, and the coverage already
  includes a Meta PM's post about it giving him "superpowers." The
  generic version of this post, AI writes my code now and it's amazing,
  is being written by product people everywhere this month. It is not
  a gap, it is the most crowded lane in the PM content space right now.
  The only way in is a specific, lived account of a real build decision,
  not the buzzword itself. See the gaps section below for how Achal's
  version differs from the generic one.

- **Generic "AI is transforming education in India" thought leadership.**
  Coverage of PhysicsWallah's results, the edtech market correcting from
  a claimed bubble valuation to a smaller sustainable one, and enterprise
  AI governance surveys are all being relayed by people with no hands-on
  product experience in the category. Achal has actually shipped in this
  space; a post that could have been written by any commentator reading
  the same news adds nothing next to his own record.

- **Launch-hype language.** "Excited to announce," "thrilled to share," a
  job title before an idea: already flagged as retired in
  `hook_playbook.md`, and the same LinkedIn algorithm write-ups this run
  found describe engagement-bait phrasing as actively penalised, not
  just stale. Two independent reasons to avoid it, not one.

## Gaps Achal could genuinely own

1. **Product taste as the moat, not the AI tool itself.** The generic
   version of the vibe-coding post is "AI wrote my app, look how fast."
   Achal actually directed AI to build InfiNotes and to ship the NEET
   counselling product end to end, and he has specific decisions and
   tradeoffs from that process that a "look what AI can do" post never
   gets into: what he chose not to build, where he overrode the AI's
   first answer, what broke in production. That is a different post from
   everyone else's vibe-coding celebration, and it is one only someone
   who has actually shipped this way can write honestly.

2. **What an AI feature actually costs to run, priced off real model
   cost.** Every founder in this space talks about funding rounds and
   almost nobody shows the other side of the ledger, what a query
   actually costs against the model bill and how that shaped a pricing
   or feature decision. Achal has priced a token economy against real
   model cost rather than guessing at a subscription number. A post
   built around that arithmetic, without disclosing anything
   confidential about the unlaunched companion, is a gap nobody else in
   this feed is filling, because most of them are pre-revenue and
   haven't had to solve it yet.

3. **The counselling funnel as its own category, separate from tutoring
   apps.** Every funded competitor named in the past week of trend
   research, YoLearn.ai, Lytmus AI, ProLearn, SigIQ.ai, is building a
   pre-exam tutor or mentor. None of them are talking about what happens
   after the exam, when a student has a result and has to make a
   counselling and admissions decision under time pressure. Achal
   shipped that product end to end. Nobody adjacent to him is publishing
   in that specific gap between "AI tutor" and "what a family does with
   a NEET score," and it is a real, already-built credential rather than
   a hypothetical.

## Notable posts and sources worth learning from

- [LinkedIn lets users showcase 'vibe coding' skills as AI-driven
  development gains hiring edge](https://www.thehansindia.com/tech/linkedin-lets-users-showcase-vibe-coding-skills-as-ai-driven-development-gains-hiring-edge-1043412):
  the platform itself is now amplifying this topic, which is exactly why
  it is saturated rather than open. Worth reading to understand the wave
  Achal would be adding to, not joining generically.
- [A Meta product manager with no technical background says vibe coding
  gave him 'superpowers'](https://www.aol.com/news/meta-product-manager-no-technical-060448066.html):
  the shape of the generic version of this post. Useful as a contrast
  case, since it is a feeling ("superpowers") rather than a specific
  decision or number, which is the gap Achal's version should close.
- [The complete AI PM masterclass for 2026, Aakash Gupta](https://www.news.aakashg.com/p/jyothi-nookula-podcast):
  an actively publishing AI PM voice with real reach among product
  people, including Indian PMs who follow him. Worth tracking as a
  format reference (structured, framework-driven long posts) even though
  his audience is global rather than India-specific.
- The three funding stories already logged in `trends/2026-07-26.md`
  through `trends/2026-07-28.md` (ProLearn, SigIQ.ai, YoLearn.ai, Lytmus
  AI) are the actual peer content Achal is competing with in-feed this
  week. Treat those trend files as the live record of what the closest
  adjacent builders are being covered for, and check them before reusing
  a funding-reaction angle.
