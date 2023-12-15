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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 ± 0.23 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.8 | 1.03 ± 0.23 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.8 | 1.06 ± 0.24 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.0 | 3.7 | 2.45 ± 0.44 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 5.7 | 2.50 ± 0.47 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.6 | 5.6 | 2.52 ± 0.47 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.4 | 5.8 | 2.53 ± 0.50 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.4 | 14.07 ± 2.35 |
| mattcl-ts | input-mattcl | 17.4 ± 0.4 | 16.4 | 18.6 | 14.10 ± 2.35 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.4 | 18.9 | 14.11 ± 2.36 |
| mattcl-ts | input-lanjian | 17.5 ± 0.4 | 16.4 | 18.5 | 14.17 ± 2.36 |
| mattcl-py | input-kcen | 25.6 ± 0.9 | 24.6 | 29.2 | 20.79 ± 3.51 |
| mattcl-py | input-mattcl | 25.8 ± 0.8 | 24.7 | 28.6 | 20.94 ± 3.53 |
| mattcl-py | input-pting | 26.2 ± 0.9 | 25.2 | 29.1 | 21.24 ± 3.58 |
| mattcl-py | input-lanjian | 26.2 ± 1.0 | 25.0 | 31.5 | 21.30 ± 3.61 |
| pting | input-kcen | 26.8 ± 1.4 | 25.5 | 39.1 | 21.71 ± 3.76 |
| pting | input-mattcl | 26.9 ± 0.8 | 25.8 | 29.9 | 21.85 ± 3.66 |
| pting | input-pting | 27.1 ± 0.8 | 26.2 | 29.4 | 21.97 ± 3.68 |
| pting | input-lanjian | 27.4 ± 2.9 | 25.6 | 55.9 | 22.22 ± 4.36 |
| kcen | input-pting | 47.1 ± 1.0 | 45.7 | 49.6 | 38.22 ± 6.36 |
| kcen | input-lanjian | 48.9 ± 6.0 | 46.6 | 94.0 | 39.67 ± 8.15 |
| kcen | input-mattcl | 50.0 ± 1.1 | 48.4 | 53.1 | 40.54 ± 6.76 |
| kcen | input-kcen | 50.5 ± 1.3 | 48.6 | 53.9 | 40.96 ± 6.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|