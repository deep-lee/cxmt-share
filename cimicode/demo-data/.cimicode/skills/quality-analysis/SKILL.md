---
name: quality-analysis
description: Quality test data analysis and report generation
---

## What I do
When given quality test data (CSV format), I will:
1. Read and understand the data structure
2. Calculate overall pass rates
3. Analyze per-batch and per-product pass rates
4. Identify failure patterns and root causes
5. Generate a formatted quality report

## When to use me
Use this when you have quality test data in CSV format and need automated analysis and reporting.

## Steps
1. First read the CSV file to understand columns and data
2. Calculate pass rate statistics (overall, by batch, by product, by test item)
3. Identify batches with failures and analyze patterns
4. Generate a Markdown report with findings and recommendations
5. Save the report as `quality-report-<date>.md`

## Notes
- Expect columns: 批次号, 产品型号, 测试项, 规格下限, 规格上限, 实测值, 结果, 测试日期
- Results column should contain 通过/不通过
