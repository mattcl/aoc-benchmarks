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
| whyando | input-whyando | 503.2 ± 162.2 | 0.0 | 1099.4 | 1.00 |
| mattcl | input-lanjian | 519.0 ± 162.3 | 0.0 | 1068.5 | 1.03 ± 0.46 |
| mattcl | input-whyando | 521.2 ± 151.1 | 71.6 | 980.2 | 1.04 ± 0.45 |
| whyando | input-mattcl | 524.1 ± 156.4 | 0.0 | 966.9 | 1.04 ± 0.46 |
| mattcl | input-mattcl | 533.0 ± 164.6 | 0.0 | 985.8 | 1.06 ± 0.47 |
| whyando | input-lanjian | 536.5 ± 142.8 | 21.9 | 969.5 | 1.07 ± 0.45 |
| kcen | input-whyando | 808.3 ± 160.3 | 226.3 | 1290.8 | 1.61 ± 0.61 |
| kcen | input-lanjian | 849.1 ± 156.5 | 109.9 | 1608.6 | 1.69 ± 0.63 |
| kcen | input-mattcl | 849.7 ± 167.8 | 0.0 | 1342.7 | 1.69 ± 0.64 |
| lanjian | input-mattcl | 1083.9 ± 221.5 | 406.5 | 1810.6 | 2.15 ± 0.82 |
| lanjian | input-whyando | 1147.6 ± 162.2 | 568.5 | 1807.3 | 2.28 ± 0.80 |
| lanjian | input-lanjian | 1167.5 ± 248.8 | 256.0 | 2027.9 | 2.32 ± 0.90 |
| mattcl-py | input-lanjian | 18311.1 ± 583.0 | 17133.3 | 21031.3 | 36.39 ± 11.79 |
| mattcl-py | input-mattcl | 18357.5 ± 639.3 | 17214.2 | 21402.5 | 36.48 ± 11.83 |
| mattcl-py | input-whyando | 18415.9 ± 850.4 | 17324.1 | 22141.3 | 36.60 ± 11.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|