---
triggers:
  - "user asks about EVs, shipping, aviation, or transport decarbonisation"
  - "user mentions sustainable aviation fuel, green shipping, or freight"
  - "user is comparing fuel options for heavy transport"
use_when:
  - "the question is about how to decarbonise specific transport modes"
  - "the user is being sold a near-term solution for hard-to-abate transport"
  - "you need the energy-density framework for transport choices"
fails_when:
  - "the question is about urban planning or modal shift (different domain)"
  - "you treat all transport as one problem"
  - "you collapse the EV-passenger-car story (succeeding) with heavy transport (much harder)"
related:
  - "power-density.md"
  - "innovation-hype-and-failure.md"
  - "the-decarbonisation-paradox.md"
---

# Transportation Decarbonisation

## When to Use
- When a transport decarbonisation strategy is being assessed.
- When the question is which transport modes can realistically electrify by when.
- When sustainable aviation fuel, green shipping, or hydrogen heavy trucks are being proposed.
- When teaching the energy-density framework for transport.

## Fails When
- **The question is about urban planning.** Modal shift (cars to bikes to public transport) is a different and important problem; Smil's framing focuses on the fuel-and-energy question once you have the trips.
- **You collapse the modes.** Passenger cars, light trucks, heavy trucks, rail, shipping, and aviation have very different physics and economics.
- **You under-state the EV success in passenger cars.** Light passenger transport has moved from techno-optimist territory to deployed-industry territory.

## Core Concept
Transport accounts for about 25% of global energy-related CO₂ emissions. The decarbonisation difficulty varies dramatically by mode, governed by energy density: how much energy a fuel carries per unit mass and per unit volume. Energy density matters most when the fuel has to be carried for long distances or in compact vehicles.

**Energy densities (approximate, by mass):**
- Jet fuel: ~43 MJ/kg
- Diesel: ~43 MJ/kg
- Marine bunker fuel: ~40 MJ/kg
- Liquid hydrogen: ~120 MJ/kg (but needs cryogenic storage at -253°C)
- Compressed hydrogen (700 bar): effective ~6 MJ/kg-system after tank
- Lithium-ion battery: ~0.5 MJ/kg (best cells, system-level lower)
- Ammonia: ~18.6 MJ/kg

**Energy densities (approximate, by volume):**
- Diesel: ~36 MJ/L
- Jet fuel: ~35 MJ/L
- Liquid hydrogen: ~8.5 MJ/L
- Compressed hydrogen (700 bar): ~5 MJ/L
- Lithium-ion battery: ~1.5 MJ/L
- Liquid ammonia: ~15 MJ/L

The gap between hydrocarbons and batteries is roughly 80× by mass and 25× by volume. This is the physics that governs transport decarbonisation choices.

**Passenger cars.** Light passenger transport: short trips, frequent stops, lots of dwell time at home or workplace where charging is feasible. Lithium-ion batteries work well here — the energy-density penalty is acceptable because the cars are not range-constrained for most use. EVs have moved from techno-optimist territory to deployed-industry territory. Global EV share of new car sales reached about 18% in 2024, with China leading. This is real and accelerating.

**Light commercial / urban delivery.** Similar: short routes, return-to-base operations, predictable duty cycles. EVs are increasingly viable. Significant fleet adoption underway.

**Heavy long-haul trucking.** This is harder. A typical long-haul truck travels 600-1,000 km per shift, carries 20-40 tonnes payload, and needs to refuel in minutes not hours. Batteries large enough for 800 km of heavy hauling weigh several tonnes themselves, displacing payload. Solutions: depot-charged regional electric trucks (working), megawatt-charging on highway corridors (early deployment), hydrogen fuel cell trucks (pilot scale), e-fuels (concept). The deployment story is at the beginning, not the middle.

**Rail.** Already substantially electrified in much of the world; further electrification is a known engineering problem and largely a political-economy question.

**Shipping.** Global shipping moves about 80% of trade by volume on marine bunker fuel. A modern container ship's voyage from Shanghai to Rotterdam takes about 30 days and consumes thousands of tonnes of fuel. Battery-electric is not feasible at this energy density. Options being developed: LNG (already deployed but still fossil), bio-methanol (small but growing), green ammonia (interesting because ammonia has decent energy density and the bunkering infrastructure issues are tractable), sail-assist (real for some routes), green hydrogen (very hard for the reasons above). No solution is close to commercial dominance. The fleet renewal cycle (25-30 years) means even rapid order-book transformation produces slow fleet transformation.

**Aviation.** The hardest case. Jet fuel's energy density (mass and volume) cannot be substituted by batteries for anything beyond short regional flights. Hydrogen aircraft are decades away from commercial scale. Sustainable Aviation Fuel (SAF) is the industry's primary near-term strategy: drop-in biofuels and synthetic e-fuels. Current SAF production globally in 2024 is less than 1% of total jet fuel use, with extremely steep cost curves. Long-haul aviation decarbonisation on the 2040 horizon is not in sight.

**The transport priority order (from realistic to extremely difficult):**
1. Passenger cars — happening
2. Urban delivery — happening
3. Rail — known engineering, political question
4. Regional heavy trucking — emerging
5. Long-haul trucking — early
6. Shipping — early, no clear winner
7. Long-haul aviation — distant

A serious transport decarbonisation strategy works this priority order, not all sectors simultaneously.

## How to Apply
1. **Disaggregate by mode.** Different modes have different physics and different timelines.
2. **Use energy density as the binding constraint diagnostic.** Modes where batteries work (passenger cars) decarbonise differently from modes where they do not (shipping, aviation).
3. **Distinguish demonstration from deployment.** Hydrogen aircraft demonstrations exist; commercial fleets do not.
4. **For development planning, distinguish freight from passenger.** Urban passenger transport in African cities can leapfrog to electric. Long-distance freight will continue on diesel for decades.
5. **Engage the fleet turnover rate.** New orders today implies fleet composition twenty years from now. The capital cycle is the binding rate.

## Examples
**Situation:** A South African logistics company is considering a "fully decarbonised fleet by 2035" commitment.
**Application:** Disaggregate by vehicle category. Light commercial — feasible by 2035 with strong order-book commitments. Regional heavy trucks — partially feasible with depot-charging investment. Long-haul heavy trucks (Johannesburg to Durban, Cape Town to Johannesburg) — not feasible on this timeline; diesel will dominate. Reframe the commitment to specific vehicle categories and timelines.
**Result:** A credible commitment replaces an aspirational one. The company avoids reputational risk of missed target.

**Situation:** A donor is funding a "sustainable shipping corridor" for African ports.
**Application:** Define what is meant by sustainable. If the project is bunkering infrastructure for LNG or methanol, it is real and useful. If it is hydrogen bunkering at commercial scale by 2035, it is not currently buildable. The donor's expectations need calibration.
**Result:** Programme is scoped to what is actually deployable on the timeline.

## Anti-Patterns
**Don't:** Treat transport as a single decarbonisation problem.
**Why:** The modes differ by orders of magnitude in difficulty. Strategy must disaggregate.

**Don't:** Extrapolate the EV passenger-car success to heavy transport.
**Why:** The success is real but specific to low-energy-density use cases. Heavy transport is a different problem.

**Don't:** Frame SAF as a near-term solution at scale.
**Why:** Current SAF production is well under 1% of jet fuel use. The cost gap and feedstock constraints will not be resolved by 2030.
