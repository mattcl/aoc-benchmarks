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
| whyando | input-mattcl | 330.1 ± 153.7 | 0.0 | 854.0 | 1.00 |
| whyando | input-whyando | 335.5 ± 175.2 | 0.0 | 1075.6 | 1.02 ± 0.71 |
| whyando | input-lanjian | 353.4 ± 154.2 | 0.0 | 981.4 | 1.07 ± 0.68 |
| mattcl | input-mattcl | 383.2 ± 162.5 | 0.0 | 1124.4 | 1.16 ± 0.73 |
| mattcl | input-lanjian | 385.6 ± 159.5 | 0.0 | 977.7 | 1.17 ± 0.73 |
| mattcl | input-whyando | 392.0 ± 159.4 | 0.0 | 1045.4 | 1.19 ± 0.73 |
| kcen | input-lanjian | 836.4 ± 187.0 | 0.0 | 1562.1 | 2.53 ± 1.31 |
| kcen | input-mattcl | 855.2 ± 158.6 | 0.0 | 1434.4 | 2.59 ± 1.30 |
| kcen | input-whyando | 888.3 ± 179.5 | 0.0 | 1471.9 | 2.69 ± 1.37 |
| mattcl-py | input-lanjian | 17236.5 ± 680.9 | 16255.3 | 20381.7 | 52.21 ± 24.39 |
| mattcl-py | input-mattcl | 17309.3 ± 608.1 | 16373.2 | 20641.1 | 52.43 ± 24.48 |
| mattcl-py | input-whyando | 17406.4 ± 751.5 | 16405.3 | 20923.0 | 52.73 ± 24.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|