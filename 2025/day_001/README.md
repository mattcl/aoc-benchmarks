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
| whyando | input-mattcl | 489.2 ± 155.5 | 0.0 | 1138.0 | 1.00 |
| whyando | input-whyando | 503.8 ± 163.4 | 0.0 | 1021.5 | 1.03 ± 0.47 |
| mattcl | input-lanjian | 513.0 ± 205.0 | 0.0 | 1304.9 | 1.05 ± 0.54 |
| mattcl | input-whyando | 513.6 ± 153.7 | 0.0 | 1041.1 | 1.05 ± 0.46 |
| mattcl | input-mattcl | 528.5 ± 194.0 | 0.0 | 1242.5 | 1.08 ± 0.52 |
| whyando | input-lanjian | 542.2 ± 182.5 | 0.0 | 1478.4 | 1.11 ± 0.51 |
| kcen | input-whyando | 825.0 ± 159.5 | 27.7 | 1633.3 | 1.69 ± 0.63 |
| kcen | input-mattcl | 842.4 ± 155.8 | 366.4 | 1485.7 | 1.72 ± 0.63 |
| lanjian | input-whyando | 857.6 ± 142.7 | 387.1 | 1356.9 | 1.75 ± 0.63 |
| lanjian | input-mattcl | 867.1 ± 146.0 | 351.0 | 1390.4 | 1.77 ± 0.64 |
| lanjian | input-lanjian | 894.3 ± 187.2 | 0.0 | 1521.2 | 1.83 ± 0.70 |
| kcen | input-lanjian | 895.6 ± 155.2 | 0.0 | 1382.3 | 1.83 ± 0.66 |
| mattcl-py | input-whyando | 18181.6 ± 609.5 | 17234.9 | 21131.6 | 37.17 ± 11.88 |
| mattcl-py | input-mattcl | 18231.2 ± 595.9 | 17074.5 | 20870.7 | 37.27 ± 11.91 |
| mattcl-py | input-lanjian | 18348.2 ± 819.6 | 16940.3 | 21850.5 | 37.51 ± 12.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|