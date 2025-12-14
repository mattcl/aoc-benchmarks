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
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 301.4 ± 203.6 | 0.0 | 921.7 | 1.00 |
| whyando | input-mattcl | 391.3 ± 173.7 | 0.0 | 975.8 | 1.30 ± 1.05 |
| mattcl | input-whyando | 412.4 ± 198.0 | 0.0 | 1328.3 | 1.37 ± 1.13 |
| whyando | input-whyando | 425.9 ± 166.4 | 0.0 | 962.1 | 1.41 ± 1.10 |
| whyando | input-lanjian | 443.1 ± 148.5 | 0.0 | 976.4 | 1.47 ± 1.11 |
| mattcl | input-lanjian | 446.8 ± 164.8 | 0.0 | 1002.2 | 1.48 ± 1.14 |
| lanjian | input-mattcl | 548.9 ± 254.9 | 0.0 | 1124.9 | 1.82 ± 1.49 |
| lanjian | input-lanjian | 762.5 ± 103.1 | 301.7 | 959.1 | 2.53 ± 1.74 |
| lanjian | input-whyando | 773.0 ± 143.4 | 322.8 | 1242.2 | 2.56 ± 1.80 |
| kcen | input-mattcl | 886.4 ± 152.3 | 409.6 | 1407.1 | 2.94 ± 2.05 |
| kcen | input-whyando | 929.6 ± 144.4 | 141.4 | 1419.4 | 3.08 ± 2.14 |
| kcen | input-lanjian | 970.2 ± 155.0 | 517.4 | 1658.5 | 3.22 ± 2.23 |
| mattcl-py | input-lanjian | 17452.0 ± 581.3 | 16511.3 | 20459.1 | 57.90 ± 39.15 |
| mattcl-py | input-mattcl | 17631.2 ± 823.9 | 16047.1 | 20882.7 | 58.49 ± 39.60 |
| mattcl-py | input-whyando | 17676.1 ± 717.2 | 16329.3 | 20608.4 | 58.64 ± 39.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|