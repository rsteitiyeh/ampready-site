---
title: "Journeyman Electrician Exam Questions and Answers PDF: What to Look For, Plus 8 Worked Samples"
description: ""
keyword: "journeyman electrician exam questions and answers pdf"
publishDate: 2026-07-17
---

A journeyman electrician exam questions and answers PDF is only useful if it cites specific NEC articles, explains the reasoning behind each answer, and matches your state's current code edition. Below are 8 original sample questions we wrote and verified against 2023 NEC concepts, covering code lookups and calculations, with full explanations for each.

Most free PDFs floating around online fail on one of those three points. They're copied and recopied without a source, so nobody can tell you which NEC edition they were written against, and some quietly reproduce copyrighted material from actual exam vendors, which is both a legal problem and a reliability problem since nobody vets the answers.

## What should a real exam questions and answers PDF contain?

A resource worth using has three things every free download from a forum usually lacks: a cited NEC article or table for every answer, a written explanation of the reasoning (not just a letter), and a stated code edition so you know it applies to your state's exam.

Without a citation, you can't verify the answer yourself, and you can't tell if the resource is testing 2017 NEC concepts against a 2023 exam. Without an explanation, you memorize an answer instead of learning the method, which fails the moment the real exam rephrases the question. The National Fire Protection Association maintains the NEC as NFPA 70, and any credible study resource should be traceable back to specific numbered sections in that document, not a paraphrase someone wrote from memory. See [NFPA's NEC product page](https://www.nfpa.org/product/nfpa-70-national-electrical-code-nec/p0070code) for the current edition status.

## Why free PDFs are risky

Three problems show up constantly in free, uncredited exam-prep PDFs:

1. **Wrong edition.** A PDF built on the 2017 or 2020 NEC will have article numbers and table values that don't match a 2023-based exam. Table 250.66 and Chapter 9 conduit fill values, for example, have shifted between editions.
2. **No source, no accountability.** If a document doesn't say who wrote it or what it's based on, there's no way to verify the answer key is correct. Wrong answers in a free PDF cost you real study time.
3. **Copyright exposure.** Some "leaked" PDFs reproduce actual questions from licensed exam vendors like PSI or Pearson VUE. Using copyrighted exam content isn't just a legal risk for whoever posted it, it also means the questions may not reflect what your state board currently tests, since vendors update their item banks.

The safer path is a resource built from scratch around real NEC concepts, with citations you can check against your own codebook, not a copy of someone else's copy.

## 8 original sample questions with answers and explanations

These are questions we wrote from scratch based on real 2023 NEC concepts. They are not copied from any copyrighted exam bank. Grab your codebook and check the citations as you go.

**1. Box fill: Does a 4x1.5 square box hold this circuit?**
A 4x1.5 square metal box has a listed volume of 21.0 cubic inches. It contains six 12 AWG current-carrying conductors (three 2-conductor NM cables), one internal cable clamp, one duplex receptacle, and two 12 AWG grounding conductors. Is the box large enough?
*Answer: No.* Per NEC 314.16(B), each 12 AWG conductor counts as one volume allowance of 2.25 cubic inches (Table 314.16(B)). Count: 6 conductors + 1 for the clamp (one allowance total, based on the largest conductor) + 2 for the device (one per strap) + 1 for all grounding conductors combined = 10 allowances × 2.25 = 22.5 cubic inches required. The 21.0 cubic inch box is undersized; you need a larger box, such as a 4-11/16 square, or fewer conductors in the box.

**2. Ampacity vs. overcurrent protection: what breaker size is allowed?**
A branch circuit uses 12 AWG copper THHN conductors terminating on standard 60°C-rated devices. Table 310.16 lists 12 AWG copper at 30A in the 90°C column. What's the maximum standard overcurrent device size allowed for this conductor?
*Answer: 20A.* Per NEC 110.14(C)(1), conductors terminating on equipment rated 60°C (typical for circuits 100A or less) must use the 60°C ampacity column, which lists 12 AWG copper at 25A. But NEC 240.4(D)(5) caps 12 AWG copper conductors at 20A maximum overcurrent protection regardless of the higher ampacity shown in the tables. The answer is 20A, not 25A or 30A.

**3. Grounding electrode conductor sizing**
A dwelling service uses 2/0 AWG copper service-entrance conductors, connecting to a concrete-encased electrode. What size copper grounding electrode conductor does NEC Table 250.66 require?
*Answer: 4 AWG copper.* Table 250.66 sizes the grounding electrode conductor based on the largest ungrounded service conductor. Service conductors sized between 1/0 and 3/0 AWG copper (or 3/0 through 4/0 aluminum) require a 4 AWG copper grounding electrode conductor, or 2 AWG aluminum.

**4. Dwelling unit receptacle spacing**
In a dwelling living room, per NEC 210.52(A)(1), how far apart can general-use receptacle outlets be spaced along the wall, and what triggers a required outlet on a short wall segment?
*Answer:* No point measured horizontally along the floor line of a wall can be more than 6 feet from a receptacle outlet, which works out to receptacles spaced no more than 12 feet apart. Any individual wall space 2 feet or wider must have its own receptacle outlet, including narrow spaces between doors and windows.

**5. GFCI protection: kitchen receptacles**
Does every receptacle in a dwelling kitchen need GFCI protection, or only the ones serving countertops?
*Answer:* Both, for different reasons. NEC 210.8(A)(6) requires GFCI protection for all 125V through 250V receptacles that serve kitchen countertop or work surfaces. Separately, 210.8(A)(7) requires GFCI protection for any receptacle within 6 feet of the outside edge of a sink, in any room of the dwelling, not just the kitchen. A kitchen receptacle that isn't serving a countertop but sits within 6 feet of the sink still needs GFCI protection under the second rule.

**6. Voltage drop calculation**
A 120V, 16A branch circuit runs 100 feet one-way using 12 AWG copper (6,530 circular mils). Using VD = (2 × K × I × D) ÷ CM, with K = 12.9 for copper, what's the approximate voltage drop, and does it meet the NEC's recommended limit for branch circuits?
*Answer:* VD = (2 × 12.9 × 16 × 100) ÷ 6,530 ≈ 6.3 volts, or about 5.3% of 120V. NEC 210.19(A), Informational Note No. 4, recommends keeping branch circuit voltage drop to 3% or less (5% combined with the feeder), so this circuit exceeds the recommended limit. It's a recommendation, not a hard code violation, but the fix is upsizing to 10 AWG copper to bring the drop back under 3%.

**7. Conduit fill calculation**
How many 12 AWG THHN conductors (each with a conductor area of 0.0133 square inches per NEC Chapter 9, Table 5) can be pulled into 1/2 inch EMT, which has a total internal area of 0.304 square inches per Chapter 9, Table 4?
*Answer:* 9 conductors. NEC Chapter 9, Table 1 limits conduit fill to 40% of the internal area when there are three or more conductors. 40% of 0.304 square inches is 0.122 square inches. Dividing 0.122 by 0.0133 gives 9.17, and you always round down, so the maximum is 9 conductors.

**8. Service load calculation basics**
A 2,000 square foot dwelling uses the standard method under NEC Article 220. What's the general lighting and receptacle load before any demand factors are applied?
*Answer:* 6,000 VA. NEC Table 220.12 sets the general lighting load for a dwelling unit at 3 VA per square foot. 2,000 square feet × 3 VA = 6,000 VA. This is the starting number before applying demand factors under 220.42 and adding the other required loads (small appliance circuits, laundry circuit, appliances) to reach the total service load.

## Where to go from here

Working through 8 questions won't get you exam-ready by itself. Build a rotation that covers box fill, ampacity, grounding, spacing rules, GFCI/AFCI requirements, voltage drop, conduit fill, and load calculations in roughly the same proportion your state's exam uses, and always check your answer against the actual codebook article, not just a key. That's the same method we use when we build practice sets for AmpExam: cite the article, show the math, then let you verify it yourself in the book.

## FAQ

**Are free journeyman exam questions and answers PDFs accurate?**
Some are, many aren't. The main risks are an outdated NEC edition, uncredited answer keys with no way to verify them, and in some cases reproduced copyrighted exam content. Check for a stated NEC edition and cited article numbers before trusting any free PDF.

**What NEC edition should my study questions be based on?**
Whatever edition your state board currently tests. As of mid-2026 many states still test the 2020 or 2023 NEC rather than the newly published 2026 edition, so confirm directly with your licensing board before studying a specific edition's article numbers.

**Are these sample questions from a real exam?**
No. These 8 questions are original, written from scratch based on real 2023 NEC concepts and cited article and table numbers. They are not copied from PSI, Pearson VUE, ICC, or any other exam vendor's copyrighted material.

**Why do calculation questions matter as much as code-lookup questions?**
Most state exams test both, and calculation questions often combine multiple code tables into one problem, which trips up candidates who only memorized isolated facts. Practicing both types in the same proportion as your real exam builds the pacing you need on test day.

**How do I know if a PDF's answer key is wrong?**
Check the cited article or table number against your own current codebook. If the PDF doesn't cite a specific NEC section for each answer, treat every answer as unverified until you can confirm it yourself.
