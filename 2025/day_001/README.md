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
| whyando | input-whyando | 709.8 ± 142.1 | 0.0 | 1151.4 | 1.00 |
| whyando | input-mattcl | 709.9 ± 154.9 | 0.0 | 1216.8 | 1.00 ± 0.30 |
| whyando | input-lanjian | 711.4 ± 133.8 | 239.9 | 1158.4 | 1.00 ± 0.28 |
| kcen | input-mattcl | 823.2 ± 132.2 | 338.7 | 1373.0 | 1.16 ± 0.30 |
| kcen | input-lanjian | 826.0 ± 157.8 | 302.6 | 1388.8 | 1.16 ± 0.32 |
| kcen | input-whyando | 832.0 ± 139.7 | 238.9 | 1327.1 | 1.17 ± 0.31 |
| mattcl | input-whyando | 1062.5 ± 299.7 | 101.5 | 1851.6 | 1.50 ± 0.52 |
| mattcl | input-mattcl | 1101.3 ± 184.5 | 479.0 | 1850.6 | 1.55 ± 0.41 |
| lanjian | input-whyando | 1122.0 ± 322.1 | 60.5 | 2101.1 | 1.58 ± 0.55 |
| mattcl | input-lanjian | 1175.5 ± 234.3 | 178.1 | 1943.8 | 1.66 ± 0.47 |
| lanjian | input-lanjian | 1261.7 ± 240.0 | 434.1 | 2026.8 | 1.78 ± 0.49 |
| lanjian | input-mattcl | 1306.5 ± 230.7 | 602.4 | 2634.4 | 1.84 ± 0.49 |
| mattcl-py | input-lanjian | 18141.7 ± 658.0 | 16757.9 | 21470.8 | 25.56 ± 5.20 |
| mattcl-py | input-mattcl | 18152.1 ± 709.3 | 16794.4 | 21442.0 | 25.57 ± 5.22 |
| mattcl-py | input-whyando | 18244.1 ± 510.0 | 17522.0 | 20913.4 | 25.70 ± 5.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|