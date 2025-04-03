# CWE Comparison Metrics Report

## Overall Metrics

- **Total CVEs**: 6825
- **CVEs in both datasets**: 6825
- **CVEs with at least one CWE match**: 5437 (79.66%)
- **CVEs with exact CWE matches**: 5437 (79.66%)

## Classification Metrics

- **Precision**: 0.7966
- **Recall**: 0.6493
- **F1 Score**: 0.7155
- **Accuracy**: 0.9993

## Confusion Matrix

- **True Positives**: 5437
- **False Positives**: 1388
- **False Negatives**: 2936
- **True Negatives**: 6501289

## Top 10 Most Frequently Matched CWEs

| CWE ID | Matches | In JSON | In Benchmark | Precision | Recall | F1 Score |
|--------|---------|---------|--------------|-----------|--------|----------|
| CWE-862 | 434 | 434 | 497 | 1.00 | 0.87 | 0.93 |
| CWE-20 | 427 | 427 | 757 | 1.00 | 0.56 | 0.72 |
| CWE-78 | 313 | 313 | 412 | 1.00 | 0.76 | 0.86 |
| CWE-284 | 289 | 289 | 300 | 1.00 | 0.96 | 0.98 |
| CWE-122 | 211 | 211 | 328 | 1.00 | 0.64 | 0.78 |
| CWE-121 | 176 | 176 | 253 | 1.00 | 0.70 | 0.82 |
| CWE-416 | 168 | 168 | 297 | 1.00 | 0.57 | 0.72 |
| CWE-863 | 123 | 123 | 148 | 1.00 | 0.83 | 0.91 |
| CWE-79 | 100 | 100 | 212 | 1.00 | 0.47 | 0.64 |
| CWE-77 | 99 | 99 | 120 | 1.00 | 0.82 | 0.90 |

## Top 10 Least Frequently Matched CWEs

| CWE ID | Matches | In JSON | In Benchmark | Precision | Recall | F1 Score |
|--------|---------|---------|--------------|-----------|--------|----------|
| CWE-908 | 5 | 5 | 19 | 1.00 | 0.26 | 0.42 |
| CWE-90 | 5 | 5 | 5 | 1.00 | 1.00 | 1.00 |
| CWE-1286 | 5 | 5 | 10 | 1.00 | 0.50 | 0.67 |
| CWE-356 | 5 | 5 | 5 | 1.00 | 1.00 | 1.00 |
| CWE-24 | 5 | 5 | 7 | 1.00 | 0.71 | 0.83 |
| CWE-212 | 5 | 5 | 15 | 1.00 | 0.33 | 0.50 |
| CWE-407 | 5 | 5 | 6 | 1.00 | 0.83 | 0.91 |
| CWE-703 | 5 | 5 | 7 | 1.00 | 0.71 | 0.83 |
| CWE-338 | 5 | 5 | 8 | 1.00 | 0.62 | 0.77 |
| CWE-1386 | 5 | 5 | 6 | 1.00 | 0.83 | 0.91 |

## Top 10 Most Frequent CWEs in JSON Results

| CWE ID | In JSON | In Benchmark | Matches | Precision | Recall |
|--------|---------|--------------|---------|-----------|--------|
| CWE-862 | 434 | 497 | 434 | 1.00 | 0.87 |
| CWE-20 | 427 | 757 | 427 | 1.00 | 0.56 |
| CWE-78 | 313 | 412 | 313 | 1.00 | 0.76 |
| CWE-284 | 289 | 300 | 289 | 1.00 | 0.96 |
| CWE-122 | 211 | 328 | 211 | 1.00 | 0.64 |
| CWE-121 | 176 | 253 | 176 | 1.00 | 0.70 |
| CWE-416 | 168 | 297 | 168 | 1.00 | 0.57 |
| CWE-863 | 123 | 148 | 123 | 1.00 | 0.83 |
| CWE-79 | 100 | 212 | 100 | 1.00 | 0.47 |
| CWE-77 | 99 | 120 | 99 | 1.00 | 0.82 |

## Top 10 Least Frequent CWEs in JSON Results

| CWE ID | In JSON | In Benchmark | Matches | Precision | Recall |
|--------|---------|--------------|---------|-----------|--------|
| CWE-908 | 5 | 19 | 5 | 1.00 | 0.26 |
| CWE-476;CWE-252 | 5 | 0 | 0 | 0.00 | 0.00 |
| CWE-90 | 5 | 5 | 5 | 1.00 | 1.00 |
| CWE-352;CWE-79;CWE-116 | 5 | 0 | 0 | 0.00 | 0.00 |
| CWE-1286 | 5 | 10 | 5 | 1.00 | 0.50 |
| CWE-356 | 5 | 5 | 5 | 1.00 | 1.00 |
| CWE-24 | 5 | 7 | 5 | 1.00 | 0.71 |
| CWE-790;CWE-94 | 5 | 0 | 0 | 0.00 | 0.00 |
| CWE-212 | 5 | 15 | 5 | 1.00 | 0.33 |
| CWE-407 | 5 | 6 | 5 | 1.00 | 0.83 |

