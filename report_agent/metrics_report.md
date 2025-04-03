# CWE Comparison Metrics Report

## Overall Metrics

- **Total CVEs**: 6954
- **CVEs in both datasets**: 6938
- **CVEs with at least one CWE match**: 5656 (81.52%)
- **CVEs with exact CWE matches**: 938 (13.52%)

## Classification Metrics

- **Precision**: 0.3735
- **Recall**: 0.8145
- **F1 Score**: 0.5122
- **Accuracy**: 0.9967

## Confusion Matrix

- **True Positives**: 5656
- **False Positives**: 9487
- **False Negatives**: 1288
- **True Negatives**: 3210225

## Top 10 Most Frequently Matched CWEs

| CWE ID | Matches | In JSON | In Benchmark | Precision | Recall | F1 Score |
|--------|---------|---------|--------------|-----------|--------|----------|
| CWE-20 | 527 | 791 | 755 | 0.67 | 0.70 | 0.68 |
| CWE-862 | 435 | 636 | 475 | 0.68 | 0.92 | 0.78 |
| CWE-78 | 321 | 645 | 322 | 0.50 | 1.00 | 0.66 |
| CWE-416 | 212 | 365 | 224 | 0.58 | 0.95 | 0.72 |
| CWE-284 | 210 | 377 | 297 | 0.56 | 0.71 | 0.62 |
| CWE-121 | 205 | 316 | 213 | 0.65 | 0.96 | 0.78 |
| CWE-122 | 198 | 270 | 221 | 0.73 | 0.90 | 0.81 |
| CWE-79 | 99 | 274 | 106 | 0.36 | 0.93 | 0.52 |
| CWE-36 | 92 | 93 | 94 | 0.99 | 0.98 | 0.98 |
| CWE-863 | 91 | 423 | 137 | 0.22 | 0.66 | 0.33 |

## Top 10 Least Frequently Matched CWEs

| CWE ID | Matches | In JSON | In Benchmark | Precision | Recall | F1 Score |
|--------|---------|---------|--------------|-----------|--------|----------|
| CWE-213 | 0 | 5 | 7 | 0.00 | 0.00 | 0.00 |
| CWE-138 | 2 | 7 | 60 | 0.29 | 0.03 | 0.06 |
| CWE-305 | 2 | 21 | 5 | 0.10 | 0.40 | 0.15 |
| CWE-366 | 2 | 14 | 12 | 0.14 | 0.17 | 0.15 |
| CWE-274 | 2 | 20 | 6 | 0.10 | 0.33 | 0.15 |
| CWE-356 | 2 | 8 | 5 | 0.25 | 0.40 | 0.31 |
| CWE-1391 | 3 | 17 | 9 | 0.18 | 0.33 | 0.23 |
| CWE-602 | 3 | 6 | 5 | 0.50 | 0.60 | 0.55 |
| CWE-909 | 3 | 8 | 5 | 0.38 | 0.60 | 0.46 |
| CWE-444 | 4 | 16 | 6 | 0.25 | 0.67 | 0.36 |

## Top 10 Most Frequent CWEs in JSON Results

| CWE ID | In JSON | In Benchmark | Matches | Precision | Recall |
|--------|---------|--------------|---------|-----------|--------|
| CWE-787 | 818 | 74 | 70 | 0.09 | 0.95 |
| CWE-20 | 791 | 755 | 527 | 0.67 | 0.70 |
| CWE-78 | 645 | 322 | 321 | 0.50 | 1.00 |
| CWE-862 | 636 | 475 | 435 | 0.68 | 0.92 |
| CWE-119 | 490 | 77 | 55 | 0.11 | 0.71 |
| CWE-863 | 423 | 137 | 91 | 0.22 | 0.66 |
| CWE-284 | 377 | 297 | 210 | 0.56 | 0.71 |
| CWE-416 | 365 | 224 | 212 | 0.58 | 0.95 |
| CWE-121 | 316 | 213 | 205 | 0.65 | 0.96 |
| CWE-400 | 315 | 81 | 79 | 0.25 | 0.98 |

## Top 10 Least Frequent CWEs in JSON Results

| CWE ID | In JSON | In Benchmark | Matches | Precision | Recall |
|--------|---------|--------------|---------|-----------|--------|
| CWE-213 | 5 | 7 | 0 | 0.00 | 0.00 |
| CWE-778 | 5 | 2 | 2 | 0.40 | 1.00 |
| CWE-331 | 5 | 5 | 4 | 0.80 | 0.80 |
| CWE-1236 | 5 | 2 | 2 | 0.40 | 1.00 |
| CWE-648 | 5 | 4 | 4 | 0.80 | 1.00 |
| CWE-610 | 5 | 3 | 2 | 0.40 | 0.67 |
| CWE-1007 | 5 | 2 | 2 | 0.40 | 1.00 |
| CWE-834 | 5 | 1 | 1 | 0.20 | 1.00 |
| CWE-776 | 5 | 4 | 3 | 0.60 | 0.75 |
| CWE-506 | 5 | 4 | 4 | 0.80 | 1.00 |

