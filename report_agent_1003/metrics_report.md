# CWE Comparison Metrics Report

## Overall Metrics

- **Total CVEs**: 6826
- **CVEs in both datasets**: 6152
- **CVEs with at least one CWE match**: 5364 (87.19%)
- **CVEs with exact CWE matches**: 1630 (26.50%)

## Classification Metrics

- **Precision**: 0.4327
- **Recall**: 0.8684
- **F1 Score**: 0.5776
- **Accuracy**: 0.9908

## Confusion Matrix

- **True Positives**: 5364
- **False Positives**: 7034
- **False Negatives**: 813
- **True Negatives**: 840039

## Top 10 Most Frequently Matched CWEs

| CWE ID | Matches | In JSON | In Benchmark | Precision | Recall | F1 Score |
|--------|---------|---------|--------------|-----------|--------|----------|
| CWE-20 | 666 | 868 | 887 | 0.77 | 0.75 | 0.76 |
| CWE-119 | 604 | 914 | 653 | 0.66 | 0.92 | 0.77 |
| CWE-862 | 437 | 637 | 477 | 0.69 | 0.92 | 0.78 |
| CWE-78 | 321 | 645 | 322 | 0.50 | 1.00 | 0.66 |
| CWE-416 | 212 | 365 | 224 | 0.58 | 0.95 | 0.72 |
| CWE-287 | 187 | 326 | 225 | 0.57 | 0.83 | 0.68 |
| CWE-22 | 176 | 253 | 190 | 0.70 | 0.93 | 0.79 |
| CWE-200 | 144 | 434 | 153 | 0.33 | 0.94 | 0.49 |
| CWE-79 | 108 | 275 | 115 | 0.39 | 0.94 | 0.55 |
| CWE-522 | 97 | 153 | 110 | 0.63 | 0.88 | 0.74 |

## Top 10 Least Frequently Matched CWEs

| CWE ID | Matches | In JSON | In Benchmark | Precision | Recall | F1 Score |
|--------|---------|---------|--------------|-----------|--------|----------|
| CWE-754 | 1 | 39 | 5 | 0.03 | 0.20 | 0.05 |
| CWE-662 | 1 | 6 | 9 | 0.17 | 0.11 | 0.13 |
| CWE-909 | 3 | 9 | 7 | 0.33 | 0.43 | 0.38 |
| CWE-404 | 4 | 17 | 8 | 0.24 | 0.50 | 0.32 |
| CWE-665 | 4 | 10 | 5 | 0.40 | 0.80 | 0.53 |
| CWE-610 | 4 | 10 | 6 | 0.40 | 0.67 | 0.50 |
| CWE-426 | 4 | 6 | 8 | 0.67 | 0.50 | 0.57 |
| CWE-331 | 4 | 5 | 5 | 0.80 | 0.80 | 0.80 |
| CWE-444 | 4 | 16 | 6 | 0.25 | 0.67 | 0.36 |
| CWE-565 | 5 | 14 | 5 | 0.36 | 1.00 | 0.53 |

## Top 10 Most Frequent CWEs in JSON Results

| CWE ID | In JSON | In Benchmark | Matches | Precision | Recall |
|--------|---------|--------------|---------|-----------|--------|
| CWE-119 | 914 | 653 | 604 | 0.66 | 0.92 |
| CWE-20 | 868 | 887 | 666 | 0.77 | 0.75 |
| CWE-787 | 826 | 75 | 72 | 0.09 | 0.96 |
| CWE-78 | 645 | 322 | 321 | 0.50 | 1.00 |
| CWE-862 | 637 | 477 | 437 | 0.69 | 0.92 |
| CWE-200 | 434 | 153 | 144 | 0.33 | 0.94 |
| CWE-863 | 433 | 139 | 94 | 0.22 | 0.68 |
| CWE-668 | 369 | 70 | 62 | 0.17 | 0.89 |
| CWE-416 | 365 | 224 | 212 | 0.58 | 0.95 |
| CWE-306 | 346 | 112 | 93 | 0.27 | 0.83 |

## Top 10 Least Frequent CWEs in JSON Results

