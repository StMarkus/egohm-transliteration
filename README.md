# Review of the arabic Vocalisiation

1. **Click Variant A or B.** The selection is highlighted in green.
2. If both are wrong: write the correct form in the "or other form" field.
   Only add vowel marks — the letters must stay the same (no ‎ى → ‎ي, no
   ‎ا → ‎أ).
3. The progress is shown in the bar at the bottom. "Next open" jumps to the
   first undecided card.
4. At the end, click **"Download decisions"** — this creates
   `entscheidungen.csv` in the download folder. Please send this file back.

Progress is stored in the browser (localStorage). You can close it in between
and continue later — same file, same browser. Switching browsers or clearing
browser data will delete it.

**As an aid to decision-making**, below the two variants you'll find the
complete Arabic sentence, and below that the German translation of the same
paragraph. The disputed word appears in the sentence **unvocalized** — it
stands out on its own between its vocalized neighbors, so you don't need to
search for it.

### Authoritative standard

- Full vocalization **including** case and mood ending: ‎الرَّبُّ, not
  ‎الرَّبّ. In pausal speech it's pronounced without the ending, but it's
  written with it — this is how the rest of the corpus, which comes from the
  fully vocalized Van Dyck edition, handles it.
- The article as ‎الْ with sukun, and with shadda before sun letters:
  ‎السَّلَامُ.
- The liturgical pronunciation of the Coptic Orthodox tradition is
  authoritative, not newspaper language.
- **Do not correct spelling errors in the source text.** Where ‎إلي appears
  instead of ‎إلى, or a word is garbled, please just note it in the "or other
  form" field. Orthography will be cleaned up in a separate pass, because by
  design the vocalization tools must not change any letters.

### What the cases are

These are exclusively places where two independent passes arrived at
**different** results. Matching vocalizations have already been adopted.
Typical categories:

| Category | Example |
| --- | --- |
| Case in apposition | ‎سِمْعَانَ / ‎سِمْعَانُ |
| Genitive vs. nominative | ‎وَزَوْجُهَا / ‎وَزَوْجِهَا |
| Imperative vowel | ‎وَأُدْخُلِي / ‎وَأَدْخُلِي |
| Perfect vs. subjunctive | ‎تَأْخُذُ / ‎تَأْخُذَ |
| Noun vs. verb | ‎أَعْلَمُوا / ‎أَعْلِمُوا |

The disagreement rate is 1.5–3% of the words. The double pass is designed
specifically to isolate the places that need a decision, rather than
presenting the whole text for review.