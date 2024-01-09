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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.5 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.7 | 1.8 | 1.04 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 2.9 | 1.05 ± 0.22 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.6 | 1.8 | 1.07 ± 0.21 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.09 ± 0.22 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 2.1 | 1.11 ± 0.23 |
| pting | input-pting | 18.3 ± 0.7 | 17.5 | 21.3 | 15.45 ± 2.45 |
| pting | input-mattcl | 18.4 ± 0.8 | 17.2 | 21.0 | 15.50 ± 2.49 |
| pting | input-lanjian | 18.4 ± 0.6 | 17.5 | 21.2 | 15.51 ± 2.46 |
| pting | input-kcen | 18.6 ± 0.7 | 17.3 | 21.1 | 15.66 ± 2.50 |
| kcen | input-mattcl | 18.8 ± 0.6 | 17.9 | 21.7 | 15.88 ± 2.51 |
| kcen | input-lanjian | 18.9 ± 0.7 | 17.6 | 22.0 | 15.94 ± 2.53 |
| kcen | input-kcen | 18.9 ± 0.5 | 17.6 | 21.2 | 15.96 ± 2.51 |
| kcen | input-pting | 19.0 ± 0.8 | 17.8 | 22.1 | 16.01 ± 2.57 |
| mattcl-py | input-lanjian | 20.1 ± 0.5 | 19.0 | 22.5 | 16.97 ± 2.66 |
| mattcl-py | input-mattcl | 20.2 ± 0.7 | 18.6 | 23.0 | 17.05 ± 2.71 |
| mattcl-py | input-kcen | 20.2 ± 0.7 | 19.0 | 23.3 | 17.06 ± 2.71 |
| mattcl-py | input-pting | 20.3 ± 2.1 | 19.2 | 44.3 | 17.17 ± 3.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|