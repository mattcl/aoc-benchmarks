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
| whyando | input-whyando | 378.6 ± 177.2 | 0.0 | 857.4 | 1.00 |
| whyando | input-mattcl | 392.4 ± 168.4 | 0.0 | 618.3 | 1.04 ± 0.66 |
| whyando | input-lanjian | 397.6 ± 165.7 | 0.0 | 992.0 | 1.05 ± 0.66 |
| mattcl | input-whyando | 657.8 ± 184.5 | 0.0 | 1288.0 | 1.74 ± 0.95 |
| lanjian | input-lanjian | 679.9 ± 153.6 | 0.0 | 1170.9 | 1.80 ± 0.93 |
| lanjian | input-mattcl | 685.1 ± 169.9 | 0.0 | 1276.7 | 1.81 ± 0.96 |
| mattcl | input-lanjian | 689.5 ± 218.5 | 79.6 | 2529.2 | 1.82 ± 1.03 |
| mattcl | input-mattcl | 694.9 ± 153.5 | 166.1 | 1187.6 | 1.84 ± 0.95 |
| lanjian | input-whyando | 709.8 ± 173.1 | 0.0 | 1196.4 | 1.87 ± 0.99 |
| kcen | input-whyando | 786.1 ± 127.0 | 32.4 | 1341.4 | 2.08 ± 1.03 |
| kcen | input-mattcl | 813.2 ± 189.5 | 0.0 | 1554.3 | 2.15 ± 1.12 |
| kcen | input-lanjian | 852.7 ± 206.1 | 80.2 | 1585.1 | 2.25 ± 1.19 |
| mattcl-py | input-whyando | 20528.2 ± 595.4 | 19159.3 | 23052.2 | 54.22 ± 25.42 |
| mattcl-py | input-lanjian | 20676.3 ± 608.4 | 19612.5 | 23773.1 | 54.61 ± 25.60 |
| mattcl-py | input-mattcl | 20805.2 ± 582.7 | 19710.5 | 23692.9 | 54.95 ± 25.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|