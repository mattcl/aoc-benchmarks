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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.5 | 1.01 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.21 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.7 | 1.04 ± 0.21 |
| lanjian | input-lanjian | 3.0 ± 0.1 | 2.3 | 3.3 | 2.49 ± 0.39 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 4.0 | 2.50 ± 0.40 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.6 | 5.9 | 2.53 ± 0.44 |
| lanjian | input-kcen | 3.1 ± 0.4 | 2.2 | 5.9 | 2.53 ± 0.51 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.2 | 18.3 | 14.25 ± 2.16 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.4 | 14.28 ± 2.16 |
| mattcl-ts | input-pting | 17.3 ± 0.3 | 16.6 | 18.9 | 14.31 ± 2.16 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.4 | 18.5 | 14.37 ± 2.18 |
| mattcl-py | input-kcen | 25.5 ± 0.8 | 24.4 | 28.0 | 21.07 ± 3.21 |
| mattcl-py | input-mattcl | 25.5 ± 0.7 | 24.4 | 28.5 | 21.12 ± 3.21 |
| mattcl-py | input-lanjian | 25.9 ± 1.0 | 25.1 | 35.1 | 21.45 ± 3.32 |
| mattcl-py | input-pting | 26.0 ± 0.8 | 24.9 | 29.0 | 21.51 ± 3.28 |
| pting | input-kcen | 26.7 ± 1.0 | 25.7 | 30.5 | 22.08 ± 3.40 |
| pting | input-mattcl | 26.8 ± 0.8 | 25.7 | 29.8 | 22.17 ± 3.38 |
| pting | input-lanjian | 27.0 ± 0.8 | 26.2 | 29.5 | 22.29 ± 3.40 |
| pting | input-pting | 27.5 ± 3.2 | 26.0 | 54.9 | 22.74 ± 4.31 |
| kcen | input-pting | 47.2 ± 1.2 | 45.5 | 50.0 | 39.03 ± 5.92 |
| kcen | input-lanjian | 47.9 ± 1.0 | 46.5 | 50.7 | 39.58 ± 5.98 |
| kcen | input-kcen | 49.9 ± 0.9 | 48.4 | 53.0 | 41.28 ± 6.22 |
| kcen | input-mattcl | 50.1 ± 1.1 | 48.5 | 52.8 | 41.43 ± 6.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|