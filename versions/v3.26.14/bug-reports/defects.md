# Historical defect examples — v3.26.14

These are paraphrased examples from failed historical test rows. Current resolution, severity, root cause, and production impact were not verified.

## Duplicate active unit validation

The source records a failed duplicate-identifier check. Exact unit identifiers and dimensions are omitted.

**Reproduction summary:** Attempt to create a duplicate identifier while the existing unit is active, then compare with a decommissioned-record scenario.

**Expected:** An active unit cannot receive a duplicate identifier under the tested rule.

**Observed:** Duplicate-identifier validation did not behave as expected.

**Source:** 9 July, row 8; recorded status **Fail**.

## Restricted role can use direct status editing

A restricted role could use the direct status dropdown despite the expected control restriction. Exact role configuration and system details are omitted.

**Reproduction summary:** Compare direct status editing for restricted and administrator roles.

**Expected:** Roles can change status only through permitted controls.

**Observed:** Restricted roles could still edit the status through the direct dropdown.

**Source:** 24 July, row 3; recorded status **Fail**.
