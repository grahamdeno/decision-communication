# Slide Critique & Storyline

Two prompts for the two ways slides go wrong: the **storyline** prompt fixes the order before you build, and the **critique** prompt fixes the clutter after you've built. Most bad decks fail at storyline and get blamed on formatting. Fix the sequence first; a well-ordered ugly deck briefs better than a beautiful one in the wrong order.

## The One Principle Behind Both

**Decision-makers scan; they do not read.** A slide has about ten seconds to land its one message before the reader either gets it or starts skimming. Every rule below serves that reality:

- **One message per slide.** If a slide makes two points, it makes neither. The headline states the message; the body proves it.
- **The headline is the message, not the topic.** "Q3 Budget" is a topic. "Q3 spend is on track; one line item needs a decision" is a message. Write headlines a reader could skim alone and still get the story.
- **Story before formatting.** Sequence carries the argument. No amount of alignment saves a deck that's out of order.
- **One idea competes for attention at a time.** Clutter is two things fighting to be seen. The fix is subtraction, not rearrangement.

---

## Prompt 1 — Storyline (before you build)

Use this when you have material but not a sequence. It produces the deck's spine so you build in the right order instead of building slides and hoping they add up.

```
You are a presentation strategist. Help me sequence a deck before I build it.

AUDIENCE: [who's in the room, seniority, what they can decide]
THEIR QUESTION: [the one question they walk in wanting answered]
WHAT I NEED FROM THEM: [decision / funding / concurrence / awareness]
TIME / SLIDE BUDGET: [e.g., 10 minutes, ~12 slides]
RAW MATERIAL: [dump everything you might include — unordered is fine]

Produce:
1. THE ONE-LINE STORY. The whole deck in a single sentence. If it doesn't fit
   in one line, the deck has no spine yet — tell me that and propose one.
2. SLIDE-BY-SLIDE HEADLINES. For each slide, write the headline as a MESSAGE
   (a claim the audience should leave with), not a topic. The headlines read
   top to bottom as a coherent argument on their own.
3. THE CUT LIST. What in my raw material does NOT serve the one-line story.
   Name it and set it aside. Every deck is improved by what it leaves out.
4. THE ASK SLIDE. Where the request lands and how it's phrased.
```

---

## Prompt 2 — Critique (fix a deck you have)

Use this on a deck that feels cluttered, unclear, or off. Describe each slide, or paste the outline, or attach exported slide images if your tool supports it.

```
You are a ruthless but constructive slide reviewer. My deck feels cluttered and
the story isn't landing. Review it for a scanning decision-maker, not a careful reader.

AUDIENCE: [who, seniority, what they care about]
INTENDED MESSAGE OF THE DECK: [the one thing they should leave with]
[Paste outline / describe each slide / attach slide images]

For the DECK as a whole:
- Does the headline sequence tell a coherent story on its own? Read the headlines
  top to bottom and tell me what argument they make. If it's not my intended
  message, the story is out of order — show me the reordering.
- What should be cut entirely? What's competing with the main line?

For EACH slide:
- ONE-MESSAGE TEST: what is this slide's single message? If you find two, tell me
  where to split it.
- HEADLINE TEST: is the headline a message or just a topic? Rewrite topic headlines
  as messages.
- SCAN TEST: in ten seconds, what does a reader take away? If that's not the
  intended message, what's stealing attention?
- CLUTTER: name the specific elements to remove, merge, or move to an appendix.

Then give me:
- The three highest-leverage fixes, ranked. If I only do three things, these.
- Any slide I should delete outright.
```

---

## Tips From Decks That Worked

- **"Sponsors scan" changes the layout, not just the words.** A five-item status deck became five health cards read in ten seconds instead of five paragraphs. When the critique says a slide fails the scan test, the fix is usually a structural one (cards, a single chart, a matrix), not a wording tweak.
- **Consistent slide layouts read as competence.** When every session/item/status slide shares one layout, the audience learns to read it once and then scans the rest effortlessly. Ask the critique to flag slides that break an established pattern.
- **The cut list is the hardest and most valuable output.** Cutting good material that doesn't serve the one-line story is what separates a tight deck from a thorough one. Expect to resist it; do it anyway.
- **Run storyline, build, then critique.** The two prompts are a front end and a back end. Storyline sets the spine, you build, critique catches what drifted. Pair either with the [Draft, Critique, Revise](https://github.com/grahamdeno/ai-delivery-toolkit/blob/main/templates/draft-critique-revise.md) template from my AI Delivery Toolkit for a self-iterating pass.
- **Headlines are the whole game.** If you do one thing from this file, write every headline as a message. A deck whose headlines tell the story when read alone is already 80% of the way to clear.

## Data Sensitivity

Slides carry the most sensitive material you produce: real numbers, names, program status, decisions. Sanitize before pasting into any AI tool your organization hasn't approved for that data. Describe the structure and the problem rather than pasting live content when in doubt.
