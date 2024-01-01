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
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.1 | 1.05 ± 0.22 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 2.3 | 1.07 ± 0.23 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.4 | 5.7 | 2.36 ± 0.41 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 4.8 | 2.40 ± 0.43 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.4 | 6.1 | 2.40 ± 0.46 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.4 | 5.8 | 2.50 ± 0.51 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.7 | 18.6 | 13.56 ± 2.11 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.4 | 19.2 | 13.58 ± 2.12 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.3 | 19.7 | 13.64 ± 2.12 |
| mattcl-ts | input-lanjian | 17.6 ± 0.4 | 16.4 | 19.0 | 13.66 ± 2.13 |
| mattcl-py | input-kcen | 25.9 ± 0.9 | 24.5 | 29.5 | 20.07 ± 3.17 |
| mattcl-py | input-mattcl | 25.9 ± 0.9 | 24.6 | 29.1 | 20.11 ± 3.18 |
| mattcl-py | input-lanjian | 26.3 ± 0.9 | 24.6 | 30.0 | 20.38 ± 3.22 |
| mattcl-py | input-pting | 26.3 ± 0.9 | 25.0 | 29.3 | 20.40 ± 3.22 |
| pting | input-kcen | 27.0 ± 0.7 | 25.9 | 29.8 | 20.93 ± 3.27 |
| pting | input-mattcl | 27.0 ± 0.7 | 25.8 | 29.9 | 21.00 ± 3.28 |
| pting | input-pting | 27.1 ± 0.6 | 25.9 | 30.2 | 21.07 ± 3.28 |
| pting | input-lanjian | 27.3 ± 0.7 | 26.3 | 30.6 | 21.17 ± 3.31 |
| kcen | input-pting | 47.7 ± 2.2 | 45.4 | 61.4 | 37.05 ± 5.95 |
| kcen | input-lanjian | 48.7 ± 1.3 | 46.5 | 51.9 | 37.84 ± 5.91 |
| kcen | input-mattcl | 50.0 ± 1.1 | 48.1 | 53.1 | 38.85 ± 6.04 |
| kcen | input-kcen | 50.6 ± 1.2 | 48.8 | 53.8 | 39.24 ± 6.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|