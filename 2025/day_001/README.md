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
| whyando | input-whyando | 723.3 ± 148.1 | 0.0 | 1169.6 | 1.00 |
| whyando | input-lanjian | 723.5 ± 154.8 | 5.0 | 1126.6 | 1.00 ± 0.30 |
| whyando | input-mattcl | 735.3 ± 146.8 | 0.0 | 1181.9 | 1.02 ± 0.29 |
| kcen | input-whyando | 816.1 ± 148.6 | 335.0 | 1362.9 | 1.13 ± 0.31 |
| kcen | input-lanjian | 828.0 ± 144.8 | 292.3 | 1355.4 | 1.14 ± 0.31 |
| kcen | input-mattcl | 838.5 ± 140.3 | 235.8 | 1443.5 | 1.16 ± 0.31 |
| mattcl | input-lanjian | 1016.2 ± 180.0 | 470.4 | 1710.8 | 1.40 ± 0.38 |
| mattcl | input-mattcl | 1027.7 ± 148.9 | 586.5 | 1719.7 | 1.42 ± 0.36 |
| mattcl | input-whyando | 1082.9 ± 186.1 | 476.3 | 1954.8 | 1.50 ± 0.40 |
| lanjian | input-mattcl | 1307.7 ± 197.9 | 639.6 | 2104.3 | 1.81 ± 0.46 |
| lanjian | input-whyando | 1327.7 ± 219.1 | 424.8 | 2086.9 | 1.84 ± 0.48 |
| lanjian | input-lanjian | 1355.0 ± 182.6 | 658.4 | 2077.3 | 1.87 ± 0.46 |
| mattcl-py | input-mattcl | 18164.2 ± 696.6 | 17283.4 | 21170.7 | 25.11 ± 5.23 |
| mattcl-py | input-whyando | 18223.8 ± 909.1 | 16844.2 | 23286.9 | 25.19 ± 5.31 |
| mattcl-py | input-lanjian | 18257.0 ± 682.1 | 17240.2 | 21396.5 | 25.24 ± 5.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|