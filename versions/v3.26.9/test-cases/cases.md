# Selected test cases — v3.26.9

Public adaptations of selected source records. Actions and expected outcomes are summarized for a portfolio. Use synthetic accounts and non-production payment fixtures when reproducing these scenarios.

The original notes do not establish which datasets were synthetic. These public instructions replace identifiable records with generic test fixtures.

<a id="tc-3-26-9-01"></a>

## TC-3-26-9-01 — Customer list during booking creation

**Action:** Open the new booking panel in the admin portal.

**Expected:** The customer list loads for selection.

<a id="tc-3-26-9-02"></a>

## TC-3-26-9-02 — Upcoming payment visibility

**Action:** Open the admin dashboard and inspect upcoming payments.

**Expected:** Scheduled payment data is displayed.

<a id="tc-3-26-9-03"></a>

## TC-3-26-9-03 — Payment retry state transition

**Action:** Retry payment for an eligible overdue booking.

**Expected:** A successful payment updates the booking to Active.
