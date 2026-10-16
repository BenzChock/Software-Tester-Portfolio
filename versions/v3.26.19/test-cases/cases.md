# Selected test cases — v3.26.19

Public adaptations of selected source records. Actions and expected outcomes are summarized for a portfolio. Use synthetic accounts and non-production payment fixtures when reproducing these scenarios.

The original notes do not establish which datasets were synthetic. These public instructions replace identifiable records with generic test fixtures.

<a id="tc-3-26-19-01"></a>

## TC-3-26-19-01 — User search across supported fields

**Action:** Search with different supported name and address fields using synthetic accounts.

**Expected:** Search returns the matching account for each supported field.

<a id="tc-3-26-19-02"></a>

## TC-3-26-19-02 — Unit dropdown ordering

**Action:** Open the booking unit dropdown and inspect the ordering.

**Expected:** Units are ordered by size.

<a id="tc-3-26-19-03"></a>

## TC-3-26-19-03 — Required payment method

**Action:** Attempt to create a booking without a payment method, then select one and complete creation.

**Expected:** Creation requires a payment method and the selected method appears on the receipt.

<a id="tc-3-26-19-04"></a>

## TC-3-26-19-04 — Customer checkout request workflow

**Action:** Submit a test checkout request and process it through the admin review flow.

**Expected:** The request enters a pending state and completes through the review flow.

<a id="tc-3-26-19-05"></a>

## TC-3-26-19-05 — Refund role restrictions

**Action:** Compare refund access for a permitted role and restricted roles.

**Expected:** Only permitted roles can use the refund function.

<a id="tc-3-26-19-06"></a>

## TC-3-26-19-06 — Accounting role permissions

**Action:** Assign the accounting role to a test account and inspect allowed and restricted functions.

**Expected:** The role can access its permitted functions and cannot access restricted functions.

<a id="tc-3-26-19-07"></a>

## TC-3-26-19-07 — Saved card reference cleanup

**Action:** Delete or replace a saved test card and inspect the related payment reference lifecycle.

**Expected:** Obsolete card references are removed and a replacement reference is associated correctly.
