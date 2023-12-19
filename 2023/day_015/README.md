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
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.9 | 1.03 ± 0.27 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.28 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.4 | 1.04 ± 0.28 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.27 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.9 | 1.05 ± 0.27 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.4 | 1.06 ± 0.26 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 2.1 | 1.08 ± 0.27 |
| pting | input-mattcl | 18.1 ± 0.6 | 17.1 | 21.0 | 16.35 ± 3.43 |
| pting | input-kcen | 18.3 ± 0.8 | 17.0 | 21.7 | 16.60 ± 3.51 |
| pting | input-lanjian | 18.3 ± 0.8 | 17.1 | 21.2 | 16.62 ± 3.52 |
| pting | input-pting | 18.4 ± 0.9 | 17.3 | 22.2 | 16.62 ± 3.54 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.7 | 21.6 | 16.93 ± 3.55 |
| kcen | input-pting | 18.7 ± 0.7 | 17.5 | 21.5 | 16.96 ± 3.58 |
| kcen | input-mattcl | 18.9 ± 1.8 | 17.5 | 38.7 | 17.10 ± 3.89 |
| kcen | input-kcen | 18.9 ± 0.8 | 17.4 | 21.8 | 17.12 ± 3.61 |
| mattcl-py | input-mattcl | 19.8 ± 0.5 | 18.8 | 21.8 | 17.97 ± 3.75 |
| mattcl-py | input-pting | 19.9 ± 0.6 | 18.7 | 22.8 | 18.04 ± 3.78 |
| mattcl-py | input-kcen | 20.0 ± 0.6 | 18.9 | 23.1 | 18.08 ± 3.79 |
| mattcl-py | input-lanjian | 20.0 ± 0.6 | 19.2 | 22.2 | 18.08 ± 3.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|