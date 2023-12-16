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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.9 | 1.01 ± 0.23 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 2.0 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.9 | 1.04 ± 0.23 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.3 | 3.8 | 2.41 ± 0.43 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 5.5 | 2.44 ± 0.47 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 4.7 | 2.45 ± 0.48 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 4.7 | 2.48 ± 0.48 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.6 | 18.5 | 14.11 ± 2.39 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.3 | 18.9 | 14.14 ± 2.40 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.4 | 18.7 | 14.14 ± 2.39 |
| mattcl-ts | input-lanjian | 17.7 ± 0.5 | 16.4 | 19.0 | 14.26 ± 2.42 |
| mattcl-py | input-kcen | 25.9 ± 0.8 | 24.7 | 29.4 | 20.95 ± 3.58 |
| mattcl-py | input-mattcl | 26.1 ± 0.9 | 24.9 | 29.5 | 21.04 ± 3.60 |
| mattcl-py | input-lanjian | 26.4 ± 1.0 | 25.0 | 29.8 | 21.31 ± 3.67 |
| mattcl-py | input-pting | 26.4 ± 0.9 | 24.4 | 29.8 | 21.36 ± 3.66 |
| pting | input-pting | 27.2 ± 0.8 | 25.7 | 30.5 | 21.94 ± 3.74 |
| pting | input-kcen | 27.2 ± 0.8 | 25.9 | 29.6 | 21.96 ± 3.74 |
| pting | input-mattcl | 27.2 ± 0.8 | 26.1 | 29.9 | 21.96 ± 3.75 |
| pting | input-lanjian | 27.4 ± 1.1 | 26.2 | 34.4 | 22.12 ± 3.82 |
| kcen | input-pting | 47.5 ± 1.1 | 45.8 | 50.7 | 38.39 ± 6.51 |
| kcen | input-lanjian | 48.4 ± 1.4 | 46.5 | 51.6 | 39.09 ± 6.65 |
| kcen | input-kcen | 50.5 ± 1.1 | 48.6 | 53.3 | 40.81 ± 6.91 |
| kcen | input-mattcl | 50.6 ± 1.2 | 48.2 | 53.6 | 40.90 ± 6.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|