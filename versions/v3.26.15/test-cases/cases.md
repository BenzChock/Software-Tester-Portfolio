# Selected test cases — v3.26.15

Public adaptations of selected source records. Actions and expected outcomes are summarized for a portfolio. Use synthetic accounts and non-production payment fixtures when reproducing these scenarios.

The original notes do not establish which datasets were synthetic. These public instructions replace identifiable records with generic test fixtures.

<a id="tc-3-26-15-01"></a>

## TC-3-26-15-01 — Replace a saved card

**Action:** Replace a saved test payment card while a subscription is active.

**Expected:** The card can be replaced without cancelling the subscription.

<a id="tc-3-26-15-02"></a>

## TC-3-26-15-02 — Delete a card used by a subscription

**Action:** Attempt to delete a saved test card associated with an active subscription.

**Expected:** The system prevents deletion and explains the dependency.

<a id="tc-3-26-15-03"></a>

## TC-3-26-15-03 — Retry an overdue payment

**Action:** Retry payment for an overdue test booking.

**Expected:** Successful payment updates the booking status.

<a id="tc-3-26-15-04"></a>

## TC-3-26-15-04 — Receipt tender filter

**Action:** Select the available tender types on the receipt report.

**Expected:** The filter options are available and return matching receipts.
