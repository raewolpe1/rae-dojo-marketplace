---
triggers:
  - "user makes a job creation claim"
  - "user is comparing instruments"
  - "user asks how many jobs an initiative will create"
use_when:
  - "employment is an outcome of the proposed initiative"
fails_when:
  - "the outcome is explicitly not employment"
related:
  - "adjudicating-an-initiative.md"
  - "evidence-base-high-growth-selection.md"
---

# Evidence Base — Cost per Job Created

> **Provenance.** Figures compiled July 2026 from the sources named in each entry. Verify against the primary source before quoting in a client deliverable. Entries marked `[CHECK]` have not been verified to the primary source and must not be quoted without checking.

## When to Use
- **Whenever employment appears as an outcome.** This is the discipline the sector avoids.
- When comparing instruments for a funding decision.

## Fails When
- **The initiative honestly claims a non-employment outcome.** Then the metric is irrelevant and should not be forced.

## Headline

| Instrument | Cost per job | Source |
|---|---|---|
| **Nigeria business plan competition (YouWiN!)** | **~US$8,500** | McKenzie (2017), ~7,000 jobs from US$34–36m |
| Business training, wage subsidies, smaller grants | **US$11,000 – US$80,000** | McKenzie's comparative work `[CHECK]` |
| Conventional BDS to survivalist firms | Effectively undefined (denominator ≈ 0) | Implied by the training evidence |

**The benchmark to hold in mind: US$8,500 is the good case.** It is the cheapest well-identified job in this literature, and it was achieved by extreme selectivity plus a US$50,000 cheque.

---

## THE EVIDENCE

### The Nigeria benchmark
- **Study:** McKenzie (2017), *American Economic Review* 107(8): 2278–2307, plus author's cost-effectiveness commentary.
- **Country:** Nigeria.
- **Intervention:** Business plan competition; US$34–36 million in grants; ~US$50,000 per winner.
- **Finding:** The programme generated **a little over 7,000 new jobs**, costing the government about **US$8,500 per job**. Adjusting for spillovers changed the estimated employment creation by around 100 jobs — i.e. the estimate is robust to the general equilibrium check in that context.
- **Caveat:** Nigeria, a large and at the time growing market, with an unusually deep applicant pool (24,000 applications). Cost per job excludes the administrative cost of running a competition at that scale, which is non-trivial.

### The comparator band
- **Study:** McKenzie's comparative assessment of job-creation programmes. `[CHECK]` — the underlying compilation should be located and verified before this band is quoted in a deliverable.
- **Country:** Multi-country.
- **Intervention:** Business training, wage subsidies, smaller grants.
- **Finding:** Other job-creation programmes **typically cost between US$11,000 and US$80,000 per job**.
- **Caveat:** `[CHECK]`. Directionally well-attested; the precise band should be sourced. The range itself is the finding — a nearly eight-fold spread between the best and worst instruments doing nominally the same thing.

### Wage subsidies — the denominator disappears
- **Study:** de Mel, McKenzie & Woodruff, "Labor Drops", *AEJ: Applied*. `[CHECK]`
- **Country:** Sri Lanka.
- **Finding:** Firms increased employment during the subsidy; **no lasting impact on firm employment** four years out.
- **Caveat:** If the jobs end with the subsidy, cost per *permanent* job is undefined; cost per *job-year* is the only honest metric.

### Matching grants — the numerator is known, the denominator is not
- **Study:** See `evidence-base-capital-and-credit.md`.
- **Finding:** There is not yet solid evidence that SME job creation is attributable to matching grants.
- **Caveat:** You cannot compute cost per job for an instrument with no established employment effect. Reporting one is fabrication.

### Best practice for job-creation studies
- **Study:** McKenzie, "More Bang for Your Buck: Best-Practice Recommendations for Designing, Implementing, and Evaluating Job Creation Studies". `[CHECK]` — publication venue unverified.
- **Finding:** Job-creation evaluation requires attention to displacement, to job quality, to duration, and to the counterfactual employment path — most studies address none of these.
- **Caveat:** `[CHECK]`. Worth locating if the DEDAT M&E framework is being designed around G4J employment targets.

---

## How to Apply

1. **Compute it. Every time.** Total programme cost ÷ jobs credibly attributable. Not jobs "supported", "sustained", or "touched".
2. **Benchmark against US$8,500 and the US$11,000–80,000 band.** Convert at the current rate and state the assumption.
3. **Where there is no established employment effect, refuse to compute.** A cost per job for an instrument with no measured employment effect is a fabricated number.
4. **Use job-years for temporary instruments.** Wage subsidies buy job-years, not jobs.
5. **Deduct displacement in saturated markets.** Gross jobs are not net jobs where the market is full.
6. **Expect the number to end the argument.** That is the point of computing it.

## Examples

**Situation:** A strategy claims a suite of MSME initiatives will contribute meaningfully to a provincial employment target.

**Application:** Take each line. Compute budget ÷ plausible attributable jobs. For a conventional BDS line reaching 15,000 survivalist firms, the denominator is close to zero on the training evidence, so the cost per job is effectively undefined — which is the finding, and it should be stated. For a selective grant line, apply the Nigerian benchmark with a discount for smaller cheque size. The exercise will typically show that 80% of the budget sits in lines with undefined cost per job and 20% in lines with a defensible one, and the strategy's employment contribution rests almost entirely on the 20%.

**Result:** A budget reallocation argument grounded in arithmetic rather than in advocacy.

## Anti-Patterns

**Don't:** Report "jobs supported" or "jobs sustained".
**Why:** These are not attributable outcomes. They are participation counts wearing an employment label.

**Don't:** Compute cost per job for an instrument with no measured employment effect.
**Why:** You are dividing by a number you invented.

**Don't:** Ignore the administrative cost of selectivity.
**Why:** The Nigerian US$8,500 excludes the cost of processing 24,000 applications. Selection is cheap per job but not free.
