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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.7 | 1.01 ± 0.24 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.6 | 1.02 ± 0.22 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.5 | 1.4 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.22 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.6 | 1.07 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 2.0 | 1.09 ± 0.26 |
| pting | input-mattcl | 18.2 ± 0.7 | 16.7 | 21.9 | 16.19 ± 2.64 |
| pting | input-lanjian | 18.3 ± 0.7 | 17.0 | 21.4 | 16.28 ± 2.64 |
| pting | input-pting | 18.3 ± 0.9 | 17.3 | 21.7 | 16.28 ± 2.69 |
| pting | input-kcen | 18.4 ± 0.8 | 17.3 | 21.7 | 16.33 ± 2.68 |
| kcen | input-mattcl | 18.6 ± 0.5 | 17.5 | 21.7 | 16.57 ± 2.66 |
| kcen | input-pting | 18.6 ± 0.5 | 17.7 | 21.9 | 16.57 ± 2.66 |
| kcen | input-kcen | 18.8 ± 0.7 | 17.6 | 21.8 | 16.71 ± 2.71 |
| kcen | input-lanjian | 18.8 ± 0.7 | 17.7 | 22.0 | 16.72 ± 2.72 |
| mattcl-py | input-pting | 19.9 ± 0.5 | 19.1 | 22.6 | 17.68 ± 2.83 |
| mattcl-py | input-kcen | 20.0 ± 0.7 | 18.9 | 23.3 | 17.79 ± 2.88 |
| mattcl-py | input-mattcl | 20.1 ± 0.7 | 18.7 | 22.8 | 17.85 ± 2.89 |
| mattcl-py | input-lanjian | 20.1 ± 0.6 | 19.2 | 22.9 | 17.86 ± 2.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|