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
| mattcl | input-pting | 10.7 ± 0.4 | 9.9 | 12.0 | 1.00 |
| mattcl | input-lanjian | 10.7 ± 0.4 | 9.5 | 12.4 | 1.00 ± 0.05 |
| mattcl | input-mattcl | 10.7 ± 0.4 | 9.8 | 11.8 | 1.00 ± 0.05 |
| mattcl | input-kcen | 10.8 ± 0.4 | 9.8 | 12.1 | 1.01 ± 0.05 |
| lanjian | input-pting | 19.6 ± 0.8 | 18.1 | 22.6 | 1.84 ± 0.10 |
| lanjian | input-mattcl | 19.8 ± 0.7 | 18.5 | 22.5 | 1.85 ± 0.09 |
| lanjian | input-lanjian | 20.0 ± 0.8 | 18.6 | 22.8 | 1.87 ± 0.09 |
| lanjian | input-kcen | 20.0 ± 0.7 | 18.7 | 23.2 | 1.88 ± 0.09 |
| mattcl-py | input-pting | 298.3 ± 3.8 | 293.1 | 304.0 | 27.90 ± 0.99 |
| mattcl-py | input-mattcl | 302.9 ± 1.5 | 300.5 | 305.3 | 28.33 ± 0.95 |
| mattcl-py | input-kcen | 306.1 ± 3.8 | 301.5 | 314.1 | 28.63 ± 1.02 |
| mattcl-py | input-lanjian | 306.4 ± 4.8 | 300.5 | 316.7 | 28.66 ± 1.05 |
| pting | input-mattcl | 1866.7 ± 37.5 | 1825.1 | 1898.1 | 174.61 ± 6.79 |
| pting | input-lanjian | 1896.6 ± 41.3 | 1851.3 | 1932.3 | 177.41 ± 7.05 |
| pting | input-kcen | 1906.0 ± 22.4 | 1880.5 | 1922.6 | 178.29 ± 6.29 |
| pting | input-pting | 1911.5 ± 30.5 | 1883.9 | 1944.2 | 178.80 ± 6.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|