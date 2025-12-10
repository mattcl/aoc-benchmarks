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
| whyando | input-lanjian | 512.9 ± 183.1 | 0.0 | 1017.8 | 1.00 |
| whyando | input-mattcl | 517.6 ± 191.6 | 0.0 | 1327.1 | 1.01 ± 0.52 |
| whyando | input-whyando | 523.5 ± 159.5 | 0.0 | 1129.2 | 1.02 ± 0.48 |
| mattcl | input-mattcl | 531.7 ± 147.5 | 0.0 | 1049.7 | 1.04 ± 0.47 |
| mattcl | input-whyando | 532.0 ± 156.3 | 0.0 | 985.6 | 1.04 ± 0.48 |
| mattcl | input-lanjian | 545.0 ± 157.3 | 0.0 | 1055.7 | 1.06 ± 0.49 |
| lanjian | input-whyando | 862.5 ± 187.7 | 0.0 | 1660.3 | 1.68 ± 0.70 |
| kcen | input-mattcl | 862.9 ± 152.5 | 246.5 | 1366.3 | 1.68 ± 0.67 |
| kcen | input-whyando | 863.9 ± 125.5 | 372.9 | 1415.0 | 1.68 ± 0.65 |
| lanjian | input-mattcl | 869.1 ± 184.6 | 0.0 | 1793.8 | 1.69 ± 0.70 |
| kcen | input-lanjian | 916.6 ± 180.5 | 453.8 | 1598.0 | 1.79 ± 0.73 |
| lanjian | input-lanjian | 918.4 ± 171.4 | 357.2 | 1449.3 | 1.79 ± 0.72 |
| mattcl-py | input-mattcl | 18216.7 ± 543.2 | 17334.9 | 21563.0 | 35.52 ± 12.72 |
| mattcl-py | input-lanjian | 18284.2 ± 585.8 | 17245.6 | 21047.2 | 35.65 ± 12.78 |
| mattcl-py | input-whyando | 18334.1 ± 586.2 | 17194.2 | 21693.3 | 35.75 ± 12.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|