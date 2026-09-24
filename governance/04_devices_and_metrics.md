# Devices and Metrics

Status: Canonical v1 governance  
Purpose: Prevent definition drift across deals and prompts.

The devices organize thinking. They are not a requirement to make every article visibly templated.

## 1. The Bet

### Purpose

State the provisional underwriting hypothesis early enough that research can test it.

### Definition

One or two sentences explaining what may be unusually attractive, mispriced, misunderstood, or fragile about the deal and what must be true for that interpretation to hold.

### Rules

- Provisional, never sacred.
- Research may strengthen, rewrite, or kill it.
- Specific to the business.
- Not a generic category thesis.
- The Price section closes with: **Did the Bet survive?**

### Good

> The listing is priced like a small owner-operated service company, but if the recurring maintenance book is geographically dense and survives owner replacement, the real asset may be a local route network with better incremental economics than the headline margin suggests.

### Bad

> This is an attractive company in a growing market with opportunities to improve operations.

## 2. Business Physics

### Purpose

Expose the economic machine beneath the accounting presentation.

### Definition

The few operating variables that create revenue and profit.

### Good form

> Revenue is roughly technicians × productive stops per technician × realized revenue per stop. The likely binding constraint is technician capacity; the scarce asset may be dense customer routes.

The equation is a mental model. It does not need to capture every accounting detail.

### Bad

> Growth depends on sales, marketing, operations, and execution.

## 3. What Binds

### Purpose

Name the constraint that most limits the business.

Examples:

- labor availability;
- route density;
- sales capacity;
- physical throughput;
- working capital;
- inventory;
- licensing;
- owner decision-making;
- real estate;
- demand.

The binding constraint can change under New Management.

## 4. What Is Scarce

### Purpose

Name the difficult-to-replicate resource that explains economic value.

Examples:

- dense routes;
- licensed employees;
- a permit;
- referrals;
- reputation;
- specialized know-how;
- local distribution;
- long-held customer access;
- scarce physical capacity.

Scarcity must connect to economics.

## 5. Quality Card

### Purpose

Let a reader understand the kind of economic machine in approximately thirty seconds.

### Definition

Applicable economic attributes receive a 1 to 5 score and one crisp reason.

Attributes:

- Gross Margin
- Normalized Profitability
- Revenue Durability
- Operating Leverage
- Working-Capital Intensity
- Capital Intensity
- Demand Backdrop
- Natural Expansion
- Pricing Power
- Transferability

Use governance/05_quality_card_anchors.md.

### Rules

- No overall weighted score.
- Drop irrelevant attributes.
- Explanation matters more than number.
- Scores that rely on unverified assumptions should say so.
- Positive scores require the same explanatory rigor as negative scores.

## 6. "This business is really about"

### Purpose

Give the reader a fast mental model.

### Definition

One line naming the one or two economic attributes that define the investment.

Example:

> This business is really about exceptional revenue durability plus technician density.

Avoid generic summaries such as:

> This business is really about growth and profitability.

## 7. Reconstructed P&L

### Purpose

Show the difference between what the listing advertises, what we think survives today, and what the business could become.

### Columns

1. **As Listed**
2. **Year 0, Our View**
3. **New Management Case, Year 3**

### Row states

Every row is one of:

- point estimate;
- range;
- not enough evidence.

### Evidence

Every reconstructed row should preserve evidence class.

The exhibit should show:

- evidence coverage;
- reconstruction confidence.

Suggested confidence interpretation:

**High**  
Revenue, cost of sales, payroll, rent, and owner role are substantially observed.

**Medium**  
Revenue and earnings are observed plus meaningful operating detail such as headcount or owner role.

**Low**  
Revenue and stated earnings are essentially all that is known.

Low-confidence reconstruction should be visibly low confidence. It should not be made to look precise through formatting.

## 8. Earnings Keep Rate

### Purpose

Show how much of broker-advertised earnings survives our normalization.

### Formula

**Earnings Keep Rate = Year 0 cash earnings ÷ stated SDE**

If only EBITDA is stated, use EBITDA as the denominator and label the result **vs stated EBITDA**.

### Example

Stated SDE: $600K  
Year 0 cash earnings: $390K  
Earnings Keep Rate: 65%

### Edge cases

- May exceed 100%. Report it.
- May be negative. Report it.
- If Year 0 is a range, Keep Rate is a range.
- If neither SDE nor EBITDA is stated, not applicable.
- Suppress when the denominator is not comparable, such as a projected or blended figure or a figure including income excluded from our reconstruction.
- Suppress at Low reconstruction confidence when the result would imply more knowledge than the evidence supports.
- Carry the evidence class.

## 9. Owner Replacement Tax

### Purpose

Answer whether the buyer is acquiring a company or acquiring a job.

### Formula

**Owner Replacement Tax = replacement cost of the owner's actual work ÷ stated SDE**

If only EBITDA is available, label the denominator accordingly.

### Rules

- Price actual owner functions, not a mechanical GM salary.
- Multiple working owners are summed.
- If compensation is already embedded in stated EBITDA, deduct only the gap between embedded compensation and true replacement cost.
- If the owner role is partially known, use an explicit range where supportable.
- If there is no usable owner-role evidence, not applicable may be better than fake precision.
- Suppress when the denominator is not comparable or reconstruction confidence is too low.

## 10. Under New Management

### Purpose

Tell the operating story of the third P&L column.

### Horizons

**Day 1**  
What we leave alone.

**Year 1**  
What we change.

**Year 3**  
What business we are trying to create.

### Rules

Use governance/08_value_creation_standard.md.

Every material lever should:

- move a Business Physics variable;
- answer What Has to Be True;
- answer why it remains uncaptured;
- include cost, timeline, confidence, and first action;
- appear in the earnings bridge if quantified.

## 11. What Has to Be True

### Purpose

Turn uncertainty into the diligence agenda.

### Opening

> The deal really turns on: [one to three most important unknowns].

Then provide three to seven Swing Questions.

Each Swing Question contains:

- question;
- why it matters;
- evidence needed;
- encouraging answer;
- concerning answer;
- decision impact.

### Decision impacts

Use one or more:

- could kill deal;
- could materially reprice;
- could materially strengthen thesis;
- refines thesis.

### Bad

> What is customer concentration?

### Better

> Does the recurring maintenance book depend on a handful of property managers who can rebid the work annually, or is the revenue distributed across many independently sticky relationships?

The second question tests the thesis.

## 12. Bear Case

### Purpose

State the strongest plausible case that the Bet is wrong.

### Include

- where normalized earnings could be weaker;
- what may fail to transfer;
- what concentration or fragility matters;
- what could make value creation fail;
- what is left if wrong.

The Bear Case is not a list of generic risks.

## 13. What Is Left If We Are Wrong

### Purpose

Make downside concrete.

Potential residual value may include:

- liquid assets;
- real estate;
- permits or licenses;
- contracts;
- customer relationships;
- strategic value;
- scarce capacity.

Sometimes the answer is very little.

Say so.

## 14. Implied Effective Multiple

### Purpose

Show the real economic price after normalization.

### Formula

**Implied Effective Multiple = Asking Price ÷ Year 0 normalized cash earnings**

If Year 0 is a range, the effective multiple is a range.

### Interpretation

The broker multiple answers:

> What does the listing appear to cost?

The effective multiple answers:

> What are we actually paying for the earnings we think survive?

That distinction is often more useful than a long precedent-transaction exercise.
