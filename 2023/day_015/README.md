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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.23 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.23 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.07 ± 0.22 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.6 | 1.7 | 1.09 ± 0.21 |
| pting | input-pting | 17.9 ± 0.7 | 17.0 | 21.2 | 15.41 ± 2.61 |
| pting | input-kcen | 18.0 ± 0.7 | 17.4 | 21.1 | 15.51 ± 2.63 |
| pting | input-mattcl | 18.1 ± 0.8 | 17.1 | 21.1 | 15.55 ± 2.67 |
| pting | input-lanjian | 18.1 ± 0.8 | 17.1 | 23.6 | 15.57 ± 2.67 |
| kcen | input-pting | 18.5 ± 0.7 | 17.4 | 22.2 | 15.94 ± 2.71 |
| kcen | input-mattcl | 18.6 ± 0.7 | 17.7 | 21.9 | 15.98 ± 2.71 |
| kcen | input-lanjian | 18.7 ± 0.8 | 17.5 | 22.3 | 16.09 ± 2.74 |
| kcen | input-kcen | 18.9 ± 2.8 | 17.5 | 52.7 | 16.29 ± 3.62 |
| mattcl-py | input-mattcl | 19.7 ± 0.6 | 18.8 | 22.7 | 16.96 ± 2.86 |
| mattcl-py | input-lanjian | 19.9 ± 0.7 | 18.7 | 22.6 | 17.13 ± 2.91 |
| mattcl-py | input-pting | 19.9 ± 0.9 | 18.6 | 23.0 | 17.14 ± 2.94 |
| mattcl-py | input-kcen | 20.0 ± 0.7 | 18.7 | 22.7 | 17.16 ± 2.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|