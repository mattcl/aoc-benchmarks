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
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.6 | 1.00 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.2 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.21 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.06 ± 0.23 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.0 | 1.07 ± 0.24 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.4 | 2.9 | 1.13 ± 0.28 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.0 | 1.13 ± 0.27 |
| pting | input-pting | 18.2 ± 0.7 | 16.9 | 21.7 | 15.83 ± 2.62 |
| pting | input-mattcl | 18.3 ± 0.8 | 17.0 | 21.5 | 15.89 ± 2.64 |
| pting | input-kcen | 18.4 ± 0.6 | 17.1 | 21.0 | 15.96 ± 2.62 |
| pting | input-lanjian | 18.4 ± 0.7 | 17.3 | 21.7 | 15.98 ± 2.63 |
| kcen | input-pting | 18.9 ± 0.8 | 17.8 | 22.1 | 16.36 ± 2.71 |
| kcen | input-mattcl | 19.0 ± 0.8 | 17.5 | 22.1 | 16.47 ± 2.73 |
| kcen | input-kcen | 19.1 ± 0.8 | 18.0 | 22.3 | 16.58 ± 2.75 |
| kcen | input-lanjian | 19.2 ± 4.3 | 17.6 | 72.0 | 16.68 ± 4.61 |
| mattcl-py | input-pting | 20.0 ± 0.6 | 18.7 | 22.5 | 17.33 ± 2.84 |
| mattcl-py | input-kcen | 20.2 ± 0.7 | 19.1 | 23.5 | 17.50 ± 2.88 |
| mattcl-py | input-mattcl | 20.2 ± 0.8 | 19.0 | 23.3 | 17.53 ± 2.90 |
| mattcl-py | input-lanjian | 20.2 ± 0.8 | 19.0 | 23.1 | 17.56 ± 2.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|