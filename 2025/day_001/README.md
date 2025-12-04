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
| whyando | input-mattcl | 716.4 ± 148.0 | 0.0 | 955.4 | 1.00 |
| whyando | input-whyando | 722.9 ± 146.0 | 207.4 | 1121.4 | 1.01 ± 0.29 |
| whyando | input-lanjian | 759.7 ± 123.8 | 101.9 | 1034.0 | 1.06 ± 0.28 |
| kcen | input-whyando | 865.9 ± 149.4 | 0.0 | 1300.9 | 1.21 ± 0.33 |
| kcen | input-lanjian | 879.0 ± 117.2 | 443.7 | 1412.2 | 1.23 ± 0.30 |
| kcen | input-mattcl | 958.8 ± 189.6 | 375.3 | 1572.3 | 1.34 ± 0.38 |
| mattcl | input-whyando | 1057.9 ± 208.0 | 445.6 | 1896.1 | 1.48 ± 0.42 |
| mattcl | input-mattcl | 1070.9 ± 191.9 | 17.5 | 1814.4 | 1.49 ± 0.41 |
| mattcl | input-lanjian | 1089.5 ± 206.6 | 488.5 | 1891.5 | 1.52 ± 0.43 |
| lanjian | input-whyando | 1344.0 ± 206.7 | 487.9 | 2091.0 | 1.88 ± 0.48 |
| lanjian | input-lanjian | 1361.7 ± 180.5 | 539.4 | 2014.3 | 1.90 ± 0.47 |
| lanjian | input-mattcl | 1365.5 ± 182.4 | 701.1 | 1863.2 | 1.91 ± 0.47 |
| mattcl-py | input-lanjian | 18141.8 ± 561.7 | 16901.3 | 21270.9 | 25.32 ± 5.29 |
| mattcl-py | input-mattcl | 18192.1 ± 623.4 | 17319.7 | 21624.8 | 25.39 ± 5.32 |
| mattcl-py | input-whyando | 18281.2 ± 736.2 | 16892.6 | 21666.0 | 25.52 ± 5.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|