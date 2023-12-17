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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.8 | 1.5 | 1.02 ± 0.19 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.20 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.8 | 2.1 | 1.04 ± 0.20 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.7 | 2.44 ± 0.40 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.3 | 3.8 | 2.44 ± 0.35 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.5 | 2.44 ± 0.39 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.4 | 5.7 | 2.47 ± 0.45 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.4 | 18.5 | 13.65 ± 1.87 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.5 | 18.7 | 13.67 ± 1.87 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.3 | 18.5 | 13.75 ± 1.89 |
| mattcl-ts | input-lanjian | 17.7 ± 2.4 | 16.6 | 47.8 | 13.93 ± 2.65 |
| mattcl-py | input-kcen | 25.5 ± 0.9 | 24.2 | 28.4 | 20.09 ± 2.82 |
| mattcl-py | input-mattcl | 25.6 ± 0.7 | 24.7 | 28.8 | 20.18 ± 2.79 |
| mattcl-py | input-lanjian | 25.9 ± 0.7 | 24.8 | 28.9 | 20.43 ± 2.82 |
| mattcl-py | input-pting | 25.9 ± 0.7 | 25.0 | 28.8 | 20.45 ± 2.83 |
| pting | input-kcen | 26.6 ± 0.7 | 25.5 | 30.0 | 20.95 ± 2.89 |
| pting | input-pting | 27.1 ± 0.6 | 26.2 | 29.5 | 21.35 ± 2.93 |
| pting | input-lanjian | 27.1 ± 0.7 | 26.1 | 30.2 | 21.35 ± 2.95 |
| pting | input-mattcl | 27.1 ± 1.0 | 25.9 | 30.5 | 21.38 ± 3.00 |
| kcen | input-pting | 47.1 ± 1.2 | 45.4 | 50.7 | 37.17 ± 5.13 |
| kcen | input-lanjian | 48.0 ± 1.0 | 46.2 | 50.8 | 37.81 ± 5.18 |
| kcen | input-kcen | 49.9 ± 1.1 | 48.1 | 55.0 | 39.33 ± 5.40 |
| kcen | input-mattcl | 50.1 ± 1.1 | 48.4 | 52.6 | 39.49 ± 5.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|