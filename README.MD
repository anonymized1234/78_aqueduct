# Rebuttal for “ Aqueduct: In-Memory Data Organization for Rapid and Smooth Elasticity in Key-Value Stores “ (Paper #78), Middleware 26


**1\. Raw Numbers**

 **955**
[ycsb_plots.pdf](955.pdf)<!-- {"embed":"true", "preview":"true"} -->

### Baseline Numbers:
| System     | Throughput (baseline) | Median Latency (baseline) | Tail Latency (baseline) |
|------------|-----------------------|---------------------------|-------------------------|
| aqueduct   | 568335.00             | 530.03                    | 12909.52                |
| rocksteady | 444648.00             | 19.23                     | 61.82                   |
| ramcloud   | 458502.00             | 18.81                     | 54.01                   |
| fulva      | 442813.00             | 24.44                     | 60.25                   |

**5050**
[ycsb_plots 2.pdf](Rebuttal%20for%20%E2%80%9C%20Aqueduct%20In-Memory%20Data%20Organization%20for%20Rapid%20and%20Smooth%20Elasticity%20in%20Key-Value%20Stores%20%E2%80%9C%20%28Paper%20%2378%29,%20Middleware%2026/ycsb_plots%202.pdf)<!-- {"embed":"true", "preview":"true"} -->
### Baseline Numbers:
| System     | Throughput (baseline) | Median Latency (baseline) | Tail Latency (baseline) |
|------------|-----------------------|---------------------------|-------------------------|
| aqueduct   | 369775.00             | 769.26                    | 1104                    |
| rocksteady | 224648.00             | 29.23                     | 61.82 (normalized)      |
| ramcloud   | 219137.00             | 34.20                     | 52.17                   |
| fulva      | 237449.00             | 31.41                     | 53.88                   |

**2\. Fair Experiment - 1 thread on the source on thread on the recipient**

**955**
[ycsb_plots 3.pdf](955.pdf)<!-- {"embed":"true", "preview":"true"} -->

**5050**
[5050.pdf](5050.pdf)<!-- {"embed":"true", "preview":"true"} -->
