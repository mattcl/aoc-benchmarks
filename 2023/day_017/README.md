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
| mattcl | input-pting | 10.7 ± 0.4 | 9.9 | 12.4 | 1.00 |
| mattcl | input-lanjian | 10.8 ± 0.4 | 9.9 | 12.1 | 1.01 ± 0.05 |
| mattcl | input-mattcl | 10.8 ± 0.4 | 9.9 | 12.6 | 1.01 ± 0.05 |
| mattcl | input-kcen | 10.8 ± 0.4 | 9.4 | 11.9 | 1.01 ± 0.05 |
| lanjian | input-pting | 19.8 ± 0.9 | 18.7 | 23.1 | 1.85 ± 0.10 |
| lanjian | input-lanjian | 20.0 ± 0.8 | 18.8 | 23.5 | 1.87 ± 0.10 |
| lanjian | input-mattcl | 20.1 ± 0.7 | 18.6 | 22.7 | 1.88 ± 0.09 |
| lanjian | input-kcen | 20.1 ± 0.7 | 18.6 | 23.1 | 1.88 ± 0.09 |
| mattcl-py | input-pting | 296.7 ± 5.5 | 291.3 | 309.3 | 27.70 ± 1.05 |
| mattcl-py | input-lanjian | 298.9 ± 2.3 | 296.5 | 302.8 | 27.91 ± 0.95 |
| mattcl-py | input-mattcl | 299.3 ± 2.7 | 294.7 | 303.7 | 27.95 ± 0.96 |
| mattcl-py | input-kcen | 303.4 ± 3.6 | 298.6 | 308.6 | 28.33 ± 1.00 |
| pting | input-mattcl | 1883.0 ± 18.5 | 1862.7 | 1898.9 | 175.83 ± 6.06 |
| pting | input-lanjian | 1884.5 ± 13.3 | 1869.2 | 1893.5 | 175.97 ± 5.95 |
| pting | input-kcen | 1898.6 ± 40.5 | 1873.9 | 1945.3 | 177.29 ± 6.97 |
| pting | input-pting | 1930.8 ± 48.8 | 1876.5 | 1971.1 | 180.30 ± 7.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|