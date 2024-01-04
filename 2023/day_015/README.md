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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.5 | 1.6 | 1.02 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 2.0 | 1.03 ± 0.25 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.24 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.5 | 1.7 | 1.04 ± 0.22 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.9 | 1.07 ± 0.26 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.9 | 1.08 ± 0.26 |
| pting | input-pting | 17.9 ± 0.6 | 17.2 | 21.0 | 15.64 ± 2.69 |
| pting | input-mattcl | 18.0 ± 0.7 | 17.0 | 21.4 | 15.75 ± 2.74 |
| pting | input-kcen | 18.0 ± 0.7 | 17.0 | 21.5 | 15.76 ± 2.72 |
| kcen | input-pting | 18.4 ± 0.7 | 17.4 | 21.7 | 16.12 ± 2.79 |
| pting | input-lanjian | 18.4 ± 4.4 | 17.0 | 68.4 | 16.13 ± 4.73 |
| kcen | input-mattcl | 18.5 ± 1.7 | 17.4 | 39.4 | 16.22 ± 3.14 |
| kcen | input-kcen | 18.5 ± 0.6 | 17.7 | 21.2 | 16.23 ± 2.79 |
| kcen | input-lanjian | 18.6 ± 0.7 | 17.4 | 21.5 | 16.27 ± 2.82 |
| mattcl-py | input-pting | 19.7 ± 0.7 | 18.7 | 22.9 | 17.28 ± 2.98 |
| mattcl-py | input-lanjian | 19.9 ± 0.7 | 18.7 | 23.0 | 17.39 ± 3.01 |
| mattcl-py | input-mattcl | 19.9 ± 0.9 | 18.7 | 23.1 | 17.46 ± 3.06 |
| mattcl-py | input-kcen | 20.0 ± 0.8 | 19.0 | 22.9 | 17.48 ± 3.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|