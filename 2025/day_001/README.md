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
| whyando | input-mattcl | 565.7 ± 190.0 | 0.0 | 995.4 | 1.00 |
| whyando | input-lanjian | 589.0 ± 171.2 | 0.0 | 971.9 | 1.04 ± 0.46 |
| mattcl | input-mattcl | 590.9 ± 156.4 | 0.0 | 1001.7 | 1.04 ± 0.45 |
| whyando | input-whyando | 597.3 ± 188.3 | 0.0 | 1087.4 | 1.06 ± 0.49 |
| mattcl | input-lanjian | 601.0 ± 159.6 | 0.0 | 1139.3 | 1.06 ± 0.45 |
| mattcl | input-whyando | 609.1 ± 205.6 | 0.0 | 1388.0 | 1.08 ± 0.51 |
| kcen | input-whyando | 822.2 ± 259.7 | 0.0 | 1378.9 | 1.45 ± 0.67 |
| kcen | input-lanjian | 871.4 ± 240.4 | 27.5 | 1165.1 | 1.54 ± 0.67 |
| kcen | input-mattcl | 1001.4 ± 170.4 | 436.2 | 1591.9 | 1.77 ± 0.67 |
| lanjian | input-lanjian | 1396.8 ± 258.2 | 289.2 | 2084.0 | 2.47 ± 0.95 |
| lanjian | input-whyando | 1432.4 ± 214.6 | 362.6 | 2267.7 | 2.53 ± 0.93 |
| lanjian | input-mattcl | 1444.0 ± 175.0 | 654.7 | 2176.6 | 2.55 ± 0.91 |
| mattcl-py | input-mattcl | 18425.0 ± 708.9 | 17336.2 | 21666.2 | 32.57 ± 11.01 |
| mattcl-py | input-whyando | 18429.8 ± 776.6 | 16993.6 | 21641.5 | 32.58 ± 11.03 |
| mattcl-py | input-lanjian | 18452.2 ± 733.0 | 17342.5 | 21675.1 | 32.62 ± 11.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|