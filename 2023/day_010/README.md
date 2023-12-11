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
| mattcl | input-mattcl | 1.8 ± 0.2 | 1.0 | 2.3 | 1.00 |
| mattcl | input-pting | 1.8 ± 0.2 | 0.7 | 2.4 | 1.01 ± 0.17 |
| mattcl | input-kcen | 1.9 ± 0.2 | 1.0 | 2.2 | 1.02 ± 0.16 |
| mattcl | input-lanjian | 1.9 ± 0.1 | 1.4 | 2.3 | 1.04 ± 0.15 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 5.7 | 1.71 ± 0.24 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.7 | 1.72 ± 0.26 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 6.1 | 1.72 ± 0.28 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.3 | 5.9 | 1.72 ± 0.27 |
| mattcl-ts | input-pting | 16.2 ± 0.5 | 15.1 | 18.0 | 8.93 ± 1.12 |
| mattcl-ts | input-mattcl | 16.3 ± 0.4 | 15.1 | 17.5 | 9.00 ± 1.12 |
| mattcl-ts | input-kcen | 16.3 ± 0.4 | 14.9 | 17.5 | 9.00 ± 1.12 |
| mattcl-ts | input-lanjian | 16.5 ± 0.4 | 15.6 | 17.6 | 9.09 ± 1.13 |
| pting | input-kcen | 26.8 ± 1.0 | 25.7 | 30.4 | 14.74 ± 1.88 |
| pting | input-pting | 26.9 ± 0.6 | 25.9 | 29.3 | 14.82 ± 1.84 |
| pting | input-lanjian | 26.9 ± 0.8 | 25.5 | 29.9 | 14.84 ± 1.87 |
| pting | input-mattcl | 27.2 ± 2.4 | 25.9 | 49.9 | 14.97 ± 2.24 |
| mattcl-py | input-kcen | 36.4 ± 1.0 | 35.2 | 39.2 | 20.08 ± 2.51 |
| mattcl-py | input-mattcl | 36.7 ± 1.0 | 35.3 | 39.5 | 20.20 ± 2.53 |
| mattcl-py | input-lanjian | 37.2 ± 1.0 | 35.9 | 40.9 | 20.47 ± 2.56 |
| mattcl-py | input-pting | 37.2 ± 0.8 | 36.1 | 40.3 | 20.51 ± 2.54 |
| kcen | input-pting | 47.0 ± 0.9 | 45.7 | 50.1 | 25.89 ± 3.20 |
| kcen | input-lanjian | 47.8 ± 1.0 | 46.1 | 51.0 | 26.31 ± 3.26 |
| kcen | input-mattcl | 50.2 ± 1.4 | 48.3 | 55.6 | 27.66 ± 3.46 |
| kcen | input-kcen | 50.2 ± 1.6 | 48.4 | 56.0 | 27.67 ± 3.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|