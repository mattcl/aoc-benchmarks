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
| mattcl | input-pting | 10.4 ± 0.4 | 9.4 | 12.6 | 1.00 |
| mattcl | input-lanjian | 10.4 ± 0.4 | 9.6 | 11.5 | 1.01 ± 0.05 |
| mattcl | input-mattcl | 10.5 ± 0.3 | 9.4 | 11.7 | 1.01 ± 0.05 |
| mattcl | input-kcen | 10.5 ± 0.4 | 9.4 | 12.4 | 1.01 ± 0.05 |
| lanjian | input-pting | 19.1 ± 0.5 | 18.1 | 21.9 | 1.84 ± 0.09 |
| lanjian | input-mattcl | 19.4 ± 0.6 | 18.2 | 22.2 | 1.87 ± 0.09 |
| lanjian | input-lanjian | 19.5 ± 0.7 | 18.0 | 23.1 | 1.88 ± 0.10 |
| lanjian | input-kcen | 19.7 ± 0.6 | 18.3 | 22.4 | 1.90 ± 0.10 |
| mattcl-py | input-pting | 296.1 ± 4.5 | 289.3 | 305.7 | 28.54 ± 1.19 |
| mattcl-py | input-mattcl | 300.2 ± 3.6 | 295.5 | 307.1 | 28.94 ± 1.17 |
| mattcl-py | input-lanjian | 303.4 ± 1.6 | 300.6 | 305.2 | 29.24 ± 1.14 |
| mattcl-py | input-kcen | 306.7 ± 1.7 | 303.8 | 309.0 | 29.56 ± 1.15 |
| pting | input-mattcl | 1885.6 ± 28.6 | 1863.0 | 1917.8 | 181.75 ± 7.55 |
| pting | input-kcen | 1902.7 ± 19.1 | 1882.5 | 1920.4 | 183.40 ± 7.32 |
| pting | input-pting | 1911.8 ± 19.3 | 1894.6 | 1932.6 | 184.28 ± 7.36 |
| pting | input-lanjian | 1919.5 ± 41.4 | 1887.8 | 1966.4 | 185.02 ± 8.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|