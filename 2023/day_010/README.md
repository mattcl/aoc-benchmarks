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
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.1 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.1 | 1.01 ± 0.19 |
| mattcl | input-pting | 1.5 ± 0.2 | 1.0 | 2.0 | 1.06 ± 0.20 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.1 | 1.08 ± 0.21 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.4 | 4.0 | 2.25 ± 0.35 |
| lanjian | input-kcen | 3.2 ± 0.3 | 2.6 | 5.7 | 2.27 ± 0.38 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.5 | 4.7 | 2.29 ± 0.39 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.5 | 5.8 | 2.32 ± 0.42 |
| mattcl-ts | input-mattcl | 17.7 ± 0.4 | 16.8 | 18.8 | 12.68 ± 1.80 |
| mattcl-ts | input-pting | 17.7 ± 0.4 | 16.9 | 19.0 | 12.70 ± 1.80 |
| mattcl-ts | input-kcen | 17.7 ± 0.4 | 16.6 | 18.8 | 12.72 ± 1.81 |
| mattcl-ts | input-lanjian | 17.9 ± 0.5 | 16.8 | 19.1 | 12.81 ± 1.83 |
| mattcl-py | input-kcen | 25.8 ± 0.7 | 24.8 | 28.4 | 18.49 ± 2.64 |
| mattcl-py | input-mattcl | 26.0 ± 0.9 | 24.7 | 29.3 | 18.66 ± 2.70 |
| mattcl-py | input-pting | 26.2 ± 1.0 | 24.7 | 29.9 | 18.78 ± 2.73 |
| mattcl-py | input-lanjian | 26.4 ± 0.9 | 25.2 | 29.5 | 18.90 ± 2.73 |
| pting | input-kcen | 27.1 ± 0.8 | 25.9 | 30.1 | 19.40 ± 2.78 |
| pting | input-mattcl | 27.3 ± 0.7 | 26.1 | 29.8 | 19.56 ± 2.79 |
| pting | input-pting | 27.3 ± 0.7 | 26.2 | 30.2 | 19.58 ± 2.79 |
| pting | input-lanjian | 28.3 ± 5.4 | 26.1 | 67.6 | 20.27 ± 4.81 |
| kcen | input-pting | 47.5 ± 1.0 | 46.0 | 51.4 | 34.02 ± 4.83 |
| kcen | input-lanjian | 48.4 ± 1.1 | 46.8 | 51.5 | 34.70 ± 4.93 |
| kcen | input-mattcl | 50.5 ± 1.2 | 48.6 | 54.5 | 36.18 ± 5.15 |
| kcen | input-kcen | 50.6 ± 1.3 | 48.3 | 54.1 | 36.24 ± 5.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|