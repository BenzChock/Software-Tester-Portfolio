# Selected test cases — v3.26.16

Public adaptations of selected source records. Actions and expected outcomes are summarized for a portfolio. Use synthetic accounts and non-production payment fixtures when reproducing these scenarios.

The original notes do not establish which datasets were synthetic. These public instructions replace identifiable records with generic test fixtures.

<a id="tc-3-26-16-01"></a>

## TC-3-26-16-01 — Invoice classification after customer type change

**Action:** Change the test customer type, retry payment, and compare new and previous receipts.

**Expected:** The new receipt follows the updated type while previous receipts retain their historical classification.

<a id="tc-3-26-16-02"></a>

## TC-3-26-16-02 — Card summary refresh

**Action:** Replace a test card and return to the booking card.

**Expected:** The masked card summary updates to the new card.

<a id="tc-3-26-16-03"></a>

## TC-3-26-16-03 — Prevent duplicate payment links

**Action:** Generate an extension payment link and try to repeat the extension while payment is pending.

**Expected:** The pending payment prevents duplicate extension requests.

<a id="tc-3-26-16-04"></a>

## TC-3-26-16-04 — Late fee grace-period handling

**Action:** Extend an overdue test booking that is still inside the configured grace period.

**Expected:** No late fee is applied inside the configured grace period.
