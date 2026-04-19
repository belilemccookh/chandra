# Full 90-Language Benchmark

This is a comprehensive multilingual evaluation covering 90 languages, comparing Chandra 2 against Gemini 2.5 Flash. The average scores are lower than the [43-language benchmark](README.md#multilingual-benchmark-table) because this includes many lower-resource languages.

## Overall Scores

| | Chandra 2 | Gemini 2.5 Flash |
|---|:---:|:---:|
| **Average** | **72.7% +/- 1.2%** | **60.8% +/- 1.3%** |

## Results by Language

> **Note:** Bold rows indicate languages where Gemini 2.5 Flash outperforms Chandra 2.

<!-- Languages are identified by ISO 639-1 codes. See https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes for reference. -->
<!-- Personal note: languages where Chandra 2 leads by 20%+ points are particularly interesting for low-resource NLP research. -->
<!-- Personal note: languages with a Gap of +30% or more (am, ka, km, kn, lo, ml, my) are worth investigating further - possibly training data differences. -->
<!-- Personal note: lo, ml, my, km all have Gemini scoring under 20% - these might be near-random for Gemini, worth checking raw outputs. -->

| Language | Chandra 2 | Gemini 2.5 Flash | Gap |
|----------|:--------:|:----------------:|:---:|
| af | 80.4% | 85.8% | -5.4% |
| am | 34.4% | 0.5% | +33.9% |
| ar | 68.4% | 84.4% | -16.0% |
| as | 35.8% | 23.1% | +12.7% |
| az | 75.2% | 74.0% | +1.2% |
| be | 80.7% | 66.4% | +14.3% |
| bg | 83.1% | 64.3% | +18.8% |
| bn | 72.8% | 55.3% | +17.5% |
| br | 90.0% | 69.4% | +20.6% |
| bs | 84.8% | 85.1% | -0.3% |
| ca | 85.1% | 88.0% | -2.9% |
| cs | 85.3% | 79.1% | +6.2% |
| cy | 82.2% | 77.6% | +4.6% |
| da | 91.1% | 86.0% | +5.1% |
| de | 94.8% | 88.3% | +6.5% |
| el | 85.6% | 83.5% | +2.1% |
| en | 96.6% | 90.3% | +6.3% |
| eo | 80.1% | 71.9% | +8.2% |
| es | 89.3% | 86.8% | +2.5% |
| et | 75.2% | 73.7% | +1.5% |
| eu | 80.2% | 74.6% | +5.6% |
| fa | 75.1% | 61.8% | +13.3% |
| fi | 83.4% | 86.0% | -2.6% |
| fr | 93.7% | 86.1% | +7.6% |
| fy | 81.2% | 70.1% | +11.1% |
| ga | 80.9% | 70.1% | +10.8% |
| gd | 71.8% | 59.5% | +12.3% |
| gl | 80.9% | 80.9% | 0.0% |
| gu | 70.8% | 47.6% | +23.2% |
| ha | 72.1% | 59.1% | +13.0% |
| he | 70.4% | 50.9% | +19.5% |
| hi | 78.4% | 82.7% | -4.3% |
| hr | 90.1% | 88.2% | +1.9% |
| hu | 82.1% | 84.5% | -2.4% |
| hy | 64.2% | 42.1% | +22.1% |
| id | 91.6% | 88.3% | +3.3% |
| is | 77.3% | 72.2% | +5.1% |
| it | 94.6% | 85.7% | +8.9% |
| ja | 86.9% | 80.0% | +6.9% |
| jv | 73.2% | 80.4% | -7.2% |
| ka | 77.0% | 39.3% | +37.7% |
| kk | 80.5% | 77.2% | +3.3% |
| km | 46.1% | 6.3% | +39.8% |
| kn | 63.2% | 24.5% | +38.7% |
| ko | 81.5% | 84.8% | -3.3% |
| ku | 62.0% | 63.2% | -1.2% |
| ky | 81.2% | 69.8% | +11.4% |
| la | 73.8% | 70.5% | +3.3% |
| lo | 60.9% | 13.3% | +47.6% |
| lt | 79.8% | 70.5% | +9.3% |
| lv | 76.9% | 81.5% | -4.6% |
| mg | 81.2% | 78.4% | +2.8% |
| mk | 83.5% | 77.4% | +6.1% |
| ml | 64.3% | 23.8% | +40.5% |
| mn | 88.4% | 71.4% | +17.0% |
| mr | 75.0% | 69.7% | +5.3% |
| ms | 79.3% | 79.8% | -0.5% |
| my | 55.9% | 15.8% | +40.1% |
| ne | 45.3% | 43.0% | +2.3% |
| nl | 88.6% | 87.5% | +1.1% |
| no | 90.5% | 87.8% | +2.7% |
| or | 31.1% | 11.2% | +19.9% |
