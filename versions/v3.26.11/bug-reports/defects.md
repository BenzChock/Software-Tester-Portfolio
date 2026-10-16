# Historical defect examples — v3.26.11

These are paraphrased examples from failed historical test rows. Current resolution, severity, root cause, and production impact were not verified.

## Credit missing from a created booking

The credit displayed in the preview was not applied to the created transaction. This demonstrates comparing the UI preview with the persisted payment result.

**Reproduction summary:** Create a booking for a test account with credit and compare the preview with the saved transaction.

**Expected:** The saved transaction reflects the credit shown in the preview.

**Observed:** The preview showed credit but the created transaction did not apply it as a discount.

**Source:** 19 May, row 5; recorded status **Fail**.

## Credit differs between billing-date flows

The customer flow applied credit, while the admin flow did not. This demonstrates comparing equivalent operations across two portals.

**Reproduction summary:** Change a booking billing date through both admin and customer flows using an account with credit.

**Expected:** Credit is applied consistently across both flows.

**Observed:** Credit was applied in the customer flow but was not applied in the admin flow.

**Source:** 19 May, row 6; recorded status **Fail**.
