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
| lanjian | input-lanjian | 1.0 ± 0.3 | 0.3 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 2.7 | 0.3 | 38.3 | 1.10 ± 2.72 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.20 ± 0.43 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.5 | 1.24 ± 0.42 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.7 | 1.7 | 1.24 ± 0.42 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.27 ± 0.44 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 2.1 | 1.28 ± 0.45 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.6 | 2.8 | 1.31 ± 0.49 |
| pting | input-kcen | 18.2 ± 0.5 | 17.4 | 20.8 | 18.40 ± 5.87 |
| pting | input-lanjian | 18.3 ± 0.8 | 17.3 | 21.3 | 18.52 ± 5.94 |
| pting | input-pting | 18.4 ± 0.8 | 17.3 | 22.1 | 18.59 ± 5.97 |
| pting | input-mattcl | 18.4 ± 0.8 | 17.1 | 21.6 | 18.61 ± 5.97 |
| kcen | input-pting | 18.8 ± 0.8 | 17.7 | 21.7 | 18.97 ± 6.08 |
| kcen | input-lanjian | 18.9 ± 0.7 | 18.2 | 22.0 | 19.04 ± 6.09 |
| kcen | input-kcen | 18.9 ± 0.7 | 17.9 | 21.9 | 19.05 ± 6.09 |
| kcen | input-mattcl | 19.3 ± 3.5 | 17.7 | 50.9 | 19.46 ± 7.13 |
| mattcl-py | input-kcen | 20.0 ± 0.6 | 18.8 | 22.5 | 20.24 ± 6.46 |
| mattcl-py | input-lanjian | 20.0 ± 0.7 | 18.8 | 24.0 | 20.24 ± 6.47 |
| mattcl-py | input-pting | 20.1 ± 0.8 | 18.5 | 23.5 | 20.32 ± 6.51 |
| mattcl-py | input-mattcl | 20.1 ± 0.7 | 18.9 | 23.4 | 20.33 ± 6.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|