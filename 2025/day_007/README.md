# Day 7 benchmarks

[link to problem](https://adventofcode.com/2025/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 394.6 ± 142.4 | 0.0 | 643.9 | 1.00 |
| mattcl | input-mattcl | 400.9 ± 175.9 | 0.0 | 1025.4 | 1.02 ± 0.58 |
| whyando | input-whyando | 410.0 ± 152.8 | 0.0 | 973.1 | 1.04 ± 0.54 |
| whyando | input-mattcl | 416.3 ± 154.6 | 0.0 | 886.5 | 1.05 ± 0.55 |
| mattcl | input-whyando | 417.5 ± 180.2 | 0.0 | 984.8 | 1.06 ± 0.60 |
| mattcl | input-lanjian | 426.6 ± 157.8 | 0.0 | 1019.1 | 1.08 ± 0.56 |
| kcen | input-lanjian | 875.7 ± 168.3 | 0.0 | 1461.7 | 2.22 ± 0.91 |
| kcen | input-mattcl | 893.8 ± 149.7 | 0.0 | 1340.8 | 2.26 ± 0.90 |
| kcen | input-whyando | 941.8 ± 146.5 | 383.5 | 1475.5 | 2.39 ± 0.94 |
| mattcl-py | input-mattcl | 17385.1 ± 554.5 | 16381.3 | 21257.3 | 44.05 ± 15.96 |
| mattcl-py | input-lanjian | 17399.3 ± 628.9 | 16301.5 | 20855.7 | 44.09 ± 15.99 |
| mattcl-py | input-whyando | 17476.9 ± 702.8 | 16399.9 | 20625.1 | 44.29 ± 16.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|