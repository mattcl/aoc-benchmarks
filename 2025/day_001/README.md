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
| whyando | input-whyando | 547.8 ± 162.0 | 0.0 | 921.6 | 1.00 |
| whyando | input-lanjian | 581.0 ± 157.0 | 62.9 | 1135.5 | 1.06 ± 0.42 |
| whyando | input-mattcl | 582.1 ± 139.3 | 136.4 | 1019.7 | 1.06 ± 0.40 |
| kcen | input-mattcl | 787.8 ± 133.6 | 361.9 | 1318.1 | 1.44 ± 0.49 |
| kcen | input-whyando | 789.5 ± 140.0 | 245.6 | 1342.6 | 1.44 ± 0.50 |
| kcen | input-lanjian | 794.2 ± 147.9 | 257.3 | 1511.2 | 1.45 ± 0.51 |
| mattcl | input-mattcl | 946.9 ± 174.8 | 92.2 | 1634.0 | 1.73 ± 0.60 |
| mattcl | input-lanjian | 952.9 ± 189.7 | 0.0 | 1721.6 | 1.74 ± 0.62 |
| mattcl | input-whyando | 977.9 ± 145.3 | 348.2 | 1734.2 | 1.79 ± 0.59 |
| lanjian | input-mattcl | 1275.1 ± 194.6 | 540.9 | 1903.8 | 2.33 ± 0.77 |
| lanjian | input-lanjian | 1322.0 ± 195.1 | 529.5 | 1894.5 | 2.41 ± 0.80 |
| lanjian | input-whyando | 1338.8 ± 179.4 | 700.2 | 2033.9 | 2.44 ± 0.79 |
| mattcl-py | input-lanjian | 18190.3 ± 555.9 | 17052.7 | 21060.6 | 33.21 ± 9.87 |
| mattcl-py | input-whyando | 18262.8 ± 630.9 | 17261.7 | 21254.7 | 33.34 ± 9.92 |
| mattcl-py | input-mattcl | 18354.5 ± 751.6 | 17333.5 | 21419.9 | 33.51 ± 10.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|