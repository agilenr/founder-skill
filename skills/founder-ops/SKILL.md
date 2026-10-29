---
name: founder-ops
description: >-
  Your operations manager. Works out how the business actually runs on day one:
  suppliers and what they cost, who works when, the step-by-step routines for
  opening, serving or shipping and closing, the tools to run it, the licences and
  permits to check, and a risk register with what to do when each thing goes
  wrong. Feeds real costs back to the CFO. Use when the user says "how do I run
  this", "operations", "suppliers", "staffing", "SOPs", "what do I need to open",
  "permits", or "day one".
argument-hint: "[city or country]"
---

# founder-ops

A plan that works on paper fails at 7am on a Monday. This skill makes sure the
first day, week and month can actually be run, and that the CFO's numbers include
what running it really costs.

## Step 1: what the business has to do every day

From `founder/idea.md`, `founder/offer.md` and `founder/numbers.json`, write the
daily cycle as a list of steps from first thing to last (for a café: deliveries,
prep, open, serve, clean, cash up, order; for an online store: orders in, pick,
pack, ship, returns, support). Mark which steps a customer sees.

## Step 2: suppliers

For every input in the CFO's variable costs and every piece of equipment: two or
three real suppliers the user can contact, their public prices or how to get a
quote, minimum orders, lead times and payment terms. Link the sources. Where only
a quote will tell, say so and add it to the open questions. If a real price
differs from `founder/numbers.json`, update it and say the CFO should re-run.

## Step 3: people

Who does what, when: a weekly rota for the planned volume and for the slow first
month. The roles, the hours, and the wage assumption (from the user, or a public
source for the local minimum and typical pay, linked). Payroll costs beyond wages
vary by country; flag them for the accountant.

## Step 4: routines (SOPs)

Short, numbered routines for the moments that make or break the business: opening,
the core service or fulfilment, handling a complaint, closing, and a weekly
reorder. Each fits on one page someone could follow on their first day.

## Step 5: tools

The smallest stack that runs it: payments, point of sale or store, scheduling,
bookkeeping, inventory. Real products with their published prices, and why each.

## Step 6: licences, permits and insurance

A checklist of what businesses of this type usually need in the user's city or
country (registration, tax numbers, health or food permits, signage permits,
insurance), each with the official page to confirm it. Say plainly that rules
differ by place and change, and the user must confirm each with the authority or a
professional. Not legal advice.

### In Malaysia

If `founder/malaysia.md` exists (written by `/founder-malaysia`), use its
council and checklist. Otherwise find the local council (PBT) for the exact
address first, since premise and signboard licences, fees and timelines differ
by council (DBKL in KL, MBPP or MBSP in Penang, Majlis Bandaraya Seremban, MBJB
in Johor Bahru, and so on). Check, each with the official page or `VERIFY`:
SSM registration (Sabah and Sarawak use their own state process for sole
proprietors), LHDN tax file, the unit's zoning and CCC or CF, Bomba fire
requirements, and for food: food handler training and typhoid vaccination for
every food handler, and JAKIM halal certification if the business will call
itself halal. For staff: the current minimum wage and the employer share of
EPF, SOCSO and EIS, looked up, never from memory. Put the Malaysian calendar
(Ramadan, festive weeks, school holidays, east coast monsoon) into the rota and
the risk register.

## Step 7: risk register

The ten things most likely to go wrong (a supplier runs out, a key person is sick,
the card terminal fails, a bad review, a slow month), each with how likely, how
bad, and the plan.

## Output

`founder/ops.md`, plus updated `founder/numbers.json` if real costs changed. Next:
`/founder-launch`.
