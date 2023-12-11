# Day 10 benchmarks

[link to problem](https://adventofcode.com/2023/day/10)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 10)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.8 ± 0.2 | 0.9 | 2.3 | 1.00 |
| mattcl | input-pting | 1.8 ± 0.2 | 0.7 | 2.1 | 1.01 ± 0.14 |
| mattcl | input-mattcl | 1.8 ± 0.1 | 1.0 | 2.2 | 1.01 ± 0.13 |
| mattcl | input-lanjian | 1.9 ± 3.2 | 0.6 | 46.3 | 1.07 ± 1.79 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 4.7 | 1.70 ± 0.21 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.2 | 5.6 | 1.72 ± 0.24 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.8 | 5.6 | 1.73 ± 0.24 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 4.6 | 1.74 ± 0.24 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.4 | 18.9 | 9.85 ± 1.07 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.3 | 18.6 | 9.86 ± 1.06 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.6 | 18.7 | 9.88 ± 1.06 |
| mattcl-ts | input-lanjian | 18.2 ± 7.2 | 16.6 | 110.5 | 10.26 ± 4.23 |
| pting | input-kcen | 27.1 ± 0.8 | 25.4 | 29.5 | 15.27 ± 1.68 |
| pting | input-lanjian | 27.2 ± 0.7 | 26.1 | 30.0 | 15.36 ± 1.68 |
| pting | input-mattcl | 27.2 ± 0.9 | 26.1 | 30.5 | 15.37 ± 1.71 |
| pting | input-pting | 27.4 ± 0.8 | 26.1 | 30.6 | 15.47 ± 1.70 |
| mattcl-py | input-mattcl | 39.2 ± 1.1 | 37.3 | 42.9 | 22.11 ± 2.42 |
| mattcl-py | input-kcen | 39.5 ± 1.8 | 37.6 | 51.9 | 22.27 ± 2.56 |
| mattcl-py | input-pting | 40.1 ± 1.2 | 38.5 | 46.4 | 22.64 ± 2.49 |
| mattcl-py | input-lanjian | 40.3 ± 2.7 | 38.3 | 59.5 | 22.75 ± 2.85 |
| kcen | input-pting | 47.0 ± 0.9 | 45.5 | 50.3 | 26.51 ± 2.85 |
| kcen | input-lanjian | 48.5 ± 1.1 | 46.4 | 51.9 | 27.35 ± 2.96 |
| kcen | input-mattcl | 50.4 ± 1.1 | 48.5 | 54.1 | 28.47 ± 3.08 |
| kcen | input-kcen | 50.7 ± 1.4 | 48.4 | 54.2 | 28.63 ± 3.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|