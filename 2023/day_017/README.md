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
| mattcl | input-pting | 10.7 ± 0.4 | 9.6 | 12.5 | 1.00 |
| mattcl | input-mattcl | 10.7 ± 0.4 | 9.8 | 11.9 | 1.01 ± 0.05 |
| mattcl | input-lanjian | 10.8 ± 0.4 | 9.7 | 12.3 | 1.01 ± 0.06 |
| mattcl | input-kcen | 10.9 ± 0.4 | 10.0 | 13.2 | 1.02 ± 0.05 |
| lanjian | input-pting | 19.8 ± 0.9 | 18.6 | 22.9 | 1.85 ± 0.11 |
| lanjian | input-mattcl | 19.9 ± 0.8 | 18.2 | 23.0 | 1.86 ± 0.10 |
| lanjian | input-lanjian | 20.0 ± 0.6 | 18.8 | 22.6 | 1.87 ± 0.09 |
| lanjian | input-kcen | 20.0 ± 0.6 | 18.9 | 23.5 | 1.87 ± 0.09 |
| mattcl-py | input-pting | 298.9 ± 2.4 | 293.2 | 302.1 | 27.98 ± 1.08 |
| mattcl-py | input-lanjian | 303.7 ± 3.7 | 298.9 | 308.8 | 28.42 ± 1.13 |
| mattcl-py | input-mattcl | 304.3 ± 3.6 | 301.4 | 312.0 | 28.48 ± 1.13 |
| mattcl-py | input-kcen | 323.6 ± 47.2 | 305.1 | 449.3 | 30.29 ± 4.57 |
| pting | input-mattcl | 1885.0 ± 30.6 | 1856.6 | 1917.5 | 176.44 ± 7.26 |
| pting | input-kcen | 1900.7 ± 9.9 | 1889.3 | 1907.6 | 177.90 ± 6.79 |
| pting | input-lanjian | 1920.3 ± 15.2 | 1911.5 | 1937.9 | 179.74 ± 6.94 |
| pting | input-pting | 1947.1 ± 13.6 | 1938.6 | 1962.8 | 182.25 ± 7.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|