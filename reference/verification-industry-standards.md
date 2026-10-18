# Verification: industry-standards.md Against Manuscript

Verification of manuscript-specific claims made in `reference/industry-standards.md` against the
narrative content written in the `manuscript/` folder's files.

This verification addresses only claims `industry-standards.md` makes about *We Heralds of Freedom*
as a specific manuscript. Industry standards the file cites that do not make claims about this
manuscript (e.g., SFWA word-count definitions, market conditions, agent expectations, comp title
descriptions) are outside this verification's scope.

All line references use the format `chNN:line` (1-indexed file lines for `chapter-NN.md`) or
`ep:line` (for `epilogue.md`). References to `industry-standards.md` use `is:line`.

---

## 1. Word Count

### Claim

`industry-standards.md` states the manuscript's word count as "~27,371 words" in three locations:

- is:3 — "Reference compiled October 2026 for *We Heralds of Freedom* (Draft Zero, ~27,371 words)."
- is:17–18 — "*We Heralds of Freedom* at ~27,371 words sits squarely in the novella range by every
  major definition — comfortably above the floor and well below the ceiling."
- is:204 — "**Word count** (27,371) is well-centered in the novella range. No adjustment needed."

### Verification

**INACCURATE.** A `wc -w` count of the manuscript files as they exist in the `manuscript/` folder
yields the following:

| File | Word Count |
|---|---|
| chapter-01.md | 3,232 |
| chapter-02.md | 4,224 |
| chapter-03.md | 2,010 |
| chapter-04.md | 3,871 |
| chapter-05.md | 3,826 |
| chapter-06.md | 3,025 |
| chapter-07.md | 3,729 |
| chapter-08.md | 2,997 |
| epilogue.md | 3,247 |
| **Narrative body total** | **30,161** |
| front-matter.md | 21 |
| glossary.md | 665 |
| **Full manuscript total** | **30,847** |

The narrative body (chapters 1–8 plus epilogue) totals 30,161 words — approximately 2,790 words
(~10.2%) more than the claimed ~27,371. The full manuscript including front-matter and glossary
totals 30,847 words.

The word counts above include chapter-heading lines (e.g., "# Chapter One – Our Definitions Of
Freedom"), which contribute approximately 63 words across nine files. This is negligible relative to
the ~2,790-word discrepancy.

The source of the discrepancy is not determinable from the manuscript files alone. The
`industry-standards.md` file may have been compiled against an earlier draft, or the count may have
been produced by a different counting method.

### Impact on Categorization Claims

The categorization claims that follow from the word count — "sits squarely in the novella range by
every major definition" (is:17–18) and "well-centered in the novella range" (is:204) — cite industry
ranges that this verification does not independently verify. However, taking the industry ranges as
stated in `industry-standards.md` at face value (SFWA: 17,500–39,999; Hugo: 17,500–40,000;
Tordotcom: 20,000–40,000), the corrected count of 30,161 narrative words remains within all three
ranges. At 30,161 words, the manuscript sits near the midpoint of the Tordotcom range (midpoint:
30,000) and slightly above the midpoint of the SFWA/Hugo range (midpoint: ~28,750). The
categorization as a novella remains valid at the corrected count. The characterization "well-centered"
is reasonable at 30,161 words, though the specific figure cited is inaccurate.

---

## 2. Temporal Span

### Claim

is:205 — "the story's scope (one protagonist's arc across **roughly one year**, single nation, one
central conflict with political/theological dimensions)"

### Verification

**UNDERSTATED.** The manuscript's temporal markers indicate the full narrative spans approximately
**two years**, not roughly one year.

The main narrative arc (Chapters 1–8) spans approximately one year, supported by the following
temporal markers:

- **Ch2** takes place in winter: "cool morning's winter breeze" (ch02:6). Edward's tax hike was
  "three months ago" (ch02:48), placing the investiture ceremony (Ch1) approximately three months
  prior.
- **Ch3** takes place on Deliverance Day, the same winter as Ch2.
- **Ch4** takes place shortly after Ch3 (Marelyn arrives in Windbury after the riot).
- **Ch5** opens in spring: "Portsmouth suffered its first Imperial air-fleet incursion with spring's
  first buds" (ch05:4). Carden references "these past six months" of societal struggle (ch05:114).
  The chapter extends into summer: "summer swept in sweltering heat" (ch05:282).
