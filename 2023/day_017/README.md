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
| mattcl | input-pting | 10.7 ± 0.4 | 9.4 | 13.0 | 1.00 |
| mattcl | input-lanjian | 10.7 ± 0.4 | 10.0 | 12.4 | 1.00 ± 0.05 |
| mattcl | input-mattcl | 10.7 ± 0.4 | 9.9 | 12.7 | 1.00 ± 0.05 |
| mattcl | input-kcen | 10.8 ± 0.4 | 9.8 | 11.8 | 1.01 ± 0.05 |
| lanjian | input-pting | 19.6 ± 0.6 | 18.5 | 22.2 | 1.84 ± 0.09 |
| lanjian | input-mattcl | 19.7 ± 0.7 | 18.2 | 22.8 | 1.84 ± 0.10 |
| lanjian | input-lanjian | 20.0 ± 0.8 | 18.6 | 22.6 | 1.87 ± 0.11 |
| lanjian | input-kcen | 20.0 ± 0.8 | 18.9 | 22.9 | 1.87 ± 0.10 |
| mattcl-py | input-pting | 296.6 ± 3.6 | 291.4 | 304.4 | 27.76 ± 1.15 |
| mattcl-py | input-mattcl | 298.2 ± 3.6 | 292.6 | 305.9 | 27.91 ± 1.15 |
| mattcl-py | input-lanjian | 299.4 ± 3.1 | 293.6 | 302.7 | 28.02 ± 1.14 |
| mattcl-py | input-kcen | 304.1 ± 3.0 | 297.7 | 307.3 | 28.46 ± 1.16 |
| pting | input-mattcl | 1865.6 ± 12.8 | 1853.0 | 1878.6 | 174.60 ± 6.99 |
| pting | input-kcen | 1878.7 ± 31.0 | 1851.3 | 1912.3 | 175.82 ± 7.52 |
| pting | input-lanjian | 1896.4 ± 14.4 | 1887.9 | 1913.1 | 177.48 ± 7.13 |
| pting | input-pting | 1902.5 ± 36.4 | 1874.6 | 1943.7 | 178.05 ± 7.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|