| CWE ID | In JSON | In Benchmark | Matches | Precision | Recall |
|--------|---------|--------------|---------|-----------|--------|
| CWE-669 | 5 | 0 | 0 | 0.00 | 0.00 |
| CWE-1236 | 5 | 2 | 2 | 0.40 | 1.00 |
| CWE-331 | 5 | 5 | 4 | 0.80 | 0.80 |
| CWE-776 | 5 | 4 | 3 | 0.60 | 0.75 |
| CWE-834 | 5 | 1 | 1 | 0.20 | 1.00 |
| CWE-706 | 6 | 2 | 0 | 0.00 | 0.00 |
| CWE-426 | 6 | 8 | 4 | 0.67 | 0.50 |
| CWE-662 | 6 | 9 | 1 | 0.17 | 0.11 |
| CWE-384 | 7 | 3 | 2 | 0.29 | 0.67 |
| CWE-494 | 8 | 1 | 1 | 0.12 | 1.00 |

## Top 10 Most Frequent CWEs in Benchmark

| CWE ID | In Benchmark | In JSON | Matches | Precision | Recall |
|--------|--------------|---------|---------|-----------|--------|
| CWE-20 | 887 | 868 | 666 | 0.77 | 0.75 |
| CWE-119 | 653 | 914 | 604 | 0.66 | 0.92 |
| CWE-862 | 477 | 637 | 437 | 0.69 | 0.92 |
| CWE-78 | 322 | 645 | 321 | 0.50 | 1.00 |
| CWE-287 | 225 | 326 | 187 | 0.57 | 0.83 |
| CWE-416 | 224 | 365 | 212 | 0.58 | 0.95 |
| CWE-22 | 190 | 253 | 176 | 0.70 | 0.93 |
| CWE-200 | 153 | 434 | 144 | 0.33 | 0.94 |
| CWE-863 | 139 | 433 | 94 | 0.22 | 0.68 |
| CWE-79 | 115 | 275 | 108 | 0.39 | 0.94 |

## Top 10 Least Frequent CWEs in Benchmark

| CWE ID | In Benchmark | In JSON | Matches | Precision | Recall |
|--------|--------------|---------|---------|-----------|--------|
| CWE-565 | 5 | 14 | 5 | 0.36 | 1.00 |
| CWE-613 | 5 | 19 | 5 | 0.26 | 1.00 |
| CWE-407 | 5 | 26 | 5 | 0.19 | 1.00 |
| CWE-665 | 5 | 10 | 4 | 0.40 | 0.80 |
| CWE-754 | 5 | 39 | 1 | 0.03 | 0.20 |
| CWE-331 | 5 | 5 | 4 | 0.80 | 0.80 |
| CWE-552 | 5 | 32 | 5 | 0.16 | 1.00 |
| CWE-835 | 5 | 12 | 5 | 0.42 | 1.00 |
| CWE-276 | 6 | 39 | 5 | 0.13 | 0.83 |
| CWE-610 | 6 | 10 | 4 | 0.40 | 0.67 |

## CVEs With No Matches

| CVE ID | JSON CWEs | Benchmark CWEs |
|--------|-----------|----------------|
| CVE-2021-0214 | CWE-770, CWE-400 | CWE-20 |
| CVE-2021-0313 | CWE-770, CWE-400, CWE-1284 | CWE-20 |
| CVE-2021-0336 | CWE-862 | CWE-732 |
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
| CVE-2021-0964 | CWE-787, CWE-119 | CWE-681 |
| CVE-2021-0978 | CWE-200, CWE-203 | CWE-862 |
| CVE-2021-1053 | CWE-787, CWE-1284 | CWE-20 |
| CVE-2021-1732 | CWE-269 | CWE-787 |
| CVE-2021-21126 | CWE-863 | CWE-20 |
| CVE-2021-21177 | CWE-200 | CWE-732 |
| CVE-2021-21445 | CWE-20, CWE-74, CWE-79 | CWE-444 |

*...and 768 more CVEs with no matches*

## Primary vs Secondary CWE Analysis

- **Total primary CWE matches**: 4745
- **Total secondary CWE matches**: 1195
- **CVEs where only primary CWEs matched**: 4169
- **CVEs where only secondary CWEs matched**: 619
- **CVEs where both primary and secondary CWEs matched**: 576
