---
name: humanize
description: |
  Turns flat, AI-sounding text into writing people want to read: posts, captions,
  emails, scripts, landing pages, proposals. Four passes: cut the AI words, fix the
  AI shape, rewrite it with some life in it, then apply the writer's own voice. Use
  when the user says "humanize this", "make this sound human", "make this less
  boring" or "does this read like AI", or before anything gets published or sent.
---

# humanize

Take text that reads like a chatbot wrote it and turn it into something a real person would write, and that people would actually stop to read. Keep what it says. Never add facts, numbers, names or quotes that were not there.

## Pass 1: the words (20 patterns)

Based on Wikipedia's "Signs of AI writing" guide. Fix each one you find.

1. "Not X, but Y" contrasts that add drama instead of facts. ("It's not a tool, it's a mindset.")
2. One-line closers and dramatic fragments. ("And that changes everything." "Simple as that.")
3. Sayings that sound deep and mean nothing. ("Growth lives outside your comfort zone.")
4. Run-ups before the point. ("Here's the thing:" "The truth is:" "Let that sink in.")
5. Arguing with no one: answering an objection nobody raised.
6. Lists of three, everywhere, out of habit.
7. Several sentences in a row that start the same way.
8. Dashes as the default glue between clauses. Use a full stop, a comma or a colon.
9. Inflated importance: "a pivotal moment", "a testament to", "plays a crucial role", "in today's fast-paced world".
10. Stock AI words: delve, tapestry, landscape, realm, navigate, leverage, unlock, elevate, seamless, robust, game-changer, ever-evolving, vibrant.
11. Sales talk: transform, revolutionize, supercharge, unleash, next-level.
12. Vague authority: "experts say", "studies show", "many believe", with no name or source.
13. Stacked hedges: "arguably", "potentially", "it's worth noting that".
14. Empty -ing tails on a sentence: ", highlighting the importance of...", ", ensuring that...".
15. Fancy stand-ins for "is" and "has": "serves as", "stands as", "boasts", "features".
16. Bold on random phrases, and Title Case On Every Heading.
17. Headings and bullet points on a piece that should be a few plain paragraphs.
18. Chatbot leftovers: "Great question!", "Certainly!", "I hope this helps", "Let me know if you'd like...".
19. Writing about the text instead of the subject: "In this post, we'll explore...".
20. Explaining what the reader already knows, so the real point arrives last.

## Pass 2: the shape

Text can pass every word check and still read as AI because of how it is built. The StoryScope study (2026) compared 61,608 stories by people and by five AI models. Structure alone told them apart with a 93.2% F1 score. Fix these, in this order:

1. The line that explains what it all means. Usually the last line or the last paragraph: the lesson, the moral, the "and that's why...". Delete it. Let the specifics make the point. (In the study, AI stated the theme outright in 77% of stories. People did it in 52%.)
2. Feelings acted out through the body: "my chest tightened", "his jaw clenched", "a knot in my stomach". Say the feeling plainly: "I was nervous." (81% of AI stories did this, against 38% of human ones. It was the widest gap in the study.)
3. Stories that resolve too neatly. If every problem is solved by one clear decision, put back what really happened: the false start, the luck, the person who helped, the part that still isn't fixed. Only use what the text or the writer tells you. Never invent it.
4. Every line pitched harder than the one before. Let one part land flat.

Then check that the text does at least three of these:
- names real specifics: tools, numbers, dates, places, people
- talks to the reader directly
- admits a trade-off or something that didn't work
- breaks strict time order somewhere
- names an emotion plainly

## Pass 3: make it worth reading

Clean text can still be boring. Rewrite it with some life in it, using only what the writer gave you.

1. Open on the most interesting true thing in the text: a moment, a number, something someone said, a mistake. Not a summary.
2. Swap each general claim for the concrete picture behind it, when the text has one. "We care about quality" becomes what they actually do.
3. Mix sentence lengths. A long sentence, then a short one that lands.
4. Let the writer's personality show: an opinion, a small joke, an honest admission.
5. End on something specific or a real question. Never on a moral.
6. If the text has no real detail to work with, ask the writer one short question to get one (a name, a number, a moment). Don't make one up.

## Pass 4: the voice

These rules win if they clash with passes 1 to 3. They are a starter set. Replace them with your own.

- No em dashes.
- No filler openers: "Great question", "Absolutely", "In today's world".
- Short sentences. One idea per sentence.
- Plain words. If a simpler word works, use it.
- Keep the writer's own pet words and phrases. Don't smooth them out.
- (Add your own: words you never use, how you open, how you sign off.)

## Never touch

Code, data, quotes from real people (testimonials, customer messages, interviews) and legal text. If asked to humanize one of these, say why and stop.

## How to answer

- No text yet: reply with one line, "Ready. Paste the text you want humanized."
- "humanize this" plus the text: give the rewritten text first. Then a short "What I changed" list with counts per pass, like "Words: cut 3 stock words and 2 not-X-but-Y lines. Shape: removed the closing moral. Life: opened on the first customer instead of a summary."
- "humanize --check" plus the text: only list what reads as AI. Change nothing.
- "humanize <file>" (where you can edit files): rewrite that file in place, then give the same short list.
- Never say the text is "now human" or "undetectable". Say what you removed.

Sources: Wikipedia, "Signs of AI writing". Russell, Rajendhran, Pham, Iyyer and Wieting, "StoryScope: Investigating idiosyncrasies in AI fiction" (2026). Made by Allen Thomas, The Growth Engine.
