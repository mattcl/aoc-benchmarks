# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 550.9 ± 171.0 | 0.0 | 804.4 | 1.00 |
| whyando | input-whyando | 565.6 ± 187.5 | 0.0 | 1043.4 | 1.03 ± 0.47 |
| whyando | input-mattcl | 567.0 ± 197.6 | 0.0 | 1270.7 | 1.03 ± 0.48 |
| mattcl | input-whyando | 590.6 ± 175.2 | 0.0 | 1044.4 | 1.07 ± 0.46 |
| mattcl | input-mattcl | 601.2 ± 165.4 | 0.0 | 1027.4 | 1.09 ± 0.45 |
| mattcl | input-lanjian | 605.9 ± 161.8 | 27.3 | 1095.1 | 1.10 ± 0.45 |
| kcen | input-mattcl | 903.2 ± 173.2 | 0.0 | 1370.6 | 1.64 ± 0.60 |
| kcen | input-whyando | 913.3 ± 177.4 | 329.2 | 1470.8 | 1.66 ± 0.61 |
| kcen | input-lanjian | 985.6 ± 176.0 | 461.3 | 1560.0 | 1.79 ± 0.64 |
| lanjian | input-mattcl | 1123.1 ± 208.7 | 154.3 | 1806.9 | 2.04 ± 0.74 |
| lanjian | input-whyando | 1137.8 ± 231.5 | 261.4 | 1869.0 | 2.07 ± 0.77 |
| lanjian | input-lanjian | 1174.2 ± 216.6 | 553.2 | 2011.9 | 2.13 ± 0.77 |
| mattcl-py | input-lanjian | 18678.7 ± 1936.6 | 17093.5 | 39608.2 | 33.91 ± 11.10 |
| mattcl-py | input-mattcl | 19123.9 ± 5032.2 | 17360.2 | 63221.5 | 34.72 ± 14.13 |
| mattcl-py | input-whyando | 19162.7 ± 4321.4 | 17242.0 | 52867.9 | 34.79 ± 13.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|