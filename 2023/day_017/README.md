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
| mattcl | input-pting | 10.5 ± 0.4 | 9.8 | 13.0 | 1.00 |
| mattcl | input-lanjian | 10.5 ± 0.4 | 9.6 | 11.7 | 1.00 ± 0.05 |
| mattcl | input-mattcl | 10.5 ± 0.4 | 9.7 | 12.3 | 1.00 ± 0.05 |
| mattcl | input-kcen | 10.6 ± 0.4 | 9.6 | 12.6 | 1.01 ± 0.05 |
| lanjian | input-pting | 19.3 ± 0.8 | 18.1 | 22.5 | 1.84 ± 0.10 |
| lanjian | input-lanjian | 19.6 ± 0.7 | 18.5 | 22.7 | 1.86 ± 0.09 |
| lanjian | input-mattcl | 19.6 ± 0.9 | 18.3 | 23.3 | 1.87 ± 0.11 |
| lanjian | input-kcen | 19.7 ± 0.7 | 18.5 | 22.6 | 1.88 ± 0.09 |
| mattcl-py | input-pting | 293.0 ± 2.6 | 289.0 | 297.4 | 27.89 ± 1.04 |
| mattcl-py | input-mattcl | 298.0 ± 4.2 | 293.5 | 305.7 | 28.36 ± 1.11 |
| mattcl-py | input-lanjian | 298.3 ± 2.8 | 293.7 | 303.9 | 28.39 ± 1.07 |
| mattcl-py | input-kcen | 301.9 ± 1.7 | 299.8 | 304.0 | 28.73 ± 1.06 |
| pting | input-mattcl | 1867.8 ± 19.6 | 1852.9 | 1890.0 | 177.77 ± 6.74 |
| pting | input-pting | 1881.4 ± 11.7 | 1869.8 | 1893.3 | 179.07 ± 6.62 |
| pting | input-lanjian | 1894.7 ± 19.8 | 1877.3 | 1916.4 | 180.34 ± 6.84 |
| pting | input-kcen | 1902.0 ± 22.5 | 1881.7 | 1926.1 | 181.03 ± 6.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|