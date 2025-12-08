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
| whyando | input-mattcl | 504.9 ± 182.2 | 0.0 | 1003.2 | 1.00 |
| mattcl | input-whyando | 514.0 ± 185.9 | 0.0 | 1147.7 | 1.02 ± 0.52 |
| whyando | input-lanjian | 524.4 ± 165.7 | 0.0 | 1045.1 | 1.04 ± 0.50 |
| whyando | input-whyando | 529.5 ± 208.1 | 37.1 | 2601.5 | 1.05 ± 0.56 |
| mattcl | input-mattcl | 541.8 ± 172.6 | 0.0 | 989.0 | 1.07 ± 0.52 |
| mattcl | input-lanjian | 549.1 ± 140.5 | 0.0 | 857.9 | 1.09 ± 0.48 |
| lanjian | input-mattcl | 869.7 ± 169.8 | 396.8 | 1481.5 | 1.72 ± 0.71 |
| kcen | input-mattcl | 879.9 ± 145.3 | 136.0 | 1082.2 | 1.74 ± 0.69 |
| lanjian | input-lanjian | 885.4 ± 154.3 | 154.5 | 1346.0 | 1.75 ± 0.70 |
| lanjian | input-whyando | 887.5 ± 150.2 | 0.0 | 1367.4 | 1.76 ± 0.70 |
| kcen | input-lanjian | 890.5 ± 216.3 | 0.0 | 1842.8 | 1.76 ± 0.77 |
| kcen | input-whyando | 922.5 ± 187.0 | 0.0 | 1691.0 | 1.83 ± 0.76 |
| mattcl-py | input-whyando | 18172.5 ± 492.8 | 17266.1 | 21097.7 | 35.99 ± 13.03 |
| mattcl-py | input-mattcl | 18181.3 ± 569.1 | 17287.0 | 21431.6 | 36.01 ± 13.05 |
| mattcl-py | input-lanjian | 18329.8 ± 631.5 | 16906.7 | 21215.9 | 36.31 ± 13.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|