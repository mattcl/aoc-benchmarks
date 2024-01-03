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
| mattcl | input-pting | 1.1 ± 3.7 | 0.4 | 53.0 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.9 | 1.24 ± 4.31 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.0 | 1.26 ± 4.40 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.1 | 1.29 ± 4.50 |
| lanjian | input-pting | 2.6 ± 0.4 | 1.9 | 3.6 | 2.41 ± 8.40 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.1 | 4.7 | 2.86 ± 9.94 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.4 | 4.0 | 2.86 ± 9.95 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 5.9 | 2.86 ± 9.96 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.2 | 18.9 | 16.46 ± 57.30 |
| mattcl-ts | input-kcen | 17.6 ± 0.5 | 16.7 | 19.0 | 16.56 ± 57.64 |
| mattcl-ts | input-lanjian | 17.8 ± 0.4 | 16.7 | 18.8 | 16.66 ± 57.99 |
| mattcl-ts | input-pting | 17.9 ± 3.0 | 16.6 | 56.2 | 16.76 ± 58.43 |
| mattcl-py | input-mattcl | 26.1 ± 0.8 | 24.9 | 28.9 | 24.46 ± 85.15 |
| mattcl-py | input-kcen | 26.1 ± 1.1 | 24.7 | 31.3 | 24.46 ± 85.17 |
| mattcl-py | input-lanjian | 26.2 ± 0.8 | 25.1 | 29.5 | 24.61 ± 85.69 |
| pting | input-kcen | 27.0 ± 0.7 | 26.0 | 29.8 | 25.35 ± 88.24 |
| pting | input-pting | 27.3 ± 0.8 | 26.3 | 29.9 | 25.60 ± 89.13 |
| pting | input-lanjian | 27.3 ± 0.9 | 26.3 | 30.1 | 25.66 ± 89.33 |
| pting | input-mattcl | 27.4 ± 0.9 | 25.7 | 29.8 | 25.70 ± 89.45 |
| mattcl-py | input-pting | 27.4 ± 6.5 | 24.8 | 71.1 | 25.72 ± 89.75 |
| kcen | input-pting | 47.3 ± 1.3 | 45.2 | 52.3 | 44.41 ± 154.61 |
| kcen | input-lanjian | 48.3 ± 1.2 | 46.6 | 51.3 | 45.34 ± 157.85 |
| kcen | input-mattcl | 50.3 ± 0.9 | 48.6 | 52.8 | 47.22 ± 164.37 |
| kcen | input-kcen | 50.7 ± 2.2 | 48.6 | 65.3 | 47.56 ± 165.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|