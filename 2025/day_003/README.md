# Day 3 benchmarks

[link to problem](https://adventofcode.com/2025/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 549.6 ± 155.5 | 64.7 | 940.8 | 1.00 |
| whyando | input-whyando | 556.6 ± 165.9 | 0.0 | 1106.0 | 1.01 ± 0.42 |
| mattcl | input-lanjian | 563.0 ± 156.3 | 0.0 | 1193.0 | 1.02 ± 0.41 |
| mattcl | input-mattcl | 563.7 ± 171.2 | 0.0 | 1371.1 | 1.03 ± 0.43 |
| whyando | input-lanjian | 575.1 ± 161.4 | 29.1 | 1177.8 | 1.05 ± 0.42 |
| mattcl | input-whyando | 581.0 ± 142.9 | 0.0 | 941.6 | 1.06 ± 0.40 |
| kcen | input-whyando | 915.5 ± 150.5 | 318.2 | 1354.3 | 1.67 ± 0.54 |
| kcen | input-mattcl | 922.4 ± 135.5 | 439.6 | 1423.5 | 1.68 ± 0.53 |
| kcen | input-lanjian | 960.5 ± 171.0 | 341.1 | 1585.5 | 1.75 ± 0.58 |
| lanjian | input-mattcl | 4107.6 ± 327.6 | 3487.3 | 5293.7 | 7.47 ± 2.20 |
| lanjian | input-whyando | 4117.3 ± 296.3 | 3510.9 | 5119.7 | 7.49 ± 2.19 |
| lanjian | input-lanjian | 4176.8 ± 339.2 | 3479.3 | 5072.0 | 7.60 ± 2.24 |
| mattcl-py | input-mattcl | 21068.8 ± 491.6 | 20200.4 | 23402.8 | 38.33 ± 10.88 |
| mattcl-py | input-lanjian | 21169.7 ± 611.1 | 20125.6 | 24433.9 | 38.52 ± 10.95 |
| mattcl-py | input-whyando | 21541.8 ± 760.6 | 20202.5 | 24826.4 | 39.20 ± 11.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|