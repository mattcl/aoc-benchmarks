# Day 2 benchmarks

[link to problem](https://adventofcode.com/2025/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 251.9 ± 221.2 | 0.0 | 834.2 | 1.00 |
| whyando | input-mattcl | 418.9 ± 173.1 | 0.0 | 852.5 | 1.66 ± 1.61 |
| whyando | input-whyando | 423.4 ± 181.4 | 0.0 | 982.4 | 1.68 ± 1.64 |
| kcen | input-whyando | 529.6 ± 443.0 | 0.0 | 3667.8 | 2.10 ± 2.55 |
| mattcl | input-whyando | 569.2 ± 207.9 | 0.0 | 1246.7 | 2.26 ± 2.15 |
| lanjian | input-whyando | 579.6 ± 420.4 | 0.0 | 2520.3 | 2.30 ± 2.62 |
| mattcl | input-lanjian | 656.2 ± 145.1 | 217.4 | 1095.7 | 2.60 ± 2.36 |
| mattcl | input-mattcl | 681.2 ± 159.6 | 121.9 | 1040.6 | 2.70 ± 2.46 |
| kcen | input-mattcl | 790.3 ± 194.5 | 0.0 | 1297.2 | 3.14 ± 2.86 |
| kcen | input-lanjian | 849.9 ± 144.4 | 0.0 | 1312.6 | 3.37 ± 3.02 |
| lanjian | input-lanjian | 865.8 ± 160.6 | 56.4 | 1358.0 | 3.44 ± 3.08 |
| lanjian | input-mattcl | 895.9 ± 142.8 | 257.5 | 1618.9 | 3.56 ± 3.17 |
| mattcl-py | input-whyando | 20560.3 ± 655.2 | 19090.3 | 24317.7 | 81.61 ± 71.70 |
| mattcl-py | input-mattcl | 20757.0 ± 605.8 | 19846.4 | 23739.8 | 82.40 ± 72.38 |
| mattcl-py | input-lanjian | 20795.1 ± 646.8 | 19582.5 | 23418.4 | 82.55 ± 72.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|