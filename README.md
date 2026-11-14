# Minnesota Noncompete Decisions Since the 2023 Ban

A dataset of Minnesota Court of Appeals and Minnesota Supreme Court decisions on noncompete, non-solicitation, and trade-secret disputes filed from July 1, 2023 (the effective date of Minn. Stat. § 181.988) through November 13, 2026. Compiled by Aaron Hall, a Minnesota business attorney. Updated yearly.

The full write-up, including what the courts said about the 2023 ban and the cases still pending, is at https://aaronhall.com/minnesota-noncompete-decisions/

## File

`minnesota-noncompete-decisions.csv`: one row per decision (12 rows), sorted by filed date.

| Column | Meaning |
|---|---|
| case | Case name as captioned, with reporter citation where one exists |
| court | Deciding court |
| filed | Filed date (YYYY-MM-DD) |
| docket | Appellate docket number(s) |
| status | Precedential or nonprecedential, and any later review |
| covenant_type | The covenant or claim at issue |
| what_the_court_did | One-sentence disposition |
| opinion_url | The court's own opinion PDF |

## Method

- **Sources.** The court's opinion search on mncourts.gov, the public Minnesota opinion pages on HallApproved.com, and a Westlaw search of Minnesota state cases. CourtListener returned leads only.
- **Terms.** noncompete, non-solicit, not to compete, covenant not to solicit, restrictive covenant, trade secret, and the section numbers 181.988, 181.9881, and chapter 325C.
- **What counts.** Precedential, nonprecedential, and order opinions. Special term orders on stays, scheduling, consolidation, and appealability are not counted, nor are opinions where a search term appeared only in passing.
- **Checks.** Each row was read from the court's PDF, and each row's later history was checked on Westlaw on November 13, 2026.

## Limits

This lists the decisions found by the searches above; it does not guarantee completeness. District court rulings are outside these searches. Eleven of the 12 decisions are nonprecedential: under Minn. R. Civ. App. P. 136.01, subd. 1(c), they are not binding authority except as law of the case, res judicata, or collateral estoppel, though they may be cited as persuasive authority. Each figure is a count of public decisions, not a prediction of any outcome, and nothing here is legal advice for a particular agreement.

## Related Guides

- [Minnesota noncompete cases since the ban](https://aaronhall.com/minnesota-noncompete-decisions/): the full index with analysis and pending cases
- [Minnesota noncompete agreement FAQ](https://aaronhall.com/minnesota-noncompete-agreements/)
- [Minnesota noncompete agreement ban](https://aaronhall.com/practice-areas/employment/noncompete-agreement/)
- [Noncompetes signed before the ban took effect](https://aaronhall.com/how-the-minnesota-noncompete-ban-impacts-your-pre-2023-agreements/)
- [Noncompete vs. non-solicitation agreements](https://aaronhall.com/the-legalities-of-noncompete-non-solicitation-agreements/)
- [Minnesota employment law for businesses](https://aaronhall.com/practice-areas/employment/)

## Also Available

- [Google Sheet version](https://docs.google.com/spreadsheets/d/e/2PACX-1vS--KRkvlEmRxmsCqXYcouMlzCq5z1KoST4v7MxI4NythJdviFrE-0K7YXFMEVshChD36ibhb8nELYV/pubhtml)

## License

Data: CC BY 4.0. Please credit "Aaron Hall, aaronhall.com" and link to the page above.
