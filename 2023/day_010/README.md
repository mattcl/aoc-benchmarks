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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.5 | 2.0 | 1.01 ± 0.27 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.8 | 1.04 ± 0.24 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.04 ± 0.24 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.8 | 2.39 ± 0.46 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.2 | 4.7 | 2.41 ± 0.47 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.4 | 5.9 | 2.42 ± 0.50 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.2 | 6.0 | 2.42 ± 0.49 |
| mattcl-ts | input-pting | 17.7 ± 0.5 | 16.9 | 19.2 | 13.84 ± 2.38 |
| mattcl-ts | input-kcen | 17.7 ± 0.5 | 16.6 | 20.5 | 13.85 ± 2.38 |
| mattcl-ts | input-lanjian | 17.8 ± 0.5 | 16.7 | 19.6 | 13.94 ± 2.40 |
| mattcl-ts | input-mattcl | 19.1 ± 1.9 | 17.2 | 29.8 | 14.96 ± 2.95 |
| mattcl-py | input-kcen | 25.9 ± 0.8 | 24.3 | 29.3 | 20.30 ± 3.51 |
| mattcl-py | input-lanjian | 26.3 ± 1.1 | 24.7 | 31.8 | 20.63 ± 3.60 |
| mattcl-py | input-pting | 26.6 ± 0.8 | 25.3 | 29.2 | 20.80 ± 3.59 |
| mattcl-py | input-mattcl | 27.3 ± 3.3 | 24.8 | 60.0 | 21.39 ± 4.47 |
| pting | input-kcen | 27.3 ± 0.9 | 26.0 | 30.4 | 21.40 ± 3.70 |
| pting | input-lanjian | 27.5 ± 0.9 | 26.1 | 30.6 | 21.56 ± 3.73 |
| pting | input-pting | 28.1 ± 4.6 | 26.2 | 62.5 | 21.98 ± 5.20 |
| pting | input-mattcl | 29.3 ± 1.1 | 27.6 | 33.1 | 22.92 ± 3.99 |
| kcen | input-lanjian | 49.3 ± 1.1 | 47.2 | 51.8 | 38.62 ± 6.62 |
| kcen | input-pting | 50.0 ± 3.5 | 46.5 | 71.6 | 39.18 ± 7.19 |
| kcen | input-kcen | 50.6 ± 1.2 | 48.8 | 53.9 | 39.64 ± 6.80 |
| kcen | input-mattcl | 50.9 ± 1.7 | 49.2 | 60.2 | 39.82 ± 6.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|