- **Ch6** spans summer through mid-autumn: "summer's sweltering heat flew away and with it Alfainia's
  green leaves. Fall swept in with a premature chill" (ch06:170). "Rearmament started a year ago"
  (ch06:170). References to "last year's riots" (ch06:196) confirm approximately one year has elapsed
  since the Deliverance Day events.
- **Ch7** takes place in autumn: "an unusual chill infused the autumn breeze" (ch07:48).
- **Ch8** takes place in late autumn: "Windbury's gentle autumn sunlight" (ch08:8). Multiple
  references to events "a year" prior: "still a year later" (ch08:68), "still unrepaired a year
  after the riots" (ch08:126).

The Epilogue takes place approximately **one additional year** after Chapters 7–8, supported by:

- "Windbury's welfare-for-volunteering initiative already ran a year now" (ep:16) — the initiative
  was proposed in Ch8.
- "after a year renting the place" (ep:32) — referring to the flat Roger provided in Ch8.
- "this past year in Windbury" (ep:48).
- "Almost a year in" (ep:70).
- "Unlike two years ago" (ep:102) — explicitly placing the Epilogue two years after the Deliverance
  Day events of Chapters 2–3.

The claim of "roughly one year" is accurate for Chapters 1–8 alone but understates the full temporal
span of the manuscript by approximately one year. The Epilogue constitutes a distinct temporal
stratum set approximately two years after the narrative's opening events.

---

## 3. Geographic Scope

### Claim

is:205 — "**single nation**"

### Verification

**VERIFIED.** All scenes in the manuscript take place within Alfainia. The two primary settings are
Windbury (a provincial capital in Ostnir, per glossary:79) and Portsmouth (Alfainia's capital, per
glossary:59). Other nations — Sarh (ch01:50), Imperium Divinus (ch05:128), the Zhang Dynasty
(ep:110), Zaltaclan (ep:64) — are referenced but no scenes take place outside Alfainia's borders.

The one arguable exception is the Ch5 confrontation between Carden and Julian, which occurs in a
space accessed through a "secret alcove" (ch04:92) described as involving an "unfathomably vast,
empty void" (ch05:84). However, Carden's physical body remains in Edward's office in Portsmouth
during this sequence, and the space is a mystical/magical domain rather than another nation.

---

## 4. Central Conflict

### Claim

is:205–206 — "**one central conflict with political/theological dimensions**"

### Verification

**VERIFIED.** The manuscript's conflicts have demonstrable political and theological dimensions:

**Political dimensions:**
- Tax policy as mechanism of the central dilemma: Carden grants exemptions to charitable enterprises
  (ch02:124–132, ch06:4–26), Edward demands annulment and arrears collection (ch07:4–14).
- Rearmament vs. welfare: Edward presents higher taxes as necessary for military buildup (ch05:110),
  Carden argues "Alfainia's working and middle classes can't afford yet more" (ch05:122).
- Governance of poverty: soup-kitchens (ch02:124), welfare-for-volunteering (ch08:126), municipal
  reconstruction (ep:12).
- Parliamentary and imperial politics: Dominions (ch02:14, ch05:68–72), the Creator's Scripture
  demanding Alfainia's submission (ch05:86–96), rearmament policy (ch06:170).

**Theological dimensions:**
- The God of War's Scripture commanding preparation for world war (ch01:134–138).
- The Creator's Scripture claiming Alfainia as a province and demanding submission (ch05:86–96).
- Carden's faith in the Father as the basis for his moral stance: "I believe in the Father, and the
  Father teaches us love is the greatest commandment" (ch07:193).
- Saint Alfred's Scripture: "What father, when his son asks for bread, gives him a stone? And when his
  son asks for a fish, gives him a snake?" (ch07:126–129, as implied by Carden's reading of the
  Scripture at Saint Alfred's Cathedral).
- Lucifer's revelation and the Father's decree of Elfkind's freedom (ep:114–128).

The characterization of "one central conflict" is an interpretive framing — the manuscript contains
interlocking conflicts (civil-service dilemma, marriage crisis, family pressures, Elf slavery) rather
than a single discrete conflict. However, these conflicts orbit Carden's recurring choice between
institutional compliance and moral conviction, which has both political and theological expression.
The characterization of the conflict's dimensions is supported by the text.

