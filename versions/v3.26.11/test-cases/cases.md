# Selected test cases — v3.26.11

Public adaptations of selected source records. Actions and expected outcomes are summarized for a portfolio. Use synthetic accounts and non-production payment fixtures when reproducing these scenarios.

The original notes do not establish which datasets were synthetic. These public instructions replace identifiable records with generic test fixtures.

<a id="tc-3-26-11-01"></a>

## TC-3-26-11-01 — Payment email totals

**Action:** Complete test payments with and without a discount and inspect confirmation emails.

**Expected:** Discount information appears only when applicable and totals match the scenario.

<a id="tc-3-26-11-02"></a>

## TC-3-26-11-02 — Credit balance in a new booking

**Action:** Create a booking for a test account with credit and compare the preview with the saved transaction.

**Expected:** The saved transaction reflects the credit shown in the preview.

<a id="tc-3-26-11-03"></a>

## TC-3-26-11-03 — Credit balance when changing billing date

**Action:** Change a booking billing date through both admin and customer flows using an account with credit.

**Expected:** Credit is applied consistently across both flows.

<a id="tc-3-26-11-04"></a>

## TC-3-26-11-04 — Credit balance when extending a booking

**Action:** Extend a booking through admin and customer flows using an account with credit.

**Expected:** Credit is applied during extension in both flows.

<a id="tc-3-26-11-05"></a>

## TC-3-26-11-05 — Receipt export fields

**Action:** Download a receipt report and compare unit fields with the report page.

**Expected:** Unit number and size are included and agree with the page.

<a id="tc-3-26-11-06"></a>

## TC-3-26-11-06 — Failed scheduled payment explanation

**Action:** Run the expired-card payment scenario and inspect the failed transaction.

**Expected:** The failed transaction explains the payment failure.
