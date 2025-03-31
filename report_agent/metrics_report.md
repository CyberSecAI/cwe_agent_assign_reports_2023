# CWE Comparison Metrics Report

## Overall Metrics

- **Total CVEs**: 6927
- **CVEs in both datasets**: 5423
- **CVEs with at least one CWE match**: 4631 (85.40%)
- **CVEs with exact CWE matches**: 1014 (18.70%)

## Classification Metrics

- **Precision**: 0.4290
- **Recall**: 0.6133
- **F1 Score**: 0.5049
- **Accuracy**: 0.9969

## Confusion Matrix

- **True Positives**: 5135
- **False Positives**: 6834
- **False Negatives**: 3238
- **True Negatives**: 3219702

## Top 10 Most Frequently Matched CWEs

| CWE ID | Matches | In JSON | In Benchmark | Precision | Recall | F1 Score |
|--------|---------|---------|--------------|-----------|--------|----------|
| CWE-20 | 385 | 605 | 757 | 0.64 | 0.51 | 0.57 |
| CWE-862 | 346 | 492 | 497 | 0.70 | 0.70 | 0.70 |
| CWE-78 | 333 | 522 | 412 | 0.64 | 0.81 | 0.71 |
| CWE-416 | 235 | 299 | 297 | 0.79 | 0.79 | 0.79 |
| CWE-787 | 197 | 660 | 266 | 0.30 | 0.74 | 0.43 |
| CWE-122 | 189 | 217 | 328 | 0.87 | 0.58 | 0.69 |
| CWE-121 | 170 | 241 | 253 | 0.71 | 0.67 | 0.69 |
| CWE-284 | 163 | 283 | 300 | 0.58 | 0.54 | 0.56 |
| CWE-79 | 151 | 212 | 212 | 0.71 | 0.71 | 0.71 |
| CWE-352 | 85 | 107 | 113 | 0.79 | 0.75 | 0.77 |

## Top 10 Least Frequently Matched CWEs

| CWE ID | Matches | In JSON | In Benchmark | Precision | Recall | F1 Score |
|--------|---------|---------|--------------|-----------|--------|----------|
| CWE-356 | 1 | 5 | 5 | 0.20 | 0.20 | 0.20 |
| CWE-124 | 1 | 6 | 5 | 0.17 | 0.20 | 0.18 |
| CWE-909 | 2 | 6 | 5 | 0.33 | 0.40 | 0.36 |
| CWE-552 | 2 | 17 | 5 | 0.12 | 0.40 | 0.18 |
| CWE-312 | 2 | 50 | 6 | 0.04 | 0.33 | 0.07 |
| CWE-274 | 2 | 15 | 6 | 0.13 | 0.33 | 0.19 |
| CWE-280 | 2 | 55 | 7 | 0.04 | 0.29 | 0.06 |
| CWE-1286 | 2 | 24 | 10 | 0.08 | 0.20 | 0.12 |
| CWE-366 | 2 | 11 | 13 | 0.18 | 0.15 | 0.17 |
| CWE-378 | 2 | 9 | 6 | 0.22 | 0.33 | 0.27 |

## Top 10 Most Frequent CWEs in JSON Results

| CWE ID | In JSON | In Benchmark | Matches | Precision | Recall |
|--------|---------|--------------|---------|-----------|--------|
| CWE-787 | 660 | 266 | 197 | 0.30 | 0.74 |
| CWE-20 | 605 | 757 | 385 | 0.64 | 0.51 |
| CWE-78 | 522 | 412 | 333 | 0.64 | 0.81 |
| CWE-862 | 492 | 497 | 346 | 0.70 | 0.70 |
| CWE-119 | 388 | 108 | 51 | 0.13 | 0.47 |
| CWE-863 | 332 | 148 | 71 | 0.21 | 0.48 |
| CWE-416 | 299 | 297 | 235 | 0.79 | 0.79 |
| CWE-284 | 283 | 300 | 163 | 0.58 | 0.54 |
| CWE-121 | 241 | 253 | 170 | 0.71 | 0.67 |
| CWE-306 | 238 | 93 | 64 | 0.27 | 0.69 |

## Top 10 Least Frequent CWEs in JSON Results

| CWE ID | In JSON | In Benchmark | Matches | Precision | Recall |
|--------|---------|--------------|---------|-----------|--------|
| CWE-526 | 5 | 2 | 2 | 0.40 | 1.00 |
| CWE-356 | 5 | 5 | 1 | 0.20 | 0.20 |
| CWE-1007 | 5 | 3 | 3 | 0.60 | 1.00 |
| CWE-441 | 5 | 3 | 2 | 0.40 | 0.67 |
| CWE-41 | 5 | 2 | 0 | 0.00 | 0.00 |
| CWE-749 | 5 | 4 | 1 | 0.20 | 0.25 |
| CWE-943 | 5 | 5 | 3 | 0.60 | 0.60 |
| CWE-233 | 5 | 4 | 4 | 0.80 | 1.00 |
| CWE-489 | 5 | 5 | 3 | 0.60 | 0.60 |
| CWE-214 | 5 | 5 | 3 | 0.60 | 0.60 |

