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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 2.0 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 2.1 | 1.01 ± 0.24 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.1 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.9 | 1.01 ± 0.22 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.3 | 3.5 | 2.33 ± 0.39 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.8 | 2.37 ± 0.45 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.7 | 2.38 ± 0.44 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.4 | 5.6 | 2.39 ± 0.48 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.3 | 18.4 | 13.32 ± 2.17 |
| mattcl-ts | input-kcen | 17.2 ± 0.4 | 16.3 | 18.5 | 13.38 ± 2.18 |
| mattcl-ts | input-lanjian | 17.4 ± 0.5 | 16.2 | 18.5 | 13.51 ± 2.21 |
| mattcl-ts | input-pting | 17.4 ± 3.2 | 16.4 | 59.1 | 13.54 ± 3.34 |
| mattcl-py | input-mattcl | 25.7 ± 0.9 | 24.7 | 29.1 | 19.97 ± 3.29 |
| mattcl-py | input-kcen | 25.8 ± 0.9 | 24.5 | 28.8 | 20.02 ± 3.31 |
| mattcl-py | input-pting | 26.1 ± 0.9 | 24.6 | 29.6 | 20.28 ± 3.35 |
| mattcl-py | input-lanjian | 26.2 ± 1.0 | 25.2 | 30.4 | 20.38 ± 3.37 |
| pting | input-mattcl | 27.0 ± 0.7 | 25.6 | 30.7 | 20.95 ± 3.43 |
| pting | input-kcen | 27.1 ± 0.9 | 25.8 | 30.0 | 21.05 ± 3.47 |
| pting | input-pting | 27.2 ± 0.9 | 26.0 | 33.0 | 21.10 ± 3.48 |
| pting | input-lanjian | 27.3 ± 0.8 | 26.2 | 30.4 | 21.23 ± 3.49 |
| kcen | input-pting | 47.5 ± 1.2 | 45.8 | 51.7 | 36.84 ± 6.03 |
| kcen | input-lanjian | 48.5 ± 1.4 | 46.4 | 53.7 | 37.65 ± 6.18 |
| kcen | input-kcen | 50.0 ± 0.9 | 48.7 | 53.5 | 38.83 ± 6.31 |
| kcen | input-mattcl | 50.4 ± 1.1 | 48.4 | 53.5 | 39.12 ± 6.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|