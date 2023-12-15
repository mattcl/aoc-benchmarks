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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.8 | 1.01 ± 0.19 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.6 | 2.47 ± 0.40 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 5.6 | 2.48 ± 0.38 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.7 | 2.49 ± 0.42 |
| lanjian | input-kcen | 3.1 ± 0.4 | 2.3 | 5.7 | 2.50 ± 0.44 |
| mattcl-ts | input-mattcl | 16.7 ± 0.4 | 15.9 | 18.3 | 13.56 ± 1.83 |
| mattcl-ts | input-pting | 16.8 ± 0.4 | 15.6 | 18.0 | 13.62 ± 1.83 |
| mattcl-ts | input-kcen | 16.8 ± 0.4 | 15.9 | 18.3 | 13.62 ± 1.83 |
| mattcl-ts | input-lanjian | 17.0 ± 0.5 | 16.0 | 18.4 | 13.75 ± 1.86 |
| mattcl-py | input-kcen | 25.4 ± 0.7 | 24.5 | 28.6 | 20.61 ± 2.79 |
| mattcl-py | input-mattcl | 25.8 ± 1.0 | 24.6 | 30.6 | 20.94 ± 2.90 |
| mattcl-py | input-lanjian | 26.2 ± 0.9 | 25.1 | 29.3 | 21.22 ± 2.90 |
| mattcl-py | input-pting | 26.3 ± 1.0 | 25.1 | 30.2 | 21.32 ± 2.95 |
| pting | input-kcen | 26.7 ± 0.8 | 25.6 | 30.1 | 21.64 ± 2.94 |
| pting | input-mattcl | 26.9 ± 0.8 | 25.9 | 29.8 | 21.81 ± 2.96 |
| pting | input-lanjian | 26.9 ± 0.8 | 26.1 | 30.1 | 21.84 ± 2.96 |
| pting | input-pting | 27.1 ± 0.8 | 26.3 | 29.9 | 21.99 ± 2.98 |
| kcen | input-pting | 47.1 ± 0.9 | 45.5 | 49.2 | 38.22 ± 5.11 |
| kcen | input-lanjian | 47.9 ± 1.7 | 46.3 | 57.9 | 38.83 ± 5.32 |
| kcen | input-kcen | 50.2 ± 1.0 | 48.5 | 52.9 | 40.70 ± 5.45 |
| kcen | input-mattcl | 50.3 ± 1.1 | 48.2 | 53.0 | 40.79 ± 5.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|