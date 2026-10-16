# REDD · QA / Software Tester Portfolio

ผลงานด้าน Software QA ของ **BenzChock** จากการทำงานที่ **REDD** จัดเรียงตามเวอร์ชันของงานเดิม
พอร์ตนี้นำเสนอตัวอย่างการออกแบบกรณีทดสอบ การเปรียบเทียบผลที่คาดหวังกับผลจริง
การทดสอบซ้ำ และการบันทึกข้อบกพร่อง โดยสรุปข้อมูลให้เหมาะกับการเผยแพร่

A version-based collection of selected manual QA work: functional checks, regression scenarios,
payment flows, data consistency, permissions, and timezone testing.

## Browse the work

**13 version folders · 53 selected test examples · 4 historical defect examples**

| Version | Selected focus | Public test examples |
| --- | --- | ---: |
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
    evidence/README.md          # Original-file categories and local retention
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
original executions used synthetic data. No original production dataset is distributed here.

## Public data handling

ไฟล์ต้นฉบับ **585 ไฟล์** จัดแยกประเภทไว้ในเครื่อง โดยคงเวอร์ชันและโครงสร้างบริบทเดิม
ชุด Public นี้เผยแพร่เฉพาะตัวอย่างที่เขียนสรุปใหม่ ไม่มีไฟล์ข้อมูลลูกค้า รายงาน production
ภาพหน้าจอ วิดีโอ เอกสารภายใน ลิงก์งานภายใน หรือไฟล์ Excel ต้นฉบับ

The repository contains curated text examples. Raw spreadsheets, CSV exports, screenshots,
recordings, documents, notes, and internal tools are retained locally and are not uploaded.
See [publication scope](PUBLICATION.md) for the selection and retention approach.

Prepared from the supplied archive on 16 October 2026.