## Top 10 Most Frequent CWEs in Benchmark

| CWE ID | In Benchmark | In JSON | Matches | Precision | Recall |
|--------|--------------|---------|---------|-----------|--------|
| CWE-20 | 757 | 605 | 385 | 0.64 | 0.51 |
| CWE-862 | 497 | 492 | 346 | 0.70 | 0.70 |
| CWE-78 | 412 | 522 | 333 | 0.64 | 0.81 |
| CWE-122 | 328 | 217 | 189 | 0.87 | 0.58 |
| CWE-284 | 300 | 283 | 163 | 0.58 | 0.54 |
| CWE-416 | 297 | 299 | 235 | 0.79 | 0.79 |
| CWE-787 | 266 | 660 | 197 | 0.30 | 0.74 |
| CWE-121 | 253 | 241 | 170 | 0.71 | 0.67 |
| CWE-79 | 212 | 212 | 151 | 0.71 | 0.71 |
| CWE-863 | 148 | 332 | 71 | 0.21 | 0.48 |

## Top 10 Least Frequent CWEs in Benchmark

| CWE ID | In Benchmark | In JSON | Matches | Precision | Recall |
|--------|--------------|---------|---------|-----------|--------|
| CWE-909 | 5 | 6 | 2 | 0.33 | 0.40 |
| CWE-552 | 5 | 17 | 2 | 0.12 | 0.40 |
| CWE-602 | 5 | 6 | 3 | 0.50 | 0.60 |
| CWE-303 | 5 | 14 | 4 | 0.29 | 0.80 |
| CWE-1220 | 5 | 23 | 4 | 0.17 | 0.80 |
| CWE-337 | 5 | 8 | 5 | 0.62 | 1.00 |
| CWE-356 | 5 | 5 | 1 | 0.20 | 0.20 |
| CWE-124 | 5 | 6 | 1 | 0.17 | 0.20 |
| CWE-1394 | 5 | 7 | 4 | 0.57 | 0.80 |
| CWE-613 | 5 | 15 | 4 | 0.27 | 0.80 |

## CVEs With No Matches

| CVE ID | JSON CWEs | Benchmark CWEs |
|--------|-----------|----------------|
| CVE-2021-0070 | CWE-1284 | CWE-20 |
| CVE-2021-0267 | CWE-400, CWE-1286 | CWE-20 |
| CVE-2021-0313 | CWE-400, CWE-1284, CWE-770 | CWE-20 |
| CVE-2021-0336 | CWE-285, CWE-862, CWE-925 | CWE-732 |
| CVE-2021-0418 | CWE-1284, CWE-770 | CWE-20 |
| CVE-2021-0928 | CWE-248 | CWE-20, CWE-755 |
| CVE-2021-1053 | CWE-1284, CWE-787 | CWE-20 |
| CVE-2021-1060 | CWE-20, CWE-1284 | CWE-1285 |
| CVE-2021-1957 | CWE-269, CWE-413 | CWE-284 |
| CVE-2021-20260 | CWE-522, CWE-256, CWE-200 | CWE-201 |
| CVE-2021-21126 | CWE-451, CWE-942, CWE-358 | CWE-20 |
| CVE-2021-21177 | CWE-358, CWE-200 | CWE-732 |
| CVE-2021-21472 | CWE-22, CWE-1393 | CWE-306 |
| CVE-2021-21793 | CWE-131, CWE-787 | CWE-122 |
| CVE-2021-22482 | CWE-457 | CWE-456 |
| CVE-2021-23484 | CWE-23, CWE-59 | CWE-22 |
| CVE-2021-23937 | CWE-20, CWE-441 | CWE-201 |
| CVE-2021-24917 | CWE-807, CWE-425, CWE-306 | CWE-863 |
| CVE-2021-25326 | CWE-522, CWE-284, CWE-306 | CWE-79, CWE-352 |
| CVE-2021-25517 | CWE-1284, CWE-1285 | CWE-20 |

*...and 772 more CVEs with no matches*

## Primary vs Secondary CWE Analysis

- **Total primary CWE matches**: 4402
- **Total secondary CWE matches**: 733
- **CVEs where only primary CWEs matched**: 3910
- **CVEs where only secondary CWEs matched**: 498
- **CVEs where both primary and secondary CWEs matched**: 223
