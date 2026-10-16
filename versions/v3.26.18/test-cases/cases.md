# Selected test cases — v3.26.18

Public adaptations of selected source records. Actions and expected outcomes are summarized for a portfolio. Use synthetic accounts and non-production payment fixtures when reproducing these scenarios.

The original notes do not establish which datasets were synthetic. These public instructions replace identifiable records with generic test fixtures.

<a id="tc-3-26-18-01"></a>

## TC-3-26-18-01 — Unit search regression

**Action:** Search for the same test unit from booking and unit pages.

**Expected:** Both pages return the corresponding unit and booking information.

<a id="tc-3-26-18-02"></a>

## TC-3-26-18-02 — Customer status consistency

**Action:** Compare a test customer status across booking, user management, and report pages.

**Expected:** All pages display the same stored status.

<a id="tc-3-26-18-03"></a>

## TC-3-26-18-03 — Renewal after a grace period

**Action:** Process the overdue renewal scenario outside the configured grace period.

**Expected:** Applicable fees are included and calculation details are recorded.

<a id="tc-3-26-18-04"></a>

## TC-3-26-18-04 — Refund eligibility boundary

**Action:** Inspect a test transaction beyond the configured refund window.

**Expected:** The refund action is disabled with an explanation.

<a id="tc-3-26-18-05"></a>

## TC-3-26-18-05 — Renewal preview without charging

**Action:** Run the subscription renewal preview mode.

**Expected:** The preview shows renewal information without processing charges.
