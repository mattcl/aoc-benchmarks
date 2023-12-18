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
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.9 | 1.04 ± 0.28 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.25 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.6 | 1.06 ± 0.27 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.6 | 1.07 ± 0.27 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.12 ± 0.25 |
| lanjian | input-kcen | 1.4 ± 3.7 | 0.3 | 54.0 | 1.26 ± 3.47 |
| pting | input-kcen | 18.0 ± 0.7 | 17.0 | 20.8 | 16.63 ± 3.17 |
| pting | input-pting | 18.0 ± 0.7 | 16.9 | 21.3 | 16.65 ± 3.18 |
| pting | input-mattcl | 18.0 ± 0.7 | 17.0 | 21.2 | 16.66 ± 3.18 |
| pting | input-lanjian | 18.1 ± 0.7 | 16.9 | 20.8 | 16.68 ± 3.19 |
| kcen | input-lanjian | 18.6 ± 0.6 | 17.5 | 21.4 | 17.15 ± 3.25 |
| kcen | input-pting | 18.6 ± 0.7 | 17.7 | 21.7 | 17.15 ± 3.26 |
| kcen | input-mattcl | 18.6 ± 0.7 | 17.6 | 21.4 | 17.23 ± 3.28 |
| kcen | input-kcen | 18.7 ± 2.3 | 17.4 | 45.6 | 17.31 ± 3.86 |
| mattcl-py | input-mattcl | 19.9 ± 0.8 | 18.9 | 22.9 | 18.37 ± 3.51 |
| mattcl-py | input-lanjian | 19.9 ± 0.8 | 18.8 | 23.0 | 18.41 ± 3.51 |
| mattcl-py | input-pting | 19.9 ± 0.9 | 18.8 | 23.3 | 18.42 ± 3.53 |
| mattcl-py | input-kcen | 20.6 ± 5.7 | 18.6 | 75.2 | 19.02 ± 6.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|