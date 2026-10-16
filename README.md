# QA / Software Tester Portfolio

A portfolio of manual software QA work by **BenzChock**, organized by application version.
The collection includes test case design, expected and actual results, regression checks,
historical defect reports, and release documentation.

Selected examples cover booking and payment flows, data consistency, permissions,
reporting, and timezone behavior.

## Release documentation

The release archive covers **3.26.6–3.26.19** and contains **13 documents** with **74 images**.
Individual PDFs are stored under their corresponding versions. A **65-page combined PDF**
includes a clickable table of contents and bookmarks.

- [Release index and individual PDFs](release-notes/README.md)
- [View the combined PDF](release-notes/REDD-Release-3.26.6-to-3.26.19-Combined.pdf)
- [Download the complete PDF archive](release-notes/REDD-Release-PDFs-3.26.6-to-3.26.19.zip)

## Browse the work

**585 original QA files · 13 Scribehow release documents · 53 selected test examples · 4 historical defect examples**

| Version | Selected focus | Public test examples |
| --- | --- | ---: |
| [v3.26.6](versions/v3.26.6/README.md) | Release documentation from Scribehow | 0 |
| [v3.26.7](versions/v3.26.7/README.md) | Admin portal regression, language persistence, search, and booking extension | 4 |
| [v3.26.9](versions/v3.26.9/README.md) | Booking creation, scheduled payments, and payment retry | 3 |
| [v3.26.10](versions/v3.26.10/README.md) | Booking exports, date filters, activity logs, and vouchers | 4 |
| [v3.26.11](versions/v3.26.11/README.md) | Credit balance consistency, receipt fields, and payment failure reporting | 6 |
| [v3.26.12](versions/v3.26.12/README.md) | Voucher filters, receipt filters, and booking navigation | 4 |
| [v3.26.13](versions/v3.26.13/README.md) | Occupancy reporting and consistent unit labels | 2 |
| [v3.26.14](versions/v3.26.14/README.md) | Concurrent bookings, unit validation, payment links, and role restrictions | 6 |
| [v3.26.15](versions/v3.26.15/README.md) | Saved cards, subscription dependencies, payment retry, and receipt filters | 4 |
| [v3.26.16](versions/v3.26.16/README.md) | Invoice classification, card summaries, duplicate payment links, and fee boundaries | 4 |
| [v3.26.17](versions/v3.26.17/README.md) | Booking and billing consistency across device timezones | 4 |
| [v3.26.18](versions/v3.26.18/README.md) | Search regression, customer status, renewal previews, and refund boundaries | 5 |
| [v3.26.19](versions/v3.26.19/README.md) | Search, checkout requests, required payment fields, and role permissions | 7 |
| [v3.26.20](versions/v3.26.20/README.md) | Booking and calculator design artifacts | 0 |

Version v3.26.8 was not present in the supplied folder. v3.26.20 contains a design summary only.
Folder dates are grouping labels and do not establish release or deployment dates.

## What each version contains

```text
versions/
  v3.26.x/
    README.md
    test-cases/cases.md
    test-logs/execution-log.md
    bug-reports/defects.md       # Versions with selected historical failures
    evidence/README.md          # Original-file category inventory
    screenshots/                # Original PNG / JPG evidence
    videos/                     # Original MOV / MP4 recordings
    spreadsheets/               # Original Excel workbooks
    data/                       # Original CSV exports
    test-templates/             # Original checklist workbooks
    documents/                  # Original PDFs
    notes/                      # Original notes
    tools/                      # Original HTML tools
```

The design-only version uses `design/summary.md` in place of test cases and results.
All work examples and evidence notes stay inside their corresponding version.

## Selected examples

- [Credit balance differs between preview and saved transaction](versions/v3.26.11/bug-reports/defects.md)
- [Competing booking attempts and restricted status editing](versions/v3.26.14/test-cases/cases.md)
- [Consistent booking dates across device timezones](versions/v3.26.17/test-cases/cases.md)
- [Renewal preview without processing charges](versions/v3.26.18/test-cases/cases.md)
- [Refund and accounting role checks](versions/v3.26.19/test-cases/cases.md)

## How to read the results

Cases are selected public adaptations of the original Test Log workbooks. Expected outcomes,
actions, and observations are paraphrased. Recorded Pass, Fail, and Pending statuses retain the
historical source row's status. A row can remain Pending even when its observation looks successful.
No full-release pass rate, performance benchmark, current fix status, or root cause is claimed.

The actions use generic test fixtures for publication. The source notes do not establish that all
original executions used synthetic data. The original attachments, including source datasets, are included separately in their version folders.

## Original work files

All **585 original work files** are included and grouped by file type within their original version:
**447 images**, **71 videos**, **34 Excel workbooks**, **26 CSV files**, **3 PDFs**,
**2 text files**, and **2 HTML files**. Original file contents are preserved without redaction.

Original filenames and nested test-case folders are preserved. The six macOS `.DS_Store`
metadata files are excluded. [file-manifest.csv](file-manifest.csv) records each source path,
repository path, size, and SHA-256 checksum.

## Download the complete files

Binary files are stored with Git LFS. Copy this repository's HTTPS URL from the **Code** menu,
then install Git LFS and run the following commands, replacing `<repository-url>` with that URL:

```sh
git lfs install
git clone <repository-url> qa-portfolio
cd qa-portfolio
git lfs pull
```

For individual files, open the file on GitHub and use its download button.
Source ZIP downloads may contain Git LFS pointers instead of the binary files.

See [publication scope](PUBLICATION.md) for how the originals and curated examples relate.

Prepared from the supplied archive on 16 October 2026.
