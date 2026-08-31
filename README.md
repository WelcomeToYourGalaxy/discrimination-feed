# discrimination-feed

A live wire on discrimination worldwide: who is treated unequally, by whom,
under what law, and what is done about it.

Built after the Discrimination section on Welcome to Your Galaxy, and scoped to
the forms it names.

## The twenty subjects

The first ten are the forms the section lists outright:

| | |
|---|---|
| Sexism and women's rights | Racism and racial discrimination |
| Ethnicity, skin colour and language | LGBTQIA+ people and the law |
| Class and social origin | Religious freedom and persecution |
| Disability and ableism | Intellectual discrimination |
| Stature and appearance | Speciesism and animal standing |

To those it adds age and nationality, the places discrimination is met — work,
and access to housing, health and services — and hate crime and targeted
violence. The last five carry the section's own structural claims:

- **Discriminatory actors inside institutions** — the section's point that
  states lack effective machinery to stop covert actors infiltrating and
  hijacking government, the protection existing on the books and in background
  disclosures rather than in practice
- **Division as a route to power** — leaders who are not themselves
  discriminatory exploiting these divisions anyway
- **Anti-discrimination law and enforcement** — including whether it is
  enforced or merely written
- **Measuring who is discriminated against** — the surveys behind figures like
  1 in 6 people, 40% on ethnicity, skin colour or language, 70% living without
  religious freedom, 64 countries criminalising homosexuality, 90% holding some
  sexist prejudice
- **What is set against it**

## The gate

Every subject term carries the words it must appear beside. The word's other
senses are refused outright — a discriminating palate, price discrimination,
discriminant analysis, the discriminating power of a test — as is opinion and
entertainment that uses the vocabulary without being about anyone's treatment.

A story no subject will claim is refused and counted as refused, rather than
filed under a fallback subject it did not earn.

## Weight

A decision (2), institutional material (2), a measured figure (1), a pending
decision with a date (1), a named jurisdiction (1), a primary source (1). At
three or more it is marked consequential.

## Sources

179 wires. 25 direct feeds carried over from the sibling repos where they are
already proven — OHCHR and the special procedures, UN News human rights, the
European Court of Human Rights, the Inter-American Commission, the CPT, UNHCR,
IOM, Human Rights Watch, Amnesty, Freedom House, CIVICUS, ILGA World, the
European Roma Rights Centre, Article 19, Front Line Defenders, OMCT, Redress,
APT, Statewatch, Privacy International, EDRi, Access Now and APTN. Plus 138
Google News locale searches across 26 languages with 24 rotating queries, and
16 subject searches.

Worth adding, with URLs you have opened: Minority Rights Group, the Equal
Rights Trust, the International Disability Alliance, Dalit rights
organisations, and national equality bodies.

## Running it

    python3 harvest_discrimination.py
    python3 harvest_discrimination.py --dry-run
    python3 verify_sources.py
