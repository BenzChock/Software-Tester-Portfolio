# Selected test cases — v3.26.14

Public adaptations of selected source records. Actions and expected outcomes are summarized for a portfolio. Use synthetic accounts and non-production payment fixtures when reproducing these scenarios.

The original notes do not establish which datasets were synthetic. These public instructions replace identifiable records with generic test fixtures.

<a id="tc-3-26-14-01"></a>

## TC-3-26-14-01 — Duplicate active unit validation

**Action:** Attempt to create a duplicate identifier while the existing unit is active, then compare with a decommissioned-record scenario.

**Expected:** An active unit cannot receive a duplicate identifier under the tested rule.

<a id="tc-3-26-14-02"></a>

## TC-3-26-14-02 — Unit release after cancellation

**Action:** Create a booking, cancel it, and attempt a new booking for the released unit.

**Expected:** Cancellation releases the unit without duplicate assignment.

<a id="tc-3-26-14-03"></a>

## TC-3-26-14-03 — Concurrent booking attempts

**Action:** Use two test sessions to attempt a booking for the same unit at the same time.

**Expected:** The same unit is not assigned to two active bookings.

<a id="tc-3-26-14-04"></a>

## TC-3-26-14-04 — Extension through a payment link

**Action:** Generate and complete a test extension payment link.

**Expected:** The booking dates, payment information, and status update correctly.

<a id="tc-3-26-14-05"></a>

## TC-3-26-14-05 — Restricted unit status editing

**Action:** Compare direct status editing for restricted and administrator roles.

**Expected:** Roles can change status only through permitted controls.

<a id="tc-3-26-14-06"></a>

## TC-3-26-14-06 — Receipt-to-booking navigation

**Action:** Open booking details from the receipt report.

**Expected:** The details panel loads the associated booking.
