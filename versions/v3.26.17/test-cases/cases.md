# Selected test cases — v3.26.17

Public adaptations of selected source records. Actions and expected outcomes are summarized for a portfolio. Use synthetic accounts and non-production payment fixtures when reproducing these scenarios.

The original notes do not establish which datasets were synthetic. These public instructions replace identifiable records with generic test fixtures.

<a id="tc-3-26-17-01"></a>

## TC-3-26-17-01 — Date and timezone consistency

**Action:** Inspect the date/time standardization checks recorded for this version.

**Expected:** Date/time values display consistently in the intended business timezone.

<a id="tc-3-26-17-02"></a>

## TC-3-26-17-02 — Billing date across device timezones

**Action:** Use a device timezone outside Thailand, change the billing date, and compare portal and email displays.

**Expected:** The billing date remains consistent in Thailand time across the checked views.

<a id="tc-3-26-17-03"></a>

## TC-3-26-17-03 — Booking creation across device timezones

**Action:** Create a test booking from a device in a different timezone and compare booking dates across views.

**Expected:** Booking dates remain consistent across portal, confirmation, and email.

<a id="tc-3-26-17-04"></a>

## TC-3-26-17-04 — Booking extension across device timezones

**Action:** Extend a test booking from a device in a different timezone and compare end dates.

**Expected:** The new end date and transaction time use the intended timezone consistently.
