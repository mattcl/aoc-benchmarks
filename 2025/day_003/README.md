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
| whyando | input-whyando | 520.8 ± 167.3 | 0.0 | 994.0 | 1.00 |
| mattcl | input-lanjian | 527.5 ± 167.5 | 0.0 | 1025.9 | 1.01 ± 0.46 |
| whyando | input-lanjian | 537.1 ± 165.8 | 0.0 | 1120.2 | 1.03 ± 0.46 |
| whyando | input-mattcl | 540.6 ± 148.4 | 0.0 | 1009.4 | 1.04 ± 0.44 |
| mattcl | input-mattcl | 541.2 ± 152.3 | 0.0 | 923.5 | 1.04 ± 0.44 |
| mattcl | input-whyando | 544.2 ± 143.3 | 7.4 | 946.2 | 1.04 ± 0.43 |
| kcen | input-lanjian | 895.9 ± 196.3 | 0.0 | 1461.0 | 1.72 ± 0.67 |
| kcen | input-mattcl | 928.3 ± 109.6 | 511.3 | 1441.1 | 1.78 ± 0.61 |
| kcen | input-whyando | 949.9 ± 172.9 | 263.7 | 1539.7 | 1.82 ± 0.67 |
| lanjian | input-mattcl | 8593.3 ± 60.1 | 8469.7 | 8803.4 | 16.50 ± 5.30 |
| lanjian | input-whyando | 8594.8 ± 83.7 | 8424.9 | 8922.1 | 16.50 ± 5.30 |
| lanjian | input-lanjian | 8603.8 ± 107.5 | 8447.3 | 9569.8 | 16.52 ± 5.31 |
| mattcl-py | input-lanjian | 21198.5 ± 691.9 | 20154.2 | 24595.5 | 40.70 ± 13.14 |
| mattcl-py | input-whyando | 21291.5 ± 711.3 | 20055.4 | 24680.0 | 40.88 ± 13.20 |
| mattcl-py | input-mattcl | 21340.9 ± 762.0 | 19946.5 | 24940.1 | 40.97 ± 13.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|