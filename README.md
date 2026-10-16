# REDD · QA / Software Tester Portfolio

ผลงานด้าน Software QA ของ **BenzChock** จากการทำงานที่ **REDD** จัดเรียงตามเวอร์ชันของงานเดิม
พอร์ตนี้นำเสนอตัวอย่างการออกแบบกรณีทดสอบ การเปรียบเทียบผลที่คาดหวังกับผลจริง
การทดสอบซ้ำ และการบันทึกข้อบกพร่อง โดยสรุปข้อมูลให้เหมาะกับการเผยแพร่

A version-based collection of selected manual QA work: functional checks, regression scenarios,
payment flows, data consistency, permissions, and timezone testing.

## Release documentation

เพิ่มเอกสาร Release จาก Scribehow ช่วง **3.26.6–3.26.19** ครบ **13 ฉบับ** พร้อมภาพ **74 ภาพ**
PDF แยกฉบับอยู่ใต้เวอร์ชันนั้น และมี PDF รวม **67 หน้า** พร้อมสารบัญและบุ๊กมาร์ก

- [สารบัญ Release และ PDF แยกฉบับ](release-notes/README.md)
- [เปิด PDF รวม](release-notes/REDD-Release-3.26.6-to-3.26.19-Combined.pdf)
- [ดาวน์โหลด ZIP ทั้งชุด](release-notes/REDD-Release-PDFs-3.26.6-to-3.26.19.zip)

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

ไฟล์ต้นฉบับครบ **585 ไฟล์** อยู่ใน repo นี้แล้ว โดยแยกประเภทภายใต้เวอร์ชันเดิม
มีภาพ **447 ไฟล์** วิดีโอ **71 ไฟล์** Excel **34 ไฟล์** CSV **26 ไฟล์** PDF **3 ไฟล์**
TXT **2 ไฟล์** และ HTML **2 ไฟล์** เนื้อหาไฟล์ต้นฉบับไม่ได้ปิดหรือแก้ไขข้อมูล

Original filenames and nested test-case folders are preserved. The six macOS `.DS_Store`
metadata files are excluded. [file-manifest.csv](file-manifest.csv) records each source path,
repository path, size, and SHA-256 checksum.

## Download the complete files

Binary files are stored with Git LFS. To download their full contents, install Git LFS and run:

```sh
git lfs install
git clone https://github.com/BenzChock/redd-qa-portfolio.git
cd redd-qa-portfolio
git lfs pull
```

For individual files, open the file on GitHub and use its download button.
Source ZIP downloads may contain Git LFS pointers instead of the binary files.

See [publication scope](PUBLICATION.md) for how the originals and curated examples relate.

Prepared from the supplied archive on 16 October 2026.
