# Day 15 benchmarks

[link to problem](https://adventofcode.com/2023/day/15)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 15)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.5 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.4 | 1.6 | 1.02 ± 0.36 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.5 | 1.8 | 1.07 ± 0.34 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.6 | 2.5 | 1.15 ± 0.34 |
| mattcl | input-lanjian | 1.0 ± 1.3 | 0.6 | 14.4 | 1.26 ± 1.62 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.7 | 1.5 | 1.53 ± 0.40 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.6 | 1.6 | 1.61 ± 0.43 |
| lanjian | input-kcen | 1.4 ± 2.5 | 0.6 | 19.5 | 1.73 ± 3.04 |
| pting | input-pting | 18.5 ± 0.6 | 17.3 | 21.2 | 22.76 ± 5.17 |
| pting | input-mattcl | 19.1 ± 0.7 | 18.0 | 21.6 | 23.43 ± 5.34 |
| kcen | input-pting | 19.5 ± 0.6 | 18.3 | 22.2 | 24.00 ± 5.44 |
| mattcl-py | input-pting | 22.0 ± 3.7 | 19.6 | 33.6 | 26.96 ± 7.59 |
| pting | input-kcen | 25.3 ± 0.5 | 24.5 | 28.3 | 31.03 ± 7.00 |
| kcen | input-lanjian | 26.9 ± 4.0 | 25.4 | 68.1 | 33.05 ± 8.93 |
| mattcl-py | input-kcen | 28.2 ± 0.9 | 26.8 | 32.0 | 34.58 ± 7.85 |
| mattcl-py | input-mattcl | 28.3 ± 7.1 | 19.7 | 37.5 | 34.71 ± 11.73 |
| pting | input-lanjian | 31.2 ± 0.4 | 28.8 | 32.6 | 38.32 ± 8.62 |
| kcen | input-mattcl | 32.0 ± 1.6 | 22.0 | 34.1 | 39.29 ± 9.05 |
| kcen | input-kcen | 33.2 ± 1.0 | 28.8 | 34.3 | 40.72 ± 9.23 |
| mattcl-py | input-lanjian | 35.5 ± 0.9 | 33.7 | 40.3 | 43.61 ± 9.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|