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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.5 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.7 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.7 | 1.06 ± 0.22 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.2 | 5.5 | 2.48 ± 0.42 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.5 | 2.49 ± 0.45 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.3 | 4.8 | 2.49 ± 0.40 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.3 | 5.5 | 2.50 ± 0.43 |
| mattcl-ts | input-mattcl | 16.7 ± 0.4 | 15.6 | 17.7 | 13.79 ± 2.09 |
| mattcl-ts | input-pting | 16.8 ± 0.4 | 15.9 | 17.8 | 13.88 ± 2.10 |
| mattcl-ts | input-lanjian | 16.9 ± 0.4 | 15.9 | 18.5 | 13.99 ± 2.12 |
| mattcl-ts | input-kcen | 17.2 ± 3.8 | 15.8 | 51.9 | 14.22 ± 3.81 |
| mattcl-py | input-kcen | 25.5 ± 0.9 | 24.6 | 29.4 | 21.06 ± 3.23 |
| mattcl-py | input-mattcl | 25.7 ± 0.8 | 24.5 | 29.2 | 21.25 ± 3.25 |
| mattcl-py | input-pting | 26.1 ± 0.9 | 25.0 | 29.8 | 21.60 ± 3.31 |
| mattcl-py | input-lanjian | 26.2 ± 1.4 | 25.1 | 37.2 | 21.71 ± 3.44 |
| pting | input-mattcl | 26.9 ± 0.8 | 25.9 | 30.5 | 22.21 ± 3.39 |
| pting | input-lanjian | 26.9 ± 0.8 | 26.0 | 29.9 | 22.29 ± 3.40 |
| pting | input-pting | 27.0 ± 0.8 | 25.8 | 30.0 | 22.35 ± 3.40 |
| pting | input-kcen | 27.3 ± 5.2 | 25.4 | 79.6 | 22.56 ± 5.43 |
| kcen | input-pting | 47.3 ± 1.5 | 45.7 | 54.7 | 39.09 ± 5.97 |
| kcen | input-lanjian | 48.0 ± 1.0 | 46.4 | 50.2 | 39.69 ± 5.99 |
| kcen | input-mattcl | 49.9 ± 1.0 | 47.8 | 52.6 | 41.24 ± 6.22 |
| kcen | input-kcen | 50.0 ± 1.1 | 48.7 | 53.7 | 41.39 ± 6.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|