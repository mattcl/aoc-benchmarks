# Day 17 benchmarks

[link to problem](https://adventofcode.com/2023/day/17)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 17)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 10.5 ± 0.4 | 9.6 | 12.8 | 1.00 |
| mattcl | input-mattcl | 10.5 ± 0.3 | 9.7 | 11.6 | 1.00 ± 0.05 |
| mattcl | input-lanjian | 10.5 ± 0.4 | 9.7 | 13.0 | 1.01 ± 0.05 |
| mattcl | input-kcen | 10.6 ± 0.4 | 9.7 | 11.7 | 1.01 ± 0.05 |
| lanjian | input-pting | 19.4 ± 0.8 | 18.3 | 23.0 | 1.85 ± 0.11 |
| lanjian | input-mattcl | 19.5 ± 0.5 | 18.5 | 22.1 | 1.86 ± 0.09 |
| lanjian | input-lanjian | 19.7 ± 0.7 | 18.3 | 22.5 | 1.88 ± 0.10 |
| lanjian | input-kcen | 19.7 ± 0.8 | 18.4 | 23.4 | 1.89 ± 0.11 |
| mattcl-py | input-pting | 295.5 ± 3.2 | 292.4 | 301.8 | 28.24 ± 1.17 |
| mattcl-py | input-mattcl | 301.6 ± 6.1 | 297.1 | 315.1 | 28.82 ± 1.29 |
| mattcl-py | input-lanjian | 302.0 ± 3.2 | 298.3 | 307.5 | 28.86 ± 1.19 |
| mattcl-py | input-kcen | 305.6 ± 4.5 | 300.6 | 314.1 | 29.20 ± 1.24 |
| pting | input-mattcl | 1874.0 ± 10.4 | 1866.3 | 1885.9 | 179.08 ± 7.21 |
| pting | input-kcen | 1907.7 ± 9.1 | 1897.8 | 1915.7 | 182.30 ± 7.32 |
| pting | input-lanjian | 1908.5 ± 26.9 | 1891.6 | 1939.5 | 182.37 ± 7.71 |
| pting | input-pting | 1916.5 ± 10.8 | 1904.1 | 1923.5 | 183.14 ± 7.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|