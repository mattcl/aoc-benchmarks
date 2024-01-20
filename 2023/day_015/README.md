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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.6 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.26 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.6 | 1.04 ± 0.24 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.6 | 1.07 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.08 ± 0.27 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.09 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.10 ± 0.25 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.10 ± 0.26 |
| pting | input-lanjian | 17.9 ± 0.5 | 17.2 | 20.3 | 16.59 ± 2.94 |
| pting | input-pting | 17.9 ± 0.6 | 16.8 | 20.9 | 16.61 ± 2.96 |
| pting | input-kcen | 18.0 ± 0.7 | 17.1 | 21.0 | 16.68 ± 2.99 |
| pting | input-mattcl | 18.0 ± 0.8 | 16.7 | 21.1 | 16.72 ± 3.01 |
| kcen | input-pting | 18.6 ± 0.7 | 17.6 | 21.9 | 17.24 ± 3.09 |
| kcen | input-mattcl | 18.6 ± 0.8 | 17.5 | 22.0 | 17.25 ± 3.11 |
| kcen | input-lanjian | 18.6 ± 0.7 | 17.7 | 21.4 | 17.27 ± 3.09 |
| kcen | input-kcen | 18.7 ± 0.7 | 17.7 | 21.4 | 17.38 ± 3.11 |
| mattcl-py | input-kcen | 19.7 ± 0.5 | 18.5 | 22.3 | 18.25 ± 3.24 |
| mattcl-py | input-mattcl | 19.8 ± 0.7 | 18.7 | 23.2 | 18.35 ± 3.28 |
| mattcl-py | input-lanjian | 19.8 ± 0.5 | 18.9 | 22.2 | 18.36 ± 3.25 |
| mattcl-py | input-pting | 19.8 ± 0.6 | 18.9 | 22.2 | 18.38 ± 3.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|