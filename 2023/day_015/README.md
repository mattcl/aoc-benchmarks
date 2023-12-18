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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.4 | 1.8 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.6 | 1.03 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.4 | 1.04 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 2.0 | 1.05 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.6 | 1.05 ± 0.23 |
| pting | input-mattcl | 18.3 ± 0.7 | 17.0 | 21.4 | 16.12 ± 2.85 |
| pting | input-kcen | 18.3 ± 0.8 | 17.4 | 22.0 | 16.12 ± 2.86 |
| pting | input-lanjian | 18.5 ± 0.9 | 17.2 | 23.1 | 16.26 ± 2.91 |
| pting | input-pting | 18.5 ± 1.5 | 17.0 | 34.9 | 16.28 ± 3.11 |
| kcen | input-pting | 18.7 ± 0.7 | 17.6 | 21.5 | 16.52 ± 2.92 |
| kcen | input-lanjian | 18.8 ± 0.7 | 17.6 | 21.5 | 16.61 ± 2.93 |
| kcen | input-mattcl | 18.9 ± 0.9 | 17.5 | 22.3 | 16.64 ± 2.98 |
| kcen | input-kcen | 18.9 ± 0.8 | 17.8 | 22.5 | 16.68 ± 2.96 |
| mattcl-py | input-kcen | 19.9 ± 0.6 | 18.8 | 22.2 | 17.52 ± 3.06 |
| mattcl-py | input-lanjian | 19.9 ± 0.6 | 18.6 | 23.2 | 17.53 ± 3.07 |
| mattcl-py | input-mattcl | 20.1 ± 0.8 | 19.2 | 22.7 | 17.73 ± 3.13 |
| mattcl-py | input-pting | 20.2 ± 2.6 | 18.8 | 49.7 | 17.82 ± 3.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|