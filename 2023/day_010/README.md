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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.8 | 1.7 | 1.01 ± 0.17 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.18 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.03 ± 0.19 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.7 | 2.43 ± 0.33 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.6 | 2.44 ± 0.36 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.6 | 2.44 ± 0.36 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.7 | 2.46 ± 0.38 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.4 | 18.5 | 13.64 ± 1.67 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.2 | 19.1 | 13.69 ± 1.67 |
| mattcl-ts | input-pting | 17.4 ± 0.3 | 16.5 | 18.4 | 13.72 ± 1.67 |
| mattcl-ts | input-lanjian | 17.5 ± 0.4 | 16.4 | 18.6 | 13.83 ± 1.69 |
| mattcl-py | input-kcen | 25.5 ± 0.7 | 24.6 | 27.9 | 20.18 ± 2.49 |
| mattcl-py | input-pting | 26.2 ± 0.9 | 25.1 | 29.2 | 20.67 ± 2.59 |
| mattcl-py | input-mattcl | 26.2 ± 3.3 | 24.9 | 59.9 | 20.70 ± 3.58 |
| mattcl-py | input-lanjian | 26.3 ± 3.1 | 24.8 | 58.7 | 20.75 ± 3.50 |
| pting | input-kcen | 26.6 ± 0.6 | 25.7 | 28.9 | 21.01 ± 2.57 |
| pting | input-pting | 27.0 ± 0.7 | 26.1 | 30.1 | 21.31 ± 2.62 |
| pting | input-mattcl | 27.0 ± 0.9 | 26.1 | 30.3 | 21.37 ± 2.67 |
| pting | input-lanjian | 27.1 ± 1.1 | 25.8 | 34.6 | 21.39 ± 2.71 |
| kcen | input-pting | 47.7 ± 1.3 | 45.9 | 52.2 | 37.70 ± 4.66 |
| kcen | input-lanjian | 48.2 ± 4.0 | 46.3 | 78.2 | 38.09 ± 5.57 |
| kcen | input-kcen | 49.9 ± 1.0 | 48.3 | 53.1 | 39.39 ± 4.81 |
| kcen | input-mattcl | 49.9 ± 1.1 | 48.4 | 53.7 | 39.43 ± 4.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|