## Top 10 Most Frequent CWEs in Benchmark

| CWE ID | In Benchmark | In JSON | Matches | Precision | Recall |
|--------|--------------|---------|---------|-----------|--------|
| CWE-20 | 755 | 791 | 527 | 0.67 | 0.70 |
| CWE-862 | 475 | 636 | 435 | 0.68 | 0.92 |
| CWE-78 | 322 | 645 | 321 | 0.50 | 1.00 |
| CWE-284 | 297 | 377 | 210 | 0.56 | 0.71 |
| CWE-416 | 224 | 365 | 212 | 0.58 | 0.95 |
| CWE-122 | 221 | 270 | 198 | 0.73 | 0.90 |
| CWE-121 | 213 | 316 | 205 | 0.65 | 0.96 |
| CWE-863 | 137 | 423 | 91 | 0.22 | 0.66 |
| CWE-79 | 106 | 274 | 99 | 0.36 | 0.93 |
| CWE-287 | 101 | 199 | 81 | 0.41 | 0.80 |

## Top 10 Least Frequent CWEs in Benchmark

| CWE ID | In Benchmark | In JSON | Matches | Precision | Recall |
|--------|--------------|---------|---------|-----------|--------|
| CWE-497 | 5 | 36 | 5 | 0.14 | 1.00 |
| CWE-305 | 5 | 21 | 2 | 0.10 | 0.40 |
| CWE-312 | 5 | 71 | 5 | 0.07 | 1.00 |
| CWE-459 | 5 | 6 | 4 | 0.67 | 0.80 |
| CWE-359 | 5 | 36 | 4 | 0.11 | 0.80 |
| CWE-805 | 5 | 17 | 4 | 0.24 | 0.80 |
| CWE-1394 | 5 | 9 | 5 | 0.56 | 1.00 |
| CWE-303 | 5 | 15 | 5 | 0.33 | 1.00 |
| CWE-158 | 5 | 3 | 3 | 1.00 | 0.60 |
| CWE-696 | 5 | 2 | 2 | 1.00 | 0.40 |

## CVEs With No Matches

| CVE ID | JSON CWEs | Benchmark CWEs |
|--------|-----------|----------------|
| CVE-2021-0214 | CWE-770, CWE-400 | CWE-20 |
| CVE-2021-0267 | CWE-400, CWE-1286 | CWE-20 |
| CVE-2021-0313 | CWE-770, CWE-1284, CWE-400 | CWE-20 |
| CVE-2021-0336 | CWE-925, CWE-285, CWE-862 | CWE-732 |
| CVE-2021-0418 | CWE-770, CWE-1284 | CWE-20 |
| CVE-2021-0674 | CWE-125, CWE-1284 | CWE-20 |
| CVE-2021-0676 | CWE-125, CWE-1284 | CWE-20 |
| CVE-2021-0678 | CWE-787, CWE-119 | CWE-20 |
| CVE-2021-0895 | CWE-787, CWE-119, CWE-1284 | CWE-20 |
| CVE-2021-0896 | CWE-787, CWE-119, CWE-1284 | CWE-20 |
| CVE-2021-0900 | CWE-125, CWE-1284 | CWE-20 |
| CVE-2021-0902 | CWE-125, CWE-1284 | CWE-20 |
| CVE-2021-0903 | CWE-787 | CWE-20 |
| CVE-2021-0934 | CWE-770, CWE-400 | CWE-1284 |
| CVE-2021-0964 | CWE-122, CWE-787 | CWE-681 |
| CVE-2021-0978 | CWE-203, CWE-200 | CWE-862 |
| CVE-2021-1053 | CWE-787, CWE-1284 | CWE-20 |
| CVE-2021-1060 | CWE-20, CWE-1284 | CWE-1285 |
| CVE-2021-1647 | CWE-668, CWE-74, CWE-41, CWE-138, CWE-184, CWE-22, CWE-807, CWE-131, CWE-73, CWE-1289, CWE-88, CWE-23 | CWE-1285 |
| CVE-2021-1675 | CWE-787, CWE-20 | CWE-285 |

*...and 1262 more CVEs with no matches*

## Primary vs Secondary CWE Analysis

- **Total primary CWE matches**: 4874
- **Total secondary CWE matches**: 782
- **CVEs where only primary CWEs matched**: 4874
- **CVEs where only secondary CWEs matched**: 782
- **CVEs where both primary and secondary CWEs matched**: 0
