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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 2.0 | 1.05 ± 0.27 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.23 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.9 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.07 ± 0.23 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.08 ± 0.24 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.7 | 1.9 | 1.08 ± 0.24 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 2.1 | 1.10 ± 0.28 |
| pting | input-kcen | 18.4 ± 0.7 | 17.5 | 21.5 | 16.41 ± 2.91 |
| pting | input-pting | 18.5 ± 0.8 | 17.1 | 21.5 | 16.46 ± 2.94 |
| pting | input-lanjian | 18.5 ± 0.8 | 17.3 | 21.7 | 16.46 ± 2.95 |
| pting | input-mattcl | 18.5 ± 2.1 | 17.3 | 43.8 | 16.51 ± 3.41 |
| kcen | input-mattcl | 18.8 ± 0.6 | 17.7 | 21.8 | 16.73 ± 2.95 |
| kcen | input-lanjian | 18.8 ± 0.6 | 18.0 | 22.0 | 16.74 ± 2.95 |
| kcen | input-pting | 18.9 ± 0.9 | 17.3 | 22.7 | 16.86 ± 3.03 |
| kcen | input-kcen | 18.9 ± 0.7 | 17.7 | 22.5 | 16.88 ± 3.00 |
| mattcl-py | input-kcen | 20.0 ± 0.6 | 18.9 | 23.8 | 17.81 ± 3.13 |
| mattcl-py | input-mattcl | 20.1 ± 0.6 | 19.0 | 22.5 | 17.88 ± 3.15 |
| mattcl-py | input-pting | 20.1 ± 0.7 | 18.8 | 22.9 | 17.89 ± 3.16 |
| mattcl-py | input-lanjian | 20.2 ± 0.7 | 19.0 | 23.2 | 17.98 ± 3.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|