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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.6 | 1.03 ± 0.26 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.28 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.6 | 1.6 | 1.06 ± 0.26 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.12 ± 0.30 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.5 | 1.8 | 1.15 ± 0.29 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 2.0 | 1.15 ± 0.29 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.9 | 1.15 ± 0.30 |
| pting | input-mattcl | 17.8 ± 0.5 | 17.0 | 21.0 | 16.88 ± 3.44 |
| pting | input-pting | 17.9 ± 0.5 | 16.9 | 20.7 | 16.94 ± 3.45 |
| pting | input-kcen | 17.9 ± 0.8 | 17.1 | 21.4 | 16.97 ± 3.51 |
| pting | input-lanjian | 18.0 ± 0.8 | 17.1 | 21.5 | 17.08 ± 3.54 |
| kcen | input-lanjian | 18.5 ± 0.6 | 17.6 | 21.7 | 17.58 ± 3.60 |
| kcen | input-kcen | 18.6 ± 0.7 | 17.4 | 22.0 | 17.64 ± 3.62 |
| kcen | input-pting | 18.6 ± 0.6 | 17.4 | 21.6 | 17.67 ± 3.62 |
| kcen | input-mattcl | 18.6 ± 0.7 | 17.6 | 21.5 | 17.69 ± 3.64 |
| mattcl-py | input-kcen | 19.6 ± 0.7 | 18.4 | 23.1 | 18.62 ± 3.82 |
| mattcl-py | input-pting | 19.7 ± 0.6 | 18.8 | 22.5 | 18.72 ± 3.81 |
| mattcl-py | input-mattcl | 19.8 ± 0.7 | 18.8 | 22.5 | 18.74 ± 3.83 |
| mattcl-py | input-lanjian | 19.8 ± 0.7 | 18.6 | 22.2 | 18.75 ± 3.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|