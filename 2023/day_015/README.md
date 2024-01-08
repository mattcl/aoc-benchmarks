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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 1.7 | 0.3 | 25.1 | 1.01 ± 1.44 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.9 | 1.02 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.7 | 1.8 | 1.04 ± 0.19 |
| lanjian | input-mattcl | 1.3 ± 0.1 | 0.4 | 1.7 | 1.05 ± 0.21 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.4 | 2.0 | 1.06 ± 0.22 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.8 | 1.06 ± 0.23 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.8 | 1.7 | 1.07 ± 0.21 |
| pting | input-mattcl | 17.9 ± 0.6 | 16.9 | 21.0 | 14.87 ± 2.41 |
| pting | input-kcen | 18.0 ± 0.5 | 16.9 | 20.5 | 14.92 ± 2.42 |
| pting | input-lanjian | 18.0 ± 0.7 | 17.2 | 21.2 | 14.95 ± 2.45 |
| pting | input-pting | 18.0 ± 0.8 | 17.0 | 21.1 | 14.97 ± 2.47 |
| kcen | input-lanjian | 18.6 ± 0.6 | 17.7 | 22.0 | 15.41 ± 2.51 |
| kcen | input-pting | 18.7 ± 0.8 | 17.6 | 22.0 | 15.46 ± 2.55 |
| kcen | input-mattcl | 18.7 ± 0.8 | 17.4 | 22.1 | 15.50 ± 2.56 |
| kcen | input-kcen | 18.7 ± 0.8 | 17.7 | 21.8 | 15.54 ± 2.55 |
| mattcl-py | input-pting | 19.8 ± 0.6 | 18.9 | 22.5 | 16.38 ± 2.66 |
| mattcl-py | input-lanjian | 19.9 ± 0.7 | 18.8 | 22.7 | 16.49 ± 2.68 |
| mattcl-py | input-kcen | 19.9 ± 0.7 | 19.1 | 23.4 | 16.54 ± 2.69 |
| mattcl-py | input-mattcl | 20.1 ± 0.8 | 19.0 | 23.1 | 16.65 ± 2.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|