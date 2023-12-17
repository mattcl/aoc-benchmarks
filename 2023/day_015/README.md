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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.06 ± 0.25 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.25 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.9 | 1.08 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.6 | 1.10 ± 0.24 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.7 | 1.7 | 1.11 ± 0.23 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.7 | 1.12 ± 0.22 |
| pting | input-kcen | 18.0 ± 0.6 | 17.2 | 21.1 | 16.38 ± 2.73 |
| pting | input-pting | 18.1 ± 0.8 | 17.2 | 21.6 | 16.41 ± 2.78 |
| pting | input-mattcl | 18.1 ± 0.7 | 17.2 | 21.0 | 16.42 ± 2.77 |
| pting | input-lanjian | 18.5 ± 3.9 | 17.0 | 57.5 | 16.79 ± 4.52 |
| kcen | input-pting | 18.7 ± 0.8 | 17.6 | 21.8 | 16.95 ± 2.86 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.6 | 21.6 | 16.97 ± 2.83 |
| kcen | input-kcen | 18.7 ± 0.7 | 17.5 | 22.1 | 17.02 ± 2.86 |
| kcen | input-mattcl | 18.8 ± 0.8 | 17.7 | 21.9 | 17.05 ± 2.89 |
| mattcl-py | input-lanjian | 19.9 ± 0.8 | 18.5 | 23.0 | 18.08 ± 3.04 |
| mattcl-py | input-mattcl | 19.9 ± 0.8 | 18.7 | 22.5 | 18.11 ± 3.05 |
| mattcl-py | input-pting | 19.9 ± 0.8 | 18.9 | 24.9 | 18.13 ± 3.07 |
| mattcl-py | input-kcen | 20.0 ± 0.8 | 19.0 | 23.5 | 18.16 ± 3.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|