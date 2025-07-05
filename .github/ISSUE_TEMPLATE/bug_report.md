---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

name: 🐞 گزارش خطا
description: گزارش مشکلات و باگ‌های سیستم
title: "[BUG] "
labels: bug
body:
  - type: markdown
    attributes:
      value: |
        **شرح مشکل**
  - type: textarea
    attributes:
      label: "شرح کامل خطا"
      description: "چه اتفاقی افتاده است؟"
    validations:
      required: true
  - type: textarea
    attributes:
      label: "راه تکثیر خطا"
      description: "مراحل تولید خطا را شرح دهید"
