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
| whyando | input-lanjian | 365.0 ± 203.3 | 0.0 | 709.3 | 1.00 |
| whyando | input-mattcl | 485.7 ± 138.6 | 0.0 | 728.6 | 1.33 ± 0.83 |
| mattcl | input-whyando | 521.2 ± 156.2 | 0.0 | 1084.6 | 1.43 ± 0.90 |
| mattcl | input-lanjian | 524.4 ± 140.1 | 0.0 | 942.8 | 1.44 ± 0.89 |
| whyando | input-whyando | 526.9 ± 164.7 | 0.0 | 1068.1 | 1.44 ± 0.92 |
| mattcl | input-mattcl | 534.3 ± 146.9 | 27.1 | 1037.5 | 1.46 ± 0.91 |
| kcen | input-mattcl | 822.9 ± 172.6 | 28.0 | 1531.2 | 2.25 ± 1.34 |
| kcen | input-whyando | 837.6 ± 134.5 | 340.3 | 1335.4 | 2.30 ± 1.33 |
| lanjian | input-mattcl | 846.2 ± 155.9 | 217.0 | 1280.4 | 2.32 ± 1.36 |
| kcen | input-lanjian | 860.7 ± 187.3 | 0.0 | 1463.8 | 2.36 ± 1.41 |
| lanjian | input-whyando | 865.8 ± 141.4 | 416.2 | 1341.7 | 2.37 ± 1.38 |
| lanjian | input-lanjian | 947.1 ± 172.0 | 336.3 | 1535.6 | 2.60 ± 1.52 |
| mattcl-py | input-whyando | 18204.7 ± 611.7 | 16720.7 | 21272.4 | 49.88 ± 27.83 |
| mattcl-py | input-lanjian | 18236.7 ± 483.2 | 17118.9 | 20664.6 | 49.97 ± 27.86 |
| mattcl-py | input-mattcl | 18263.3 ± 639.6 | 17059.7 | 21769.7 | 50.04 ± 27.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|