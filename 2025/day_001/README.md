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
| whyando | input-mattcl | 703.9 ± 172.5 | 0.0 | 1121.8 | 1.00 |
| whyando | input-lanjian | 723.1 ± 110.3 | 43.4 | 915.5 | 1.03 ± 0.30 |
| whyando | input-whyando | 729.5 ± 131.6 | 151.4 | 1138.7 | 1.04 ± 0.32 |
| kcen | input-mattcl | 826.2 ± 136.9 | 331.6 | 1342.6 | 1.17 ± 0.35 |
| kcen | input-whyando | 830.9 ± 168.6 | 0.0 | 1594.9 | 1.18 ± 0.38 |
| kcen | input-lanjian | 851.3 ± 141.0 | 354.9 | 1356.8 | 1.21 ± 0.36 |
| mattcl | input-lanjian | 1014.3 ± 145.3 | 425.0 | 1760.8 | 1.44 ± 0.41 |
| mattcl | input-whyando | 1020.6 ± 153.6 | 455.7 | 1783.9 | 1.45 ± 0.42 |
| mattcl | input-mattcl | 1045.9 ± 175.6 | 469.5 | 1708.3 | 1.49 ± 0.44 |
| lanjian | input-lanjian | 1298.1 ± 241.1 | 540.4 | 1988.0 | 1.84 ± 0.57 |
| lanjian | input-whyando | 1322.6 ± 235.1 | 520.8 | 2232.6 | 1.88 ± 0.57 |
| lanjian | input-mattcl | 1358.1 ± 187.0 | 714.2 | 2076.6 | 1.93 ± 0.54 |
| mattcl-py | input-mattcl | 18059.9 ± 591.9 | 17124.6 | 21082.9 | 25.66 ± 6.34 |
| mattcl-py | input-lanjian | 18126.0 ± 694.2 | 17145.5 | 20712.3 | 25.75 ± 6.39 |
| mattcl-py | input-whyando | 18192.6 ± 749.5 | 16758.6 | 21530.7 | 25.84 ± 6.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|