## Top 10 Most Frequent CWEs in Benchmark

| CWE ID | In Benchmark | In JSON | Matches | Precision | Recall |
|--------|--------------|---------|---------|-----------|--------|
| CWE-20 | 757 | 427 | 427 | 1.00 | 0.56 |
| CWE-862 | 497 | 434 | 434 | 1.00 | 0.87 |
| CWE-78 | 412 | 313 | 313 | 1.00 | 0.76 |
| CWE-122 | 328 | 211 | 211 | 1.00 | 0.64 |
| CWE-284 | 300 | 289 | 289 | 1.00 | 0.96 |
| CWE-416 | 297 | 168 | 168 | 1.00 | 0.57 |
| CWE-787 | 266 | 65 | 65 | 1.00 | 0.24 |
| CWE-121 | 253 | 176 | 176 | 1.00 | 0.70 |
| CWE-79 | 212 | 100 | 100 | 1.00 | 0.47 |
| CWE-863 | 148 | 123 | 123 | 1.00 | 0.83 |

## Top 10 Least Frequent CWEs in Benchmark

| CWE ID | In Benchmark | In JSON | Matches | Precision | Recall |
|--------|--------------|---------|---------|-----------|--------|
| CWE-90 | 5 | 5 | 5 | 1.00 | 1.00 |
| CWE-356 | 5 | 5 | 5 | 1.00 | 1.00 |
| CWE-158 | 5 | 1 | 1 | 1.00 | 0.20 |
| CWE-124 | 5 | 4 | 4 | 1.00 | 0.80 |
| CWE-552 | 5 | 3 | 3 | 1.00 | 0.60 |
| CWE-514 | 5 | 5 | 5 | 1.00 | 1.00 |
| CWE-613 | 5 | 4 | 4 | 1.00 | 0.80 |
| CWE-214 | 5 | 3 | 3 | 1.00 | 0.60 |
| CWE-909 | 5 | 2 | 2 | 1.00 | 0.40 |
| CWE-602 | 5 | 4 | 4 | 1.00 | 0.80 |

## CVEs With No Matches

| CVE ID | JSON CWEs | Benchmark CWEs |
|--------|-----------|----------------|
| CVE-2021-0417 | CWE-330;CWE-20 | CWE-20, CWE-330 |
| CVE-2021-0511 | CWE-687;CWE-20 | CWE-687, CWE-20 |
| CVE-2021-0600 | CWE-1287;CWE-79 | CWE-79, CWE-1287 |
| CVE-2021-0674 | CWE-125;CWE-20 | CWE-125, CWE-20 |
| CVE-2021-0676 | CWE-125;CWE-20 | CWE-125, CWE-20 |
| CVE-2021-0677 | CWE-190;CWE-125 | CWE-125, CWE-190 |
| CVE-2021-0678 | CWE-787;CWE-20 | CWE-20, CWE-787 |
| CVE-2021-0895 | CWE-787;CWE-20 | CWE-20, CWE-787 |
| CVE-2021-0896 | CWE-787;CWE-20 | CWE-20, CWE-787 |
| CVE-2021-0900 | CWE-125;CWE-20 | CWE-125, CWE-20 |
| CVE-2021-0902 | CWE-125;CWE-20 | CWE-125, CWE-20 |
| CVE-2021-0903 | CWE-787;CWE-20 | CWE-20, CWE-787 |
| CVE-2021-0928 | CWE-755;CWE-20 | CWE-20, CWE-755 |
| CVE-2021-0933 | CWE-116;CWE-20 | CWE-20, CWE-116 |
| CVE-2021-0934 | CWE-1284;CWE-770 | CWE-1284, CWE-770 |
| CVE-2021-0943 | CWE-787;CWE-20 | CWE-20, CWE-787 |
| CVE-2021-0946 | CWE-909;CWE-908 | CWE-909, CWE-908 |
| CVE-2021-0947 | CWE-909;CWE-908 | CWE-909, CWE-908 |
| CVE-2021-0955 | CWE-416;CWE-362 | CWE-362, CWE-416 |
| CVE-2021-0964 | CWE-681;CWE-122 | CWE-681, CWE-122 |

*...and 1368 more CVEs with no matches*

## Primary vs Secondary CWE Analysis

- **Total primary CWE matches**: 5437
- **Total secondary CWE matches**: 0
- **CVEs where only primary CWEs matched**: 5437
- **CVEs where only secondary CWEs matched**: 0
- **CVEs where both primary and secondary CWEs matched**: 0
