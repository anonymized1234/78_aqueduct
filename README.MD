# Rebuttal for “ Aqueduct: In-Memory Data Organization for Rapid and Smooth Elasticity in Key-Value Stores “ (Paper #78), Middleware 26


**1\. Raw Numbers (Baseline Performance)**

[Figure 14 raw performance figure](955.pdf)<!-- {"embed":"true", "preview":"true"} -->

### Figure 14 Baseline Numbers:
| System     | Throughput (baseline) | Median Latency (baseline) | Tail Latency (baseline) |
|------------|-----------------------|---------------------------|-------------------------|
| aqueduct   | 568335.00             | 530.03                    | 12909.52                |
| rocksteady | 444648.00             | 19.23                     | 61.82                   |
| ramcloud   | 458502.00             | 18.81                     | 54.01                   |
| fulva      | 442813.00             | 24.44                     | 60.25                   |

[Figure 15 raw performance figure](5050.pdf)<!-- {"embed":"true", "preview":"true"} -->
### Figure 15 Baseline Numbers:
| System     | Throughput (baseline) | Median Latency (baseline) | Tail Latency (baseline) |
|------------|-----------------------|---------------------------|-------------------------|
| aqueduct   | 369775.00             | 769.26                    | 1104                    |
| rocksteady | 224648.00             | 29.23                     | 61.82                   |
| ramcloud   | 219137.00             | 34.20                     | 52.17                   |
| fulva      | 237449.00             | 31.41                     | 53.88                   |
