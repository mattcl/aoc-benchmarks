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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 2.1 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 ± 0.22 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.20 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.2 | 1.05 ± 0.23 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.3 | 5.8 | 2.39 ± 0.47 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 6.0 | 2.39 ± 0.46 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 5.7 | 2.39 ± 0.43 |
| lanjian | input-mattcl | 3.3 ± 3.1 | 2.0 | 46.4 | 2.52 ± 2.41 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.7 | 18.9 | 13.54 ± 2.19 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.8 | 19.0 | 13.56 ± 2.19 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.4 | 18.9 | 13.56 ± 2.19 |
| mattcl-ts | input-lanjian | 18.1 ± 3.8 | 16.8 | 67.7 | 13.94 ± 3.71 |
| mattcl-py | input-kcen | 25.9 ± 0.9 | 24.6 | 29.1 | 19.97 ± 3.27 |
| mattcl-py | input-mattcl | 26.1 ± 1.0 | 24.8 | 30.0 | 20.11 ± 3.31 |
| mattcl-py | input-pting | 26.3 ± 0.8 | 25.2 | 29.5 | 20.31 ± 3.30 |
| mattcl-py | input-lanjian | 26.4 ± 0.9 | 25.3 | 29.9 | 20.39 ± 3.34 |
| pting | input-mattcl | 27.1 ± 0.8 | 26.1 | 30.5 | 20.89 ± 3.40 |
| pting | input-kcen | 27.1 ± 0.8 | 25.8 | 29.9 | 20.94 ± 3.41 |
| pting | input-pting | 27.4 ± 0.8 | 26.2 | 30.5 | 21.13 ± 3.43 |
| pting | input-lanjian | 27.5 ± 1.0 | 26.1 | 34.0 | 21.19 ± 3.48 |
| kcen | input-pting | 47.5 ± 1.3 | 45.4 | 51.5 | 36.66 ± 5.95 |
| kcen | input-lanjian | 48.5 ± 1.2 | 46.5 | 51.3 | 37.43 ± 6.06 |
| kcen | input-kcen | 50.3 ± 1.1 | 48.8 | 53.5 | 38.83 ± 6.26 |
| kcen | input-mattcl | 50.5 ± 1.1 | 48.7 | 52.9 | 38.95 ± 6.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|