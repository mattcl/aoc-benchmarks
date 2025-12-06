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
| mattcl | input-whyando | 509.7 ± 169.6 | 0.0 | 1057.0 | 1.00 |
| mattcl | input-lanjian | 516.1 ± 145.0 | 0.0 | 744.1 | 1.01 ± 0.44 |
| mattcl | input-mattcl | 516.7 ± 165.1 | 0.0 | 955.9 | 1.01 ± 0.47 |
| kcen | input-mattcl | 818.1 ± 154.9 | 93.0 | 1260.8 | 1.61 ± 0.61 |
| kcen | input-whyando | 828.3 ± 166.3 | 284.7 | 1388.1 | 1.63 ± 0.63 |
| kcen | input-lanjian | 842.0 ± 135.7 | 0.0 | 1318.4 | 1.65 ± 0.61 |
| whyando | input-lanjian | 990.0 ± 126.7 | 439.5 | 1528.5 | 1.94 ± 0.69 |
| whyando | input-whyando | 1016.1 ± 162.4 | 489.5 | 1644.1 | 1.99 ± 0.74 |
| whyando | input-mattcl | 1021.8 ± 187.2 | 447.2 | 1970.4 | 2.00 ± 0.76 |
| lanjian | input-lanjian | 1095.2 ± 173.5 | 484.8 | 1798.6 | 2.15 ± 0.79 |
| lanjian | input-whyando | 1162.9 ± 216.0 | 423.4 | 2073.1 | 2.28 ± 0.87 |
| lanjian | input-mattcl | 1164.7 ± 214.6 | 520.5 | 1980.6 | 2.29 ± 0.87 |
| mattcl-py | input-mattcl | 18300.6 ± 615.3 | 17189.1 | 21059.2 | 35.91 ± 12.01 |
| mattcl-py | input-whyando | 18334.9 ± 540.4 | 17443.1 | 21269.0 | 35.97 ± 12.01 |
| mattcl-py | input-lanjian | 18364.3 ± 783.7 | 16875.6 | 21525.2 | 36.03 ± 12.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|