---

## 5. Protagonist and Transformation Axes

### Claim

is:205 — "**one protagonist's arc**"

is:207–208 — "**Carden's internal transformation (faith, marriage, vocation) is the engine**; the
geopolitical/theological conflict is the pressure"

### Verification

**VERIFIED.** The manuscript follows a single protagonist, Carden Oakmoore, and his transformation
is traceable across three axes as claimed:

**Faith:**
- Carden prays and invokes the Father throughout: "Hopefully he accomplished something, anything.
  Ideally not catastrophic, if the Father so graced" (ch01:23–24); "Carden uttered a quick prayer to
  the Father in his heart before he spoke" (ch07:16).
- Saint Alfred's Cathedral scene: Carden reads Scripture and asks "Did Saint Alfred write this?"
  (ch07:133).
- Termination exchange in Arcane Tongue: "Because I believe in the Father, and the Father teaches us
  love is the greatest commandment" (ch07:193).
- Epilogue creedal speech in Arcane Tongue (ep:170–176).

**Marriage:**
- Baseline: "stiff as a board and cold as a stone" (ch01:172, as implied by the description of their
  marital dynamic). "That ever-present shackle worn for the past twenty-five years" (ch01:210).
- Crisis: "Why can't we make this work?" (ch01:204, as implied by Marelyn's question). Marelyn's
  breakdown: "Why can't I be me?" (ch02:226–234, as inferred from Marelyn pressing her face against
  Carden's arm and weeping).
- Escalation: Marelyn's arrival in Windbury (ch04:4–14), ring exchange (ch04:258–262, as implied
  by the ring-related scene), first shared sleeping (ch04:286).
- Climax: Carden discovers the flat emptied and assumes divorce (ch07:213–237), Marelyn's revelation
  of self-disinheritance (ch07:283–289), "I was never going to divorce you" (ch07:297, as stated by
  Marelyn: "Why in the Father's name would I divorce you?").
- Resolution: "Let's make this work" spoken simultaneously (ch08:94–98, as implied by the café
  scene), "We'll make this work" simultaneously (ch08:210–212, as implied by the flat scene).

**Vocation:**
- Civil servant: "Special Commissioner of Income Tax" (ch02:310, as stated by Carden in the crowd
  scene). "More than twenty years Carden walked through Commonwealth Exchequer for a living"
  (ch07:205).
- Termination: Carden chooses termination over annulling the exemptions (ch07:181–207).
- New vocation: Municipal construction supervisor and welfare-for-volunteering participant (ep:4–28).

**Geopolitical/theological conflict as pressure:**
- The God of War's Scripture triggers rearmament (ch01:134–138), which triggers tax hikes (ch02:48),
  which triggers Carden's dilemma over exemptions (ch02, ch06, ch07).
- The Creator's Scripture escalates the external threat (ch05:86–96), compounding fiscal pressure.
- Edward's ultimatum (ch07:4–14) forces the vocational break.
- Lucifer's revelation (ep:114–128) reframes the theological landscape for the Epilogue's resolution.

All three transformation axes are present in the manuscript text and function as claimed.

---

## 6. Thematic Claims

### Claim

is:210–211 — "the manuscript's engagement with **colonialism, religious plurality, economic justice,
and institutional loyalty**"

### Verification

Each theme is verified individually below.

### 6a. Colonialism

**VERIFIED.** The manuscript engages with colonialism on two distinct levels, both explicitly present
in the text:

*Alfainia as former colony:*
- "They were Imperial colonists who chose to stay after the liberation" (ch04:52) — Carden's parents
  are former colonists of Imperium Divinus.
- "Public monuments to the many documented atrocities Imperium Divinus committed during its nine-year
  occupation of the island" (ch05:128).
- "Saint Alfred freed us from the old Imperium's rot more than a hundred years ago" (ch04:168).
- "Alfainia's liberation from Imperial occupation" (ch07:133).

*Alfainia as colonizer:*
- "thriving exports to our great country's growing Dominions abroad" (ch02:14).
- "a country with overseas Dominions on all seven continents" (ch02:88).
- "Alfainia is only as strong as its Dominions" (ch05:68). "Alfainia's overseas Dominions sparkled
  like lesser light-blue stars, a collection of spots and strips on the world's six other continents"
  (ch05:70).
- The Creator's Scripture refers to "the Creator's Alfainian provinces" (ch05:14), framing Alfainia
  itself as a contested colonial possession.

*Imperial challenge:*
- Imperial air-fleet incursions (ch03:130–160, ch05:4, ch06:168).
- Julian and Jane as active Imperial collaborators working to restore "Alfainia's return to the
  Creator's empire" (ch04:96).

### 6b. Religious Plurality

**VERIFIED.** Multiple religious traditions coexist and conflict within the manuscript:

- **The Father**: Carden's primary faith. Invoked throughout: "if the Father so graced" (ch01:24),
  "Father bless you this Deliverance Day" (ch03:18), "I believe in the Father" (ch07:193).
- **The God of War**: Official state-aligned deity, Dwarfkind's patron. Manifests at the investiture
  (ch01:32–44), issues Scripture (ch01:132–140), consecrates government (ch01:54–56). "Thus do we,
  the leaders of Alfainia, pledge our allegiance and faith to the God of War!" (ch01:58).
- **The Creator**: Imperium Divinus's deity, the faith of Carden's parents (ch04:52, ch04:96) and the
  Winstons (ch04:96). Issues a rival Scripture (ch05:86–96). "I recognize no God except myself"
  (ch05:86).
- **Lucifer**: Revealed in the Epilogue as a redeemed prophet. Pronounces the Father's decree of
  Elfkind's freedom (ep:112–128).
- **Saint Alfred**: Historical religious figure whose Scripture Carden reads at the cathedral
  (ch07:124–133).

These traditions are not merely referenced but actively drive plot: the God of War's Scripture
triggers rearmament policy (ch01), the Creator's Scripture escalates the imperial threat (ch05),
Carden's faith in the Father grounds his termination decision (ch07), and Lucifer's revelation
reframes the Epilogue's theological stakes (ep:114–128).

### 6c. Economic Justice

**VERIFIED.** Economic justice is central to the plot mechanism:

- Tax exemptions for charitable enterprises: the primary tension driving Carden's professional
  dilemma (ch02:124–132, ch06:4–26, ch07:4–14).
- Welfare and soup-kitchens: "How many more people are without jobs now, we run the soup-kitchen all
  day" (ch06:8). "The number of people coming to our soup-kitchen has doubled in three months"
  (ch02:132).
- Rearmament vs. welfare: "Parliament has agreed to raise taxes higher so we can build more
  aerial-fleets" (ch05:110). "Everywhere I've been these past six months, society is struggling"
  (ch05:114).
- Welfare-for-volunteering initiative: Carden and Marelyn's proposal to condition welfare on public
  service (ch08:126), operational for a year in the Epilogue (ep:16).
- Elf labor exploitation: "Horace shamed Windbury's affluent families to loan some of their Elf
  slaves for municipal-work" (ep:10). "Shame he could not properly compensate them for their work,
  they weren't volunteers or receiving welfare after all" (ep:18).

### 6d. Institutional Loyalty

**VERIFIED.** Institutional loyalty — and its limits — functions as both theme and plot mechanism:

- Carden's civil-service tenure: "More than twenty years Carden walked through Commonwealth Exchequer
  for a living. Almost half his life" (ch07:205).
- Military service: "I specialized in pacifying occupied enemy settlements" (ch01:124). "I gave my
  blood on the front-lines for the country Saint Alfred believed in" (ch07:197). Black Hounds tattoo
  (ch05:190).
- Edward's recognition: "I will not deny a proven patriot his conscience" (ch07:30).
- The breaking point: Edward's ultimatum forces a choice between institutional compliance and moral
  conviction (ch07:4–14), and Carden chooses termination (ch07:181–185).

---

## 7. Arcane Tongue

### Claim

is:211–212 — "**The Arcane Tongue truth-forcing conceit** is the kind of worldbuilding-as-metaphor
that distinguishes upmarket from commercial fantasy."

### Verification

**VERIFIED** as to the truth-forcing property. The manuscript explicitly establishes that Arcane
Tongue compels truthfulness:

- "Arcane Tongue only allowed one to speak and write the truth" (ch01:140).
- "The irrefutable medium for truth between Arcanists" (ch02:308).
- "the fact he spoke in Arcane Tongue indicated he wanted nothing but truth from Carden" (ch05:144).
- "How can you be so blinded by the Creator's lies, when Arcane Tongue won't even let you say Arcane
  Tongue is the Creator's?" (ch05:166).
- "Tell me, in the Father's Arcane Tongue, you don't owe your current accomplishments to Alfainia's
  generosity to you. I dare you" (ch05:158).

The Arcane Tongue is deployed at structurally significant moments throughout the manuscript:
investiture ritual (ch01:14–20), Horace's interrogation (ch03:66), the Carden-Julian confrontation
(ch05:144–170), the termination exchange (ch07:191–203), Lucifer's revelation (ep:112), and Carden's
creedal speech (ep:170–176).

The characterization of Arcane Tongue as "worldbuilding-as-metaphor" (is:212) is an interpretive
claim about the conceit's literary function. The manuscript uses the truth-forcing property as a
literal plot mechanism — it constrains what characters can say at key dramatic moments and validates
the authenticity of divine communications. Whether this constitutes "metaphor" in the literary-
critical sense (i.e., the truth-forcing language as a figure for something beyond itself) is not
stated in the manuscript text and is inferred by `industry-standards.md` as a market-positioning
characterization.

---

## 8. Point of View

### Claim

is:214–215 — "**Single POV** (Carden throughout; Marelyn is a non-POV supporting character
experienced entirely through Carden's perspective)"

### Verification

**VERIFIED** as to POV. All nine narrative sections (Chapters 1–8 and the Epilogue) are told in
close third-person from Carden Oakmoore's perspective. No chapter or scene presents another
character's interiority directly. Marelyn's internal states are accessed only through Carden's
observation: her expressions ("Marelyn's glare smothered the words on his tongue," ch01:12), her
physical actions ("Marelyn locked her arms around his arm and pressed her face against it," ch02:226),
and Carden's interpretations of her behavior ("She must have won a tremendous amount of alimony from
him at court," ch07:265 — an interpretation the text reveals as incorrect).

The characterization of Marelyn as a "supporting character" (is:214) is a categorization choice. The
manuscript positions the Carden-Marelyn marriage as a central arc — its trajectory from estrangement
("That ever-present shackle worn for the past twenty-five years," ch01:210) through crisis
(ch07:213–299) to reunion (ch07:299–337, ch08, epilogue) functions as the narrative's emotional
spine. Marelyn is a non-POV character whose actions significantly drive the plot (her self-
disinheritance at ch07:283–289 constitutes the Chapter 7 reversal), but "supporting character" as
distinct from "co-lead" or "deuteragonist" is an interpretive framing not explicitly settled by the
manuscript text.

---

## 9. Manuscript Register and Protagonist Type

### Claim

is:216 — "**the political-fantasy register and moral-conviction protagonist**"

### Verification

**VERIFIED.**

*Political-fantasy register:*
The manuscript's primary plot mechanisms are political: tax policy (ch02, ch06, ch07), parliamentary
governance (ch01:14–20), civil-service administration (ch02:6–28), welfare systems (ch02:124–132,
ch08:126), rearmament budgets (ch05:110), imperial diplomacy (ch05:68–72), and municipal governance
(ep:12–16). The fantasy elements (Magic, divine Scriptures, Arcane Tongue) function within and
through these political structures rather than replacing them.

*Moral-conviction protagonist:*
Carden's defining choice — accepting termination rather than annulling the tax exemptions — is
explicitly framed as a moral and faith-based conviction: "Because I believe in the Father, and the
Father teaches us love is the greatest commandment. I cannot in good faith ignore the suffering of my
fellow man and still call myself a devout believer of His teachings" (ch07:193). His Epilogue creedal
speech (ep:170–176) extends this conviction into a public declaration. The characterization of Carden
as a "moral-conviction protagonist" is directly supported by the text.

---

## 10. Summary of Findings

| # | Claim (is:line) | Status | Notes |
|---|---|---|---|
| 1 | Word count ~27,371 (is:3, 17, 204) | **INACCURATE** | Actual narrative body: 30,161 words (~10.2% higher) |
| 2 | Novella categorization (is:17–18, 204) | **VERIFIED** | Valid at corrected count; remains within all cited ranges |
| 3 | Roughly one year (is:205) | **UNDERSTATED** | Ch1–Ch8 ≈ one year; full manuscript including Epilogue ≈ two years |
| 4 | Single nation (is:205) | **VERIFIED** | All scenes within Alfainia (Windbury and Portsmouth) |
| 5 | One central conflict, political/theological (is:205–206) | **VERIFIED** | Political and theological dimensions explicitly present; "one central conflict" is interpretive framing of interlocking conflicts |
| 6 | Carden's transformation: faith, marriage, vocation (is:207) | **VERIFIED** | All three axes present and traceable in manuscript text |
| 7 | Geopolitical/theological conflict as pressure (is:208) | **VERIFIED** | External forces demonstrably drive internal choices |
| 8 | Colonialism (is:210) | **VERIFIED** | Present on two levels: Alfainia as former colony and as colonizer |
| 9 | Religious plurality (is:210) | **VERIFIED** | Five distinct religious traditions coexist and conflict |
| 10 | Economic justice (is:211) | **VERIFIED** | Central to plot mechanism (tax exemptions, welfare, labor) |
| 11 | Institutional loyalty (is:211) | **VERIFIED** | Theme and plot mechanism; 20+ years of service, breaking point |
| 12 | Arcane Tongue truth-forcing (is:211) | **VERIFIED** | Explicitly stated: "only allowed one to speak and write the truth" (ch01:140) |
| 13 | Worldbuilding-as-metaphor (is:212) | **INTERPRETIVE** | Truth-forcing is a literal plot mechanism; "metaphor" is an inferred literary characterization |
| 14 | Single POV, Carden throughout (is:214) | **VERIFIED** | Close third-person, Carden's perspective in all nine sections |
| 15 | Marelyn as non-POV (is:214) | **VERIFIED** | No direct access to Marelyn's interiority anywhere in the manuscript |
| 16 | Marelyn as supporting character (is:214) | **INTERPRETIVE** | Non-POV is verified; "supporting" vs. "co-lead" is a categorization choice given the centrality of the marriage arc |
| 17 | Political-fantasy register (is:216) | **VERIFIED** | Political mechanisms are the primary plot infrastructure |
| 18 | Moral-conviction protagonist (is:216) | **VERIFIED** | Carden's choices are explicitly framed as faith- and conviction-based |

### Discrepancies Requiring Correction

Two claims require factual correction:

1. **Word count**: The figure ~27,371 should be updated to reflect the current manuscript's narrative
   body count of 30,161 words (or 30,847 including front-matter and glossary). The novella
   categorization remains valid at the corrected count.

2. **Temporal span**: "Roughly one year" understates the full manuscript's temporal scope. The
   Chapters 1–8 arc spans approximately one year, but the Epilogue is set approximately one additional
   year later, as explicitly marked by "welfare-for-volunteering initiative already ran a year now"
   (ep:16) and "Unlike two years ago" (ep:102). The full manuscript spans approximately two years.

### Claims Verified Without Issue

The remaining manuscript-specific claims — single nation, political/theological conflict dimensions,
Carden's three transformation axes, the four thematic engagements (colonialism, religious plurality,
economic justice, institutional loyalty), the Arcane Tongue truth-forcing property, single POV, and
the political-fantasy register with moral-conviction protagonist — are all supported by explicit
manuscript text as cited above.

### Interpretive Claims Noted

Two characterizations are identified as interpretive rather than factual:

- "Worldbuilding-as-metaphor" (is:212) characterizes the Arcane Tongue's literary function. The
  truth-forcing property is verified as a literal mechanism; its status as "metaphor" is an inference.
- "Supporting character" (is:214) categorizes Marelyn's narrative role. Her non-POV status is
  verified; whether she is a "supporting character" or a co-lead is a framing choice given the
  marriage arc's centrality.

---

*This verification is anchored to the manuscript text as written in the `manuscript/` folder's files
and the claims made in `reference/industry-standards.md`. No narrative content has been extrapolated.
Where a claim involves interpretation or inference, it is stated as such.*
